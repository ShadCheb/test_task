<template>
  <div class="t-card"
    :class="[changedTask == task.task_id ? 'active' : '']"
    :style="task | getPosition"
    @mousedown.stop.prevent="moveTask"
  >
    <div class="t-card__container" :data-status="task.status">
      <div class="t-card__body">
        <div class="t-card__text">
          <div class="t-card__header">
            <p class="t-card__time">{{ task.time_start | getClock }}</p>
            <p class="t-card__price">{{ task.price }} $</p>
          </div>
          <p 
            class="t-card__name"
            v-if="task.author"
          >{{ task.author.name }}</p>
          <p class="t-card__description">{{ task.description }}</p>
        </div>
      </div>
    </div>
    <div class="t-card__shift" 
      v-if="task.status == 'expect'"
      @mousedown.stop="shiftTask"
    ></div>
    <div class="t-card__border__shift"
      v-if="shift && changedTask == task.task_id"
      :style="'right: ' + shift + 'px'"
    ></div>
    <div class="t-card__border__move"
      v-if="changedTask == task.task_id"
      :style="'left: ' + move[0] + 'px;' + 'top: ' + move[1] + 'px;'"
    ></div>
  </div>
</template>

<script>
import {TIME_S, STEP_H} from '../const';


export default {
  name: 'Task',
  props: {
    task: Object,
    index: Array,
    shift: Number,
    move: Array,
    changedTask: Number
  },
  data() {
    return {};
  },
  filters: {
    getClock(value) {
      let whole = Math.floor(value);
      let drob = value - whole;
      let drobStr = .6 * drob * 100;

      return ('0' + whole).substr(-2) + ':' + ('0' + drobStr).substr(-2);
    },
    getPosition(task) {
      return `left: ${(task.time_start - TIME_S) * STEP_H}px; width: ${task.duration * STEP_H}px`;
    }
  },
  methods: {
    shiftTask(e) {
      let param = {
        index: this.index,
        coord: e.clientX
      };

      this.$emit('emitShiftTask', param);
    },
    moveTask(e) {
      // Если статус не "Завершен" или "Не выполнен" то ничего не делать
      if (this.task.status !== 'expect')
        return;

      let param = {
        index: this.index,
        coord: [e.clientX, e.clientY]
      };

      this.$emit('emitMoveTask', param);
    }
  }
}
</script>

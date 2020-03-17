<template>
  <div class="task-list__container__time"
    :style="'width: ' + shiftTime + 'px;'"
  >
    <p>{{ timeString }}</p>
  </div>
</template>

<script>
export default {
  name: 'Time',
  props: {
    timeString: String,
    shiftTime: Number
  }
}
</script>

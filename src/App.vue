<template>
  <div class="main">
    <article class="m-header">
      <div class="container d-flex--center">
        <div class="col-left">
          <button class="btn-menu" aria-label="Menu">Menu<span></span></button>
        </div>
        <div class="col-right d-flex--center m-header__top">
          <div>
            <label class="label">
              <input class="input m-header__input i-input" type="text" placeholder="Search" />
              <svg  class="i-input__icon i-input__icon--search"
                xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 632.399 632.399"
                xml:space="preserve">
                <path d="M255.108,0C119.863,0,10.204,109.66,10.204,244.904c0,135.245,109.659,244.905,244.904,244.905
                  c52.006,0,100.238-16.223,139.883-43.854l185.205,185.176c1.671,1.672,4.379,1.672,5.964,0.115l34.892-34.891
                  c1.613-1.613,1.47-4.379-0.115-5.965L438.151,407.605c38.493-43.246,61.86-100.237,61.86-162.702
                  C500.012,109.66,390.353,0,255.108,0z M255.108,460.996c-119.34,0-216.092-96.752-216.092-216.092
                  c0-119.34,96.751-216.091,216.092-216.091s216.091,96.751,216.091,216.091C471.199,364.244,374.448,460.996,255.108,460.996z"/>
              </svg>
            </label>
          </div>
          <div class="m-header__dropdown">
            <div class="dropdown">
              <button class="dropdown__btn">settings
                <span></span>
                <span></span>
                <span></span>
              </button>
            </div>
          </div>
          <div class="avatar m-header__avatar">
            <img src="" alt="" />
          </div>
        </div>
      </div>
    </article>
    <article class="under-head">
      <div class="container under-head__body">
        <div class="under-head__btns">
          <button class="btn-1">Schedule</button>
          <button class="btn-1">Sell goods</button>
        </div>
      </div>
    </article>
    <article class="m-body">
      <div class="container">
        <div class="calendar-head d-flex--end">
          <div class="col-left">
            <div class="opltions m-body__option">
              <svg class="opltions__icon"
                xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                viewBox="0 0 512 512" xml:space="preserve">
                  <path d="M256,0C153.755,0,70.573,83.182,70.573,185.426c0,126.888,165.939,313.167,173.004,321.035
                    c6.636,7.391,18.222,7.378,24.846,0c7.065-7.868,173.004-194.147,173.004-321.035C441.425,83.182,358.244,0,256,0z M256,278.719
                    c-51.442,0-93.292-41.851-93.292-93.293S204.559,92.134,256,92.134s93.291,41.851,93.291,93.293S307.441,278.719,256,278.719z"/>
              </svg>
              <input type="text">
              <span class="opltions__arrow"></span>
            </div>
          </div>
          <div class="col-right">
            <div class="calendar-hr">
              <div class="calendar-hr__day-txt">
                <p>mo</p>
                <p>tu</p>
                <p>we</p>
                <p>th</p>
                <p>fr</p>
                <p>sa</p>
                <p>su</p>
                <p>mo</p>
                <p class="month"></p>
                <p>tu</p>
                <p>we</p>
                <p>th</p>
                <p>fr</p>
                <p>sa</p>
                <p>su</p>
              </div>
              <div class="calendar-hr__day-num">
                <p class="active">24</p>
                <p>25</p>
                <p>26</p>
                <p>27</p>
                <p>28</p>
                <p>29</p>
                <p>30</p>
                <p>31</p>
                <p class="month">jan</p>
                <p class="block">1</p>
                <p class="block">2</p>
                <p>3</p>
                <p>4</p>
                <p>5</p>
                <p>6</p>
                <div class="calendar-hr__day-num__icon">
                  <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
                    viewBox="0 0 512 512" xml:space="preserve">
                      <path d="M452,40h-24V0h-40v40H124V0H84v40H60C26.916,40,0,66.916,0,100v352c0,33.084,26.916,60,60,60h392
                        c33.084,0,60-26.916,60-60V100C512,66.916,485.084,40,452,40z M472,452c0,11.028-8.972,20-20,20H60c-11.028,0-20-8.972-20-20V188
                        h432V452z M472,148H40v-48c0-11.028,8.972-20,20-20h24v40h40V80h264v40h40V80h24c11.028,0,20,8.972,20,20V148z"/>
                      <rect x="76" y="230" width="40" height="40"/>
                      <rect x="156" y="230" width="40" height="40"/>
                      <rect x="236" y="230" width="40" height="40"/>
                      <rect x="316" y="230" width="40" height="40"/>
                      <rect x="396" y="230" width="40" height="40"/>
                      <rect x="76" y="310" width="40" height="40"/>
                      <rect x="156" y="310" width="40" height="40"/>
                      <rect x="236" y="310" width="40" height="40"/>
                      <rect x="316" y="310" width="40" height="40"/>
                      <rect x="76" y="390" width="40" height="40"/>
                      <rect x="156" y="390" width="40" height="40"/>
                      <rect x="236" y="390" width="40" height="40"/>
                      <rect x="316" y="390" width="40" height="40"/>
                      <rect x="396" y="310" width="40" height="40"/>
                  </svg>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="task-list">
          <div class="col-left">
            <div 
              class="task-list__group"
              v-for="(group, idx) in list"
              :key="idx"
            >
              <div 
                class="task-list__row"
                v-for="(person, idx, key) in group"
                :key="key"
              >
                <div class="p-card" v-if="person.person">
                  <div class="avatar p-card__img">
                    <img :src="person.person.avatar | getAvatar" alt=""> 
                  </div>
                  <div class="p-card__text">
                    <p class="p-card__name">{{ person.person.name }}</p>
                    <p class="p-card__post">{{ person.person.post }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-right">
            <div class="task-list__view" ref="taskListView">
              <div class="task-list__container"
                ref="taskListContainer"
                :style="'transform: translateX(' + shiftContainer + 'px);'"
                @mousemove="overTask"
                @mouseup="changeFinish"
                @mousedown="startMovingContainer"
                @wheel="wheelContainer"
                @mouseleave="changeFinish"
              >
                <div class="task-list__container__markup">
                  <div><p class="passive">09:00</p></div>
                  <div></div>
                  <div><p class="passive">10:00</p></div>
                  <div></div>
                  <div><p class="passive">11:00</p></div>
                  <div></div>
                  <div><p class="passive">12:00</p></div>
                  <div></div>
                  <div><p>13:00</p></div>
                  <div></div>
                  <div><p>14:00</p></div>
                  <div></div>
                  <div><p>15:00</p></div>
                  <div></div>
                  <div><p>16:00</p></div>
                  <div></div>
                  <div><p>17:00</p></div>
                  <div></div>
                  <div><p>18:00</p></div>
                  <div></div>
                  <div></div>
                </div>
                <Time 
                  :timeString="timeString"
                  :shiftTime="shiftTime"
                />

                <div 
                  class="task-list__group"
                  v-for="(group, idx1) in list"
                  :key="'g_' + idx1"
                >
                  <div 
                    class="task-list__row"
                    v-for="(person, idx2) in group"
                    :key="'p_' + idx2"
                    @mouseleave="setChangeRow(0, idx1 + '-' + idx2)"
                    @mouseenter="setChangeRow(1, idx1 + '-' + idx2)"
                  >
                    <Task 
                      v-for="(task, idx3) in person.tasks"
                      :key="task.task_id"
                      :task="task"
                      :index="[idx1, idx2, idx3]"
                      :shift="shiftWidth"
                      :move="moveLeftUp"
                      :changedTask="changedTask && changedTask.task_id"
                      @emitShiftTask="shiftTask"
                      @emitMoveTask="moveTask"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</template>

<script>
import {STEP_H, TIME_F, TIME_S} from './const';
import Task from './components/Task.vue';
import Time from './components/Time.vue'


export default {
  name: 'App',
  components: {
    Task, Time
  },
  data() {
    return {
      list: [
        [
          {
            person: {
              person_id: 0,
              name: 'Faadi Al Rahman 1',
              post: 'Specialist',
              avatar: '../images/avatars/avatar-1.jpg'
            },
            tasks: [
              {
                task_id: 0,
                author: {
                  person_id: 10,
                  name: 'Song Bao 1'
                },
                time_start: 9,
                duration: 1.5,
                description: 'Haicut standard 1',
                price: 10,
                status: 'finish'
              },
              {
                task_id: 1,
                author: {
                  person_id: 11,
                  name: 'Song Bao 2'
                },
                time_start: 11,
                duration: 2,
                description: 'Haicut standard 2',
                price: 10,
                status: 'finish'
              },
              {
                task_id: 2,
                author: {
                  person_id: 12,
                  name: 'Song Bao 3'
                },
                time_start: 13,
                duration: 2,
                description: 'Haicut standard 3',
                price: 10,
                status: 'expect'
              }
            ],
          },
          {
            person: {
              person_id: 1,
              name: 'Faadi Al Rahman 2',
              post: 'Specialist',
              avatar: '../images/avatars/avatar-1.jpg'
            },
            tasks: [
              {
                task_id: 3,
                author: {
                  person_id: 13,
                  name: 'Song Bao 4'
                },
                time_start: 10,
                duration: 1.5,
                description: 'Haicut standard 4',
                price: 10,
                status: 'not'
              }
            ]
          }
        ],
        [
          {
            person: {
              person_id: 3,
              name: 'Faadi Al Rahman 3',
              post: 'Specialist',
              avatar: '../images/avatars/avatar-1.jpg'
            },
            tasks: [
              {
                task_id: 4,
                author: {
                  person_id: 13,
                  name: 'Song Bao 5'
                },
                time_start: 14,
                duration: 1.5,
                description: 'Haicut standard 5',
                price: 10,
                status: 'expect'
              }
            ]
          }
        ]
      ],
      // list: [],
      
      changedTask: null, // изменяемая задача
      changedTaskIdx: null, // путь до задачи (для изменения)
      startCoord: null, // начальные координаты
      limitCoords: null, // лимит на минимум и максимум сдвига

      shiftProcess: false,
      shiftWidth: 0, // сдвиг для границы (маркер)

      moveProcess: false,
      moveLeftUp: [0, 0], // сдвиг слева и сверху при перемещении
      moveRow: ['', ''], // индекс ряда, индекс нового ряда
      changeRow: false, // вышли за пределы ряда (путь до ряда)

      timerId: null, // setInterval
      timeString: '', // текущее время
      shiftTime: 0, // смещение времени (залитая площадь)

      moveContainer: false,
      shiftContainer: 0,
      shiftContainerOld: 0,
      boxSize: [],
      containerSize: []
    };
  },
  filters: {
    getAvatar(avatar) {
      return (avatar) 
        ? avatar
        : '../images/avatars/no-photo.jpg'
    },
  },
  // created() {
  //   this.readData();
  // },
  mounted() {
    this.runTime();
    this.getBoxSize();
  },
  methods: {
    readData() {
      fetch('/api/test', {
        method: 'post',
        headers: {
          'Content-Type': 'application/json;charset=utf-8',
        },
      }).then(response => response.json())
        .then(result => {
          if (result && result.result) {
            this.list = JSON.parse(result.result);
          }
          // console.log(JSON.parse(result.result));
        })
        .catch(e => {
          console.log(e);
        });
    },

    recordData() {
      const data = JSON.stringify(this.list);

      fetch('/api/test', {
        method: 'put',
        headers: {
          'Content-Type': 'application/json;charset=utf-8',
        },
        body: data
      }).then(response => response.json())
        .then(result => {
          console.log(result);
        })
        .catch(e => {
          console.log(e);
        });
    },

    getBoxSize() {
      let elem = this.$refs['taskListView'];

      if (!elem)
        return;

      let box = elem.getBoundingClientRect();

      this.boxSize = [Math.round(box.left), Math.round(box.left + box.width)];
    },
    getContainerSize() {
      let elem = this.$refs['taskListContainer'];

      if (!elem)
        return;

      let container = this.$refs['taskListContainer'].getBoundingClientRect();

      this.containerSize = [Math.round(container.left), Math.round(container.left + container.width)];
      this.shiftContainerOld = this.shiftContainer;
    },

    shiftTask({index, coord}) {
      let durationNext = 0;
      let list = this.list[index[0]][index[1]].tasks;
      let task = list[index[2]];

      for (let i = index[2] + 1; i < list.length; i++) {
        durationNext += list[i].duration;
      }

      let max = TIME_F - (task.time_start + durationNext);
      let min = .5;

      this.limitCoords = [min, max];
      this.changedTask = task;
      this.changedTaskIdx = index;
      this.startCoord = coord;
      this.shiftProcess = true;
    },
    moveTask({index, coord}) {
      let list = this.list[index[0]][index[1]].tasks;
      
      this.getLimitTask(index[2], list);
      this.changedTask = list[index[2]];
      this.changedTaskIdx = index;
      this.startCoord = coord;
      this.moveProcess = true;
    },

    getLimitTask(index, list) {
      let task = list[index];
      let durationNext = 0;
      let durationPrev = 0;

      list.map((task, idx) => {
        if (idx < index) {
          durationPrev += task.duration;
        } else if (idx > index) {
          durationNext += task.duration;
        }
      });

      let max = TIME_F - (task.duration + durationNext);
      let min = TIME_S + durationPrev;

      this.limitCoords = [min, max];
    },

    moveingContainer (shift) {
      if ((this.containerSize[0] + shift) >= this.boxSize[0]) {
        this.shiftContainer = 0;
      } else if ((this.containerSize[1] + shift) <= this.boxSize[1]) {
        this.shiftContainer = this.boxSize[1] - this.containerSize[1] + this.shiftContainerOld;
      } else {
        this.shiftContainer = shift + this.shiftContainerOld;
      }
    },

    overTask(e) {
      if (!this.startCoord)
          return;

      if (this.moveContainer) {
        let shift = e.clientX - this.startCoord;

        this.moveingContainer(shift);
      }

      if (this.shiftProcess) {      
        let shift = this.startCoord - e.clientX;
        let duration = this.changedTask.duration;

        if (Math.abs(shift) > STEP_H / 2) {
          let durationAdd = Math.round(-(shift - (shift % (STEP_H / 2))) / STEP_H * 10) / 10;
          let permit = (duration + durationAdd) >= this.limitCoords[0] 
            && (duration + durationAdd) <= this.limitCoords[1];
          
          if (permit) {
            // Изменяем задачу
            this.startCoord += -shift;
            this.changedTask.duration += durationAdd;
            shift = 0;
          }
        }
        this.shiftWidth = shift;
      }

      if (this.moveProcess) {
        let shiftLeft = e.clientX - this.startCoord[0];
        let shiftUp = 0;
        let start = this.changedTask.time_start;

        if (Math.abs(shiftLeft) > STEP_H / 2) {
          let startAdd = Math.round((shiftLeft - (shiftLeft % (STEP_H / 2))) / STEP_H * 10) / 10;
          let permit = (start + startAdd) >= this.limitCoords[0] 
            && (start + startAdd) <= this.limitCoords[1];
          
          if (permit) {
            // Изменяем задачу
            this.startCoord[0] += shiftLeft;
            this.changedTask.time_start += startAdd;
            this.$nextTick(() => {
              let direction = (startAdd > 0)
                ? 'right'
                : 'left';

              this.overlayCheck(this.changedTaskIdx, Math.abs(startAdd), direction);
            });
            shiftLeft = 0;
          }
        }

        // Если вывели из ряда, то рисуем область относительно вверха
        if (this.moveRow[0]) {
          shiftUp = e.clientY - this.startCoord[1];
        }

        if (this.moveRow[1] && this.moveRow[0] != this.moveRow[1]) {
          this.changeRow = true;

          let idx1 = this.changedTaskIdx;
          let idx2 = this.moveRow[1].split('-');
          let taskListOld = this.list[idx1[0]][idx1[1]].tasks;
          let taskListNew = this.list[idx2[0]][idx2[1]].tasks;
          let startTask = this.changedTask.time_start;
          let newIdx = 0;
          let startAdd = Math.round((shiftLeft - (shiftLeft % (STEP_H / 2))) / STEP_H * 10) / 10;
          let taskList = taskListOld.filter(task => this.changedTask.task_id != task.task_id);

          startTask += startAdd;
          this.list[idx1[0]][idx1[1]].tasks = taskList;
          this.moveRow = ['', ''];

          taskListNew.map((task, idx) => {
            if (task.time_start < startTask) 
              newIdx = idx + 1;
            // Добавить проверку на наложение 
          });
          taskListNew.splice(newIdx, 0, this.changedTask);
          this.startCoord[1] += shiftUp;
          this.changedTaskIdx = [idx2[0], idx2[1], newIdx];
          this.getLimitTask(newIdx, taskListNew);
          shiftUp = 0;
        }
        this.moveLeftUp = [shiftLeft, shiftUp];
      }
    },

    setChangeRow(idx, path) {
      if (this.moveProcess) {
        this.moveRow[idx] = path;
      }
    },

    changeFinish() {
      if (this.moveContainer) {
        this.moveContainer = false;
      }

      if (this.moveProcess) {
        this.moveProcess = false;
        this.moveLeftUp = [0, 0];
        this.moveRow = ['', ''];
        this.changeRow = false;
        this.changedTask = null;
        this.changedTaskIdx = null;

        // this.recordData();
      } else if (this.shiftProcess) {
        this.shiftProcess = false;
        this.shiftWidth = 0;
        this.startCoord = null;
        this.limitCoords = null;
        this.changedTask = null;
        this.changedTaskIdx = null;
        
        // this.recordData();
      }

      // Запись в файл вывести в отдельную функцию
    },
  
    overlayCheck(idxPath, shift, direction) {
      let list = this.list[idxPath[0]][idxPath[1]].tasks;

      if (direction == 'right') {
        let time = list[idxPath[2]].time_start + list[idxPath[2]].duration;
        let finish = list.length;

        for (let i = idxPath[2] + 1; i < finish; i++) {
          if (time > list[i].time_start) {
            this.list[idxPath[0]][idxPath[1]].tasks[i].time_start += shift;
            time += list[i].duration;
          } else {
            break;
          }
        }
      } else {
        let time = list[idxPath[2]].time_start;
        let start = 0;

        for (let i = idxPath[2] - 1; i >= start; i--) {
          if (time < (list[i].time_start + list[i].duration)) {
            let shift = time - (list[i].time_start + list[i].duration);

            this.list[idxPath[0]][idxPath[1]].tasks[i].time_start += shift;
            time -= list[i].duration;
          } else {
            break;
          }
        }
      }
    },

    runTime() {
      this.timerId = setTimeout(() => this.runTime(), 60000);

      let date = new Date();
      let hours = date.getHours() + 1;
      let minutes = date.getMinutes();
      let hoursStr = ('0' + hours).substr(-2);
      let minutesStr = ('0' + minutes).substr(-2);
      let shift = hours + Math.ceil((minutes / 60)*100)/100;

      if (shift < TIME_S ) {
        shift = 0;
      } else if (shift > TIME_F) {
        shift = TIME_F - TIME_S;
      } else {
        shift -= TIME_S;
      }

      this.timeString = `${hoursStr}:${minutesStr}`;
      this.shiftTime = shift * STEP_H;

      // / 2 заменить на константу - 2 кол-во делений в одном часе
      if (shift % 1/2 === 0) {
        this.enumerationList(shift + TIME_S, this.list);
      }
    },
    enumerationList(shift, list) {
      // list.map(item => {
      //   if (!item.tasks) {          
      //     this.enumerationList(shift, item);
      //   }
      //   else 
      //     this.changeStatusTask(shift, item.tasks);
      // })

      list.map((group, idx1) => {
        group.map((row, idx2) => {
          this.changeStatusTask({shift, tasks: row.tasks, index: [idx1, idx2]});
        });
      });
    },
    changeStatusTask({shift, tasks, index}) {
      tasks.map((task, idx) => {
        if (task.status == 'expect') {
          if (task.time_start + task.duration <= shift) {
            this.list[index[0]][index[1]].tasks[idx].status = 'not';
          }
        }
      });
    },

    startMovingContainer(e) {
      this.moveContainer = true;
      this.startCoord = e.clientX;

      this.getContainerSize();
    },

    wheelContainer(e) {
      let shift = e.deltaY || e.detail || e.wheelDelta;

      this.getContainerSize();
      this.moveingContainer(-shift / 2);
    }
  }
}
</script>

<style type="text/scss">
  @import "./App.css";
</style>


<template>
  <div id="app">
    <div class="feedbackCard">
      <div class="exit">
        <img src="@/assets/close.svg" alt="croix">
      </div>
      <div class="feedback">
        <p><strong>give feedback</strong></p>
        <p>What do you think of the editing tool ?</p>
        <div class="feedback__emoji">
          <svg viewBox="0 0 36 36" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" @click="selected = 1" :class="{ selected : selected == 1 }">
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Day-1265-Feedback-Modal-UI-Design" transform="translate(-603.000000, -392.000000)">
                <g id="Group-5" transform="translate(517.000000, 172.000000)">
                  <g id="Group" transform="translate(82.000000, 216.000000)" >
                    <polygon id="Path" points="0 0 44 0 44 44 0 44"></polygon>
                    <line x1="16.5" y1="18.3333333" x2="16.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <line x1="27.5" y1="18.3333333" x2="27.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <path d="M17.4166667,27.9583333 C18.6235708,26.726542 20.2754921,26.0323979 22,26.0323979 C23.7245079,26.0323979 25.3764292,26.726542 26.5833333,27.9583333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                    <path d="M32.2043333,32.2776667 C30.8093014,33.7130319 30.8231441,36.0019331 32.2354347,37.4203204 C33.6477254,38.8387077 35.9365458,38.8624097 37.3779068,37.4735735 C38.8192678,36.0847373 38.880508,33.7966136 37.5155,32.3326667 L34.8333333,29.3333333 L32.2043333,32.2776667 L32.2043333,32.2776667 Z" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                    <path  d="M38.2525,24.7811667 C38.4139855,23.8628423 38.4967861,22.9324092 38.5,22 C38.5,12.8873016 31.1126984,5.5 22,5.5 C12.8873016,5.5 5.5,12.8873016 5.5,22 C5.5,31.1126984 12.8873016,38.5 22,38.5 C23.265,38.5 24.4933333,38.3606667 25.6666667,38.093" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                  </g>
                </g>
              </g>
            </g>
          </svg>
          <svg viewBox="0 0 36 36" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" @click="selected = 2" :class="{ selected : selected == 2 }">
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Day-1265-Feedback-Modal-UI-Design" transform="translate(-682.000000, -392.000000)">
                <g id="Group-5" transform="translate(517.000000, 172.000000)">
                  <g id="Group" transform="translate(161.000000, 216.000000)">
                    <polygon id="Path" points="0 0 44 0 44 44 0 44"></polygon>
                    <circle id="Oval" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round" cx="22" cy="22" r="16.5"></circle>
                    <line x1="16.5" y1="18.3333333" x2="16.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <line x1="27.5" y1="18.3333333" x2="27.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <path d="M17.4166667,29.3333333 C20.7006326,27.2773563 24.551531,26.3146317 28.4166667,26.5833333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                  </g>
                </g>
              </g>
            </g>
          </svg>
          <svg viewBox="0 0 36 36" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" @click="selected = 3" :class="{ selected : selected == 3 }">
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Day-1265-Feedback-Modal-UI-Design" transform="translate(-761.000000, -392.000000)">
                <g id="Group-5" transform="translate(517.000000, 172.000000)">
                  <g id="Group" transform="translate(240.000000, 216.000000)">
                      <polygon id="Path" points="0 0 44 0 44 44 0 44"></polygon>
                      <circle id="Oval" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round" cx="22" cy="22" r="16.5"></circle>
                      <line x1="16.5" y1="18.3333333" x2="16.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                      <line x1="27.5" y1="18.3333333" x2="27.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                      <line x1="16.5" y1="27.5" x2="27.5" y2="27.5" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    </g>
                </g>
              </g>
            </g>
          </svg>
          <svg viewBox="0 0 36 36" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" @click="selected = 4" :class="{ selected : selected == 4 }">
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Day-1265-Feedback-Modal-UI-Design" transform="translate(-840.000000, -392.000000)">
                <g id="Group-5" transform="translate(517.000000, 172.000000)">
                  <g id="Group-2" transform="translate(303.000000, 200.000000)">
                    <g id="Group" transform="translate(16.000000, 16.000000)">
                      <polygon id="Path" points="0 0 44 0 44 44 0 44"></polygon>
                      <circle id="Oval" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round" cx="22" cy="22" r="16.5"></circle>
                      <line x1="16.5" y1="18.3333333" x2="16.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                      <line x1="27.5" y1="18.3333333" x2="27.5183333" y2="18.3333333" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                      <path d="M17.4166667,27.5 C18.6235708,28.7317914 20.2754921,29.4259355 22,29.4259355 C23.7245079,29.4259355 25.3764292,28.7317914 26.5833333,27.5" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </svg>
          <svg viewBox="0 0 36 36" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" @click="selected = 5" :class="{ selected : selected == 5 }">
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Day-1265-Feedback-Modal-UI-Design" transform="translate(-919.000000, -392.000000)">
                <g id="Group-5" transform="translate(517.000000, 172.000000)">
                  <g id="Group" transform="translate(398.000000, 216.000000)">
                    <polygon id="Path" points="0 0 44 0 44 44 0 44"></polygon>
                    <circle id="Oval" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round" cx="22" cy="22" r="16.5"></circle>
                    <line x1="16.5" y1="16.5" x2="16.5183333" y2="16.5" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <line x1="27.5" y1="16.5" x2="27.5183333" y2="16.5" id="Path" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></line>
                    <path d="M14.6666667,23.8333333 C14.6666667,27.8834215 17.9499118,31.1666667 22,31.1666667 C26.0500882,31.1666667 29.3333333,27.8834215 29.3333333,23.8333333 M29.3333333,23.8333333 L14.6666667,23.8333333" id="Shape" stroke="#2C3E50" stroke-width="2.75" stroke-linecap="round" stroke-linejoin="round"></path>
                  </g>
                </g>
              </g>
            </g>
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      selected: 4
    }
  },
  methods: {
    smileySelected(e) {
      e.target.className = 'selected';
    }
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  background-color: #EBEBF3;
}
#app {
  width: 100vw;
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
#app, .exit, .feedback__emoji {
  display: flex;
  justify-content: center;
  align-items: center;
}
.feedbackCard {
  position: relative;
  height: 600px;
  width: 425px;
  background-color: #fff;
  border-radius: 12px;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
}
.exit {
  position: absolute;
  top: 20px;
  right: 20px;
  width: 40px;
  height: 40px;
  background-color: #EBEBF3;
  border-radius: 50%;
  font-weight: 900;

  img {
    width: 30%;
  }
}
.feedback {
  padding: 100px 70px 80px 70px;
  text-transform: uppercase;
  font-size: 13px;

    & p:nth-child(2) {
      margin-top: 5px;
      text-transform: none;
    }
}
.feedback__emoji {
  justify-content: space-between;
  margin-top: 30px;
  height: 50px;

  svg {
    box-sizing: initial;
    width: 25px;

    &.selected {
      border: 12px solid #EBEBF3;
      border-radius: 50%;

      circle#Oval {
        fill: #EBB34B;
      }
      polygon#Path  {
        fill: #EBB34B;
      }
    }
  }
}
</style>

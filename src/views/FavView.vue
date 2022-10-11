<template>
  <div class=favList>
    <div class="container">
      <div class="wrapper" v-for="(data, index) in favLists" :key="data.id">
        <svg version="1.1" id="af01" xmlns="http://www.w3.org/2000/svg" x="0" y="0" viewBox="0 0 1280 800" style="enable-background:new 0 0 1280 800" xml:space="preserve">
          <path :style="{fill: data.logo}" id="logo" d="m711.2 386.6.3-.1c0 4.3-4.5 10.8-4.5 15V426c0 5.4 1.9 9.8 4.5 14.5 1.1 1.9 1.9 5.1 2.4 7.1.7 2.5 4.8 2.5 5.1 4.9.6 5.3 12.9 7.9 16.5 9.5 5.4 2.4 12.8 2.5 19 2.5h23c4.6 0 11.4-1.6 16-1 4.5.6 12.2-3.5 17-3.5 4.9 0 12.3-2 17-3 5.6-1.1 11.2-1.5 16.9-1.5 9 0 18.9-1.1 27.6-3.5 14-3.9 25.6-6.6 40-7.5 5.6-.3 18.1-3.3 23.5-4.5 5.1-1.1 10.5-1.1 15.5-3 11.9-4.5 19.5-4 31.5-8 4.4-1.5 10.2-1.9 14.5-3.5 2.7-1 6.2-2.8 9-3 5.3-.4 6.5.2 11.5-1.5 3.4-1.2 8.7-.7 12-2.5 4.8-2.6 8.2-2.2 13.5-2.5 2.7-.2 8.7 1.3 7.5-3-.8-2.7-11.4-5.5-14-6.5-4.8-1.8-13.5-5.3-17.5-8.5-4.9-3.9 11.9-8.3 14.5-8.5 11-5 4.8-5.5 15-11.5 4.4-2.6 18.7-23.1 22.5-26 5.6-4.2 5.2-11.2 10-16 4.4-4.4 11.4-15 14.5-20.5 2.1-3.8 8.1-9 13-9 13.5 0 17.1 14.4 17.5 26 5.5 12.7 4.7 23.9 8 34.5 3.8 12.5 7 27.2 7 40.5 0 6.8 3.5 13.4 5 20 1.1 4.8 2.2 9.7 2.5 14.7.3 4.4 1 7.2 1 11.8v.1c0 2.4 0 4.7 1.5 6.7.7.9-2.6 2.9-5.8 0-7.2-6.5-4.6-1.9-11.7-8.3-1.8-1.7-11.2-12.2-13-14-2-2-6.9-7.5-9.5-9-4.7-2.7-9.1 1.8-15 3.5-6.2 1.8-14.4 2.8-20.5 5.5-10 4.4-20 5-30 10-8.6 4.4-17.7 4.7-26.5 8.5-4.2 1.8-11.6 3.4-16.1 4.4l-.4.1c-5.2 1.1-11.8 4.8-17 5-5.6.2-8.5 4-14 5-8.6 1.6-15.7 5-24.5 5.4-9.9.5-19.1 7.6-29 7.6-3.8 0-9.9 3.1-13.5 4-10.6 2.6-18.4 5.3-29.5 6-10.6.6-20.2 5.6-30.5 7.5-4.4.8-10.7 3-15 4-8 1.8-14.7 4.5-23 4.5-6.3 0-12.6 1-18.5 3.3-9.2 3.6-17.4 3-27 5.2-4.8 1.1-8.2 1.6-13 3-4.9 1.5-10 3.5-15 4-8.8.9-17.1 2.5-26 2.5-7.6 0-18.9-2.5-26.5-2.5-6.9 0-12.7-1.2-19-4-4.2-1.8-8.9-2.1-11.5-6-1.7-2.5-7.1-5.6-9.5-8-2.2-2.2-3.4-5.7-5-8.5-2.6-4.7-11-17.5-8.5-23-1-5.5.6-12.8 2-19 1.6-6.8 4.1-10.1 8.1-16 1.9-2.9 2.6-7.1 4.9-9.5 1.8-1.8 5.7-4.5 7.8-5.9l.2-.1c4.5-3 5.9-7 9.5-11 1.8-2 5.9-4.9 8.5-6 4.5-2 7.4-7.2 11.5-9.5s8.4-3.2 12-6c4.8-3.7 12.8-5.5 19.7-6.9z"/>
          <path :style="{fill: data.sole}" id="sole" d="M121 672.5c-6.4-12.1-2.5-21-2.5-37 7 0 9 4.5 16 4.5 6.4 0 13.2 4.5 18.5 4.5 13.2 0 18.5 14.1 31 18 9.5 3 14.2 10.7 23.6 13.9 10 3.4 62.3 12.4 71.9 17.1 13.5 0 12.5 0 42 3 23.5 0 96 5 119.5 5 19-1.2 38.2.1 57 2 38.7 3.9 76.7 1.8 114.5 4 52.6 3.1 106.7.5 159.5.5 51.5-2.5 103.8-2.5 155.5-2.5 18.3 0 37.7-2 56-2 20.7 0 43.3 3.6 63-2 10.4-3 21.2.5 32.5.5 14.8 0 26.1-2.8 40-5.9 6.4-1.4 32.8-11.4 38.6-5.7 1.7 1.7-5.3 15-6.1 17.6-2.2 7.1-10.1 16-18 16-18.9 0-24 7.5-54.5 5-13 .5-13.4 2.9-21.5 2.9-12.8 0-24.6-2.7-36.5 0-7.6 1.7-14.3 1.6-22 1.6-12 0-27 2.1-38.6 2.6-8.8.3-17.7 0-26.4 0H796c-34.4 0-67.7 2-102.1 2-57.5 0-115.8-4.5-173.4-4.5H426c-37.3 0-67-6-104.5-6-25.1 0-60-5.6-71.5-9.5-14.2-4.8-32.9-1.8-46-8-8.7-4.1-17.7-2.9-27-5.5-10.5-3-10.5-2.5-33.5-6.5-13.5-3.1-19.9-20.8-22.5-25.6z"/>
        </svg>
        <img id="bg__img" src="@/assets/af1_01_v02.jpg" alt="">
        <button class="btn__del" @click="deleteFav(index)">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x" viewBox="0 0 16 16">
            <path d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z"/>
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        favLists: [],
      }
    },
    mounted() {
      if(localStorage.getItem('shoes')) {
        this.favLists = JSON.parse(localStorage.getItem('shoes'));
        console.log(this.favLists)
      }
    },
    methods: {
      deleteFav(index) {
        this.favLists.splice(index, 1);
        const deletedJsonData = JSON.stringify(this.favLists);
        localStorage.setItem('shoes', deletedJsonData)
      }
    },
  }
</script>


<style scoped>
.container {
  display: flex;
  flex-wrap: wrap;
  gap: 2%;
}

.wrapper {
  position: relative;
  width: 48%;
  margin-bottom: 20px;
}

.btn__del {
  border: solid 1px black;
  position: absolute;
  top: 10px;
  right: 10px;
  z-index: 100;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: #fff;
}

.btn__del:hover {
  background-color: #eee;
}


/* 背景画像 */
#bg__img {
  position: absolute;
  top: 0%;
  left: 0;
  width: 100%;
  height: auto;
}
/* カラーパレット */
.colors {
  list-style: none;
  display: flex;
}

.color {
  width: 50px;
  height: 50px;
  border: solid 2px #aaa;
  border-radius: 50%;
  cursor: pointer;
  transition: all 1.2s;
}

.color:hover {
  transform: scale(1.2);
  border: solid 2px #000;
}

/* UI */
#ui__wrapper {
  position: fixed;
  bottom: 4%;
  right: 2%;
  z-index: 10;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  gap: 10px;
}

/* operation */
#af01 {
  position: relative;
  top: 0%;
  z-index: 10;
  mix-blend-mode: screen;
}

#af01 > path:hover {
  stroke: gray;
  stroke-width: 4px;
  stroke-dasharray: 15 5;
}

#af01 > path:focus {
  stroke: gray;
  stroke-width: 4px;
  stroke-dasharray: 15 5;
}

.operation {
  list-style: none;
  display: flex;
  align-items: center;
  margin-left: 100px;
  gap: 20px;
}

.operation button {
  background-color: #ccc;
  border: solid 1px #999;
  border-radius: 99999999px;
  padding: 0.2em 0.5em;
  font-size: 1.6rem;
}

#logo {
  cursor: pointer;
}


</style>
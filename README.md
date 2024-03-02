Udemy課程練習 #href連結 #random

1.hmtl a href的寫法

    <a href="https://vuejs.org/"> about Vue </a>

2.動態綁定href

    <!-- html -->
    <a v-bind:href="vueLink"> about Vue </a>

2-1 利用JavaScript 綁定html的連結 

    data() {
      return {
        vueLink: "https://vuejs.org/",
      };
    },

3.Random 數學函示介於0~1之間

    Math.random()

    

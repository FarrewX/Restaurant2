<script setup>
import {ref} from 'vue'
</script>

<template>

  <div class="row g-5">
    <div class="col-md-8">
      <h3 class="pb-4 mb-4 fst-italic border-bottom">
        รีวิว
      </h3>

      <div class="blog-post" v-for="(item, index) in Review" :key="index">
          <article>
          <h2 class="display-5 link-body-emphasis mb-1">{{ item.title }}</h2>
          <p class="blog-post-meta">update {{ item.date}}</p>
          <hr>
          <blockquote class="blockquote">
            <p>ได้คะแนนรีวิว</p>
          </blockquote>
        </article>


        <article class="blog-post">
          <table class="table">
            <thead>
              <tr>
                <th>ชื่อ</th>
                <th>ความอร่อย</th>
                <th>ความสะอาด</th>
              </tr>
            </thead>
            <tbody v-for="i in 5">
              <tr>
                <td>{{score[i].name}}</td>
                <td>{{score[i].delicious}}</td>
                <td>{{score[i].clean}}</td>
              </tr>
            </tbody>
          </table><br><br>
        </article>

      </div>

      
    </div>
  </div>
</template>

<script>
const Review = ref([
  {
    title: 'ต๋องเต็มโต๊ะ',
    date : 'January 1, 2021',
  },
  {
    title: 'ข้าวซอยแม่สาย',
    date : 'January 2, 2021',
  },
  {
    title: 'Papa Curry',
    date : 'January 3, 2021',
  },
  {
    title: 'ครัวอาจารย์สายหยุด',
    date : 'January 4, 2021',
  },
  {
    title: 'คั่วไก่นิมมาน',
    date : 'January 5, 2021',
  },
]);

const score = ref([
  {
    name:'',
    delicious : '',
    clean: ''
  },
  {
    name:'bob',
    delicious : '9',
    clean: '9'
  },
  {
    name: 'jane',
    delicious : '10',
    clean: '9'
  },
  {
    name: 'mark',
    delicious : '8',
    clean: '10'
  },
  {
    name: 'tiw',
    delicious : '10',
    clean: '10'
  },
  {
    name: 'vew',
    delicious : '8',
    clean: '10'
  },
]);
</script>

<style scoped>

</style>
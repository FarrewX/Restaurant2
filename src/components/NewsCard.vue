<script setup>
import { ref } from 'vue';
import { RouterLink } from 'vue-router'

</script>

<template>
  <div class="row mb-2">
    <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
      <div class="card" style="margin-left: 30px; margin: auto; padding: auto;" v-for="(item, index) in ShopList" :key="index">
        <RouterLink :to="{name: 'info', params: {id: index}}">
          <img :src="item.imageUrl">
        </RouterLink>
        <p style="font-size: 20px;">ร้าน {{ item.title }}</p>
        
      </div>
    </div>
    
  </div>
    
</template>

<script>
const ShopList = ref([
  {
    title: 'ต๋องเต็มโต๊ะ',
    imageUrl: 'image/tonk.jpg',
    additionalInfo: 'ddd'
  },
  {
    title: 'ข้าวซอยแม่สาย',
    imageUrl: 'image/maa.jpg',
    additionalInfo: 'aaaa'
  },
  {
    title: 'Papa Curry',
    imageUrl: 'image/papa.jpg',
    additionalInfo: 'wwww'
  },
  {
    title: 'ครัวอาจารย์สายหยุด',
    imageUrl: 'image/sai.jpg',
    additionalInfo: 'ssss'
  },
  {
    title: 'คั่วไก่นิมมาน',
    imageUrl: 'image/nim.jpg',
    additionalInfo: 'eeee'
  },
]);
</script>


<style scoped>
body {
  font-family: Arial, sans-serif;
}

img{
  width: 250px;
  height: 200px;
}
.card {
  width: 250px;
  margin: 5px;
  margin-right: 30px;
  margin-top: 40px;
  padding: auto;
  display: inline-block;
  cursor: pointer;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 10px;
  text-align: center;
}
.card-container {
  position:fixed;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
}

.popup {
  display: none;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7);
  display: flex;
  justify-content: center;
  align-items: center;
}

.popup-content {
  background-color: white;
  padding: 20px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  border-radius: 5px;
  text-align: center;
}


form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

label {
  font-weight: bold;
}

input {
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 5px 15px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.buttonc {
  padding: 5px 15px;
  background-color: #d50202;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}


button:hover {
  background-color: #0056b3;
}
</style>
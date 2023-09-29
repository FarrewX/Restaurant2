<script setup>
import buttonf from './buttonf.vue';

</script>

<template>
    <h1>คั่วไก่นิมมาน</h1><br>
        <header>
            <p>ร้านอาหารเรียบง่าย ขายเมนูเส้นจานเด็ดในบรรยากาศครึกครื้น มีที่นั่งรับประทานอาหารแบบเปิดโล่ง</p><br>
             <div id="imgList">
                 <img class="images" src="\src\assets\image\innim\nimman111.png" alt="1">&ensp;
                 <img class="images" src="\src\assets\image\innim\nimman222.png" alt="2">&ensp;
                 <img class="images" src="\src\assets\image\innim\nimman333.png" alt="3">
             </div>
         </header>
         <main>
            <section id="store-info">
                <br><br><br><h2>ข้อมูลร้าน</h2>
                <p>9 ซอย สายน้ำผึ้ง ตำบลสุเทพ อำเภอเมืองเชียงใหม่ เชียงใหม่ 50200</p>
                <p>โทรศัพท์: 082-1801177</p> <br>
            </section>
            <div>
                <buttonf /> <br>
            </div>
        </main>
 </template>
 
 <style>
.images{
    height: 200px;
    width: auto;
}
 </style>
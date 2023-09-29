<script setup>
import buttonf from './buttonf.vue';

</script>

<template>
    <h1>ข้าวซอยแม่สาย</h1><br>
        <header>
            <p>อาหารอร่อย สะอาด ใส่ใจบริการ</p><br>
             <div id="imgList">
                 <img class="images" src="\src\assets\image\inmaa\maa111.png" alt="1">&ensp;
                 <img class="images" src="\src\assets\image\inmaa\maa222.png" alt="2">&ensp;
                 <img class="images" src="\src\assets\image\inmaa\maa333.png" alt="3">
             </div>
         </header>
         <main>
            <section id="store-info">
                <br><br><br><h2>ข้อมูลร้าน</h2>
                <p>29, 1 ซอย ราชพฤกษ์ ตำบลช้างเผือก อำเภอเมืองเชียงใหม่ เชียงใหม่ 50300</p>
                <p>โทรศัพท์: 053-213284</p> <br>
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
<script setup>
import buttonf from './buttonf.vue';

</script>

<template>
    <h1>Papa Curry</h1><br>
        <header>
            <p>อาหารอร่อย บริการดี ถูกสุขลักษณะอนามัย</p><br>
             <div id="imgList">
                 <img class="images" src="\src\assets\image\inpapa\papa111.png" alt="1">&ensp;
                 <img class="images" src="\src\assets\image\inpapa\papa222.png" alt="2">&ensp;
                 <img class="images" src="\src\assets\image\inpapa\papa333.png" alt="3">
             </div>
         </header>
         <main>
            <section id="store-info">
                <br><br><br><h2>ข้อมูลร้าน</h2>
                <p>14 ถนน สิโรรส 5 ตำบลสุเทพ อำเภอเมืองเชียงใหม่ เชียงใหม่ 50200</p>
                <p>โทรศัพท์: 082-6204440</p> <br>
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
<script setup>
import buttonf from './buttonf.vue';

</script>

<template>
   <h1>ครัวอาจารย์สายหยุด</h1><br>
        <header>
            <p>อาหารอร่อย สะอาด สดใหม่ทุกวัน</p><br>
            <div id="imgList">
                <img class="images" src="\src\assets\image\insai\saiyut111.png" alt="1">&ensp;
                <img class="images" src="\src\assets\image\insai\saiyut222.png" alt="2">&ensp;
                <img class="images" src="\src\assets\image\insai\saiyut333.png" alt="3">
            </div>
        </header>
        <main>
            <section id="store-info">
                <br><br><br><h2>ข้อมูลร้าน</h2>
                <p>32 ถนน ศรีลานนา ตำบลป่าตัน อำเภอเมืองเชียงใหม่ เชียงใหม่ 50300</p>
                <p>โทรศัพท์: 081-5301172</p>
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
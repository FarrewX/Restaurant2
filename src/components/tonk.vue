<script setup>
import buttonf from './buttonf.vue';

</script>


<template>
    <h1>ต๋องเต็มโต๊ะ</h1><br>
        <header>
            <p>ร้านอาหารขนาดใหญ่พร้อมที่นั่งเอาท์ดอร์ร่มรื่น เสิร์ฟเมนูแกง แกงผักรสเผ็ด และอาหารเมนูดั้งเดิมอื่นๆ</p><br>
            <div id="imgList">
                <img class="images" src="\src\assets\image\intonk\111.png" alt="1">&ensp;
                <img class="images" src="\src\assets\image\intonk\222.png" alt="2">&ensp;
                <img class="images" src="\src\assets\image\intonk\333.png" alt="3">
            </div>
        </header>
        <main>
            <section id="store-info">
                <br><br><br><h2>ข้อมูลร้าน</h2>
                <p>11 13 ถนนนิมมานเหมินท์ ตำบลสุเทพ อำเภอเ มือง, เชียงใหม่ 50200</p>
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
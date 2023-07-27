<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
    {
        'src': 'https://sc04.alicdn.com/kf/Ha967d70de576436dba03e4662ae46578Z.jpg',
        'alt': 'Picture 1',
    },
    {
        'src': 'https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//109/MTA-18751969/bos_bos_gelang_kesehatan_pria_wanita_hematite_magnet_batu_black_onyx_hitam_keren_murah_terbaru_2021_full01_erugm05h.jpg',
        'alt': 'Picture 2',
    },
    {
        'src': 'https://assets.pikiran-rakyat.com/crop/0x0:0x0/x/photo/2021/01/17/1043030952.jpg',
        'alt': 'Picture 3',
    },
    {
        'src': 'https://www.tekzoe.com/wp-content/uploads/2023/04/Cincin-Emas-Ala-Korea-400x400.png',
        'alt': 'Picture 4',
    },
    {
        'src': 'https://ae01.alicdn.com/kf/Hf88ae800f9444f289f2ef5b0f4775b50K/DAXI-Kalung-Rantai-Warna-Emas-Trendi-Kalung-Berlapis-untuk-Wanita-Set-Kalung-Rantai-Liontin-Kalung-Tebal.jpg',
        'alt': 'Picture 5',
    },
]
</script>
<template>
    <Carousel :pictures="pictures"></Carousel>
</template>

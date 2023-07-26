<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
    {
        'src': 'https://alwaystrendy.files.wordpress.com/2011/10/rings1.jpg',
        'alt': 'Picture 1',
    },
    {
        'src': 'https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//113/MTA-9979448/no-brand_gelang-pria-keren-gelang-wanita-gelang-tali-pria-gelang-tangan-wanita-gelang-cowok-aksesoris-fashion_full15.jpg',
        'alt': 'Picture 2',
    },
    {
        'src': 'https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//104/MTA-49751933/oem_oem_full01.jpg',
        'alt': 'Picture 3',
    },
    {
        'src': 'https://www.tekzoe.com/wp-content/uploads/2023/04/Cincin-Emas-Ala-Korea-400x400.png',
        'alt': 'Picture 4',
    },
    {
        'src': 'https://media.istockphoto.com/id/1343282698/id/vektor/wanita-kartun-perhiasan-kalung-perak-emas-gelang-anting-anting-cincin-wanita-perhiasan.jpg?s=1024x1024&w=is&k=20&c=U8PJNMlIR7srnF2tQyajDA546jFom4uSaOFu46kvdQc=',
        'alt': 'Picture 5',
    },
]
</script>
<template>
    <Carousel :pictures="pictures"></Carousel>
</template>

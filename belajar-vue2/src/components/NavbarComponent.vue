<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
        <template #logo>
            <NavbarLogo image-url="https://cdn.kibrispdr.org/data/69/desain-logo-toko-aksesoris-5.png">
                MyAccessories
            </NavbarLogo>
        </template>
        <template #default="{ isShowMenu }">
            <NavbarCollapse :isShowMenu="isShowMenu">
                <NavbarLink is-active>Beranda</NavbarLink>
                <NavbarLink>Tentang</NavbarLink>
                <NavbarLink>Foto</NavbarLink>
                <NavbarLink>Kontak</NavbarLink>
            </NavbarCollapse>
        </template>
    </Navbar>
</template>

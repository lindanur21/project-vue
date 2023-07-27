<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
        <template #logo>
            <NavbarLogo image-url="https://cdn.kibrispdr.org/data/742/logo-aksesoris-wanita-4.png">
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
<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar fixed="top">
      <template #logo>
        <NavbarLogo link="#" alt="Flowbite logo" image-url="https://www.pngplay.com/wp-content/uploads/2/Muscle-PNG-Free-File-Download.png">
          Muscle King
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#wave">About</NavbarLink>
          <NavbarLink link="#produk">Produk</NavbarLink>
          <NavbarLink link="#footer">kontak</NavbarLink>
        </NavbarCollapse>
      </template>
      <template #right-side>
          
        <button type="button" class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Masuk</button>
        <button type="button" class="text-white bg-gradient-to-r from-blue-500 via-blue-600 to-blue-700 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">Daftar</button>
        
      </template>
      
    </Navbar>
</template>
<style>
 html{
     scroll-behavior: smooth;;
   }
</style>

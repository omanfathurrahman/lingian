<template>
  <div>
    <header class="flex justify-between border h-[5rem] items-center px-[5rem]">
      <span class="text-xl font-bold">logo</span>
      <div class="flex items-center gap-8">
        <a href="" class="hover:text-pink-400">Home</a>
        <a href="" class="hover:text-pink-400">About</a>
        <a href="" class="hover:text-pink-400">Research</a>
        <span class="relative group h-[5rem] flex items-center">
          <Icon name="solar:hamburger-menu-linear" class="text-2xl group-hover:text-pink-400" />
          <div
            class="absolute top-[5rem] left-0 bg-white p-4 shadow-lg hidden group-hover:flex group-hover:flex-col group-hover:gap-3">
            <a href="" class="hover:text-pink-400">Business</a>
            <a href="" class="hover:text-pink-400">Research</a>
            <a href="" class="hover:text-pink-400">Inovation</a>
            <a href="" class="hover:text-pink-400">Pengabdian Masyarakat</a>
          </div>
        </span>
      </div>
      <div class=""></div>
    </header>
    <div id="hero" class="h-[calc(100dvh-5rem)] grid grid-cols-2 px-[5rem] items-center gap-6">
      <div class="">
        <h1 class="text-4xl font-semibold mb-2">Lingian Hotel</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua</p>
      </div>
      <div class="">
        <img
          src="https://images.unsplash.com/photo-1455587734955-081b22074882?q=80&w=1920&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
          alt="" class="rounded-md">
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style></style>
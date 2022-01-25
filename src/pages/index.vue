<script setup lang="ts">

</script>

<template>
  <div class=" rounded flex items-center justify-center mt-20 mx-auto">
    <form class="bg-youx p-5 flex items-center  text-center text-white flex-col shadow w-[450px]">
      <h1 class="font-bold p-5 text-2em">
        LOGIN
      </h1>
      <div class="w-full relative">
        <mdi:account class="absolute mt-11 ml-3 text-gray-500" />
        <input class="p-5 pl-10 mt-5 w-full rounded text-black" type="text" placeholder="CPF / LOGIN">
      </div>
      <div class="w-full relative">
        <mdi:key-chain-variant class="absolute mt-11 ml-3 text-gray-500" />
        <input class="p-5 pl-10 mt-5 w-full rounded text-black" type="password" placeholder="SENHA">
      </div>
      <button class="bg-light-900 font-bold p-5 mt-5 w-full rounded text-youx" hover="bg-white">
        ENTRAR
      </button>
    </form>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>

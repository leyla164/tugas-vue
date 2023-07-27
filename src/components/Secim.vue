<script setup>
import { TheCard, Rating } from 'flowbite-vue'
</script>
<template>

<br>
<p style="font-size: xx-large;"><center><b>Summer Outfits</b></center></p>
<br>
<div class="flex flex-row">
  <div class="grid grid-cols-1 gap-1 m-8">
    <the-card variant="image" img-src="https://i.pinimg.com/564x/22/3c/ed/223ced6cbaecb63ce6a5d9c512a52f23.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Kendall Jenner Just wore the Coolest Olsen-Inspired Summer Outfit</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      “Lagi cari kardigan yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!
    </p>

  <br>
  <Rating :rating="4">
    <template #besideText>
        <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
      </template>
  </Rating>

  </the-card>
</div>

  <br>
  <div class="grid grid-cols-1 gap-1 m-8">
    <the-card variant="image" img-src="https://i.pinimg.com/564x/5f/5d/e1/5f5de145a69aab3a9e804922d126afe1.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">great vest for spring</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      “Lagi cari rompi yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!""
    </p>

  <br>
  <Rating :rating="4">
    <template #besideText>
        <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
      </template>
  </Rating>

  </the-card>
  </div>

  <br>
  <div class="grid grid-cols-1 gap-1 m-8">
    <the-card variant="image" img-src="https://i.pinimg.com/564x/7f/fa/7f/7ffa7faebe410b6a890e0f44aa93ba97.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">A Few Cosy Pieces For Chilly  Summer Outfit</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      “Lagi cari kardigan yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!"
    </p>

  <br>
  <Rating :rating="4">
    <template #besideText>
        <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
      </template>
  </Rating>

  </the-card>
  </div>
   
  <div class="grid grid-cols-1 gap-1 m-8">
    <the-card variant="image" img-src="https://i.pinimg.com/564x/ef/ac/18/efac1871bee6bf611bcafead1c60795c.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">I Never Liked This Colour Trend Until I Saw & Other Stories</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
      “Lagi cari kardigan yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!"
    </p>

  <br>
  <Rating :rating="4">
    <template #besideText>
        <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
      </template>
  </Rating>
  </the-card>
  </div>

</div>
 
</template>
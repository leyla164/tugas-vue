<script setup>
import { TheCard, Rating } from 'flowbite-vue'
</script>
<template>

<br>
<p style="font-size: xx-large;"><center><b>Summer Outfits</b></center></p>
<br>
<div class="flex flex-row">
  <div class="grid grid-cols-1 gap-1 m-8">
    <the-card variant="image" img-src="https://i.pinimg.com/564x/8e/ec/48/8eec48226d0509942faaf8c1a41fbc1f.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Kendall Jenner Just wore the Coolest Olsen-Inspired Summer Outfit</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        “Lagi cari baju yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!"
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
    <the-card variant="image" img-src="https://i.pinimg.com/564x/d6/d7/64/d6d764f5dfec80cf837400d6f5f0fff0.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Drop Shoulder Plaid Sweater</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        “Lagi cari baju yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!"
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
    <the-card variant="image" img-src="https://i.pinimg.com/564x/dc/67/8b/dc678bc21cc0ddeb6b9c650e031d19e2.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">A Few Cosy Pieces For Chilly  Summer Outfit</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        “Lagi cari baju yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!"
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
    <the-card variant="image" img-src="https://i.pinimg.com/564x/0d/5c/27/0d5c27c751db41ed0958852283223fea.jpg" img-alt="Desk">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">I Never Liked This Colour Trend Until I Saw & Other Stories</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        “Lagi cari baju yang murah, bahan dan kualitas oke? Ya Sweaterku solusinya!
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
<template>
  <div class="card-container m-20" v-for="post in posts">
    <div class="flex card-content">
      <div class="card-image" v-if="post.img"> 
        <img class="rounded-lg md:w-56" :src="`/assets/img/${post.img}`" alt="Image description"> 
      </div>
      <div class="card-text">
        <!-- <NuxtLink :to="{ hash: `#${formatSlug(post.title)}` }">
          <h2 class="h-2">{{ post.title }}</h2>
        </NuxtLink> -->
        <p>{{ post.date }}</p>
        <p>{{ post.content }}</p>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
  import { defineProps } from 'vue'

  defineProps(['posts'])

  // function formatSlug(postTitle: string): string {
	// 	return postTitle.trim().toLowerCase().replace(/\s/g, '-')
	// }
</script>
  
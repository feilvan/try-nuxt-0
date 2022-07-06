<script setup>
useHead({
  title: 'rawr!',
  link: [
    { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap' }
  ]
})
</script>

<template>
  <div class="flex flex-1 flex-col p-4 w-full h-screen max-w-5xl my-0 mx-auto">
    <NuxtLayout>
      <NuxtPage/>
      <footer>
		    <span>©{{new Date().getFullYear()}} truclr</span>
	    </footer>
    </NuxtLayout>
  </div>
</template>

<style>
:root {
  @apply bg-black text-white;
  font-family: 'JetBrains Mono', monospace;
}
footer {
  @apply flex flex-col justify-center items-center;
}
</style>
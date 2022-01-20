<template>
  <div class="home">
    <img
      class="mx-auto"
      alt="Vue logo"
      src="https://www.datocms-assets.com/48401/1628644787-tailwind-vue.png"
    >
    <HelloWorld msg="Welcome to Your Vue + Tailwind App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

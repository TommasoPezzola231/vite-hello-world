<script>
import HelloWorld from './components/HelloWorld.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    HelloWorld,
    AppHero
  }
}
</script>

<template>
  <header>
    <HelloWorld src="./components/HelloWorld.vue" />
  </header>

  <main>
    <AppHero src="./components/AppHero.vue" />
  </main>
</template>

<style scoped></style>

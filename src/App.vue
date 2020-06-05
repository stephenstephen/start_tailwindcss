<template>
  <div id="app" class="antialiased text-gray-900">
    <div class="bg-gray-200 min-h-screen">
      <Navbar/>
      <Card/>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Card from './components/Card'

export default {
  name: 'app',
  components: {
    Navbar,
    Card
  },
}
</script>

<style src="./assets/tailwind.css"></style>

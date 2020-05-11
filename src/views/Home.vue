<template>
  <div class="home">

    <h1>{{msg}}</h1>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  data() {
    return {
      msg: "This is the Home page"
    }

  }
}
</script>

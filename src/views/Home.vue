<template>
  <div class="vh">
    <div class="container">
      <div class="six columns home">
        <h1 class="zero semi">Sahyog</h1>
        <h5>All in one hospital management.</h5>

        <router-link to="/about">
          <button class="cool">About</button>
        </router-link>
      </div>
      <div class="six columns">
        <div>
          <img
            src="@/assets/illustration.svg"
            draggable="false"
            alt="illustration"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
}
</script>

<style scoped>
.home {
  margin-top: 9em;
}

.vh {
  height: 83vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <v-app>
    <v-main>
    <div class="caja"></div>
    <div class="cajas">
    <div class="cajagrande">cajagrande1</div>
     <div class="cajagrande">cajagrande2</div>
     </div>
      <v-container>
      </v-container>
    </v-main>
  </v-app>
</template>

<style>
body {
background-color:rgb(255, 255, 255);
font-family: Verdana, sans-serif;
padding: 20px;
}

.caja{
  background-color:black;
  border: 2px solid #ccc;
padding: 18px;
margin-top: 20px;
border-radius: 8px;
width: 750px;
}
.cajagrande{
border-radius:8px;
border: 2px solid #ccc;
width: 375px;
padding: 180px;
margin-top: 15px;
vertical-align: middle;
}
</style>
<script setup>
</script>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

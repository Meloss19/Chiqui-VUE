<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <v-app>
    <v-main>
    <div class="cajagrande" style="width: 350px;">
    <img src="c:\Users\m2G\Downloads\fcb.jpg" style="margin-left: 35px; width:280px; height: 180px;
    margin-top: 20px; border-radius: 10px;"/>
    <h1 style="position: absolute; left: 460px; top: 300px; font-size: 30px;"> FC BARCELONA </h1>
    <div>
    <p1 style="position: absolute; left: 460px; top: 350px; font-size: 20px; max-width: 350px;"> El FC Barcelona es un club de fútbol español. </p1>
    </div>
    <div></div>
    <v-btn class="accion" style="height:50px;"> Acción </v-btn>
    </div>
    <div class="caja-pequeña">
    <img src="c:\Users\m2G\Downloads\fcb2.jpg" style="width: 50px; height: 50px; margin-left: 25px; margin-top: 16px; border-radius: 50px;"/>
     <h2 style="position: absolute; left: 540px; top: 535px;
      font-size: 15px;"> FC BARCELONA </h2>
      <p style="position: absolute; left: 540px; top: 552px;"> Información</p>
      <v-menu offset-y>
    <template #activator="{ props }">
      <v-btn icon v-bind="props" style="position: absolute; left: 740px; bottom: 60px;" variant="plain">
        <v-icon color="black">mdi-dots-vertical</v-icon>
      </v-btn>
    </template>

    <v-list>
      <v-list-item @click="accion1">
        <v-list-item-title>Opción 1</v-list-item-title>
      </v-list-item>
      <v-list-item @click="accion2">
        <v-list-item-title>Opción 2</v-list-item-title>
      </v-list-item>
    </v-list>
  </v-menu>
    </div>
    </v-main>
  </v-app>
</template>

<style>
body {
background-color:white;
font-family: Verdana, sans-serif;
padding: 25px;
}
.v-main{
  border-radius: 16px;
background-color: gray;
}
.accion{
  background: linear-gradient(to right, blue,rgb(255, 0, 0));
  width:340px;
  margin-left: 5px;
  margin-top: 170px;
}
.caja-pequeña{
  background-color: white;
  width:350px;
  height:85px;
  margin-left: 450px;
  margin-top: 25px;
  border-radius: 20px;
}
.cajagrande{
  background-color: white;
border-radius:30px;
border: 1px solid black;
height:450px;
margin-top: 40px;
margin-left: 450px;
}

</style>
<script setup>
</script>

<style scoped>
.accion{
  border-radius: 40px;
  color: white;
  background: linear-gradient(to right, blue,rgb(255, 0, 0));
}
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

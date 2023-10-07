<script setup lang="ts"></script>

<template>
  <h1 class="name">Masashi Kawakami</h1>
  <h2 class="title">Web Developer</h2>
  <div class="menu-wrapper">
    <h3 class="menu-item">Profile</h3>
    <h3 class="menu-item">Skills</h3>
    <h3 class="menu-item">Projects</h3>
    <h3 class="menu-item">Contact</h3>
  </div>
</template>

<style scoped>
.name {
  color: rgb(233, 233, 233);
  text-shadow: 3px 3px 20px black, -2px 1px 30px black;
  font-size: 100px;
  font-family: "Menlo", sans-serif;
  position: absolute;
  top: 300px;
  left: 80px;
}
.title {
  color: rgb(233, 233, 233);
  text-shadow: 3px 3px 20px black, -2px 1px 30px black;
  font-size: 60px;
  font-family: "Menlo", sans-serif;
  position: absolute;
  top: 450px;
  left: 80px;
}
.menu-wrapper {
  position: absolute;
  color: rgb(233, 233, 233);
  padding-right: 100px;
  padding-bottom: 50px;
  float: right;
  right: 0;
  bottom: 0;
  font-size: 40px;
  font-family: "Menlo", sans-serif;
  text-shadow: 3px 3px 20px black, -2px 1px 30px black;
}
.menu-item::before {
  content: "▶︎";
  padding-right: 15px;
}
</style>

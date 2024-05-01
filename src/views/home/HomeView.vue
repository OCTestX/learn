import VueDevTools from 'vite-plugin-vue-devtools';
<template>
  <div>
    <main>
      <h1>home</h1>
      <img src="./assets/icon.png" alt="" />
      <div id="row1">
        <h1>21</h1>
        <h2>d5efineAsyncComponent</h2>
      </div>

      <div>
        <h1 id="title1">标题1</h1>
        <div id="content1">
          <h2 id="c1">内容1</h2>
        </div>
        <h1 id="title2">标题2</h1>
        <div id="content2">
          <h2 id="c2">内容2</h2>
        </div>
        <div id="row2">
          <div id="r1">12</div>
          <div id="r2">11</div>
          <div id="r3">KHFS</div>
        </div>
        <div id="x1">vue easy</div>
      </div>
    </main>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
#row1 {
  display: flex;
}

#title1 {
  color: #f72585;
}
#content1 {
  background-color: #06d6a0;
  margin: 30px;
  padding: 55px;
  border-radius: 25px;
  width: fit-content;
  height: 250px;
}
#title2 {
  color: #00b4d8;
}
#content2 {
  background-color: #8f2d56;
  margin: 10px;
  padding: 15px;
  border-radius: 5px;
  width: 50%;
}

#row2 {
  display: flex;
}
#r1 {
  background-color: #00b4d8;
  flex-grow: 3;
}
#r2 {
  background-color: #06d6a0;
}
#r3 {
  background-color: #f72585;
  flex-grow: 5;
}

#x1 {
  background-color: #00b4d8;
  border-radius: 6px;
  height: 55px;
  margin: 12px;
  padding: 15px;
}
</style>

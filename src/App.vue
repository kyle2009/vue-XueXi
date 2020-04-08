<template>
  <div id="app">
    <ul>
      <li><router-link to="/" name="view1">首页</router-link></li>
      <li><router-link to="/about" name="view2">About</router-link></li>
    </ul>
    <div>
      <h1>view</h1>
      <router-view></router-view>
    </div>
    <div>
      <h1>view1</h1>
      <router-view name="view1"></router-view>
    </div>
    <div>
      <h1>view2</h1>
      <router-view name="view2"></router-view>
    </div>


  </div>
</template>

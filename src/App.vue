<template>
  <div id="app">
    <Header/>
    <Body/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'; // Import component Header
import Body from './components/Body.vue';

export default {
  name: 'App',
  components: {
    Header, Body // Khai báo component Header để sử dụng trong template
  }
};
</script>

<style>
/* Thêm CSS tùy chỉnh cho toàn bộ ứng dụng tại đây */
#app {
  font-family: Arial, sans-serif;
}

main {
  padding: 20px;
}

h1 {
  font-size: 36px;
  color: #333;
}

p {
  font-size: 18px;
  color: #666;
}
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

main {
  padding: 20px;
}
</style>

<template>
    <div id="app">
      <Header></Header>
      <div class="main-content">
          <router-view/>
      </div>
    </div>
</template>

<script>
import Header from './components/Header';

export default {
    components:{
      Header
    }
}
</script>

<style>
.main-content{
  padding: 105px 25px 0 25px;
  margin-left: 337px;
  z-index: -1;
  min-height: 600px;
  background-color: #f1fdf3;
}
</style>

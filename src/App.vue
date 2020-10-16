<template>
    <div id="app">
      <Header></Header>
      <div class="main-content">
          <router-view/>
      </div>
      <Footer></Footer>
    </div>
</template>

<script>
import Header from './components/Header';
import Footer from './components/Footer';

export default {
    components:{
      Header, Footer
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
@media only screen and (max-width: 768px) {
    .main-content{
        margin-left: 0;    
    }
}
</style>

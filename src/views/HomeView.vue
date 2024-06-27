<template >
  <div class="home">

    <h1 id="hi">Welcome to my Portfolio !!! </h1>
        
    <img  src="https://github.com/siphokuhlenyana/ImagesPortfolio/blob/main/MYPIC.jpg?raw=true" alt="" :style="{borderRadius:'10%',borderWidth:'5px',borderStyle:'solid',borderColor:'#33051c'}">
    
    <home-comp-vue/>
      </div>
</template>

<script>
import HomeCompVue from '@/components/HomeComp.vue'
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
    HomeCompVue
  }
}

</script>
<style scoped>
  .home{
    background-image: url("https://github.com/siphokuhlenyana/ImagesPortfolio/blob/main/MYPIC.jpg?raw=true");
    background-repeat:no-repeat;
    background-size: contain;
    width: 100%;
    height: 100%;
    background-color:#33051c;
  }
  #hi{
    display: flex;
    justify-content: flex-end;
    color: pink;
  }
</style>


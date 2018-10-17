<script>
import Index from "./components/Index.vue";
import Bills from "./components/Bills.vue";


export default {
  name: "app",
  
  components: {
    Index, 
    Bills,
  },
  data: function(){
    return{     
    app: "texto vindo do app"  
    }
  }
  
};
</script>



<template>
  <div id="app">
    <Bills />   
  </div>
</template>





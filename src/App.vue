<script>
import Index from "./components/Index.vue";
import Bills from "./components/Bills.vue";

export default {
  name: "app",
  components: {
    Index, 
    Bills,
  }
};
</script>



<template>
  <div id="app">
    <Index title="LS Star"/> 
    <Bills/> 
  </div>
</template>





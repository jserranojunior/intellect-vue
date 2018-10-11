<script>
import Index from "./components/Index.vue";
import Bills from "./components/Bills.vue";
import Address from "./components/Address";

export default {
  name: "app",
  components: {
    Index, 
    Bills,
    Address,
  }
};
</script>



<template>
  <div id="app">
    <Index title="LS Star"/> 
    
    <Address/> 
  </div>
</template>





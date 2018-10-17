<template>
<div>

<div class="row">
    <div class="col-12"><h2 class="text-center">FINANCEIRO</h2></div>
</div>
   <div class="row mx-auto">
       <div class=" text-center col-4 offset-4">
     
<div class="card card-sm">
    <div class="card-header">
        DATA
    </div>
    <div class="card-body">
                <date :data="data" />
    </div>
</div>

       </div>
   </div>

</div>
</template>

<script>
import date from "./date.vue";

export default {
  name: "Bills",
  components: {
    date
  },
  data() {
    return {
      data: {
        date: "17/10/2018",
        dateNextMonth: "17/11/2018",
        datePreviousMonth: "17/09/2018"
      }
    };
  }
};
</script>



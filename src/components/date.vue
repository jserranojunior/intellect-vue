<template>
<div>

    <a v-bind:href="'?date=' + data.datePreviousMonth">
        <div class="btn">Proxima</div>
    </a>

    <a v-bind:href="'?date=' + data.date">
        <div class="btn">Atual</div>
    </a>
    
    <a v-bind:href="'?date=' + data.dateNextMonth">
        <div class="btn">Proxima</div>
    </a>

    <div>
   Hoje é dia    {{data.date}}<br>
   Proximo mes:  {{data.dateNextMonth}}<br>
   Mês Anterior: {{data.datePreviousMonth}}<br>
    </div>

</div>
</template>


<script>
export default {
    name: 'date',
    props:{
         data: {
             type: Object | Array,
         },
    }    
}
</script>

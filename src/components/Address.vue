<template>
    <div class="row">
        <div class="col-4 mx-auto">   
            <input type="text" placeholder="cep" id="cep" v-on:click="buscar()" class="form-control">
            <input type="text" placeholder="Logradouro" class="form-control">
        </div>
    </div>
</template>

<script> 
    export default { 
        name: "Address",   
        methods: {
            buscar: function(){
                windows.console.log('teste');
            }
        }    
    };
</script>
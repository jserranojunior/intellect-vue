<script>
    export default {
        name: "Bills",
        data () {
            return{
                title: "Todas as datas",
                data:{
                    meses:{
                        0: "Janeiro", 
                        1: "Fevereiro", 
                    }
                }
            }
        }
    };
</script>


<template>
    <div class="row">
        <div class="col-3 mx-auto">
            <div class="card">
                <div class="card-header">
                    <div class="card-title">{{title}}</div>
                </div>
                <div class="card-body">
                    <button type="button" class="btn text-capitalize btn-sm btn-secondary dropdown-toggle" data-toggle="dropdown"
                        aria-haspopup="true" aria-expanded="false">
                        {{data.meses}}
                    </button>
                    <div class="dropdown-menu">
                       <a v-for="data in items" class="dropdown-item">{{items.data}}</a>                        
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<template>
    <h3 class="text-center">{{title}}</h3>    
</template>

<script>
export default {
  name: 'Index',
  props: {
    msg: String,
    title: String
  }
}
</script>
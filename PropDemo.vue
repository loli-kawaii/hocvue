<template>
  <div class="container">
    <p>{{fullName}}</p>
  </div>
</template>

<script>
export default {
    // props:['fullName'],
    props:{
      fullName:{
        type: String,
        required:true,
        default: 'Default value'
      }
    }
}
</script>

<style>

</style>
<template>
  <div class="container">
    <p>Tuổi: {{age}}</p>
    <button class="btn btn-primary" @click="hanleChanAge">Change age</button>
  </div>
</template>

<script>
export default {
    props:['age'],
    method:{
        hanleChanAge(){
            const newValue = this.age+1;
            this.$emit('OnChangeAge',newValue,'UpdateAge');
        }
    }
}
</script>

<style>

</style>
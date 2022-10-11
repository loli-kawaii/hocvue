<template>
    <div class="container">
        <h1>This is test components</h1>
        <p>{{message}}</p>
    </div>


</template>

<script>
export default {
    data(){
        return{
            message: "Vue CLI Lession1",
        }
    }
}
</script>

<style>
    .container{
        border: 1px solid rgb(162, 0, 255);
    }
</style>
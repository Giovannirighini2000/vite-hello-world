<template>
    <div class="bg-red">
        <h1>{{ message }}</h1>
    </div>
</template>
<script>
export default{
  data(){
    return{
      message:'La mia prima app con Vite!'
    }
  },
}
</script>
<style>
.bg-red{
    background-color: blue;
    color: red;
}
</style>
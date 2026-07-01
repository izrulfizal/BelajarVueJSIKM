<script setup>

defineProps({
  nama: {
    type: String,
    default: 'TVETMARA Besut'
  }
})

</script>

<template>
  <div class="box">
    <h1>Hello!</h1>
    <h3>{{ nama }}</h3>
  </div>
</template>

<style scoped>
.box{
    border: 2px dashed white;
    padding: 30px;
    border-radius: 30px;
    background-color:cadetblue;
    margin: 30px;
}
</style>
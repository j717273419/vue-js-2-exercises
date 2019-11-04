<template>
  <div>
    <hr />
    <h3 class="bg-purple">{{msg}}</h3>
  </div>
</template>
<script>
export default {
    name:"FisrtComponment",
    props:{
        msg:String,
    }
};
</script>
<style>
.bg-purple {
  background-color: lightpink;
}
</style>
<template>
  <div class="pup">
      <div class="pup-top">分享到微信</div>
      <div class="pup-up"></div>
  </div>
</template>
<script>
    export default {
        name:'pup',
        data(){

        }
    }

</script>
<style scoped>
.pup-top{
    background-color: gray;
    color: white;
    height: 40px;
    padding-top: 10px;
    border-radius: 5px 5px;
    white-space: nowrap;
}
.pup-up{
        width: 0;
        height:0; 
        border-left:8px solid transparent; 
        border-right:8px solid transparent; 
        border-bottom:16px solid gray;
        transform: rotate(180deg);
        position: relative;
        top: -3px;
        left: 3px;
}


</style>

<template>
  <div class="goods">
    <div class="menu-wrapper"></div>
    <div class="foods-wrapper"></div>
  </div>
</template>
<style lang="stylus" rel = "stylesheet/stylus">
  .goods
     display: flex
     position: absolute
     top: 174px
     width: 100%
     bottom: 46px
     overflow: hidden
     .menu-wrapper
       flex: 0 0 80px
       width: 80px
       background: #f3f5f7
     .foods-wrapper
       flex: 1


</style>
<script type="text/ecmascript-6">
    export default{
       props: {
         seller: {
            type: Object
         }
       },
       mounted () {
         alert(this.seller.name);
      }
    };
</script>

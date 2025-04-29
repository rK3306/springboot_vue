<template>

  <div>
<!--    head-->
    <Header></Header>
<!--    main-->
   <div style="display: flex">
     <Aside/>
     <router-view style="flex:1"></router-view>
   </div>
  </div>
</template>

<style>


</style>
<script>
import Header from "@/components/header";
import Aside from "@/components/aside.vue"
export default {
  name:"Layout_Header",
  components:{
    Header,
    Aside
  }
}
</script>

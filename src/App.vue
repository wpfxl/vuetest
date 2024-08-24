<template>
   <div>
      <StudentComponent/>
      <hr/>
      <SchoolComponent/>
   </div>
</template>

<script>
import StudentComponent from "@/components/Student";
import SchoolComponent from "@/components/School";
export default {
  name: "App",
  components:{
    SchoolComponent,
    StudentComponent,
  },
}
</script>

<style>
   /*
   全局的样式是不需要加scoped
   全局共享
   */
   .title{
     color: red;
   }
</style>



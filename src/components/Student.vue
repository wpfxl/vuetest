<template>
   <div class="student">
     <h2 class="title">姓名:{{  name }}</h2>
     <h2>性别: {{ sex }}</h2>
   </div>
</template>

<script>

export default {
  name: "StudentComponent",
  data(){
    console.log(this);
    return {
       name: '张三',
       sex: '男',
    }
  },
}
</script>

<style scoped>
  .student{
    background: orange;
    padding: 5px;
    margin-bottom: 10px;
  }
</style>

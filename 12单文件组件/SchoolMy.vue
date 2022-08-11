<template>
    <div id="demo">
         <h2>学校名称{{name}}</h2>
         <h2>学校地址{{address}}</h2>
          <button @click="showName">click me</button>  
    </div>
</template>


<script>
export default {
    name:'SchoolMy',
    data() {  //(){}这种是语法
        return {
            name:"PKIT",
            address:"pking"
        }
    },
    methods: { //这种是对象
        showName(){
            alert(this.name)
        }
    },
        
    
}
</script>

<style>
   #Demo{
    background: orange;
   }
</style>
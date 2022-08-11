<template >
    <div>
        <SchoolMy></SchoolMy>
        <studentMy></studentMy>
    </div>
</template>

<script>
// 引用组件
import SchoolMy from './SchoolMy.vue'
import studentMy from './studentMy.vue'

// app 中使用组件
export default {
    name:'appMy',
    components:{
    SchoolMy,
    studentMy
  
}
}
</script>

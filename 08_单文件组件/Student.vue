<template>
<!-- 组件的结构 -->
    <div class="demo">
        <h2>学生姓名: {{ name }}</h2>
        <h2>学生年龄: {{ age }}</h2>
        <button @click="showName"> 提示学生姓名 </button>
    </div>
</template>

<script>
    // js 代码
    export default {
        name: 'Student',
        data() {
            return {
                name: '郑科院',
                age: 19
            }
        },
        methods: {
            showName(){
                alert(this.name)
            }
        },
    }

</script>

<style>
/*
组件的样式
*/
    .demo{
        background-color: blue;
    }

</style>
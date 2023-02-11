<template>
<!-- 组件的结构 -->
    <div class="demo">
        <h2>学校名称： {{ schooleName }}</h2>
        <h2>学校地址： {{ schooleAddress }}</h2>
    </div>
</template>

<script>
    // js 代码
    export default {
        name: 'School',
        data() {
            return {
                schooleName: '郑科院',
                schooleAddress: '郑州'
            }
        },
        methods: {
            showName(){
                alert(this.schooleName)
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
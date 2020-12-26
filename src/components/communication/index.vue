<template>
    <div>
        <h2>组件通信</h2>
        <!-- props, 自定义事件 -->
        <Child1 msg="some msg from parent" @some-event="onSomeEvent"></Child1>
        <!-- 事件总线 -->
        <Child2></Child2>
    </div>
</template>

<script>
import Child1 from '../communication/Child1'
import Child2 from '../communication/Child2'

export default {
    components: {
        Child1, Child2
    },
    methods: {
        onSomeEvent(msg) {
            console.log('Communition:', msg)
        }
    }
}
</script>

<style lang="less" scoped>
</style>

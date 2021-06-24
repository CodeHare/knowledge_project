<template>
  <div></div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
    msg:  String
    
})

const state = reactive({});

// 组合式 API 的生命周期
// 注：beforeCreate和created已经setup替代
// 挂载前阶段
onBeforeMount(() => {
    // your code
}),

// 挂载阶段
onMounted(() => {
    
}),

// 更新前阶段
onBeforeUpdate(() => {
    
}),

// 更新阶段
onUpdated(() => {
    
}),

// 卸载前阶段
onBeforeUnmount(() => {
    
}),

// 卸载阶段
onUnmounted(() => {
    
}),

// 捕获错误
onErrorCaptured(() => {
    
}),

// 渲染
onRenderTracked(() => {
    
}),

// 触发渲染阶段
onRenderTriggered(() => {
    
}),
</script>

<style module lang="scss">
     
</style>
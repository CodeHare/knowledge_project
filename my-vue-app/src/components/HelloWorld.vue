<template>
  <h1>{{ msg }}</h1>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Documentation
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button type="button" @click="state.count++">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script setup>
// 组合api用法
// import { defineProps, reactive } from 'vue'
import { defineProps } from 'vue'

defineProps({
  msg: String
})

// 响应式的状态值第一种写法
// const state = reactive({ count: 0 })

// 响应式的值不引 reactive的第二种写法
ref: count = 1000


//  生命周期挂载
 onMounted: {
  count = 66
  console.log("count是:", count)
}

</script> 

<style scoped>
a {
  color: #42b983;
}
</style>

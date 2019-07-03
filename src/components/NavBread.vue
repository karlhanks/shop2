<template>
  <div class="NavBread.vue">
    <a href="/">首页</a>
    <!-- 
          原代码：<span>商品列表</span> 
          现代码：<slot name="标记"></slot>

          解    释：通过slot（插槽）占坑，当使用该组件时填充
          填充语法：<原标签名 slot="标记">数据</原标签名>
    -->
    <slot name="bread"></slot>
  </div>
</template>
 
<script>
export default {};
</script>
 
<style scoped >
</style>
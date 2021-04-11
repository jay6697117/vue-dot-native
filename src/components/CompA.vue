<template>
  <div class="comp-a" @click="$emit('sonClick', 'i am son comp')">
    组件A的内容
  </div>
</template>

<script></script>

<style>
.comp-a {
  height: 100px;
  width: 300px;
  margin: 20px auto;
  background: #ccc;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
</style>

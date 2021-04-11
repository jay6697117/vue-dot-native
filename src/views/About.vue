<template>
  <div class="about">
    首页 组件A:
    <CompA @sonClick="handleSonClick" @click.native.prevent="handleNativeClick"></CompA>
  </div>
</template>

<script>
import CompA from '@/components/CompA.vue';
export default {
  components: {
    CompA
  },
  methods: {
    handleSonClick(val) {
      console.log('val :>> ', val);
    },
    handleNativeClick() {
      console.log('native click by father :>> ', 1);
    }
  }
};
</script>

<style></style>

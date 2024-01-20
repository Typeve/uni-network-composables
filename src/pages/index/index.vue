<script setup lang="ts">
import { useUn } from '@uni-helper/uni-network/composables';
const { data } = useUn('http://jsonplaceholder.typicode.com/posts', { method: 'get' });

</script>

<template>
  <view>{{ data }}</view>
</template>

<style  scoped></style>
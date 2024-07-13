<template>
  <div>这是Home主页</div>
  <button @click="btn">按钮</button>
</template>
<script setup>
import {useRouter} from "vue-router";
const router = useRouter()
const btn = () => {
  router.push('/list')
}
</script>

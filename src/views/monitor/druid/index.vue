<template>
   <div>
      <i-frame v-model:src="url"></i-frame>
   </div>
</template>

<script setup>
import iFrame from '@/components/iFrame'

import { ref } from 'vue';

// const url = ref(import.meta.env.VITE_APP_BASE_API + '/druid/login.html');
const url = ref('http://www.patrickzhong.com/TypeScript/zh/handbook/classes.html');
</script>

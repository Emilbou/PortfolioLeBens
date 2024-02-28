<script setup lang="ts">
import { RouterLink } from 'vue-router'
import LogoHeader from './LogoHeader.vue';
</script>
<template>
    <div class="flex justify-between p-11 font-extrabold ">
<RouterLink to="/Projets" class="font-extrabold text-4xl">Projets</RouterLink>
<LogoHeader />
<RouterLink to="/Contact" class="font-extrabold text-4xl">Contact</RouterLink>
    </div>
</template>
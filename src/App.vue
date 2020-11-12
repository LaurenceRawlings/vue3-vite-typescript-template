<template>
<div class="flex h-screen items-center justify-center">
    <div class="p-10 flex flex-col items-center justify-center">
        <img class="mb-5" alt="Vue logo" src="./assets/logo.png" />
        <HelloWorld msg="Vue 3.0 + Vite + TypeScript" />
    </div>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: {
        HelloWorld,
    },
}
</script>

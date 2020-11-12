<template>
<h1 class="text-green-500 text-3xl font-bold">{{ msg }}</h1>
<button class="m-5 py-2 px-4 rounded bg-green-500 hover:bg-green-400 text-white transition duration-200 ease-out" @click="count++">
    Counter: {{ count }}
</button>
<p class="text-center">
    Edit <code class="font-bold">components/HelloWorld.vue</code> <br>to test hot module replacement.
</p>
</template>

<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String,
    },
    data() {
        return {
            count: 0,
        }
    },
}
</script>

<template>
    <p>lorem ipsum dolor</p>
    <div> {{ text }}</div>
</template>
<script>
export default {
    data() {
        return {
            text: "¡Hola!"
        }
    }
}
</script>
<style>
p {
    color: red;
}
</style>
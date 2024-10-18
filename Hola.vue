<template>
    <div>
        <p>Hola que tal</p>
        <div>{{ text }}</div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            text: "Hola!"
        };
    }
};
</script>

<style>
p {
    color: red;
}
</style>
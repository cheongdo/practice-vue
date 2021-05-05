<template>
    <div>
        <p>{{ name }}</p>
        <button @click="updateName">change name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Cheongdo',
        }
    },

    methods: {
        updateName() {
            this.name = 'Cheongdo is Updated'
        }
    }
}
</script>

<style scoped>

</style>
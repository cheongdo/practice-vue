<template>
    <div>
        
        <p>Header</p>
        <slot name="header" :cheongdo="cheongdo"></slot>
        <p>Body</p>
        <slot></slot>
        <p>Footer</p>
        
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: 'default title'
        },
        name: {
            type: String,
            default: 'default name'
        }
    },
    data() {
        return {
            cheongdo: 'gun'
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
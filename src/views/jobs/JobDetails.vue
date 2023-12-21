<template>
    <h1>Job Details Page</h1>
    <p>The job id is {{ id }}</p>
</template>

<script>
    export default {
        // data() {
        //     return {
        //         id: this.$route.params.id
        //     }
        // }
        
        // The prop is set to true so this component can accept the route params as its props.
        props: ['id']  
    }
</script>

<style>

</style>
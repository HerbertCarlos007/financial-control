<script>
import Header from '../components/Header.vue'
import Resume from '../components/Resume.vue'
import Form from '../components/Form.vue';

export default {
    name: 'Home',
    components: {
        Header,
        Resume,
        Form
    }
}
</script>

<template>
    <Header/>
    <Resume/>
    <Form/>
</template>

<style scoped>
</style>
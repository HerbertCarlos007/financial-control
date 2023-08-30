<script>
import Header from '../components/Header.vue'
import Resume from '../components/Resume.vue'
import Form from '../components/Form.vue';
import Table from '../components/Table.vue';

export default {
    name: 'Home',
    components: {
        Header,
        Resume,
        Form,
        Table
    }
}
</script>

<template>
    <Header/>
    <Resume/>
    <Form/>
    <Table/>
</template>

<style scoped>
</style>
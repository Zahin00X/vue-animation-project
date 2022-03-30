<template>
    <ul>
        <li v-for="user in users" :key="user">{{ user }}</li>
    </ul>
</template>

<script>
    export default{
        data()
        {
            return {
                users: [ 'Zahin', 'Siam', 'Maharab', 'Ilmi', 'Towsif', 'Shabab']
            }
        }
    }
</script>

<style scoped>
ul {
    list-style: none;
}
</style>
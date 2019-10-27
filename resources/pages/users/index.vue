<template>
    <div>
      <input type="text" v-model="userId">
      <button @click="onLoadUser">Load User</button>
    </div>
</template>

<script>
    export default {
        name: "index",
        data() {
            return {
                userId: ''
            }
        },
        methods :{
            onLoadUser() {
                this.$router.push('/users/' + this.userId)
            }
        }
    }
</script>

<style scoped>

</style>

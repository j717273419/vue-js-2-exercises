<template>
    <div class="hello" @click="show">Hello {{who}}</div>
</template>

<script>
module.exports = {
    data: function() {
        return {
            who: 'world'
        }
    },
    methods: {
        show: function () {
            alert('from child')
        }
    },

}
</script>

<style scoped>
.hello {
    background-color: rgb(241, 64, 19);
}
</style>
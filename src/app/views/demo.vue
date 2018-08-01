<template>
    <div class="demo">
        子组件:{{username}}

        <button @click="doSome()">我不是yy</button>
    </div>
</template>
<script>
    export default {
        name: 'demo',
        props: ['username'],
        data() {
            return {
                userName: '',
                users: [
                    {
                        name: 'xiaowang',
                        age: 12
                    },
                    {
                        name: 'xiaowang',
                        age: 17
                    }, {
                        name: 'xiaowang',
                        age: 10
                    }
                    , {
                        name: 'xiaowang',
                        age: 1
                    }
                ]
            }
        },
        computed: {
            // sum() {
            //     return 1 + 3 + 54 + 100;
            // }
        },
        created() {
            // setInterval(() => {
            //     this.users.reverse()
            // }, 2000);
        },
        methods: {
            doSome() {
                this.$emit('enlarge-text')
            },
            sum() {
                return 1 + 3 + 54 + 100;
            }
        }
    }
</script>
<style lang="scss" scoped>
</style>

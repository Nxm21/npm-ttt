<template>
    <div class="msg-wrapper">
        <span>hello!</span>
        <span class="account">{{data.name}}</span>
        <span class="account">{{data.country}}</span>
    </div>
</template>
<script>
    export default {
        name:'Msg',
        data () {
            return {}
        },
        props:{
            data:{
                type: Object,
                default: {
                    name: 'name',
                    country: 'china'
                }
            }
        },
        methods: {
 
        },
        created(){
            let that = this;
        }
    }
</script>
<style scoped lang="less">
    .msg-wrapper{
        background-color: #ccc;
    }
</style>
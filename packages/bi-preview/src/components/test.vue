<template>
    <div>{{values || '暂无数据'}}</div>
</template>

<script>
export default {
    name: '',
    props: {
        values: {
            type: String,
            default: ''
        }
    },
    data() {
        return {

        };
    }
};
</script>

<style scoped lang='scss' rel='stylesheet/scss'>
</style>

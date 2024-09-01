<template>
    <div v-if="flag">你能看见我吗</div>
    <div v-else>看</div>
</template>
<script>
export default{
    data(){
        return{
            flag:true
        }
    }
}
</script>

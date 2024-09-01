<template>
    <p v-for="item in list">{{item}}</p>
</template>
<script>
export default{
    data(){
        return{
            list:["1","2","3"]
        }
    }
}
</script>
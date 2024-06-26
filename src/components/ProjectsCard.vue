<template lang="">
    {{projectData}}
</template>
<script>
import jsonData from "/projects.json"
export default {
    data(){
        return{
            ProjectData: jsonData
        }
    }
}
</script>
<style lang="">
    
</style>
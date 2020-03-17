<template>
    <div id="footer">
       <span>written by {{this.writer}}</span>
    </div>
</template>

<script>
export default {
    
    data(){
        return {
        writer:'Wangzhiming'
        }
    }
}
</script>

<style lang="stylus" scoped>
#footer
    margin-top 40px
    text-align center
    color #bfbfbf
    font-size 10px
    text-shadow 0 1px 0  #ffffff

</style>
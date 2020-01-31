<template>
    <div class="footer">
    <h4>Pelita Utama Gaharu 2020</h4>
    </div>
</template>

<script>
export default {
    name:'Footer',
    props:{
        msg:String
    }
}
</script>

<style >
.footer{
    margin-top: -45px;
    padding-left: 10px;
    background-color:  #1B1A1F;
    height: 50px;
    
}

h4{
    line-height: 50px;
    color: white;
    text-align: center;
    padding: 10px;
}
</style>
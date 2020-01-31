<template>
    <div class="Klien" id="Klien">
        <div class="container teks">
            <br>
            <h1>Klien</h1>
        </div>

        <b-card-group class="deck">
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
        </b-card-group>

        <b-card-group class="deck">
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
            <div class="responsif">
                <img src="/assets/logo.png" alt="Photos" style="float:left"> 
            </div>
        </b-card-group>
    </div>    
</template>

<script>
export default {
    name:'Klien',
    props:{
        msg:String
    }
}
</script>

<style scoped>
@font-face {
font-family: "Gilroy-Light";
src: url('/assets/Gilroy-Light.otf');
}
@font-face {
font-family: "Gilroy-Bold";
src: url('/assets/Gilroy-ExtraBold.otf');
}
.Klien{
    margin-top: -45px;
    padding-left: 10px;
    background-color: #232428;
    height: max-content;
    padding-bottom: 10px;
}
.teks{
    color: white;
    font-family: 'Gilroy-Bold', sans-serif;
    margin-top: 8px !important;
    margin-top: 30px;
    padding-top: 90px;
}


img{
    border-radius: 10px !important;
    width: 100%;
    height: 50px;
    opacity: 0.4;
    filter: alpha(opacity=40); /* For IE8 and earlier */
    margin-left: 30px;
    margin-top: 20px;
    margin-bottom: 10px;
}
.deck{
        margin-bottom: 100px;
    margin-top: 30px;
    justify-content: center;
    
}
.responsif{
    margin-right: 50px;

}
</style>

<template>
     <div class="Kontak" id="Kontak">
        <b-jumbotron class="jumbotron jumbotron-fluid">
            <b-container fluid="md">
                <b-row style="margin-bottom: 50px">
                <b-col style="margin-top: 50px" md="6">
                    <div class="Home">
                        <h1>Hubungi Kami</h1>
                        <p>Pertanyaan, konsultasi, diskusi atau sekedar berkenalan, <br>
                        silahkan hubungi nomor dibawah. Kami akan berusaha <br>
                        memberikan solusi terbaik sesuai dengan budget yang <br>
                        anda miliki <br> <br>
                        Telepon <br>
                        +62(0283)08979 <br>
                        +62(0283)99779 <br> <br>
                        Software House Tegal : <br>
                        Jl. Pantura 20, Tunon,Tegal 62230</p>
                    </div>
                </b-col>
                <b-col md="6">
                    <div class="form">
                    <b-card class="card" >
                        <h2>Hubungi Kami</h2>

                    <b-form-group
                        label-cols-sm="4"
                        label="Nama"
                        label-align-sm="left"
                        label-for="nested-Nama"
                    >
                        <b-form-input id="nested-Nama"></b-form-input>
                    </b-form-group>

                    <b-form-group
                        label-cols-sm="4"
                        label="Layanan"
                        label-align-sm="left"
                        label-for="nested-Layanan"
                    >
                        <b-form-input id="nested-Layanan"></b-form-input>
                    </b-form-group>

                    <b-form-group
                        label-cols-sm="4"
                        label="Email"
                        label-align-sm="left"
                        label-for="nested-Email"
                    >
                        <b-form-input id="nested-Email"></b-form-input>
                    </b-form-group>

                    <b-form-group
                        label-cols-sm="4"
                        label="Pesan"
                        label-align-sm="left"
                        label-for="nested-Pesan"
                    >
                        <b-form-input id="nested-Pesan"></b-form-input>
                    </b-form-group>

                    <button type="submit">Kirim Pesan</button>

                </b-card>
                    </div>
                </b-col>
                </b-row>
                <b-ul class="ul">
                <b-li>Plugin.com</b-li>
                <b-li>Official.Plugin.com</b-li>
                <b-li>Official.Plugin.com</b-li>
                </b-ul>
            </b-container>
        </b-jumbotron>
    </div>

    
</template>

<script>
export default {
    name:'Kontak',
    props:{
        msg:String
    }
}
</script>

<style scoped>
.Kontak{
    margin-top: -45px;
}

    .card{
        margin-top: 60px;
        width: 350px; 
        height: 390px;
        background-color: #232428;
        border-radius: 0.6em;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    }
    label{
        font-family: 'Gilroy', sans-serif;
    }
    h2{
        color:white;
        text-align: center;
        margin-bottom: 40px;
        font-family: 'Gilroy-Bold', sans-serif;
    }
    .card button{
        margin-top: 40px;
        background: #1B1A1F;
        color: white;
        font-family: 'Gilroy-light', sans-serif;
        position: relative;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        width: 200px;
        height: 35px;
        border: 2px solid#1B1A1F;
        border-radius: 0.6em;
        
        
    }

    .card b-form-group{
        background-color:black;
    }

    b-li{
        list-style: none;
        margin: 20px;


    }
    .ul{
        display: inline-flex;
        margin-left: 300px;
    }

        @font-face {
    font-family: "Gilroy-Light";
    src: url('/assets/Gilroy-Light.otf');
  }
  @font-face {
    font-family: "Gilroy-Bold";
    src: url('/assets/Gilroy-ExtraBold.otf');
  }
    .jumbotron{
        background-color: #232428 ;
        color: white;
        font-family: 'Gilroy', sans-serif;
        padding-top: 50px;
    }
    h1{
        font-family: 'Gilroy-Bold', sans-serif;
        text-align: center;
    }
    .Home{
        font-family: 'Gilroy-Light', sans-serif;
        margin-left: 0px;
    }
    .Home p{
        margin-top: 40px;
    }




    /* Mobile Css */
    @media (min-width: 186px) and (max-width: 979px) {
  * {
    text-align: center;
    }
    .Home{
        margin-left: -10px;
    }
}
</style>
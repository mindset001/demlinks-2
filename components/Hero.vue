<template>
  
     <div class="hero">
    
        
        <v-container >
        <v-layout row wrap>
        <v-flex md6 xs-12>
        <h4>We Create, We Build!</h4>

                <h2>
                Demlinks Technologies is a startup solutions-based tech company driven with passion and responsibility of creating reliable and efficient solutions to problems that plague various sectors.
                </h2>
                <button>select a service</button>
        </v-flex>
            <v-flex md6 xs-12>
                <img src="../assets/mind.png" alt="">
            </v-flex>
        </v-layout>
        </v-container>
        
    </div>

 
  
   
</template>

<style lang="scss" scoped>

     .hero{
         height: 80vh;
            transition: 0.8s ease-in-out all;
            background: url('../assets/hero div.png');
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        

        img {
          width: 1034px;
            height: 825.5px;
          margin-left: 2em;
          margin-top: 1em;
        }
        h2{
            margin-top: 15px;
            color: #fff;
            font-size: 33px;
            line-height: 47px;
            font-family: 'Montserrat';
            font-style: normal;
            font-weight: 400;
            width: 890px;
            height: 56px;
        }
        button {
                background: #9B4C0E;
                border-radius: 19px;
                padding: 10px;
                color: white;
                margin-top: 180px;
                width: 280px;
                height: 80px;
                font-size: 30px;
            }
            h4 {
                font-family: 'Montserrat';
                font-style: normal;
                font-weight: 500;
                font-size: 75px;
                line-height: 55px;
                color: #FFFFFF;
                margin-top: 200px;
                width: 690px;
                margin-bottom: 40px;
            }

    }

  
    
</style>



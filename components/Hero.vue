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
          width: 834px;
            height: 625.5px;
          margin-left: 2em;
          margin-top: 2em;
        }
        h2{
            margin-top: 15px;
            color: #fff;
            font-size: 30px;
            line-height: 37px;
            font-family: 'Montserrat';
            font-style: normal;
            font-weight: 400;
            width: 910px;
            height: 56px;
        }
        button {
                background: #9B4C0E;
                border-radius: 19px;
                padding: 10px;
                color: white;
                margin-top: 180px;
                width: 180px;
                height: 50px;
                font-size: 16px;
            }
            h4 {
                font-family: 'Montserrat';
                font-style: normal;
                font-weight: 500;
                font-size: 50px;
                line-height: 55px;
                color: #FFFFFF;
                margin-top: 200px;
                width: 690px;
                margin-bottom: 40px;
            }

    }

  
    
</style>



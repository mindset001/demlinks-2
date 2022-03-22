<template>
    <div class="mb-16">
        <div class="text-center">
            <h1>Our <span style="color: #F2A839">Story</span> </h1>
            <img src="../assets/stroke.png" alt="">
            <div></div>
        </div>

        <div class="mt-16">
            <v-container >
                <v-layout row wrap class="justify-center ">
                    <v-flex md6>
                        <img src="../assets/isolation.png" alt="" class="img">
                    </v-flex>
                    <v-flex md6 class="flex">
                        <p>
                        We are a team of great minds dedicated to serving our consumer
                        with an excellent delivery service thus greatly improving our 
                        client's revenue and engagements.
                        </p>

                        <p style="margin-top: 40px; ">
                            We combine various skills to build and implement projects to suite clients wants and train interns to be best in their chosen career.
                        </p>
                    </v-flex>
                </v-layout>
            </v-container>
        </div>

        <div>
            <v-container  class="mt-16">
                <v-layout class="d-flex justify-center ">
                    <v-flex md6 class="d-flex justify-center">
                        <div class="card ml-16">
                            <h2>Mission</h2>
                            <p>To create a society for individuals with great mindsets and make there dreams a reality.</p>
                        </div>
                    </v-flex>

                    <v-flex md6 class="d-flex justify-center">
                        <div class="card mr-16">
                            <h2>Vision</h2>
                            <p>To be a global name in providing the best and unique I.T solutions that add values to business and individual.</p>
                        </div>
                    </v-flex>
                </v-layout>
            </v-container>
        </div>
    </div>
</template>


<style lang="scss" scoped>
    
    .img{
        margin-left: 80px; 
    }
    .flex{
        margin-left:-100px;

        p{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 24px;
        line-height: 36px;
        letter-spacing: 1px;
        color: #4D4D4D;
        
    }
    }

    .card{
        background: #FFFFFF;
        box-shadow: 0px 13px 60px rgba(136, 92, 23, 0.1);
        border-radius: 27px;
        width: 355px;
        height: 200px;
        padding: 20px;

        h2{
            color: #F4743B;
            font-family: 'Montserrat';
            font-style: normal;
            font-weight: 600;
            font-size: 30px;
            line-height: 27px;  
        }

        p{
            font-family: 'Poppins';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 27px;
            color: #4D4D4D;
            margin-top: 25px;
            color: #4D4D4D;
        }
    }
</style>

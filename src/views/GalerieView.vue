<template>
     <div class="header">
          <h1 class="titre">Galerie</h1>
     </div>

     <div class="about">

          <div class="container">

               <body>
                    <div class="container">
                         <div class="heading">
                              <h3>Photo Galerie</h3>

                         </div>


                         <div class="box">
                              <div class="dream">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-1.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-3.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-4.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-5.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-6.png" alt="">

                              </div>

                              <div class="dream">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-6.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-5.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-4.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-6.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-5.png" alt="">

                              </div>

                              <div class="dream">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-6.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-5.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-4.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-6.png" alt="">
                                   <img class="img-fluid" src="../assets/Micalex/Ok-5.png" alt="">

                              </div>
                              

                         </div>
                    </div>
               </body>
          </div>


     </div>


</template>

<script>


</script>



<style scoped>



* {
     
     margin: 0;
     padding: 0;
     box-sizing: border-box;
}

img {
     border-radius: 15px;
     box-shadow: 0 5px 10px #0005;

}

img:hover {
     transform: translateY(25px);
     transition: 1s ease-in-out;

}




body {
     text-align: center;
     width: 100%;
     align-items: center;
}

.container {
     display: flex;
     flex-direction: column;
     justify-content: center;
     text-align: center;
     margin: 40px 20px 0 20px;
}

.container,
.heading {
     text-align: center;
     align-content: center;
}

.container .heading h3 {
     font-size: 3em;
     font-weight: bolder;
     padding-bottom: 10px;
     border-bottom: 1px solid;
}

.container,
.heading h3 span {
     font-weight: 300;
}

.container .box {
     display: flex;
     flex-direction: row;
     align-items: center;
}

.container .dream {
     display: flex;
     flex-direction: column;
     width: 100%;
}

.dream, img {
     padding: 25px;
}

.container  img {
     width: 100%;
     border-radius: 5px;
}
a {
     text-decoration: none;
     font-size: 15px;
}

p {
     text-align: justify;
     font-family: 'Jost';
     font-size: 20px;
}

.header {
     height: 50vh;
     background-image:
          url(../assets/Ok-4.png);
     background-size: cover;
     background-position: top;
     position: relative;


}


.titre {
     top: 50%;
     right: 60%;
     position: absolute;
     color: #fff;
     font-weight: bold;
     font-size: 45px;
     text-transform: uppercase;


     @media (max-width: 550px) {
               font-size: 30px;
               padding: 10px;
          }

}


@keyframes moveInLeft {
     0% {
          opacity: 0;
          transform: translateX(-100px);
     }


     80% {
          transform: translateX(10px);
     }


     100% {
          opacity: 1;
          transform: translate(0) rotate(180deg);
     }
}



@keyframes moveInRight {
     0% {
          opacity: 0;
          transform: translateX(100px) rotate(0deg);
     }

     80% {
          transform: translateX(-20px);
     }

     100% {
          opacity: 1;
          transform: translate(0);
     }
}

@keyframes moveInBottom {
     0% {
          opacity: 0;
          transform: translateY(30px);
     }

     100% {
          opacity: 1;
          transform: translate(0);
     }
}

.title {
     max-width: 90rem;
     padding: 1rem;

}




.image {
     border-radius: 10px;

}
</style>
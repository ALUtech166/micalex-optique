<template>
     <div class="header">
          <h1 class="titre">Nos Services</h1>
     </div>
     <div class="service">

          <div class="container">
               <section class="vente">
                    <div class="description">
                         <h1>Vente</h1>
                         <hr>
                         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum vitae inventore odio dolor
                              commodi
                              voluptatum aperiam doloribus sunt ipsam consequatur est, asperiores recusandae adipisci
                              enim iure, in
                              numquam nesciunt vel.
                              Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit mollitia reiciendis
                              repudiandae, nostrum quaerat labore, vero voluptatem id enim corrupti blanditiis eos
                              optio. Deserunt aut doloremque autem veritatis quibusdam blanditiis?
                         </p>
                    </div>
               </section>

          </div>


     </div>


     <section class="offre">
          <div class="paragraph">
               <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis minus culpa sequi illum asperiores
                    laborum omnis nesciunt unde, qui beatae? Ducimus magni inventore excepturi similique adipisci ab
                    beatae repellat quidem.

                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis minus culpa sequi illum asperiores
                    laborum omnis nesciunt unde, qui beatae? Ducimus magni inventore excepturi similique adipisci ab
                    beatae repellat quidem.
               </p>
          </div>

     </section>



</template>

<script>


</script>



<style lang="scss" scoped>

     .service {
          padding: 35px;
          margin: 20px;



          .description {
               padding: 25px;


               h1 {
                    color: #001D6E;
                    font-weight: bold;
                    font-size: 45px;
                    text-transform: uppercase;
               }

               hr {
                    border: 2px solid #001D6E;
                    background-color: #001D6E;
                    color: #001D6E;
               }
          }
     }

     .offre {
          background-image: url("../assets/Ok-3.png");
          background-size: cover;
          height: 50vh;


          .paragraph {
               text-align: left;

               @media (min-width: 550px) {

                    padding: 25px;
               }


               p {
                    text-align: left;
                    color: #fff;



                    @media (min-width: 550px) {
                         width: 50%;
                         padding: 25px;
                    }
               }
          }
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
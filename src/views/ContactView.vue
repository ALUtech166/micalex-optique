<template>

     components: { FormUI }, <div class="header">
          <h1 class="titre">Contacts</h1>
     </div>


     <div class="about" style="background-color: #fff">

          <div class="">
               <div class="form">

                    <div class="row">
                         <div class="col-lg-6">
                              <FormUI></FormUI>

                         </div>
                         <div class="col-lg-6">
                              <div class="sub-title">
                                   <div class="social-media">
                                        <ul>
                                             <li>Facebook</li>
                                             <li>Instagram</li>
                                             <li>LinkedIn</li>
                                        </ul>
                                   </div>
                              </div>



                         </div>

                    </div>

               </div>

               <div class="mapouter">
                    <div class="gmap_canvas"><iframe width="100%" height="500" id="gmap_canvas"
                              src="https://maps.google.com/maps?q=Rue%20275,%20Lom%C3%A9%20&t=&z=13&ie=UTF8&iwloc=&output=embed"
                              frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe>

                    </div>

               </div>




          </div>


     </div>



</template>

<script>
     import FormUI from '@/components/UI/FormUI.vue';

     export default {
          components: {
               FormUI,
          }
     }
</script>



<style scoped>

     .sub-title {

          border: 2px solid #001D6E;
          height: 90%;
          border-radius: 5px;
          padding: 20px;
     }

     h2 {
          font-size: 20px;
     }

     .form {
          margin: 0.5rem;
          max-width: 100vw;
          padding: 3rem;
          border-radius: 10px;
          box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
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
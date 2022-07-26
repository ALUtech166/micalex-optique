<template>
     <div class="footer">
          <div class="container">
               <div class="row">
                    <div class="col-lg-3">
                         <img class="img-fluid" src="../assets/logo.png" alt="">
                         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aut accusamus labore praesentium
                              debitis beatae similique quia autem assumenda totam, qui corrupti commodi eius ipsa
                              repellendus rem ex fugiat ducimus! Culpa!</p>
                    </div>

                    <div class="col-lg-3">
                         <h1>Liens Utiles</h1>
                         <ul>
                              <li>Acceuil</li>
                              <li>A propos</li>
                              <li>Services</li>
                              <li>Galerie</li>
                         </ul>
                    </div>
                    <div class="col-lg-3">
                         <h1>Contacts</h1>
                         <ul>
                              <li>Email</li>
                              <li>Telephone</li>
                              <li>Adresse</li>
                         </ul>
                    </div>
                    <div class="col-lg-3">
                         <h1>Reseaux Sociaux</h1>
                         <ul>
                              <li>Facebook</li>
                              <li>Instagram</li>
                              <li>LinkedIn</li>
                         </ul>
                    </div>
               </div>
          </div>
     </div>
</template>

<script>
     export default {

     }
</script>

<style lang="scss" scoped>



.footer {
     padding: 25px;
     background-color: #001D6E;

     p, h1, li {
          color: #fff;
          font-family: 'Jost', sans-serif;
          font-size: 17px;
     }

     .col-lg-4 {
          padding: 10px;
     }

     ul {
          padding: 15px;
          font-size: 17px;
     }

     h1 {
          text-transform: uppercase;
          
     }
}

</style>
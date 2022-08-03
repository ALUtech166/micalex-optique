<template>

     <div class="divider">
          <div class="form">

               <form class="mb-5" @submit="addUser">
                    <div class="row">
                         <div class="col-md-6 form-group mb-5">
                              <label for="" class="col-form-label">Votre Nom *</label>
                              <input type="text" class="form-control" name="nom" id="name" placeholder="Votre Nom"
                                   required v-model="name">
                         </div>
                         <div class="col-md-6 form-group mb-5">
                              <label for="" class="col-form-label">Addresse mail *</label>
                              <input type="email" class="form-control" name="email" id="email"
                                   placeholder="Addresse mail" required v-model="email">
                         </div>
                    </div>

                    <div class="row">
                         <div class="col-md-6 form-group mb-5">
                              <label for="" class="col-form-label">Numéro de Téléphone</label>
                              <input type="number" class="form-control" name="password" id="phone"
                                   placeholder="Numéro de Téléphone" required v-model="password">
                         </div>
                         <div class="col-md-6 form-group mb-5">
                              <label for="" class="col-form-label">Objet</label>
                              <input type="text" class="form-control" name="remember_token" placeholder="Objet" required
                                   v-model="remember_token">
                         </div>
                    </div>

                    <div class="row">
                         <div class="col-md-6 form-group mb-5">
                              <label for="" class="col-form-label">Message</label>
                              <textarea name="message" id="message" class="form-control" placeholder="Le message"
                                   rows="5" required=""></textarea>
                         </div>

                    </div>




                    <div class="row">
                         <div class="col-md-12 form-group">
                              <input type="submit" value="Envoyer Message" class="btn btn-success btn-animated">
                              <span class="submitting"></span>
                         </div>
                    </div>
               </form>



          </div>

     </div>
</template>

<script>
export default {

     data() {
          return {
               name: '',
               email: '',
               password: '',
               remember_token: '',
               create_at: '',
               update_at: ''

          }
     },

     methods: {
          addUser() {

               fetch('https://app-control-f04f4-default-rtdb.firebaseio.com//users.json', {
                    // It is to post data like send a data
                    method: 'POST',
                    mode: "no-cors",
                    headers: {
                         'Content-Type': 'application/json',
                    },

                    body: JSON.stringify({
                         name: this.name,
                         email: this.email,
                         password: this.password,
                         remember_token: this.remember_token,
                         create_at: this.create_at,
                         update_at: this.update_at


                    }),
               }).then(res => res.json())
                    .then(res => console.log(res));


          }
     },

}
</script>
<style scoped>



form {
     max-width: 100%;
     border-radius: 10px;
     box-shadow: 0 1px 5px rgba(0, 0, 0, 0.273);
     padding: 20px;
     background-color: #ffffff;
     font-family: 'Jost';
}

label {
     font-weight: bold;
     font-family: 'Jost';
}


.btn:link,
.btn:visited {
     text-transform: uppercase;
     text-decoration: none;
     padding: 15px 40px;
     display: inline-block;
     border-radius: 100px;
     transition: all .2s;
     position: relative;

}



.btn-success {
     background-color: #001D6E;
     color: #fff;
}

.btn-success:hover {
     background-color: #001D6E;
     color: #fff;
}

.btn::after {
     display: inline-block;
     height: 100%;
     width: 100%;
     border-radius: 100px;
     position: absolute;
     top: 0;
     left: 0;
     z-index: -1;
     transition: all .4s;
}





.btn-animated {
     animation: moveInBottom .5ss ease-out .75s;
     animation-fill-mode: backwards;
}
</style>
<template>
  <div class="home">
    <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
          <img src="../assets/Ok.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>First slide label</h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="../assets/Ok-3.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/Ok-4.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
      </div>
    </div>
    <!-- <section class="hero">
      <div class="hero-text container">
        <h4>Vue Responsive Nav Menu</h4>
        <hr />
        <h2>
          With Vue <br />
          Animations
        </h2>
        <hr />
      </div>
    </section> -->


    <section class="services">
      <div class="container">
        <h1>Les Services de Micalex Optique</h1>
        <!-- <div class="row" v-if=" services && services.length">
          <div class="col-lg-3" v-for="service in services" :key="service.id">
            <img :src="" alt="">
            <router-link to="" class="link">
              <h2>{{ service.name }}</h2>
            </router-link>
          </div>
        </div> -->

        <div class="row">
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/vente.svg" alt="">
            <router-link to="" class="link">
              <h2> Vente </h2>
            </router-link>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/conseils.svg" alt="">
            <router-link to="" class="link">
              <h2> Conseils </h2>
            </router-link>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/entretient.svg" alt="">
            <router-link to="" class="link">
              <h2> Entretient </h2>
            </router-link>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/conseils-1.svg" alt="">
            <router-link to="" class="link">
              <h2> Controle de Vue </h2>
            </router-link>
          </div>
        </div>
      </div>

    </section>

    <section class="vision">
      <div class="container">
        <div class="aside">
          <div class="heading" style="text-align: center;">
            <h1>Notre Vision</h1>
          </div>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Doloremque suscipit adipisci, alias, porro amet
            dolores beatae natus ipsa autem mollitia est enim, eos consequuntur? Voluptas, saepe? Possimus aliquam sed
            accusamus!</p>
        </div>
      </div>

    </section>

    <section class="parterns">

    </section>

    <section class="work-hours">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <div class="flex">
              <img src="" alt="">
              <h1>Heures D'ouverture</h1>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="flex">
              <img src="" alt="">
              <h1>Service Immediat</h1>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="flex">
              <img src="" alt="">
              <h1>Cas d'Assurance</h1>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="flex">
              <img src="" alt="">
              <h1>Reparations et Ajustements</h1>
            </div>
          </div>

        </div>

      </div>

    </section>
  </div>
</template>

<script>
  // @ is an alias to /src

  export default {
    name: "HomeView",
    components: {},
    data() {
      return {
        services: [{
            id: '1',
            img: "@/assets/vente.svg",
            name: 'Vente'
          },
          {
            id: '2',
            img: "@/assets/entretient.svg",
            name: 'Entretien'
          },
          {
            id: '3',
            img: "@/assets/conseils.svg",
            name: 'Conseils'
          },
          {
            id: '4',
            img: "@/assets/conseils-1.svg",
            name: 'Controle de Vue'
          }
        ]
      }
    },
  };
</script>

<style lang="scss" scoped>
  h5 {
    font-size: 35px;
    animation-name: moveInLeft;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    color: #ffff;
    font-weight: 600;
    font-family: 'Jost', sans-serif;
    text-transform: uppercase;
    text-align: left;

  }



  p {
    font-size: 15px;
    animation: moveInRight 3s ease-out;
    font-weight: 400;
    margin-bottom: 100px;
    text-align: left;
    font-family: 'Jost', sans-serif;
    line-height: 25px;


  }

  .services {
    padding: 20px;
    text-align: center;
    @media (min-width: 550px) {
        height: 75vh;
        padding: 50px;
        margin: 15px;
      }

    h1 {
      text-align: center;
      text-transform: uppercase;
      font-size: 25px;
      padding: 5px;
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;
    }

    img {
      align-items: center;
      padding: 15px;
      

    }

    .row {
      text-align: center;
      padding: 10px;
    }

    .col-lg-3 {
      padding: 15px;
    }

    .link {
      text-decoration: none;
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;


    }



    h2 {
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;
      box-shadow: 0 10px 10px #0005;
      border: 1px solid #fff;
      text-align: center;
      padding: 5px;
      text-transform: uppercase;
      font-size: 15px;
    }
  }

  .vision {
    padding: 20px;
    background-image: url("../assets/Ok-1.png");
    height: 50vh;

    img {
      object-fit: cover;
      height: 50%;
      width: 100%;
    }

    .aside {
      padding: 10;

      @media (min-width: 550px) {
        width: 50%;
        height: 50%;
      }


      h1 {
        text-align: center;
        background-color: #fff;
        border: 2px solid#001D6E;
        width: 50%;
        align-items: center;
        margin-right: 50px;
        
      }


      p {
        padding: 20px;
        background-color: #fff;
        border: 2px solid#001D6E;

        @media (min-width: 550px) {
            padding: 50px;
          }
        
      }
    }
  }

  .parterns {
    padding: 20px;
  }

  .work-hours {
    padding: 40px;
    text-align: center;
    background-color: #CFD2CF;

    h1 {
        text-transform: uppercase;
        font-size: 20px;
        font-family: 'Jost', sans-serif;
        color: #001D6E;
        font-weight: bold;
        
    }
  }

  .hero {
    //background-image: url("../assets/hero-bg.png");
    background-attachment: fixed;
    position: relative;
    height: 100vh;

    img {
      object-fit: cover;
      height: 100%;
      width: 100%;
    }

    .hero-text {
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      color: #fff;

      h4 {
        text-transform: uppercase;
        font-size: 22px;
        padding-bottom: 4px;
      }

      h2 {
        font-size: 50px;

        @media (min-width: 550px) {
          font-size: 80px;
        }
      }

      hr:nth-child(2) {
        max-width: 365px;
        margin-bottom: 16px;
      }

      hr:nth-child(4) {
        height: 6px;
        background-color: #fff;
        border: none;
        max-width: 85px;
        margin-top: 16px;
      }
    }
  }
</style>
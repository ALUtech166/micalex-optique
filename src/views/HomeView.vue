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
            <h5>
              Confiez - Nous <br>
              Votre Regard

            </h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="../assets/Ok-3.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>
              Choisissez des <br>
              Lunettes Selon votre <br>
              Forme de Visage
            </h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/Ok-4.png" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>
              Optimiser Votre Vision <br>
              en Vous Procurant <br>
              Les meilleurs Lunettes

            </h5>
            <p><button type="button" class="btn btn-light">Prenez Un rendez-vous chez Nous</button></p>
          </div>
        </div>
      </div>
    </div>



    <section class="services">
      <div class="container">
        <h1>Les Services de Micalex Optique</h1>

        <div class="row">
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/vente.svg" alt="">
            <router-link to="" class="link">
              <h2> Vente </h2>
            </router-link>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/vente.svg" alt="">
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
            <img class="img-fluid" src="../assets/entretient.svg" alt="">
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
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
            Doloremque suscipit adipisci, alias, porro amet
            dolores beatae natus ipsa autem mollitia est enim, eos consequuntur? Voluptas,
            saepe? Possimus aliquam sed
            accusamus!</p>
        </div>
      </div>

    </section>

    <section class="work-hours">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <div class="flex">
              <div>
                <img src="../assets/1.svg" alt="">
              </div>

              <div>
                <h1>Heures D'ouverture</h1>
                <p class="hours">
                  <span>Lundi - Vendredi: 08h à 20h</span> <br>
                  <span>Samedi: 10h à 16h</span>
                </p>
              </div>


            </div>

          </div>
          <div class="col-lg-6">
            <div class="flex">
              <img src="../assets/2.svg" alt="">
              <h1>Service Immediat</h1>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-lg-6">
            <div class="flex">
              <img src="../assets/4.svg" alt="">
              <h1>Cas de Reparations <br>
              </h1>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="flex">
              <img src="../assets/3.svg" alt="">
              <h1>Cas d'Assurance</h1>
            </div>
          </div>


        </div>

      </div>

    </section>

    <section class="contact">
      <div class="">
        <div class="box">
          <div class="content">
            <h1>Prendre un rendez-vous <br>
              chez nos Experts</h1>
            <div>
              <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Dignissimos maxime inventore harum laborum natus
                libero vero corporis culpa consectetur laboriosam sint ad,
                blanditiis eligendi error, minima totam nihil
                dolore beatae.

                <br>
                <button href="" id="button" class="btn btn-outline-primary btn-aminated">Cliquez Ici</button>
              </h6>

            </div>

          </div>

          <div class="photo">
            <img class="img-fluid" src="../assets/Ok-2.png" alt="">
          </div>

        </div>
      </div>

    </section>

    <section class="products">
      <div class="container">
        <h1>Nos Produits</h1>
        <div class="row">
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-1.png" alt="">

            <h3>Outika</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-2.png" alt="">

            <h3>Fendi</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-3.png" alt="">
            <h3>Dior</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-4.png" alt="">

            <h3>Outika</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-1.png" alt="">

            <h3>Outika</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-2.png" alt="">

            <h3>Fendi</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-3.png" alt="">
            <h3>Dior</h3>
          </div>
          <div class="col-lg-3">
            <img class="img-fluid" src="../assets/Micalex/Ok-4.png" alt="">

            <h3>Outika</h3>
          </div>
        </div>
      </div>
    </section>

    <section class="marques">
      <div class="container">
        <h1>Nos Marques</h1>
        <!--     <vue3-marquee :clone="true">
          <img class="images" height="100" src="../images/LOGO.jpg" />
          <img class="images" height="100" src="../images/logo-2FEVRIER-lome.png" />
          <img class="images" height="100" src="../images/SBC.png" />
          <img class="images" height="100" src="../images/AACG.jpg" />
          <img class="images" height="100" src="../images/dowoto.jpeg" />
          <img class="images" height="100" src="../images/mayi_SarlU.jpg" />
          <img class="images" height="100" src="../images/ttibp.jpg" />
          <img class="images" height="100" src="../images/logo-zilla.png" />



        </vue3-marquee> -->
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
    font-size: 30px;
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
      margin-top: 75px;
      padding: 20px;
      height: 50vh;
    }

    h1 {
      text-align: center;
      text-transform: uppercase;
      font-size: 30px;
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
      font-size: 20px;
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
      padding: 10px;

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



  .work-hours {
    padding: 40px;
    text-align: center;
    background-color: #CFD2CF;

    h1 {
      text-transform: uppercase;
      font-size: 16px;
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;

      margin: 10px;


    }

    span {
      color: #001D6E;
    }


    .hours {
      margin: 10px;
      font-family: 'Jost', sans-serif;
    }

    .flex {
      display: flex;
      justify-content: center;
    }

    .row {
      padding: 10px;
    }

    .col-lg-6 {
      padding: 15px;
    }
  }

  .contact {
    margin-top: 40px;


    h1 {
      text-transform: uppercase;
      font-size: 25px;
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;

    }

    .box {
      display: flex;
      justify-content: space-between;

      @media (max-width: 550px) {
        display: flex;
        flex-direction: column;
      }
    }


    .content {
      text-align: center;
      padding: 20px;
      align-content: center;


      h6 {
        text-align: center;
        padding: 10px;

      }

      @media (min-width: 550px) {
        width: 50%;
      }

      #button {
        margin: 10px;
        border: 2px solid #001D6E;
        color: #000;
      }


      #button:hover {
        background-color: #001D6E;
        border: 2px solid #001D6E;
        color: #fff;
      }


    }

    .photo {
      width: 100%;
      height: 100%;

      @media (max-width: 550px) {
        max-width: fit-content;
      }
    }
  }

  .products {
    padding: 20px;
    background-color: #CFD2CF;
    text-align: center;

    h1 {
      text-align: center;
      text-transform: uppercase;
      font-size: 25px;
      padding: 5px;
      font-family: 'Jost', sans-serif;
      color: #001D6E;
      font-weight: bold;
    }

    h3 {
      font-size: 25px;
      font-weight: 400;
      font-family: 'Jost', sans-serif;
      line-height: 25px;
      padding: 10px;
      color: #001D6E;
      font-weight: bold;


    }

    .row {
      padding: 10px;

      .col-lg-3 {
        padding: 15px;
      }
    }


  }

  .marques {
    padding: 25px;
    background-color: #fff;
    text-align: center;

    h1 {
      text-align: center;
      text-transform: uppercase;
      font-size: 25px;
      padding: 5px;
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
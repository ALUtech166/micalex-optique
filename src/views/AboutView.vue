<template>
  <div class="header">
    <h1 class="titre">A propos de Nous</h1>
  </div>

  <div class="about">

    <div class="container">
      <section class="a-propos">
        <div class="square"></div>
        <div class="description">
          <h1>Micalex Optique</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum vitae inventore odio dolor commodi
            voluptatum aperiam doloribus sunt ipsam consequatur est, asperiores recusandae adipisci enim iure, in
            numquam nesciunt vel.</p>
        </div>
        <div class="square-root"></div>
      </section>


    </div>

    <section class="objectif">
      <div class="container">
        <div class="banner" style="top: -100px">
          <h1>Notre Vision et Objectif</h1>
        </div>

        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione dolores enim ad, reiciendis sunt ipsa illo
          sit temporibus adipisci possimus nam fugit architecto voluptate ab velit optio tenetur obcaecati porro.
        </p>
      </div>

    </section>

    <section class="space">

    </section>

  </div>



</template>

<script>


</script>



<style lang="scss" scoped>
  .a-propos {
    padding: 35px;
    margin: 20px;



    .description {
      padding: 25px;
      border: 1px solid #001D6E;
      border-radius: 5px;

      h1 {
        color: #001D6E;
        font-weight: bold;
        font-size: 45px;
        text-transform: uppercase;
      }
    }
  }

  .objectif {
    background-image: url("../assets/Ok-3.png");
    background-size: cover;
    height: 50vh;
    


    h1 {
      background-color: #fff;
      border: 1px solid#001D6E;
      text-transform: uppercase;
      border-radius: 5px;
      width: 35%;
      font-size: 25px;
      color: #001D6E;
      font-weight: bold;
      padding: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
    }

    p {
      padding: 20px;
      color: #fff;
      font-size: 15px;

      @media (min-width: 550px) {
        padding: 20px;
        width: 50%;
        color: #fff;
        font-size: 20px;
      }

    }
  }

  .space {
    padding: 25px;
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
<template>
  <NavBar />
  <div class="content">
    <div>
      <img src="../assets/landing_page/banner.jpg" alt="banner" />
    </div>
    <div class="title">
      <div>Premier pas sur</div>
      <div class="title1">Kassouwa Ta Niger ?</div>
      <div>
        Vous êtes un commerçant nouvellement venu, vous n'avez pas encore de compte ? Cliquez sur le bouton 
        "S'inscrire" en haut à droite de la page. Remplissez vos informations et créez rapidement vote boutique en ligne.
        Si vous avez dèjà un compte, cliquez sur le button "Se connecter" et gérez votre boutique.
        Vous n'êtes pas commerçant? Vous êtes aussi à votre place vous pouvez effectuer une visite du marché en ligne et effectuer vos achats en toute quiètude.
      </div>
      <button>Voir</button>
    </div>
    <div class="title-main">Tendance</div>
    <div class="content-double">
      <div>
        <img src="../assets/landing_page/trend1.png" alt="trend1" />
        <button class="button-left">Voir</button>
      </div>
      <div>
        <img src="../assets/landing_page/trend2.png" alt="trend2" />
        <button class="button-left">Voir</button>
      </div>
    </div>
    <div class="title">
      <div>Aperçu des produits les mieux notés par les clients.</div>
      <div class="title1">CONÇU DANS UN ESPRIT DE DURABILITÉ</div>
      <div>
      Retrouvez ici un bref aperçu des produits es plus aimés au prés des clients. Vous pourriez être intéressés:
      </div>
    </div>
    <div class="favourites-title">Favoris</div>
    <div class="favourites">
      <div class="favourites-item">
        <img src="../assets/landing_page/favourite2.png" alt="favourite2" />
        <div class="label">
          <div class="name">Nike Air Force 1 '07 Next Nature</div>
          <div class="price">25.000 fcfa</div>
          <br />
          <div class="tag">Chaussures pour femme</div>
        </div>
      </div>
      <div class="favourites-item">
        <img src="../assets/landing_page/favourite1.png" alt="favourite1" />
        <div class="label">
          <div class="name">Nike Air Force 1 Crater Next Nature</div>
          <div class="price">12.000fcfa</div>
          <br />
          <div class="tag">Chaussures pour adolescent</div>
        </div>
      </div>
      <div class="favourites-item">
        <img src="../assets/landing_page/favourite3.png" alt="favourite3" />
        <div class="label">
          <div class="name">Nike Air Force 1 '07 LX Next Nature</div>
          <div class="price">18.000fcfa</div>
          <br />
          <div class="tag">Chaussures pour homme</div>
        </div>
      </div>
      <div class="favourites-item">
        <img src="../assets/landing_page/favourite4.png" alt="favourite4" />
        <div class="label">
          <div class="name">Nike SuperRep Go 3 Next Nature Flyknit</div>
          <div class="price">₱5,295</div>
          <br />
          <div class="tag">Men's Training Shoes</div>
        </div>
      </div>
      <div class="favourites-item">
        <img src="../assets/landing_page/favourite5.png" alt="favourite5" />
        <div class="label">
          <div class="name">Nike Revolution 6 Next Nature</div>
          <div class="price">₱2,895</div>
          <br />
          <div class="tag">Men's Road Running Shoes</div>
        </div>
      </div>
    </div>
    <div class="title">
      <!--<div>'Infrared'</div>-->
      <div class="title1">AIR JORDAN XXXVI</div>
      <div></div>
      <button>Voir</button>
    </div>
    <div class="title-main">Ne pas rater des promotions!</div>
    <div>
      <img src="../assets/landing_page/dont_miss.jpg" alt="dont_miss" />
    </div>
    <!--<div class="title">
      <div>Running Gear for Your Race</div>
      <div class="title1">MAKE THOSE MILES COUNT</div>
      <div></div>
      <button>Voir</button>
    </div>-->
    <!--<div class="title-main">More Nike</div>
    <div class="content-triple">
      <div>
        <img src="../assets/landing_page/mens.png" alt="men" />
        <button class="button-left">Men's</button>
      </div>
      <div>
        <img src="../assets/landing_page/womens.png" alt="womens" />
        <button class="button-left">Women's</button>
      </div>
      <div>
        <img src="../assets/landing_page/kids.png" alt="kids" />
        <button class="button-left">Kid's</button>
      </div>
    </div>-->
  </div>
  <Footer />
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "LandingPage",
  components: {
    NavBar,
    Footer,
  },
};
</script>

<style scoped>
.content {
  padding: 50px;
  font-family: "Anton", sans-serif;
}

button {
  width: 100px;
  margin-top: 35px;
  padding: 10px;
  font-size: 15px;
  color: white;
  border: none;
  border-radius: 20px;
  background-color: black;
}

.button-left {
  z-index: 1;
  margin-top: -15%;
  margin-left: 10%;
  position: relative;
  float: left;
}

button:hover {
  background-color: gray;
  cursor: pointer;
}

.content .title {
  width: 60%;
  padding: 50px;
  margin: auto;
  font-size: 16px;
  overflow: hidden;
}

.content .title .title1 {
  font-size: 50px;
  font-weight: 900;
  line-height: 0.8em;
  margin-bottom: 35px;
}

.content .title-main {
  text-align: left;
  font-size: 20px;
  margin-bottom: 20px;
}

.content .content-double {
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.content .content-double img {
  max-width: 100%;
  max-height: 100%;
  object-fit: cover;
}

.content .favourites-title {
  text-align: left;
  font-size: 20px;
  margin-bottom: 20px;
}

.content .favourites {
  width: 100%;
  margin: auto;
  overflow: auto;
  white-space: nowrap;
}

.content .favourites-item {
  display: inline-block;
}

.content .favourites img {
  width: 400px;
  height: 400px;
  margin: 5px;
}

.content .favourites .label {
  width: 90%;
  margin: auto;
  overflow: hidden;
}

.content .favourites .name {
  font-size: 16px;
  float: left;
}

.content .favourites .price {
  font-size: 16px;
  float: right;
}

.content .favourites .tag {
  font-size: 15px;
  color: gray;
  float: left;
}

.content .content-triple {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.content .content-double img {
  width: 90%;
  height: 600px;
  margin: 0 auto;
}

/* width */
::-webkit-scrollbar {
  width: 10px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}
</style>

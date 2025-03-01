<template>
  <footer>
    <div class="footer-head">
      <div class="brands">
        <a href="#"><i class="fa-brands fa-facebook"></i></a>
        <a href="#"><i class="fa-brands fa-twitter"></i></a>
        <a href="#"><i class="fa-brands fa-youtube"></i></a>
        <a href="#"><i class="fa-brands fa-instagram"></i></a>
        <a href="#"><i class="fa-brands fa-github"></i></a>
      </div>
    </div>
    <div class="footer-body">
      <div class="content">
        <div class="about">
          <h3>A propos</h3>
          <p>
            Kassouwa ta est une plateforme nigérienne de commerce en ligne.
            Que vous menez une grande activité ou une petite vous êtes au bon endroit pour créez et gérez votre boutique. Vous n'en avez pas une? Vous ^tes au bon 
            endroit pour acheter vos articles preferés.
          </p>
        </div>
      </div>

      <div class="content">
        <div class="products">
          <h3>Categorie</h3>
          <a href="#">Hommes</a>
          <a href="#">Femmes</a>
          <a href="#">Enfants</a>
          <a href="#">Sports</a>
          <a href="#">Electro ménager</a>
        </div>
      </div>

      <div class="content">
        <div class="contacts">
          <h3>Contactez nous</h3>
          <a href="#"
            ><i class="fa-solid fa-building"></i> Niamey, Francophonie 10012, Ng</a
          >
          <a href="#"><i class="fa-solid fa-envelope"></i>nexacorpinfo@gmail.com</a>
          <a href="#"><i class="fa-solid fa-phone"></i>+227 91 69 11 23</a>
        </div>
      </div>

      <div class="content">
        <h3>Laissez-nous un message</h3>
        <input type="text" name="email" id="emailAdd" placeholder="Email" />
        <textarea
          type="text"
          id="emailMessage"
          name="message"
          placeholder="Message"
        />
        <div>
          <button>Envoyer</button>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div>&copy;Made by NexaCorp | Ecommerce site Niger</div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  text-decoration: none;

  list-style: none;
  font-family: "Open Sans", sans-serif;
}

footer {
  width: 100%;
}

footer .footer-head {
  overflow: hidden;
  background-color: black;
  padding: 10px;
}

footer .footer-head .brands {
  float: right;
  margin-right: 25px;
}

footer .footer-head .brands a {
  color: gray;
  padding: 15px;
}

footer .footer-body {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1.5fr;
  column-gap: 100px;
  padding: 50px;
  background-color: black;
}

footer .footer-body .content {
  color: white;
  text-align: left;
  border: 1px solid black;
}

footer .footer-body .content h3 {
  margin-bottom: 40px;
}

footer .footer-body .content .about {
  text-align: left;
}

footer .footer-body .content {
  width: 100%;
  display: grid;
  grid-template-columns: 1fr;
  row-gap: 10px;
}

footer .footer-body .content #emailAdd,
footer .footer-body .content #emailMessage,
footer .footer-body .content button {
  padding: 10px;
}

footer .footer-body .content #emailMessage {
  height: 100px;
}

footer .footer-body .content button {
  float: right;
  width: 25%;
}

footer .footer-body .content a {
  display: block;
  color: gray;
  margin-top: 5px;
}

footer .footer-body .content a:hover,
footer .footer-head .brands a:hover {
  color: white;
}

footer .footer-body .content i {
  margin-right: 10px;
}

footer .footer-bottom {
  width: 100%;
  background-color: black;
}

footer .footer-bottom div {
  padding: 20px;
  color: white;
}
</style>

<template>
  <div class="contact-page">
    <h1>Kontakt</h1>
    <p>Masz pytania lub potrzebujesz naszych usług? Skontaktuj się z nami!</p>

    <div class="contact-details">
      <div class="contact-info">
        <h2>Dane Kontaktowe</h2>
        <p><strong>Adres:</strong> ul. Chełmska 195, 41-403 Kopciowice</p>
        <p><strong>Telefon:</strong><span class="contact-icon phone"></span><a href="tel:+48600195390">+48 600 195 390</a></p>
<!--        <p><strong>Email:</strong> <a href="mailto:kontakt@warsztat-samochodowy.pl"><span class="contact-icon"></span>kontakt@warsztat-samochodowy.pl</a></p>-->
        <p><strong>Godziny Pracy:</strong> Poniedziałek - Piątek: 8:00 - 17:00, Sobota: 9:00 - 13:00</p>
        <p><strong>Opinie na Google:</strong> <a href="https://g.page/r/CdusukibX7-PEBM/review" target="_blank">Dodaj proszę opinie</a></p>
      </div>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style>
.contact-page {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 2rem;
  min-height: 100vh;
  background-size: cover;
}

.contact-page h1 {
  font-family: 'Arial', sans-serif;
  font-size: 36px;
  margin-bottom: 10px;
}

.contact-page p {
  font-family: 'Arial', sans-serif;
  font-size: 18px;
  margin-bottom: 20px;
}

.contact-details {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  max-width: 600px;

  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 10px;
  padding: 20px;
}

.contact-info h2 {
  font-family: 'Arial', sans-serif;
  font-size: 24px;
  margin-bottom: 10px;
}

.contact-info p {
  font-family: 'Arial', sans-serif;
  font-size: 18px;
  margin: 10px 0;
  color: black;
}

.contact-info strong {
  font-weight: bold;
}

.contact-info .contact-icon {
  margin-right: 10px;
  font-size: 24px;
}

.contact-info .contact-icon:before {
  content: '\1F4DE';
}

.contact-info .contact-icon.phone:before {
  content: '\260E';
}

@media (max-width: 600px) {
  .contact-details {
    max-width: 90%;
  }
}
</style>

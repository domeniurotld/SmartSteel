<template>
    <div>
      <div class="section-content" style="padding-top: 2.5rem;">
        <div class="text-content">
          <h1 class="page-title">Dotări</h1>
          <p class="simple-text">
            La S.C. Smart Steel Technologies S.R.L., ne mândrim cu dotările noastre moderne și performante, care ne permit să oferim servicii de înaltă calitate în domeniul debitării, lăcătușeriei, sudării și vopsitoriei.
          </p>
          <p class="simple-text">
            Iată câteva dintre echipamentele esențiale pe care le utilizăm:
          </p>
        </div>
      </div>
  
      <div class="facility-content">
        <div class="image-container">
          <img src="/assets/images/plasma-cutting.jpg" alt="Facility">
        </div>
        <div class="text-content">
          <h1 class="product-title">Mașină de debitat tablă cu plasmă și oxi-gaz</h1>
          <p class="simple-text">
            • Această mașină avansată ne permite să realizăm tăieturi precise și eficiente pe diverse tipuri de tablă, utilizând tehnologii de tăiere cu plasmă și oxi-gaz. Prin aceste metode, asigurăm o reducere a timpului de execuție și o calitate superioară a finisajului. De asemenea, dispunem și de soft-urile de optimizare eficientizând consumul de materiale.
          </p>
        </div>
      </div>
      <hr>
  
      <div class="facility-content">
        <div class="image-container mobile-only">
          <img src="/assets/images/steel-profiles.jpg" alt="Facility">
        </div>
        <div class="text-content">
          <h1 class="product-title">Fierăstrău cu bandă</h1>
          <p class="simple-text">
            • Fierăstrăul cu bandă este esențial pentru tăierea rapidă și precisă a țevilor și profilelor. Acest echipament ne permite să realizăm tăieturi uniforme și curate, indiferent de tipul de material utilizat, fiind ideal pentru lucrările de confecționare.
          </p>
        </div>
        <div class="image-container desktop-only">
          <img src="/assets/images/steel-profiles.jpg" alt="Facility">
        </div>
      </div>
      <hr>
  
      <div class="facility-content">
        <div class="image-container">
          <img src="/assets/images/bending-pipe.jpg" alt="Facility">
        </div>
        <div class="text-content">
          <h1 class="product-title">Mașină de îndoit tevi și profile</h1>
          <p class="simple-text">
            • Această mașină specializată ne permite să îndoim tevi și profile cu o precizie ridicată, adaptându-ne astfel la cerințele specifice ale fiecărui proiect. Echipamentul asigură un proces eficient și rapid, reducând timpul de producție.
          </p>
        </div>
      </div>
      <hr>
  
      <div class="facility-content">
        <div class="image-container mobile-only">
          <img src="/assets/images/sheet-bender.jpg" alt="Facility">
        </div>
        <div class="text-content">
          <h1 class="product-title">Mașină de îndoit tablă (Abkant)</h1>
          <p class="simple-text">
            • Mașina de îndoit tablă, cunoscută sub numele de Abkant, ne oferă posibilitatea de a crea forme complexe și precise din tablă. Acest echipament este esențial pentru realizarea unor piese personalizate, conform specificațiilor tehnice ale clienților noștri.
          </p>
        </div>
        <div class="image-container desktop-only">
          <img src="/assets/images/sheet-bender.jpg" alt="Facility">
        </div>
      </div>
      <hr>
  
      <div class="facility-content">
        <div class="image-container">
          <img src="/assets/images/welding-equipment.jpg" alt="Facility">
        </div>
        <div class="text-content">
          <h1 class="product-title">Echipamente de sudare MIG-MAG</h1>
          <p class="simple-text">
            • Echipamentele de sudare MIG-MAG sunt folosite pentru a realiza îmbinări solide și durabile. Aceste tehnologii de sudare sunt ideale pentru lucrările de construcție și fabricare, asigurându-ne că produsele noastre respectă cele mai înalte standarde de calitate și siguranță.
          </p>
        </div>
      </div>
  
      <div class="section-content">
        <div class="text-content">
          <p class="simple-text">
            Prin aceste dotări de vârf, S.C. Smart Steel Technologies S.R.L. își propune să ofere soluții eficiente și personalizate, menținând un standard ridicat în toate serviciile prestate.
          </p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .mobile-only {
    display: none;
  }
  .page-title {
    margin-bottom: 1.2rem;
  }
  .section-content {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    align-items: center;
    padding: 1rem 5rem;
  }
  .text-content {
    flex: 1;
  }
  .simple-text {
    font-size: 1.2rem;
    color: rgb(54, 54, 54);
    margin-top: 0;
  }
  .image-container img {
    max-height: 300px;
  }
  .image-container {
    flex: 1;
    height: auto;
    overflow: hidden;
    border-radius: 5px;
    max-width: 400px;
  }
  .product-title {
    font-size: 2rem;
    justify-content: left;
    display: flex;
    text-align: left;
  }
  .facility-content {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    align-items: center;
    padding: 1rem 5rem;
  }
  hr {
    margin: 0 5rem;
    border: 1px solid #ccc;
  }
  
  @media (max-width: 768px) {
    .desktop-only {
        display: none;
    }
    .mobile-only {
        display: block;
    }
    .section-content, .facility-content {
      padding: 1rem 2rem;
    }
    .facility-content {
        flex-direction: column;
        gap: 0;
    }
    .image-container {
      max-width: 100%;
      max-height: 200px;
    }
    .simple-text {
      font-size: 1rem;
      margin-bottom: 0;
    }
    .product-title {
      font-size: 1.5rem;
    }
    hr {
      margin: 0 2rem;
    }
  }
  </style>
  
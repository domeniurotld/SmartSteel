<template>
    <div>
      <div class="section-content" style="padding-top: 2.5rem;">
        <div class="text-content">
          <h1 class="page-title">Produse furnizate clienților</h1>
          <p class="simple-text">
            La S.C. Smart Steel Technologies S.R.L., oferim o gamă variată de produse și componente metalice, realizate la cele mai înalte standarde de calitate. Fiecare produs este fabricat cu atenție la detalii, utilizând tehnologii moderne pentru a asigura durabilitate, precizie și conformitate cu cerințele specifice ale fiecărui client.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content">
        <div class="image-container">
          <img src="/assets/images/metalic-structure.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Structuri metalice</h1>
          <p class="simple-text">
            • Proiectăm și realizăm structuri metalice de diverse dimensiuni și complexități, adaptate nevoilor fiecărui client.
          </p>
          <p class="simple-text">
            • Produsele includ cadre, platforme, schele metalice și alte structuri personalizate.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content">
        <div class="image-container">
          <img src="/assets/images/welded-component.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Componente sudate</h1>
          <p class="simple-text">
            • Oferim componente și ansambluri sudate cu precizie, utilizând tehnici avansate de sudare pentru a asigura îmbinări durabile și rezistente.
          </p>
          <p class="simple-text">
            • Acestea includ elemente pentru echipamente industriale, utilaje sau construcții metalice complexe.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content">
        <div class="image-container">
          <img src="/assets/images/steel-profiles.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Piese tăiate la laser sau plasmă</h1>
          <p class="simple-text">
            • Realizăm debitarea metalelor folosind tehnologii de tăiere de ultimă generație (plasmă și oxi-gaz) pentru a oferi piese cu precizie, conform specificațiilor tehnice.
          </p>
          <p class="simple-text">
            • Pot fi furnizate piese pentru o varietate de industrii: automotive, construcții, echipamente mecanice, infrastructură, petrol și gaze etc.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content">
        <div class="image-container">
          <img src="/assets/images/metalic-container.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Confecții metalice personalizate</h1>
          <p class="simple-text">
            • Producem o gamă largă de confecții metalice personalizate, adaptate cerințelor specifice ale fiecărui client, fie că este vorba de proiecte industriale, comerciale sau de infrastructură.
          </p>
          <p class="simple-text">
            • Acestea pot include containere metalice, dulapuri, suporturi și alte structuri funcționale.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content">
        <div class="image-container">
          <img src="/assets/images/painted-steel.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Produse vopsite</h1>
          <p class="simple-text">
            • Pentru a asigura durabilitatea și estetica produselor, oferim servicii de vopsire industrială de înaltă calitate, utilizând tehnici și materiale ce garantează o protecție ridicată împotriva coroziunii și a factorilor de mediu.
          </p>
          <p class="simple-text">
            • Aceste produse includ piese vopsite personalizate pentru industria construcțiilor, automotive și alte sectoare.
          </p>
        </div>
      </div>
      <hr>
      <div class="section-content" style="margin-bottom: 2rem;">
        <div class="image-container">
          <img src="/assets/images/ensambles.jpg" alt="Product">
        </div>
        <div class="text-content">
          <h1 class="product-title">Subansambluri și componente asamblate</h1>
          <p class="simple-text">
            • Furnizăm subansambluri metalice complete și componente pre-asamblate, gata pentru integrarea directă în proiectele clienților noștri.
          </p>
          <p class="simple-text">
            • De la componente mici până la ansambluri mari, toate sunt realizate cu grijă pentru detalii și conformitate cu specificațiile tehnice.
          </p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
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
  .image-container img {
    max-height: 200px;
  }
  .image-container {
    flex: 1;
    max-width: 250px;
    height: auto;
    overflow: hidden;
    border-radius: 5px;
  }
  .product-title {
    font-size: 2rem;
    justify-content: left;
    display: flex;
    text-align: left;
  }
  .simple-text {
    font-size: 1.2rem;
    color: rgb(54, 54, 54);
    margin-top: 0;
  }
  .text-content {
    flex: 1;
  }
  hr {
    margin: 0 5rem;
    border: 1px solid #ccc;
  }
  
  @media (max-width: 768px) {
    .section-content {
      padding: 1rem 2rem;
      flex-direction: column;
        gap: 0;
    }
    .image-container {
      max-width: 100%;
      max-height: 200px;
    }
    .image-container img {
        max-height: 300px;
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
  
<template>
    <div>
        <div class="section-content" style="padding-top: 2.5rem;">
            <div class="text-content">
                <h1 class="page-title">Bun venit la S.C. Smart Steel Technologies S.R.L</h1>
                <p class="simple-text">
                    Ne mândrim cu excelența în servicii de confecționare a metalelor, oferind soluții complete și personalizate pentru diverse industrii. Suntem specializați în debitare, lăcătușerie, sudare și vopsire, acoperind o gamă largă de nevoi tehnice și de producție.
                </p>
                <p class="simple-text" style="margin-bottom: 0;">
                    Echipa noastră de profesioniști calificați este dedicată să ofere produse de cea mai înaltă calitate, folosind echipamente moderne și tehnologii avansate. Indiferent de complexitatea proiectului, ne asigurăm că fiecare detaliu este realizat cu precizie, respectând standardele stricte de siguranță și calitate.
                </p>
            </div>
        </div>
        <hr>
        <div class="section-content">
            <div class="image-container">
                <img src="/assets/images/logo-image.jpg" alt="Worker">
            </div>
            <div class="text-content">
                <h1 class="page-title">Experiență vastă în domeniu</h1>
                <p class="simple-text">
                    Cu o experiență vastă în domeniu, am devenit un partener de încredere pentru clienți din diverse sectoare, oferind nu doar servicii, ci soluții complete, fiabile și eficiente. Ne concentrăm pe inovație și adaptabilitate, menținându-ne angajamentul de a satisface cerințele fiecărui proiect în parte.
                </p>
                <p class="simple-text" style="margin-bottom: 0;">
                    Suntem aici să transformăm metalul brut în structuri durabile și funcționale, combinând expertiza noastră tehnică cu o abordare orientată către client. La Smart Steel Technologies, fiecare proiect reprezintă o oportunitate de a demonstra calitatea, profesionalismul și pasiunea noastră pentru excelență.
                </p>
                <div class="contact-button">
                    <a href="">
                        <button class="top-section-button">Contactați-ne</button>
                    </a>
                </div>
            </div>
        </div>
        <div class="card bg-dark text-white">
            <img class="card-img main-section-img" src="/assets/images/steel-welding.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container">
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Viziunea Noastră</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Să devenim un lider de top în industria confecțiilor metalice, recunoscuți pentru inovație, calitate și fiabilitate, oferind soluții care să depășească așteptările clienților noștri.</p>
                        </div>
                    </div>
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Misiunea Noastră</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text moto-description">Să oferim servicii de confecții metalice de înaltă calitate, cu un focus pe precizie, eficiență și satisfacția clientului, contribuind astfel la succesul partenerilor noștri.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="section-content" style="display: flex; justify-content: space-between; ">
            <div class="feature-card">
                <div class="text-content">
                    <h1 class="page-title">Produse</h1>
                    <p class="simple-text" style="min-height: 200px;">
                        Oferim o gamă variată de produse și componente metalice, realizate la cele mai înalte standarde de calitate. Fiecare produs este fabricat cu atenție la detalii, utilizând tehnologii moderne pentru a asigura durabilitate, precizie și conformitate cu cerințele specifice ale fiecărui client.
                    </p>
                    <div class="card-button-size">
                        <button class="card-button" @click="goToRoute('/products')">Vezi detalii →</button>
                    </div>
                </div>
            </div>
            <div class="feature-card">
                <div class="text-content">
                    <h1 class="page-title">Servicii</h1>
                    <p class="simple-text" style="min-height: 200px;">
                        Oferim suport tehnic complet pentru fiecare etapă a proiectelor propuse de clienții noștri. Fiecare proiect beneficiază de o consultanță detaliată și o abordare personalizată, astfel încât soluțiile noastre să fie perfect adaptate nevoilor și cerințelor specifice ale fiecărui client.
                    </p>
                    <div class="card-button-size">
                        <button class="card-button" @click="goToRoute('/services')">Vezi detalii →</button>
                    </div>
                </div>
            </div>
            <div class="feature-card">
                <div class="text-content">
                    <h1 class="page-title">Dotări</h1>
                    <p class="simple-text" style="min-height: 200px;">
                        La S.C. Smart Steel Technologies S.R.L., ne mândrim cu dotările noastre moderne și performante, care ne permit să oferim servicii de înaltă calitate în domeniul debitării, lăcătușeriei, sudării și vopsitoriei.
                    </p>
                    <div class="card-button-size">
                        <button class="card-button" @click="goToRoute('/facilities')">Vezi detalii →</button>
                    </div>
                </div>
            </div>
        </div>
        <div id="careers" class="card bg-dark text-white" style="border-radius: 0;">
            <img class="card-img second-section-img" src="/assets/images/dark-steel.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container">
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Certificări</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text small-description">
                                • La S.C. Smart Steel Technologies S.R.L., ne angajăm să respectăm cele mai înalte standarde de calitate și siguranță. Fiecare proiect este controlat riguros pentru a îndeplini cerințele clienților și standardele industriei.
                                <br>• Echipa noastră de specialiști aplică cele mai bune practici în toate etapele producției. Asigurăm un mediu de lucru sigur, cu măsuri stricte de protecție și instruire periodică.
                                <br>• Construim relații de încredere cu clienții, bazate pe transparență și onestitate, pentru a deveni partenerul preferat în debitare, lăcătușerie, sudare și vopsitorie.
                            </p>
                        </div>
                    </div>
                    <div class="moto-card">
                        <div class="moto-title-size">
                            <h4 class="card-title main-moto">Cariere</h4>
                        </div>
                        <div class="moto-description-size">
                            <p class="card-text small-description">
                                • La S.C. Smart Steel Technologies S.R.L., succesul nostru se bazează pe talentul echipei. Căutăm persoane pasionate și inovatoare pentru a contribui la dezvoltarea companiei.
                                <br>• Oferim oportunități de carieră într-un mediu dinamic, cu cursuri de specializare. Dacă ești interesat de debitare, lăcătușerie, sudare sau vopsitorie, te invităm să aplici, indiferent de experiență.
                                <br>• Promovăm un mediu divers și colaborativ. Dacă vrei să faci parte dintr-o echipă dedicată, contactează-ne! Așteptăm să te cunoaștem!
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="offerrequest" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Cere o ofertă</h1>
                <p class="simple-text">
                    La S.C. Smart Steel Technologies S.R.L., suntem dedicați să îți oferim cele mai bune soluții personalizate în domeniul debitării, lăcătușeriei, sudării și vopsitoriei. Dacă ești interesat de serviciile noastre și dorești o ofertă adaptată nevoilor tale specifice, te invităm să ne contactezi.
                </p>
                <p class="simple-text">
                    Pentru a solicita o ofertă, te rugăm să ne furnizezi următoarele informații:
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    1. <b>Descrierea Proiectului:</b> O scurtă prezentare a lucrării pe care o dorești, inclusiv tipul de servicii necesare (debitare, sudare, lăcătușerie, vopsitorie etc.).
                    <br>2. <b>Materialele:</b> Tipurile de materiale care urmează să fie utilizate, precum oțel, inox sau aluminiu.
                    <br>3. <b>Cantitatea:</b> Estimarea cantității de produse sau lucrări necesare.
                    <br>4. <b>Termenul de Livrare:</b> Data la care ai nevoie de finalizarea proiectului.
                    <br>5. <b>Alte Detalii:</b> Orice informații suplimentare sau cerințe speciale pe care le consideri relevante.
                </p>
                <p class="simple-text">
                    Echipa noastră va analiza solicitarea ta și îți va răspunde în cel mai scurt timp posibil cu o ofertă personalizată, transparentă și competitivă. Suntem aici să te ajutăm să transformi ideile tale în realitate!
                </p>
            </div>
        </div>
        <hr>
        <div id="contact" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Contact</h1>
                <p class="simple-text">
                    La S.C. Smart Steel Technologies S.R.L., suntem aici pentru a răspunde întrebărilor tale și pentru a-ți oferi suportul necesar. Dacă ai nevoie de informații suplimentare, vrei să soliciți o ofertă sau dorești să discutăm despre un proiect specific, nu ezita să ne contactezi.
                </p>
                <p class="simple-text">
                    <b>Informații de Contact:</b>
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    • Adresă: <b>Loc. Fărcașa, str. Independenței, nr. 26</b>
                    <br>• Telefon: <b>[]</b>
                    <br>• Email: <b>office@smartsteel.ro</b>
                    <br>• Website: <b>smartsteel.ro</b>
                </p>
                <p class="simple-text">
                    <b>Formulare de Contact:</b>
                </p>
                <p class="simple-text">
                    Pentru o comunicare rapidă și eficientă, te invităm să completezi formularul de contact de pe site-ul nostru. Te asigurăm că toate solicitările tale vor fi tratate cu prioritate, iar echipa noastră îți va răspunde în cel mai scurt timp posibil.
                </p>
                <p class="simple-text">
                    Așteptăm cu nerăbdare să auzim de la tine și să explorăm împreună oportunitățile de colaborare!
                </p>
            </div>
            <div class="image-container">
                <img src="/assets/images/logo-image.jpg" alt="Worker">
            </div>
        </div>
    </div>
</template>

<script>
export default {
  methods: {
    goToRoute(route) {
        this.$router.push(route).then(() => {
        this.scrollToTop();
        });
    },
    scrollToTop() {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>

<style scoped>
    .mobile-only {
        display: none;
    }
    .main-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .second-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .dark-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%; /* Full width to cover the image */
        height: 100%;
        background: linear-gradient(to right, rgb(0, 0, 0), rgba(0, 0, 0, 0.275)); /* Gradient from dark to transparent */
        pointer-events: none; /* Prevents interaction with the overlay */
    }
    .main-moto {
        font-size: 3rem;
        font-weight: 700;
        text-transform: uppercase;
    }
    .moto-description {
        font-size: 1.7rem;
    }
    .top-section-button {
        font-size: 1.5rem;
        color: white;
        background: black;
        border: none;
        border-radius: 10px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
    }
    .card-button-size {
        width: 100%; 
        display: flex; 
        justify-content: center;
    }
    .card-button {
        font-size: 1.5rem;
        color: black;
        background: transparent;
        border-width: 2px;
        border-color: black;
        border-radius: 10px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
    }
    .card-button:hover {
        color: white;
        background: black;
    }
    .card-img-text {
        padding: 3rem 5rem;
        display: flex;
        align-items: center;
    }
    .main-section {
        padding: 1rem 5rem;
    }
    .main-section-title {
        width: 100%;
        font-size: 2rem;
        font-weight: 700;
        margin-bottom: 0.5rem;
    }

    .simple-text {
        font-size: 1.2rem;
        color: rgb(54, 54, 54);
        margin-top: 0;
    }

    .small-description {
        font-size: 1.4rem;
    }

    .page-title {
        margin-bottom: 1.2rem;
    }

    .image-container {
        flex: 1;
        max-width: 500px;
        height: auto;
        overflow: hidden;
        border-radius: 5px;
    }

    .section-content {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        align-items: center;
        padding: 2rem 5rem;
    }

    .text-content {
        flex: 1;
    }
    
    .feature-card {
        width: 30%;
        border-width: 3px;
        border-radius: 15px;
        border-color: #656262;
        padding: 2rem;
    }

    .contact-button {
        width: 100%; 
        margin-top: 2rem;
    }

    .moto-container {
        display: flex; 
        width: 100%;
    }

    .moto-card {
        width: 50%;
    }

    .moto-title-size {
        width: 100%; 
        margin-top: 1rem;
    }

    .moto-description-size {
        width: 70%; 
        margin-top: 1rem;
    }
    hr {
        margin: 0 5rem;
        border: 1px solid #ccc;
    }

    @media (max-width: 768px) {
    .page-title {
        margin-bottom: 1rem;
    }
    .section-content {
      padding: 1rem 2rem;
      flex-direction: column;
        gap: 1rem;
    }
    .image-container {
      max-width: 100%;
      max-height: 300px;
    }
    .image-container img {
        max-height: 300px;
    }
    .simple-text {
      font-size: 1rem;
    }
    .moto-container {
        flex-direction: column;
        gap: 1rem;
    }
    .moto-card {
        width: 100%;
    }
    .moto-title-size {
        width: 100%;
    }
    .main-moto {
        font-size: 2rem;
    }
    .moto-description-size {
        width: 100%;
    }
    .moto-description, .small-description {
        font-size: 1rem;
    }

    .main-section-img {
        height: 450px;
    }
    .second-section-img {
        height: 800px; 
    }
    .feature-card {
        width: 100%;
        padding: 1rem;
    }
    .card-button {
        font-size: 1.2rem;
    }
    .top-section-button {
        font-size: 1.2rem;
    }
    .contact-button {
        margin-top: 1rem;
        justify-content: center;
        display: flex;
    }
    .main-section {
        padding: 1rem 1rem !important;
    }
    .card-img-text {
        padding: 1rem 1rem !important;
    }
    hr {
      margin: 0 2rem;
    }
}
</style>
<template>
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-section">
          <div class="footer-title">Link-uri utile</div>
          <a class="footer-link" @click="goToRoute('/')">Acasă</a>
          <a class="footer-link" @click="goToRoute('/products')">Produse</a>
          <a class="footer-link" @click="goToRoute('/services')">Servicii</a>
          <a class="footer-link" @click="goToRoute('/facilities')">Dotări</a>
          <a class="footer-link" @click="goToHomeSection('careers')">Certificări</a>
          <a class="footer-link" @click="goToHomeSection('careers')">Cariere</a>
          <a class="footer-link" @click="goToHomeSection('offerrequest')">Cere ofertă</a>
          <a class="footer-link" @click="goToHomeSection('contact')">Contact</a>
        </div>

        <div class="footer-section">
          <div class="footer-title">Contactați-ne</div>
          <div class="contact-info">
            <Icon name="material-symbols:call-sharp" size="1.1rem" class="contact-icon" />
            <a href="" class="footer-text mobile-number">[]</a>
          </div>
          <div class="contact-info">
            <Icon name="material-symbols-light:mail-rounded" size="1.2rem" class="contact-icon" />
            <span class="footer-text">office@smartsteel.ro</span>
          </div>
          <div class="social-info">
            <Icon name="entypo-social:facebook" size="2.5rem" class="social-icon" />
            <Icon name="entypo-social:linkedin" size="2.5rem" class="social-icon" />
            <Icon name="entypo-social:instagram" size="2.5rem" class="social-icon" />
          </div>
        </div>

        <div class="footer-section">
          <div style="height: auto;">
            <img src="/assets/images/stpnation.jpg" alt="StartUp Nation">
          </div>
        </div>
      </div>
      <hr class="footer-divider" />
      <div class="footer-bottom">
        © 2024 SmartSteel - All rights reserved
      </div>
    </footer>
  </template>

<script>
export default {
  methods: {
    goToRoute(route) {
      this.$router.push(route).then(() => {
        this.scrollToTop();
      });
    },
    goToHomeSection(section) {
      this.$router.push("/").then(() => {
        this.scrollToSection(section);
      });
    },
    scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
    },
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>
  
  <style scoped>
    @media (min-width: 1300px) {
        .footer {
            padding-left: 4rem !important;
            padding-right: 4rem !important;
        }
    }

  .footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: black;
    padding: 1rem 3rem;
    color: white;
  }
  
  .footer-content {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    width: 100%;
  }
  
  .footer-section {
    flex: 1;
    margin: 1rem;
    min-width: 200px;
  }

  .footer-section img {
    width: 100%;
  }
  
  .footer-title {
    font-size: 1.5rem;
    margin-bottom: 0.8rem;
  }
  
  .footer-link {
    display: block;
    font-size: 1.2rem;
    color: white;
    margin-bottom: 0.5rem;
    text-decoration: none;
    cursor: pointer;
  }
  
  .footer-link:hover {
    text-decoration: underline;
  }
  
  .footer-text {
    font-size: 1.2rem;
  }

  .mobile-number {
    color: white;
    text-decoration: none;
  }
  
  .contact-info {
    display: flex;
    align-items: center;
    margin-bottom: 0.5rem;
  }

  .social-info {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-top: 2rem;
  }

  .social-icon {
    cursor: pointer;
  }
  
  .contact-icon {
    margin-right: 0.5rem;
  }
  
  .footer-divider {
    border: none;
    height: 1px;
    background-color: white;
    width: 100%;
    margin: 1rem 0;
  }
  
  .footer-bottom {
    text-align: center;
  }
    
  @media (max-width: 768px) {
    .footer {
        padding: 1rem 1.5rem;
    }

    .footer-content {
      flex-direction: column;
    }
    
    .footer-section {
      margin: 0.5rem 0;
      width: 100%;
    }

    .footer-section {
      margin: 0.5rem 0;
    }

    .simple-text {
        font-size: 1.2rem;
    }
  }
  </style>
  
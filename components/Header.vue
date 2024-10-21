<template>
    <header class="header">
      <div class="row desktop-only align-items-center">
        <div class="col-auto logo">
          <img src="/assets/logos/logo-description.png" alt="Logo" @click="goToRoute('/')"/>
        </div>
        <nav class="nav nav-right">
          <button class="tab-button" @click="goToRoute('/')">Acasă</button>
          <button class="tab-button" @click="goToRoute('/products')">Produse</button>
          <button class="tab-button" @click="goToRoute('/services')">Servicii</button>
          <button class="tab-button" @click="goToRoute('/facilities')">Dotări</button>
          <div class="dropdown">
            <button class="tab-button">Mai multe</button>
            <div class="dropdown-container">
              <div class="dropdown-content">
                <a @click="goToHomeSection('careers')">Certificări</a>
                <hr>
                <a @click="goToHomeSection('careers')">Cariere</a>
                <hr>
                <a @click="goToHomeSection('offerrequest')">Cere ofertă</a>
                <hr>
                <a @click="goToHomeSection('contact')">Contact</a>
              </div>
            </div>
          </div>
        </nav>
      </div>

      <div class="col mobile-only">
        <div class="logo" style="padding: 0;">
          <img src="/assets/logos/logo-description.png" alt="Logo" @click="goToRoute('/')"/>
        </div>
        <nav class="nav nav-left">
          <div style="display: flex; justify-content: center; width: 100%; gap: 1rem; padding: 0 1rem;">
            <button class="tab-button" style="width: 30%;" @click="goToRoute('/')">Acasă</button>
            <button class="tab-button" style="width: 30%;" @click="goToRoute('/products')">Produse</button>
            <button class="tab-button" style="width: 30%;" @click="goToRoute('/services')">Servicii</button>
          </div>
        </nav>
        <nav class="nav nav-left" style="margin-top: 1rem; margin-bottom: 1rem;">
          <div style="display: flex; justify-content: center; width: 100%; gap: 1rem; padding: 0 1rem;">
            <button class="tab-button" style="width: 45%;" @click="goToRoute('/facilities')">Dotări</button>
            <div class="dropdown" style="width: 45%;">
              <button class="tab-button"  style="width: 100%;">Mai multe</button>
              <div class="dropdown-container">
                <div class="dropdown-content">
                  <a @click="goToHomeSection('careers')">Certificări</a>
                  <hr>
                  <a @click="goToHomeSection('careers')">Cariere</a>
                  <hr>
                  <a @click="goToHomeSection('offerrequest')">Cere ofertă</a>
                  <hr>
                  <a @click="goToHomeSection('contact')">Contact</a>
                </div>
              </div>
            </div>
          </div>
        </nav>
      </div>
    </header>
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
  
    .desktop-only {
      width:100%; 
      flex-direction:row; 
      display: flex;
    }
  
    .mobile-only {
      display: none; 
    }
  
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: auto;
    background: black;
  }
  
  .logo {
    display: flex;
    height: 100px;
    align-items: center;
    margin-left: 20px;
  }

  .logo img {
    height: 70px;
    cursor: pointer;
  }
  
  .nav {
    display: flex;
    gap: 1rem;
  }
  
  .nav-left {
    flex: 1;
  }
  
  .nav-right {
    flex: 1;
    justify-content: flex-end;
  }
  
  .tab-button {
    font-size: 20px;
    padding: 6px 16px;
    font-weight: 600;
    border: none;
    outline: none;
    color: #000 !important;
    background: linear-gradient(
      45deg,
      #999 5%,
      #fff 10%,
      #ccc 30%,
      #ddd 50%,
      #ccc 70%,
      #fff 80%,
      #999 95%
    );
    text-shadow: 1px 1px 2px rgba(255, 255, 255, 0.5);
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
    cursor: pointer;
    transition: all 0.2s ease-in-out;
    }

    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropdown-container {
      display: none;
      position: absolute;
      right: 0;
      background: transparent;
      z-index: 1;
    }
    .dropdown-content {
      background: linear-gradient(
        45deg,
        #e3dddd 5%,
        #fff 10%,
        #ccc 30%,
        #ddd 50%,
        #ccc 70%,
        #fff 80%,
        #bebebe 95%
      );
      min-width: 150px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      border-radius: 5px;
      margin-top: 5px;
    }

    .dropdown-content a {
      color: black;
      padding: 5px 15px;
      text-decoration: none;
      display: block;
      font-weight: 600;
      border-radius: 5px;
      cursor: pointer;
      
    }

    .dropdown-content hr {
      margin: 0;
      height: 2px;
    }

    .dropdown-content a:hover {
      background-color: #000000;
      color: white;
      
    }

    .dropdown:hover .dropdown-container {
      display: block;
    }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    .desktop-only {
      display: none;
    }
  
    .mobile-only {
      width: 100%; 
      display: flex; 
      flex-direction: column;
    }
  
    .header {
      flex-direction: column;
      align-items: center;
      padding: 0;
    }
  
    .nav {
      width: 100%;
    }
  
    .nav-left, .nav-right {
      align-items: center;
    }
  
    .tab-button {
      font-size: 1.1rem;
    }

    .logo {
      margin-left: 0;
      justify-content: center;
    }
  }
  </style>
  
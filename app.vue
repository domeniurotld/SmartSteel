<template>
  <div class="main-layout">
    <Header />
    <div style="min-height: 40vh;">
      <router-view/>
    </div>
    <Footer />
    <ScrollToTopButton />
  </div>
</template>

<style scoped>
.main-layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
</style>
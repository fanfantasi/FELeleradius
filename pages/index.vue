<script setup lang="ts">
useHead({
  title: 'Leleradius - Application Billing Internet',
  meta: [
    { name: 'description', content: 'LeleRadius billing internet dengan teknik Radius Authentikasi, semua data pelanggan / voucher dari semua cabang terpusat pada dua server Leleradius memungkinkan data tetap aman walaupun server cabang / mikrotik mengalami kerusakan.' },
    { property: 'og:locale', content: "en_US" },
    { property: 'og:type', content: "website" },
    { property: 'og:title', content: "Leleradius - Application Billing Internet" },
    { property: 'og:description', content: "LeleRadius billing internet dengan teknik Radius Authentikasi, semua data pelanggan / voucher dari semua cabang terpusat pada dua server Leleradius memungkinkan data tetap aman walaupun server cabang / mikrotik mengalami kerusakan." },
    { property: 'og:url', content: "https://leleradius.com" },
    { property: 'og:site_name', content: "LeleRadius" },
    { property: 'og:image', content: "https://leleraius.com/leleradius.png" },
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/logo.png' }
  ],
})
</script>
<template>
    <div>
        <SectionsHomeHeroSection/>
        <div id="about-us"><SectionsAboutPodux/></div>
        <div id="feature"><SectionsWhyUs/></div>
        <div id="price">
          <SectionsPriceList/>
          <SectionsPricePremium/>
        </div>
        <div id="contact">
          <SectionsCallToAction/>
        </div>
    </div>
</template>
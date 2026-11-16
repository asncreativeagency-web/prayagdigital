<template>
  <LoadingScreen />
  <Cursor />
  <ProgressScroll />
  <Lines />
  <Navbar />
  <div id="smooth-wrapper">
    <div id="smooth-content">
      <main class="main-bg o-hidden">
        <Header />
        <Services />
        <CampaignResults />
        <Intro2 />
        <Numbers />
        <Portfolio />
        <Feat />
        <Testimonials />
        <Clients />
        <Blog />
        <Marq2 />
      </main>
      <Footer />
    </div>
  </div>
</template>
<script setup>
import Lines from '@/components/common/Lines';
import ProgressScroll from '@/components/common/ProgressScroll';
import Cursor from '@/components/common/cusor';
import LoadingScreen from '@/components/common/loader';
import Footer from '@/components/common/Footer';
import Navbar from '@/components/common/Navbar';
import Clients from '@/components/common/Clients';
import Marq2 from '@/components/common/Marq2';
import Header from '@/components/home-digital-agency/Header';
import Services from '@/components/home-digital-agency/Services';
import CampaignResults from '@/components/home-digital-agency/CampaignResults';
import Intro2 from '@/components/home-digital-agency/Intro2';
import Numbers from '@/components/home-digital-agency/Numbers';
import Portfolio from '@/components/home-digital-agency/Portfolio';
import Feat from '@/components/home-digital-agency/Feat';
import Testimonials from '@/components/home-digital-agency/Testimonials';
import Blog from '@/components/home-digital-agency/Blog';

useHead({
  title: 'Prayag Digital | Digital Marketing Agency',
  meta: [
    { name: 'description', content: 'Prayag Digital is a full-service digital marketing agency specializing in Meta Ads, Social Media Management, Shopify Websites, Logo Design, Graphic Design, and Video Editing.' },
  ],
  script: [
    {
      type: 'application/ld+json',
      children: JSON.stringify({
        '@context': 'https://schema.org',
        '@type': 'Organization',
        name: 'Prayag Digital',
        url: 'https://prayagdigital.com',
        logo: 'https://prayagdigital.com/assets/imgs/logo.png',
        description: 'Full-service digital marketing agency specializing in Meta Ads, Social Media Management, Shopify Websites, Logo Design, Graphic Design, and Video Editing.',
        address: {
          '@type': 'PostalAddress',
          streetAddress: 'Plot no 33, Lane no 5, Vishanpuri Colony, Mundera',
          addressLocality: 'Prayagraj',
          addressRegion: 'Uttar Pradesh',
          postalCode: '211011',
          addressCountry: 'IN',
        },
        sameAs: [
          'https://www.instagram.com/prayag.digital',
          'https://www.linkedin.com/in/prayag-digital-871b05437',
          'https://whatsapp.com/channel/0029VbBFNw9DzgT3yoACmM3J',
        ],
        contactPoint: {
          '@type': 'ContactPoint',
          telephone: '+91-9235462307',
          email: 'prayagdigital.in@gmail.com',
          contactType: 'customer service',
          availableLanguage: ['English', 'Hindi'],
        },
      }),
    },
  ],
});
</script>

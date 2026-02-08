<template>
  <nav class="navbar navbar-expand-lg bord blur">
    <div class="container o-hidden">
      <a class="logo icon-img-120" href="#">
        <img src="/assets/imgs/logo.png" alt="logo" />
      </a>

      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="icon-bar">
          <i class="fas fa-bars"></i>
        </span>
      </button>

      <div
        class="collapse navbar-collapse justify-content-center"
        id="navbarSupportedContent"
      >
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="/">
              <span class="rolling-text">Home</span>
            </a>
          </li>

          <li
            @mousemove="handleDropdownMouseMove"
            @mouseleave="handleDropdownMouseLeave"
            class="nav-item dropdown"
          >
            <a
              class="nav-link dropdown-toggle"
              data-toggle="dropdown"
              href="#"
              role="button"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="rolling-text">Company</span>
            </a>
            <ul class="dropdown-menu">
              <li>
                <a class="dropdown-item" href="/page-about"> About Us </a>
              </li>
              <li>
                <a class="dropdown-item" href="/page-team"> Our Team </a>
              </li>
              <li>
                <a class="dropdown-item" href="/page-FAQ"> FAQ </a>
              </li>
            </ul>
          </li>

          <li
            @mousemove="handleDropdownMouseMove"
            @mouseleave="handleDropdownMouseLeave"
            class="nav-item dropdown"
          >
            <a
              class="nav-link dropdown-toggle"
              data-toggle="dropdown"
              href="#"
              role="button"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="rolling-text">Services</span>
            </a>
            <ul class="dropdown-menu">
              <li>
                <a class="dropdown-item" href="/service-meta-ads"> Meta Ads </a>
              </li>
              <li>
                <a class="dropdown-item" href="/service-google-ads"> Google Ads </a>
              </li>
              <li>
                <a class="dropdown-item" href="/service-social-media"> Social Media Handling </a>
              </li>
              <li>
                <a class="dropdown-item" href="/service-shopify"> Shopify Websites </a>
              </li>
              <li>
                <a class="dropdown-item" href="/service-ppc"> Pay Per Click </a>
              </li>
            </ul>
          </li>

          <li
            @mousemove="handleDropdownMouseMove"
            @mouseleave="handleDropdownMouseLeave"
            class="nav-item dropdown"
          >
            <a
              class="nav-link dropdown-toggle"
              data-toggle="dropdown"
              href="#"
              role="button"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="rolling-text">Portfolio</span>
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="/portfolio-grid"> Portfolio Grid </a>
              <a class="dropdown-item" href="/portfolio-masonry"> Portfolio Masonry </a>
            </div>
          </li>

          <li
            @mousemove="handleDropdownMouseMove"
            @mouseleave="handleDropdownMouseLeave"
            class="nav-item dropdown"
          >
            <a
              class="nav-link dropdown-toggle"
              data-toggle="dropdown"
              href="#"
              role="button"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="rolling-text">Blog</span>
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="/blog-grid-sidebar"> Blog Grid </a>
              <a class="dropdown-item" href="/blog-details"> Blog Details </a>
            </div>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="/page-contact">
              <span class="rolling-text">Contact</span>
            </a>
          </li>
        </ul>
      </div>

      <div class="contact-button">
        <a
          href="/page-contact"
          class="butn butn-sm butn-bg main-colorbg radius-5"
        >
          <span class="text">Get a Quote</span>
        </a>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { onMounted, onUnmounted } from 'vue';
import { ref } from 'vue';

function handleScroll() {
  const bodyScroll = window.scrollY;
  const navbar = document.querySelector('.navbar');

  if (bodyScroll > 300) navbar.classList.add('nav-scroll');
  else navbar.classList.remove('nav-scroll');
}

function handleDropdownMouseMove(event) {
  event.currentTarget.querySelector('.dropdown-menu').classList.add('show');
}

function handleDropdownMouseLeave(event) {
  event.currentTarget.querySelector('.dropdown-menu').classList.remove('show');
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll);
});

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll);
});
</script>

<template>
  <section class="shopify-case-study section-padding pt-0">
    <div class="container">
      <div class="sec-head mb-50">
        <div class="row align-items-center">
          <div class="col-lg-8">
            <h6 class="sub-title main-color mb-15">E-Commerce Performance Proof • Shopify & Meta Ads</h6>
            <h2 class="fw-600 fz-50 text-u">
              Real Orders. <span class="fw-200">Real Customers. Real Results.</span>
            </h2>
            <p class="fz-18 mt-15 p-color">
              Live proof from our client Shopify stores. From rapid minute-by-minute COD order streams to ₹40,000+ revenue milestones on lean ₹400/day ad spend, we deliver with <strong>Order Assurance in Advertising</strong>.
            </p>
          </div>
          <div class="col-lg-4 text-lg-end mt-4 mt-lg-0">
            <a
              href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20to%20scale%20my%20Shopify%20store%20with%20Order%20Assurance"
              target="_blank"
              rel="noopener noreferrer"
              class="butn butn-md butn-bg main-colorbg radius-30"
            >
              <i class="fab fa-whatsapp mr-10"></i>
              <span class="text">Claim Order Assurance</span>
            </a>
          </div>
        </div>
      </div>

      <!-- Case Study Tab Switcher -->
      <div class="case-tabs d-flex flex-wrap align-items-center mb-40">
        <button
          type="button"
          class="tab-btn mr-15 mb-10"
          :class="{ active: activeTab === 'orders' }"
          @click="activeTab = 'orders'"
        >
          <i class="fas fa-boxes mr-10"></i> Live Order Stream (₹999 COD Velocity)
        </button>
        <button
          type="button"
          class="tab-btn mb-10"
          :class="{ active: activeTab === 'revenue' }"
          @click="activeTab = 'revenue'"
        >
          <i class="fas fa-chart-line mr-10"></i> ₹40,500+ Revenue Milestone (₹400/Day)
        </button>
      </div>

      <!-- Tab 1: Live Order Stream (₹999 COD Stream) -->
      <div v-if="activeTab === 'orders'">
        <!-- Metrics Row -->
        <div class="row mb-50">
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Order Velocity</span>
              <h3 class="fw-700 main-color mb-5">Every 2-3 Mins</h3>
              <p class="fz-13 opacity-7">12:04, 12:07, 12:09, 12:10, 12:11...</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Ticket Size / AOV</span>
              <h3 class="fw-700 main-color mb-5">₹999 / Order</h3>
              <p class="fz-13 opacity-7">Consistent high-margin cart</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Checkout Funnel</span>
              <h3 class="fw-700 main-color mb-5">Releasit COD Form</h3>
              <p class="fz-13 opacity-7">1-click zero-friction checkout</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Our Service Guarantee</span>
              <h3 class="fw-700 main-color mb-5">Order Assurance</h3>
              <p class="fz-13 opacity-7">Real verified customer orders</p>
            </div>
          </div>
        </div>

        <!-- Screenshot Showcase & Key Takeaways -->
        <div class="row lg-marg align-items-center">
          <div class="col-lg-7">
            <div class="proof-img-box radius-15 o-hidden bord mb-4 mb-lg-0">
              <div class="proof-img-header d-flex align-items-center px-3 py-2 bord-thin-bottom">
                <span class="circle-dot red mr-5"></span>
                <span class="circle-dot yellow mr-5"></span>
                <span class="circle-dot green mr-15"></span>
                <span class="fz-12 opacity-7"><i class="fas fa-lock mr-5"></i> Shopify Admin • Live Incoming Order Stream (CartCrave)</span>
              </div>
              <a href="/assets/imgs/shopify-orders-proof.jpg" target="_blank" rel="noopener noreferrer" title="Click to view full screenshot">
                <img
                  src="/assets/imgs/shopify-orders-proof.jpg"
                  alt="Prayag Digital Shopify Live Orders Stream Proof"
                  class="img-fluid w-100"
                  style="display: block; cursor: zoom-in;"
                />
              </a>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="pl-lg-3">
              <h4 class="mb-20 fw-500">How We Trigger Rapid-Fire Shopify Orders:</h4>
              
              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-bolt"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">1-Click COD Checkout Funnel</h6>
                  <p class="fz-14 opacity-8">We integrate high-converting Indian COD forms (Releasit) directly onto the product page, eliminating multi-step cart drop-offs.</p>
                </div>
              </div>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-bullseye"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">High-Intent Ads + Late-Night Scaling</h6>
                  <p class="fz-14 opacity-8">Our Meta ad targeting taps into late-night impulse shoppers when conversion intent is peak and competition is lowest.</p>
                </div>
              </div>

              <div class="d-flex mb-30">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-shield-alt"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Order Assurance in Advertising</h6>
                  <p class="fz-14 opacity-8">We don't settle for website traffic. We optimize exclusively for profitable, verified customer checkouts.</p>
                </div>
              </div>

              <div class="d-flex flex-wrap align-items-center">
                <NuxtLink to="/page-contact" class="butn butn-md butn-bord radius-30 mr-20 mb-10">
                  <span class="text">Scale My Store</span>
                </NuxtLink>
                <a
                  href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20to%20scale%20my%20Shopify%20orders"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="main-color fw-600 fz-14 d-inline-flex align-items-center mb-10"
                >
                  <i class="fab fa-whatsapp mr-10 fz-18"></i> Chat on WhatsApp
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Tab 2: ₹40,500+ Revenue Milestone -->
      <div v-if="activeTab === 'revenue'">
        <!-- Metrics Row -->
        <div class="row mb-50">
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Total Sales Generated</span>
              <h3 class="fw-700 main-color mb-5">₹40,500+</h3>
              <p class="fz-13 opacity-7">Direct website revenue</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Verified Orders</span>
              <h3 class="fw-700 main-color mb-5">57 Orders</h3>
              <p class="fz-13 opacity-7">Captured & fulfilled orders</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Controlled Daily Spend</span>
              <h3 class="fw-700 main-color mb-5">₹400 / day</h3>
              <p class="fz-13 opacity-7">Micro-budget scaling</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Our Service Guarantee</span>
              <h3 class="fw-700 main-color mb-5">Order Assurance</h3>
              <p class="fz-13 opacity-7">Sales-first advertising</p>
            </div>
          </div>
        </div>

        <!-- Screenshot Showcase & Key Takeaways -->
        <div class="row lg-marg align-items-center">
          <div class="col-lg-7">
            <div class="proof-img-box radius-15 o-hidden bord mb-4 mb-lg-0">
              <div class="proof-img-header d-flex align-items-center px-3 py-2 bord-thin-bottom">
                <span class="circle-dot red mr-5"></span>
                <span class="circle-dot yellow mr-5"></span>
                <span class="circle-dot green mr-15"></span>
                <span class="fz-12 opacity-7"><i class="fas fa-lock mr-5"></i> Shopify Admin • Verified Store Revenue</span>
              </div>
              <a href="/assets/imgs/shopify-result-40k.jpg" target="_blank" rel="noopener noreferrer" title="Click to view full screenshot">
                <img
                  src="/assets/imgs/shopify-result-40k.jpg"
                  alt="Prayag Digital Shopify 40k Sales Proof"
                  class="img-fluid w-100"
                  style="display: block; cursor: zoom-in;"
                />
              </a>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="pl-lg-3">
              <h4 class="mb-20 fw-500">Why Our Shopify + Ads Strategy Converts:</h4>
              
              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">High-Speed Checkout Optimization</h6>
                  <p class="fz-14 opacity-8">We eliminate checkout friction, integrate Indian COD confirmation forms, and streamline the mobile buying process.</p>
                </div>
              </div>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Low-Risk ₹400/Day Testing</h6>
                  <p class="fz-14 opacity-8">No large budget required. We validate product-market fit on just ₹400/day before putting more ad spend behind winners.</p>
                </div>
              </div>

              <div class="d-flex mb-30">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Order Assurance in Advertising</h6>
                  <p class="fz-14 opacity-8">We focus strictly on customer purchases and revenue, not vanity impressions or pointless clicks.</p>
                </div>
              </div>

              <div class="d-flex flex-wrap align-items-center">
                <NuxtLink to="/page-contact" class="butn butn-md butn-bord radius-30 mr-20 mb-10">
                  <span class="text">Build My Store</span>
                </NuxtLink>
                <a
                  href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20Order%20Assurance%20for%20my%20Shopify%20store"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="main-color fw-600 fz-14 d-inline-flex align-items-center mb-10"
                >
                  <i class="fab fa-whatsapp mr-10 fz-18"></i> Chat on WhatsApp
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';

const activeTab = ref('orders');
</script>

<style scoped>
.tab-btn {
  background: rgba(255, 255, 255, 0.04);
  color: #fff;
  border: 1px solid rgba(255, 255, 255, 0.1);
  padding: 12px 24px;
  border-radius: 30px;
  font-size: 14px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s ease;
}
.tab-btn:hover {
  background: rgba(255, 255, 255, 0.08);
  border-color: rgba(255, 255, 255, 0.2);
}
.tab-btn.active {
  background: #0f4c3a;
  border-color: #0f4c3a;
  color: #fff;
  box-shadow: 0 4px 15px rgba(15, 76, 58, 0.4);
}
.metric-card {
  background: rgba(255, 255, 255, 0.02);
  transition: all 0.3s ease;
}
.metric-card:hover {
  background: rgba(255, 255, 255, 0.05);
  transform: translateY(-4px);
}
.proof-img-box {
  background: #0b0f12;
}
.proof-img-header {
  background: rgba(255, 255, 255, 0.04);
}
.circle-dot {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  display: inline-block;
}
.circle-dot.red { background: #ff5f56; }
.circle-dot.yellow { background: #ffbd2e; }
.circle-dot.green { background: #27c93f; }
</style>

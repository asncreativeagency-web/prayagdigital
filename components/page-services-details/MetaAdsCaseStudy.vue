<template>
  <section class="meta-case-study section-padding pt-0">
    <div class="container">
      <div class="sec-head mb-50">
        <div class="row align-items-center">
          <div class="col-lg-8">
            <h6 class="sub-title main-color mb-15">Real Client Proof • Performance Marketing</h6>
            <h2 class="fw-600 fz-50 text-u">
              Stop Boosting. <span class="fw-200">Start Scaling.</span>
            </h2>
            <p class="fz-18 mt-15 p-color">
              Real Ads Manager data from our managed client accounts. We test on lean micro-budgets, validate winning creatives, and scale profitability.
            </p>
          </div>
          <div class="col-lg-4 text-lg-end mt-4 mt-lg-0">
            <a
              href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20a%20Meta%20Ads%20Audit"
              target="_blank"
              rel="noopener noreferrer"
              class="butn butn-md butn-bg main-colorbg radius-30"
            >
              <i class="fab fa-whatsapp mr-10"></i>
              <span class="text">Get Free Ads Audit</span>
            </a>
          </div>
        </div>
      </div>

      <!-- Case Study Tab Switcher -->
      <div class="case-tabs d-flex flex-wrap align-items-center mb-40">
        <button
          type="button"
          class="tab-btn mr-15 mb-10"
          :class="{ active: activeTab === 'leadgen' }"
          @click="activeTab = 'leadgen'"
        >
          <i class="fab fa-whatsapp mr-10"></i> 1,082 WhatsApp Leads (₹7.98 – ₹12)
        </button>
        <button
          type="button"
          class="tab-btn mr-15 mb-10"
          :class="{ active: activeTab === 'ecom' }"
          @click="activeTab = 'ecom'"
        >
          <i class="fas fa-shopping-cart mr-10"></i> E-Commerce Purchases ($0.60 CPA)
        </button>
        <button
          type="button"
          class="tab-btn mb-10"
          :class="{ active: activeTab === 'sales' }"
          @click="activeTab = 'sales'"
        >
          <i class="fas fa-rupee-sign mr-10"></i> 33 Website Sales (₹61.85 / Purchase)
        </button>
      </div>

      <!-- Case 1: WhatsApp Lead Generation (1,082 Chats) -->
      <div v-if="activeTab === 'leadgen'">
        <!-- Metrics Row -->
        <div class="row mb-50">
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Total Customer Chats</span>
              <h3 class="fw-700 main-color mb-5">1,082 Leads</h3>
              <p class="fz-13 opacity-7">Direct WhatsApp messaging</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Cost Per Customer Chat</span>
              <h3 class="fw-700 main-color mb-5">₹7.98 – ₹12</h3>
              <p class="fz-13 opacity-7">Cheapest chat: ₹7.98</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Campaign Timeline</span>
              <h3 class="fw-700 main-color mb-5">19 Days</h3>
              <p class="fz-13 opacity-7">Sep 1 – Sep 19, 2026</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Total Ad Spend</span>
              <h3 class="fw-700 main-color mb-5">₹13,051</h3>
              <p class="fz-13 opacity-7">Across 3 active campaigns</p>
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
                <span class="fz-12 opacity-7"><i class="fas fa-lock mr-5"></i> Meta Ads Manager • Verified 1,082 WhatsApp Leads</span>
              </div>
              <a href="/assets/imgs/whatsapp-leads-1082.jpg" target="_blank" rel="noopener noreferrer" title="Click to view full screenshot">
                <img
                  src="/assets/imgs/whatsapp-leads-1082.jpg"
                  alt="Prayag Digital 1082 WhatsApp Leads Proof"
                  class="img-fluid w-100"
                  style="display: block; cursor: zoom-in;"
                />
              </a>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="pl-lg-3">
              <h4 class="mb-20 fw-500">19 Days. 1,082 Customers. ~₹12 Each.</h4>
              
              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Direct-to-WhatsApp Funnels</h6>
                  <p class="fz-14 opacity-8">We route targeted traffic straight into WhatsApp conversations, shortening the sales cycle and closing buyers immediately.</p>
                </div>
              </div>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">₹7.98 Lowest Customer Chat</h6>
                  <p class="fz-14 opacity-8">Our top-performing ad set generated 285 messaging leads at just ₹7.98 each on a ₹200/day micro-budget.</p>
                </div>
              </div>

              <div class="d-flex mb-30">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Your Ads Aren't The Problem</h6>
                  <p class="fz-14 opacity-8">Still spending on ads with no incoming leads? It's not the platform—it's the targeting, creative hook, and setup. We fix all three.</p>
                </div>
              </div>

              <div class="d-flex flex-wrap align-items-center">
                <NuxtLink to="/page-contact" class="butn butn-md butn-bord radius-30 mr-20 mb-10">
                  <span class="text">Book Free Ad Audit</span>
                </NuxtLink>
                <a
                  href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20to%20audit%20my%20Meta%20Ads%20for%20lead%20generation"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="main-color fw-600 fz-14 d-inline-flex align-items-center mb-10"
                >
                  <i class="fab fa-whatsapp mr-10 fz-18"></i> DM "ADS" on WhatsApp
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Case 2: E-Commerce Micro-Testing ($0.60 CPA) -->
      <div v-else-if="activeTab === 'ecom'">
        <!-- Metrics Row -->
        <div class="row mb-50">
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Cost Per Purchase</span>
              <h3 class="fw-700 main-color mb-5">$0.60 – $0.72</h3>
              <p class="fz-13 opacity-7">Industry avg: $15 – $25</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Verified Orders</span>
              <h3 class="fw-700 main-color mb-5">100+ Purchases</h3>
              <p class="fz-13 opacity-7">On micro-testing campaigns</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Micro-Budget Testing</span>
              <h3 class="fw-700 main-color mb-5">$2 – $3 / day</h3>
              <p class="fz-13 opacity-7">Proving ROAS before scaling</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Account Reach & CTR</span>
              <h3 class="fw-700 main-color mb-5">548K+ Reach</h3>
              <p class="fz-13 opacity-7">2.08% overall link CTR</p>
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
                <span class="fz-12 opacity-7"><i class="fas fa-lock mr-5"></i> Meta Ads Manager • Verified E-Commerce Purchases</span>
              </div>
              <a href="/assets/imgs/meta-ads-result.jpg" target="_blank" rel="noopener noreferrer" title="Click to view full screenshot">
                <img
                  src="/assets/imgs/meta-ads-result.jpg"
                  alt="Prayag Digital Meta Ads Real Results"
                  class="img-fluid w-100"
                  style="display: block; cursor: zoom-in;"
                />
              </a>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="pl-lg-3">
              <h4 class="mb-20 fw-500">How We Engineered These Results:</h4>
              
              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Micro-Budget Validation</h6>
                  <p class="fz-14 opacity-8">We tested single winning angles on just $2 to $3/day, generating 15 sales from $9.03 ad spend without burning client capital.</p>
                </div>
              </div>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">High-Converting Creative Hooks</h6>
                  <p class="fz-14 opacity-8">Scroll-stopping 3-second triggers kept our CTR above 2.08% across 665,000+ impressions.</p>
                </div>
              </div>

              <div class="d-flex mb-30">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Low Budget ≠ Low Results</h6>
                  <p class="fz-14 opacity-8">A single $2/day campaign generated 76 purchases at $0.72 CPA ($54.66 total spent).</p>
                </div>
              </div>

              <div class="d-flex flex-wrap align-items-center">
                <NuxtLink to="/page-contact" class="butn butn-md butn-bord radius-30 mr-20 mb-10">
                  <span class="text">Book Free Consultation</span>
                </NuxtLink>
                <a
                  href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20to%20scale%20my%20Meta%20Ads"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="main-color fw-600 fz-14 d-inline-flex align-items-center mb-10"
                >
                  <i class="fab fa-whatsapp mr-10 fz-18"></i> Quick WhatsApp Chat
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Case 3: Website Sales Campaign (33 Purchases @ ₹61.85) -->
      <div v-else-if="activeTab === 'sales'">
        <!-- Metrics Row -->
        <div class="row mb-50">
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Website Purchases</span>
              <h3 class="fw-700 main-color mb-5">33 Sales</h3>
              <p class="fz-13 opacity-7">Tracked via Meta Pixel</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Cost Per Purchase</span>
              <h3 class="fw-700 main-color mb-5">₹61.85</h3>
              <p class="fz-13 opacity-7">Per verified website sale</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Total Ad Spend</span>
              <h3 class="fw-700 main-color mb-5">₹2,040.97</h3>
              <p class="fz-13 opacity-7">On a ₹400/day budget</p>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6 mb-30">
            <div class="metric-card p-4 radius-15 bord h-100">
              <span class="p-color fz-14 d-block mb-10">Impressions</span>
              <h3 class="fw-700 main-color mb-5">35,032</h3>
              <p class="fz-13 opacity-7">Sep 16 – Sep 22, 2026</p>
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
                <span class="fz-12 opacity-7"><i class="fas fa-lock mr-5"></i> Meta Ads Manager • Verified 33 Website Purchases</span>
              </div>
              <a href="/assets/imgs/meta-ads-sales-33-purchases.png" target="_blank" rel="noopener noreferrer" title="Click to view full screenshot">
                <img
                  src="/assets/imgs/meta-ads-sales-33-purchases.png"
                  alt="Prayag Digital Meta Ads Sales Campaign - 33 Website Purchases at ₹61.85 Cost per Purchase"
                  class="img-fluid w-100"
                  loading="lazy"
                  style="display: block; cursor: zoom-in;"
                />
              </a>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="pl-lg-3">
              <h4 class="mb-20 fw-500">33 Purchases in Just 7 Days 🔥</h4>
              <p class="fz-15 opacity-8 mb-25">A properly structured Meta Ads campaign reaches the right audience and generates real website sales.</p>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">Optimized for Purchases, Not Clicks</h6>
                  <p class="fz-14 opacity-8">The campaign was set up on the Sales objective with pixel-tracked purchase events, so Meta spent money finding buyers instead of browsers.</p>
                </div>
              </div>

              <div class="d-flex mb-25">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">₹2,040.97 Total Spend</h6>
                  <p class="fz-14 opacity-8">A controlled ₹400/day budget brought in 33 real website orders in a single week, with no wasted spend on vanity metrics.</p>
                </div>
              </div>

              <div class="d-flex mb-30">
                <div class="mr-15 main-color fz-20">
                  <i class="fas fa-check-circle"></i>
                </div>
                <div>
                  <h6 class="fz-16 mb-5">One Focused Winning Campaign</h6>
                  <p class="fz-14 opacity-8">We paused the weaker campaigns and put the full budget behind the one that converted.</p>
                </div>
              </div>

              <div class="d-flex flex-wrap align-items-center">
                <NuxtLink to="/page-contact" class="butn butn-md butn-bord radius-30 mr-20 mb-10">
                  <span class="text">Run Meta Ads for My Business</span>
                </NuxtLink>
                <a
                  href="https://wa.me/919235462307?text=Hi%20Prayag%20Digital,%20I%20want%20to%20generate%20sales%20through%20Meta%20Ads"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="main-color fw-600 fz-14 d-inline-flex align-items-center mb-10"
                >
                  <i class="fab fa-whatsapp mr-10 fz-18"></i> +91 92354 62307
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

const activeTab = ref('leadgen');
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

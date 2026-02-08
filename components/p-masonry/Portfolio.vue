<template>
  <section class="work-minimal section-padding pb-40">
    <div class="container">
      <div class="row mb-80">
        <div class="col-lg-4">
          <div class="sec-head">
            <h6 class="sub-title main-color mb-10">DISCOVER OUR CASES</h6>
            <h3>Latest Projects</h3>
          </div>
        </div>
        <div
          class="filtering col-lg-8 d-flex justify-content-end align-items-end"
        >
          <div>
            <div class="filter">
              <span data-filter="*" class="active" data-count="08"> All </span>
              <span data-filter=".meta-ads" data-count="02"> Meta Ads </span>
              <span data-filter=".google-ads" data-count="02"> Google Ads </span>
              <span data-filter=".social" data-count="02"> Social </span>
              <span data-filter=".shopify" data-count="01"> Shopify </span>
              <span data-filter=".ppc" data-count="01"> PPC </span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-xxl">
      <div class="gallery2 row sm-marg">
        <div class="col-lg-6 items social">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/h1.jpg" alt="" />
              <div class="cont inline d-flex align-items-center">
                <div>
                  <h5>
                    <a href="/project-details">Viral Campaign</a>
                  </h5>
                </div>
                <div class="ml-auto">
                  <p>
                    <a href="/project-details">Social Media</a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 items width2 google-ads">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/1.jpg" alt="" />
              <div class="cont">
                <h5>
                  <a href="/project-details">Search Intent</a>
                </h5>
                <p>
                  <a href="/project-details">Google Ads</a>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 items width2 shopify">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/2.jpg" alt="" />
              <div class="cont">
                <h5>
                  <a href="/project-details">Store Scale</a>
                </h5>
                <p>
                  <a href="/project-details">Shopify</a>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 items width2 meta-ads">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/3.jpg" alt="" />
              <div class="cont">
                <h5>
                  <a href="/project-details">FB Audience</a>
                </h5>
                <p>
                  <a href="/project-details">Meta Ads</a>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 items width2 ppc">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/4.jpg" alt="" />
              <div class="cont">
                <h5>
                  <a href="/project-details">Acquisition</a>
                </h5>
                <p>
                  <a href="/project-details">PPC</a>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 items social">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/h2.jpg" alt="" />
              <div class="cont inline d-flex align-items-center">
                <div>
                  <h5>
                    <a href="/project-details">Brand Awareness</a>
                  </h5>
                </div>
                <div class="ml-auto">
                  <p>
                    <a href="/project-details">Social Media</a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 items meta-ads">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/h3.jpg" alt="" />
              <div class="cont inline d-flex align-items-center">
                <div>
                  <h5>
                    <a href="/project-details">Retargeting</a>
                  </h5>
                </div>
                <div class="ml-auto">
                  <p>
                    <a href="/project-details">Meta Ads</a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 items google-ads">
          <div class="item mt-10">
            <div class="img">
              <img src="/assets/imgs/works/4/h4.jpg" alt="" />
              <div class="cont inline d-flex align-items-center">
                <div>
                  <h5>
                    <a href="/project-details">Shopping Ads</a>
                  </h5>
                </div>
                <div class="ml-auto">
                  <p>
                    <a href="/project-details">Google Ads</a>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// You can include your initIsotope function here
import initIsotope2 from '@/common/initIsotope2';

// Ensure the initIsotope function is called after the component is mounted
onMounted(() => {
  initIsotope2();
});
</script>

<style scoped>
/* Add your styles here */
</style>

<template>
  <section
    class="relative"
    style="
      background: linear-gradient(
        8.8deg,
        #fbfcfe -5.41%,
        #fbfcfe -0.47%,
        rgba(253, 242, 251, 0.5) 53.08%,
        rgba(258, 248, 243, 0.5) 64.74%,
        rgba(222, 234, 251, 0.5) 93.93%
      );
    "
  >
    <ul class="stacking-cards-list">
      <!-- CARD 1 -->
      <li class="stacking-card sticky z-10">
        <div class="card-content bg-white">
          <div
            class="grid grid-cols-1 lg:grid-cols-2 items-center h-full web-container gap-x-20 gap-y-10"
          >
            <div class="text-center lg:text-left">
              <div class="flex flex-col gap-8">
                <h1
                  class="text-[60px] font-bold leading-[1.15] text-[#2E353E]"
                >
                  Post To All Your
                  <span class="text-[#E77619]">Social Media</span>
                  In One GO
                </h1>

                <p
                  class="text-[#73849B] text-[28px] leading-[1.8] font-medium"
                >
                  Connect all your social media accounts and manage posts from
                  one clean interface.
                </p>
              </div>
            </div>

            <div class="flex items-center justify-center">
              <img
                src="https://sociair.com/_nuxt/socialMedia.Bm_SD4gv.svg"
                class="w-full max-w-[650px]"
              />
            </div>
          </div>
        </div>
      </li>

      <!-- CARD 2 -->
      <li class="stacking-card sticky z-20">
        <div class="card-content bg-white">
          <div
            class="grid grid-cols-1 lg:grid-cols-2 items-center h-full web-container gap-x-20 gap-y-10"
          >
            <div class="text-center lg:text-left">
              <div class="flex flex-col gap-8">
                <h1
                  class="text-[60px] font-bold leading-[1.15] text-[#2E353E]"
                >
                  All Your
                  <span class="text-[#E77619]">Customer</span>
                  Messages In One Place
                </h1>

                <p
                  class="text-[#73849B] text-[28px] leading-[1.8] font-medium"
                >
                  Handle all your Facebook, Instagram, WhatsApp and TikTok
                  customers from one place.
                </p>
              </div>
            </div>

            <div class="flex items-center justify-center">
              <img
                src="https://sociair.com/_nuxt/customer.D8rJy0ie.svg"
                class="w-full max-w-[650px]"
              />
            </div>
          </div>
        </div>
      </li>

      <!-- CARD 3 -->
      <li class="stacking-card sticky z-30">
        <div class="card-content bg-white">
          <div
            class="grid grid-cols-1 lg:grid-cols-2 items-center h-full web-container gap-x-20 gap-y-10"
          >
            <div class="text-center lg:text-left">
              <div class="flex flex-col gap-8">
                <h1
                  class="text-[60px] font-bold leading-[1.15] text-[#2E353E]"
                >
                  Still Tracking
                  <span class="text-[#E77619]">Payments</span>
                  And
                  <span class="text-[#E77619]">Deliveries</span>
                  Manually?
                </h1>

                <p
                  class="text-[#73849B] text-[28px] leading-[1.8] font-medium"
                >
                  Track delivery and payment status from one dashboard.
                </p>
              </div>
            </div>

            <div class="flex items-center justify-center">
              <img
                src="https://sociair.com/_nuxt/payment.BY9B--Ef.svg"
                class="w-full max-w-[650px]"
              />
            </div>
          </div>
        </div>
      </li>

      <!-- CARD 4 -->
      <li class="stacking-card sticky z-40">
        <div class="card-content bg-white">
          <div
            class="grid grid-cols-1 lg:grid-cols-2 items-center h-full web-container gap-x-20 gap-y-10"
          >
            <div class="text-center lg:text-left">
              <div class="flex flex-col gap-8">
                <h1
                  class="text-[60px] font-bold leading-[1.15] text-[#2E353E]"
                >
                  Build Your
                  <span class="text-[#E77619]">Dream Website</span>
                  In Minutes
                </h1>

                <p
                  class="text-[#73849B] text-[28px] leading-[1.8] font-medium"
                >
                  Create and customize professional websites easily.
                </p>
              </div>
            </div>

            <div class="flex items-center justify-center">
              <img
                src="https://sociair.com/_nuxt/dreamWebsite.CVnEb3Cj.svg"
                class="w-full max-w-[650px]"
              />
            </div>
          </div>
        </div>
      </li>
    </ul>
  </section>
</template>

<style scoped>
.stacking-cards-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

/* STICKY CARD */
.stacking-card {
  position: sticky;
  top: 0;
  height: 100vh;
}

/* CARD DESIGN */
.card-content {
  height: 100vh;
  overflow: hidden;

  display: flex;
  align-items: center;

  border-radius: 32px 32px 0 0;

  box-shadow: 0 -10px 40px rgba(0, 0, 0, 0.06);

  border-top: 1px solid rgba(0, 0, 0, 0.04);
}

/* STACK EFFECT */
.stacking-card:nth-child(1) {
  top: 0;
}

.stacking-card:nth-child(2) {
  top: 20px;
}

.stacking-card:nth-child(3) {
  top: 40px;
}

.stacking-card:nth-child(4) {
  top: 60px;
}

/* MOBILE */
@media (max-width: 1024px) {
  .card-content {
    padding: 40px 20px;
  }

  h1 {
    font-size: 42px !important;
  }

  p {
    font-size: 20px !important;
    line-height: 1.6 !important;
  }
}
</style>
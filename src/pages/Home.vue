<template>
  <head>
    <title>Local Terra Roadmap</title>
  </head>
  <body>
    <header class="page-layout">
      <router-link to="/">
        <img
          src="@/assets/logo-horizontal-dark.svg"
          alt="Local Terra Logo"
          class="logo"
        />
      </router-link>
    </header>

    <div class="wrap-hero page-layout section-spacer">
      <article>
        <h1>Trade with your peers, locally.</h1>
        <p class="sub-header">
          Local Terra is a P2P decentralized marketplace that provides access to
          all that
          <a href="https://terra.money/" target="_blank">Terra Money</a> has to
          offer.
        </p>
        <div class="wrap-cta">
          <p>Want to know more about us?</p>
          <a
            href="https://localterra.money/localterra-litepaper-v1.pdf"
            target="_blank"
          >
            <button class="primary">Litepaper</button>
          </a>
        </div>
      </article>
      <div class="hero-img">
        <img
          src="@/assets/header-img.png"
          alt="Two people making a successful trade"
        />
      </div>
    </div>

    <main>
      <section class="featured section-spacer">
        <div class="wrap-featured page-layout">
          <div class="feature">
            <h2>
              <span class="text-primary">Fast and easy</span> on-off ramps
            </h2>
            <div class="wrap-img">
              <img
                v-if="!isMobile"
                src="@/assets/top-feature-01.png"
                alt="Image displaying a top feature"
              />
              <img
                v-else
                src="@/assets/top-feature-01-mobile.png"
                alt="Image displaying a top feature"
              />
            </div>
          </div>
          <div class="feature">
            <h2>
              <span class="text-primary">Trustless</span> trading experience
            </h2>
            <div class="wrap-img">
              <img
                v-if="!isMobile"
                src="@/assets/top-feature-02.png"
                alt="Image displaying a top feature"
              />
              <img
                v-else
                src="@/assets/top-feature-02-mobile.png"
                alt="Image displaying a top feature"
              />
            </div>
          </div>
        </div>
      </section>

      <section class="team section-spacer">
        <div class="wrap-team page-layout">
          <h2>Meet the <span class="text-primary">team</span></h2>
          <div class="wrap-members">
            <div class="team-member">
              <img
                src="@/assets/team/01.png"
                alt="Local Terra Bull"
                class="avatar squircicle"
              />
              <p class="name">Sam B</p>
              <p class="role">Rust Intern</p>
            </div>

            <div class="team-member">
              <img
                src="@/assets/team/02.png"
                alt="Local Terra Bull"
                class="avatar squircicle"
              />
              <p class="name">Gabs</p>
              <p class="role">Designer</p>
            </div>

            <div class="team-member">
              <img
                src="@/assets/team/03.png"
                alt="Local Terra Bull"
                class="avatar squircicle"
              />
              <p class="name">Davi</p>
              <p class="role">Smart Contract Developer</p>
            </div>

            <div class="team-member">
              <img
                src="@/assets/team/04.png"
                alt="Local Terra Bull"
                class="avatar squircicle"
              />
              <p class="name">Revo</p>
              <p class="role">Smart Contract Developer</p>
            </div>

            <div class="team-member">
              <img
                src="@/assets/team/05.png"
                alt="Local Terra Bull"
                class="avatar squircicle"
              />
              <p class="name">Gus</p>
              <p class="role">Business Development</p>
            </div>
          </div>
        </div>
      </section>

      <section class="roadmap page-layout section-spacer">
        <h2>Roadmap</h2>

        <div class="timeline-line"></div>

        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-done">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M20 6L9 17L4 12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Feb 18th, 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content done">
              <p class="title">LBP</p>
              <p class="description">$LOCAL token initial offer.</p>
            </div>
          </div>
        </div>
        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-done">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M20 6L9 17L4 12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Feb 23th, 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content done">
              <p class="title">Astroport LOCAL-UST pool</p>
              <p class="description">
                We are happy to announce that $LOCAL is now officially available
                on Astroport.
              </p>
              <p class="description">
                <a
                  href="https://app.astroport.fi/swap?from=uusd&to=terra1vchw83qt25j89zqwdpmdzj722sqxthnckqzxxp"
                  target="_blank"
                  >$LOCAL on Astroport</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-done">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M20 6L9 17L4 12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Mar 7th, 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content done">
              <p class="title">Discord Server Launch</p>
              <p class="description">
                Our community has a cozy place to get together now.
              </p>
              <p class="description">
                <a href="https://discord.gg/meXhfQ8TWr" target="_blank"
                  >Discord Server</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-done">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M20 6L9 17L4 12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Apr 2nd, 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content done">
              <p class="title">Testnet Launch</p>
              <p class="description">
                Beta on Testnet with community members. We're looking forward to
                receive your feedback and suggestions on the Testnet channel on
                our Discord.
              </p>
              <p class="description">
                <a href="https://testnet.localterra.money/" target="_blank"
                  >Testnet</a
                >
              </p>
            </div>
          </div>
        </div>
        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-todo">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M21 16V8.00002C20.9996 7.6493 20.9071 7.30483 20.7315 7.00119C20.556 6.69754 20.3037 6.44539 20 6.27002L13 2.27002C12.696 2.09449 12.3511 2.00208 12 2.00208C11.6489 2.00208 11.304 2.09449 11 2.27002L4 6.27002C3.69626 6.44539 3.44398 6.69754 3.26846 7.00119C3.09294 7.30483 3.00036 7.6493 3 8.00002V16C3.00036 16.3508 3.09294 16.6952 3.26846 16.9989C3.44398 17.3025 3.69626 17.5547 4 17.73L11 21.73C11.304 21.9056 11.6489 21.998 12 21.998C12.3511 21.998 12.696 21.9056 13 21.73L20 17.73C20.3037 17.5547 20.556 17.3025 20.7315 16.9989C20.9071 16.6952 20.9996 16.3508 21 16Z"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M3.27 6.96002L12 12.01L20.73 6.96002"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M12 22.08V12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Q2 . 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content todo">
              <p class="title">v1.0</p>
              <p class="description">Security Audit</p>
              <p class="description">
                Within the first release of Local Terra, makers will be able to
                create offers to buy and sell UST.
              </p>
            </div>
          </div>
        </div>
        <!-- END ROADMAP ITEM -->

        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-todo">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M21 16V8.00002C20.9996 7.6493 20.9071 7.30483 20.7315 7.00119C20.556 6.69754 20.3037 6.44539 20 6.27002L13 2.27002C12.696 2.09449 12.3511 2.00208 12 2.00208C11.6489 2.00208 11.304 2.09449 11 2.27002L4 6.27002C3.69626 6.44539 3.44398 6.69754 3.26846 7.00119C3.09294 7.30483 3.00036 7.6493 3 8.00002V16C3.00036 16.3508 3.09294 16.6952 3.26846 16.9989C3.44398 17.3025 3.69626 17.5547 4 17.73L11 21.73C11.304 21.9056 11.6489 21.998 12 21.998C12.3511 21.998 12.696 21.9056 13 21.73L20 17.73C20.3037 17.5547 20.556 17.3025 20.7315 16.9989C20.9071 16.6952 20.9996 16.3508 21 16Z"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M3.27 6.96002L12 12.01L20.73 6.96002"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M12 22.08V12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Q3 . 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content todo">
              <p class="title">Luna and CW20 tokens support.</p>
              <p class="description">
                We'll provide easy and quick fiat conversion to and from your
                favorite Terra Alt by leveraging the existing UST pairs on
                different AMMs and the composability of DeFi.
              </p>
            </div>
          </div>
        </div>
        <!-- END ROADMAP ITEM -->

        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-todo">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M21 16V8.00002C20.9996 7.6493 20.9071 7.30483 20.7315 7.00119C20.556 6.69754 20.3037 6.44539 20 6.27002L13 2.27002C12.696 2.09449 12.3511 2.00208 12 2.00208C11.6489 2.00208 11.304 2.09449 11 2.27002L4 6.27002C3.69626 6.44539 3.44398 6.69754 3.26846 7.00119C3.09294 7.30483 3.00036 7.6493 3 8.00002V16C3.00036 16.3508 3.09294 16.6952 3.26846 16.9989C3.44398 17.3025 3.69626 17.5547 4 17.73L11 21.73C11.304 21.9056 11.6489 21.998 12 21.998C12.3511 21.998 12.696 21.9056 13 21.73L20 17.73C20.3037 17.5547 20.556 17.3025 20.7315 16.9989C20.9071 16.6952 20.9996 16.3508 21 16Z"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M3.27 6.96002L12 12.01L20.73 6.96002"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M12 22.08V12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">Q4 . 2022</p>
          </div>
          <div class="wrap-content">
            <div class="content todo">
              <p class="title">IBC integration</p>
              <p class="description">
                (Inter-Blockchain Communication Protocol)
              </p>
              <p class="description">
                Your Cosmos native asset will have a direct bridge with fiat
                providers, powered by the combination of the best makers and
                liquidity pools with the decentralized stablecoin, $UST.
              </p>
            </div>
          </div>
        </div>
        <!-- END ROADMAP ITEM -->

        <div class="roadmap-item">
          <div class="wrap-date">
            <div class="icon-todo">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none">
                <path
                  d="M21 16V8.00002C20.9996 7.6493 20.9071 7.30483 20.7315 7.00119C20.556 6.69754 20.3037 6.44539 20 6.27002L13 2.27002C12.696 2.09449 12.3511 2.00208 12 2.00208C11.6489 2.00208 11.304 2.09449 11 2.27002L4 6.27002C3.69626 6.44539 3.44398 6.69754 3.26846 7.00119C3.09294 7.30483 3.00036 7.6493 3 8.00002V16C3.00036 16.3508 3.09294 16.6952 3.26846 16.9989C3.44398 17.3025 3.69626 17.5547 4 17.73L11 21.73C11.304 21.9056 11.6489 21.998 12 21.998C12.3511 21.998 12.696 21.9056 13 21.73L20 17.73C20.3037 17.5547 20.556 17.3025 20.7315 16.9989C20.9071 16.6952 20.9996 16.3508 21 16Z"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M3.27 6.96002L12 12.01L20.73 6.96002"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
                <path
                  d="M12 22.08V12"
                  stroke="inherit"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
            </div>
            <p class="date">2023</p>
          </div>
          <div class="wrap-content">
            <div class="content todo">
              <p class="title">To the future and beyond</p>
              <p class="description">Mobile App</p>
              <p class="description">Thorchain integration</p>
              <p class="description">Deeper Anchor integration</p>
            </div>
          </div>
        </div>
        <!-- END ROADMAP ITEM -->
      </section>
    </main>
    <footer class="section-spacer">
      <div class="wrap-footer page-layout">
        <router-link to="/">
          <img
            src="@/assets/logo-horizontal-dark.svg"
            alt="Local Terra Logo"
            class="logo"
          />
        </router-link>
        <div class="social">
          <a href="https://twitter.com/local_terra" target="_blank">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path
                d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
              ></path></svg
          ></a>

          <a href="https://github.com/Local-Terra" target="_blank">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path
                d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
              ></path></svg
          ></a>
          <a href="https://local-terra.medium.com/" target="_blank">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
              <circle cx="6" cy="12" r="5" fill="white" />
              <ellipse cx="15.5" cy="12" rx="2.5" ry="5" fill="white" />
              <ellipse cx="21" cy="12" rx="1" ry="5" fill="white" />
            </svg>
          </a>
        </div>
      </div>
    </footer>
  </body>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
  components: {},

  data: () => ({
    isMobile: false,
  }),

  beforeUnmount() {
    if (typeof window !== "undefined") {
      window.removeEventListener("resize", this.onResize, { passive: true });
    }
  },

  mounted() {
    this.onResize();
    window.addEventListener("resize", this.onResize, { passive: true });
  },

  methods: {
    onResize() {
      this.isMobile = window.innerWidth < 600;
    },
  },
});
</script>

<style lang="scss">
@import "@/style/app.scss";

.squircicle {
  mask: url(../assets/team/squircicle-mask.svg);
  mask-size: 100%;
}
</style>

<template>
  <section
    :class="{ 'is-large': $route.name === 'home' }"
    class="hero is-dark is-bold"
  >
    <div class="hero-body">
      <div class="container">
        <article class="media">
          <figure class="media-left">
            <p class="image is-128x128">
              <img
                src="@/assets/logo.svg"
                alt="brain.js logo"
                class="bordered"
                width="128"
                height="128"
              />
            </p>
          </figure>
          <div class="media-content">
            <div class="content">
              <p>
                <span class="title is-1">Brain.js</span>
                <br />
                <span class="subtitle is-2"
                  >GPU accelerated Neural networks in JavaScript</span
                >
                <br />
                for Browsers and Node.js
              </p>

              <div class="description">
                <hr />
                <p class="is-size-5">
                  Brain.js is a GPU accelerated library of Neural Networks
                  written in JavaScript for Browsers and Node.js. It is simple,
                  fast and easy to use.
                </p>
                <div class="field is-grouped">
                  <p class="control">
                    <router-link
                      to="/getting-started"
                      class="button is-light"
                      title="Installation & Quick Start"
                    >
                      <i class="material-icons">flash_on</i>
                      <span>Get Started Now</span>
                    </router-link>
                  </p>
                  <p class="control npm">
                    <a
                      href="https://nodei.co/npm/brain.js"
                      style="border-bottom: none"
                    >
                      <img
                        src="https://nodei.co/npm/brain.js.png/?compact=true"
                      />
                    </a>
                  </p>
                </div>
              </div>

              <!-- <br />
              <p class="control">
                <a
                  href="https://nodei.co/npm/brain.js/"
                  style="border-bottom: none"
                >
                  <img src="https://nodei.co/npm/brain.js.png?mini=true" />
                </a>
              </p> -->
            </div>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="sass" scoped>
.hero.is-large
  height: calc(100vh - 52px)

.control.npm
  img
    height: 36px;
</style>

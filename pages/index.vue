<template>
  <div>
    <div class="columns">
      <div class="column left-side is-one-fifth has-text-centered">
        <my-icon></my-icon>
      </div>
      <div class="column right-side">
        <section class="hero">
          <div class="hero-body">
            <div class="container">
              <h1 class="title">
                @corocn
              </h1>
              <h2 class="subtitle">
                Takahiro Tsuchiya
              </h2>
            </div>
          </div>
        </section>
      </div>
    </div>

    <div class="columns">
      <div class="column left-side is-one-fifth has-text-centered">
        Social
      </div>
      <div class="column right-side">
        <div class="tags">
          <span class="tag">Twitter</span>
          <span class="tag">Github</span>
          <span class="tag">Facebook</span>
          <span class="tag">Blog</span>
        </div>
      </div>
    </div>

    <div class="columns">
      <div class="column left-side is-one-fifth has-text-centered">
        Skills
      </div>
      <div class="column right-side">
        <div class="tags">
          <span class="tag">Ruby</span>
          <span class="tag">Rails</span>
          <span class="tag">PHP</span>
          <span class="tag">CakePHP</span>
          <span class="tag">MySQL</span>
          <span class="tag">AWS</span>
          <span class="tag">Modern Frontend</span>
          <span class="tag">React.js</span>
          <span class="tag">Vue.js</span>
          <span class="tag">Nuxt.js</span>
          <span class="tag">Speech Recognition</span>
          <span class="tag">Julius</span>
          <span class="tag">MMDAgent</span>
          <span class="tag">Auth0</span>
        </div>
      </div>
    </div>

    <div class="columns">
      <div class="column left-side is-one-fifth has-text-centered">
        Carrer
      </div>
      <div class="column right-side">
        <ul>
          <li>Misoca Inc. / Web Application Developer / 2017 - now</li>
          <li>Arc co.,ltd. / Web Application Developer / 2015 - 2017</li>
          <li>Denso Corporation. / Testing Enginner / 2013 - 2015</li>
          <li>Nagoya Institute of Technology. / Department of Scientific and Engineering Simulation. / 2011 - 2013 </li>
          <li>Nagoya Institute of Technology. / Computer Science. / 2007 - 2011</li>
        </ul>
      </div>
    </div>

  </div>
</template>

<script>
import MyIcon from '~/components/MyIcon.vue'
export default {
  components: { MyIcon }
}
</script>

<style>
  .left-side {
    padding-top: 30px;
  }

  h1 {
    bottom: 0;
  }

  .right-side {
    background-color: white;
  }

  li {
    margin-bottom: 3px;
  }
</style>

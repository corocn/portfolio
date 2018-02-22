<template>
  <div>
    <div class="columns summary">
      <div class="column left-side is-one-fifth has-text-centered">
        <my-icon></my-icon>
      </div>
      <div class="column right-side">
        <div class="hero">
          <div class="hero-body">
            <div class="container has-text-centered-mobile">
              <h1 class="title is-2">
                corocn
              </h1>
              <h2 class="subtitle is-4">
                Takahiro Tsuchiya
              </h2>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section class="columns social">
      <div class="column left-side is-one-fifth has-text-centered">
        <h3 class="title is-4">Social</h3>
      </div>
      <div class="column right-side">
        <div class="tags">
          <span class="tag">Twitter</span>
          <span class="tag">Github</span>
          <span class="tag">Facebook</span>
          <span class="tag">Blog</span>
        </div>
      </div>
    </section>

    <section class="columns skill">
      <div class="column left-side is-one-fifth has-text-centered">
        <h3 class="title is-4">Skill</h3>
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
    </section>

    <section class="columns carrer">
      <div class="column left-side is-one-fifth has-text-centered">
        <h3 class="title is-4">Carrer</h3>
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
    </section>

  </div>
</template>

<script>
import MyIcon from '~/components/MyIcon.vue'
export default {
  components: { MyIcon }
}
</script>

<style>
  h2 {
    margin-top: 10px;
  }

  .right-side {
    margin-left: 20px;
    margin-right: 20px;
    background-color: white;
  }

  li {
    margin-bottom: 3px;
  }

  section.social div.left-side{
    border-right: 10px solid #ff98be;
  }

  section.skill div.left-side{
    border-right: 10px solid #85d6ff;
  }

  section.carrer div.left-side{
    border-right: 10px solid #ffe893;
  }

  section div{
    margin-bottom: 40px;
  }
</style>

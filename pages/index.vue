<template>
  <div>
    <section class="hero is-dark">
      <div class="hero-body">
        <div class="container has-text-centered">
          <my-icon></my-icon>
          <h1 class="title">
            corocn
          </h1>
          <h2 class="subtitle">
            Takahiro Tsuchiya
          </h2>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="columns">
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Social Accounts
              </p>
            </header>
            <div class="card-content">
              <div class="content">
                <div class="tags">
                  <social-tag name="twitter" href="https://twitter.com/corocn"></social-tag>
                  <social-tag name="github" href="https://github.com/corocn"></social-tag>
                  <social-tag name="facebook" href="https://www.facebook.com/takahiro.tsuchiya.1217"></social-tag>
                  <social-tag name="book" href="http://blog.corocn.jp"></social-tag>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="columns">
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Interested
              </p>
            </header>
            <div class="card-content">
              <div class="content">
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
          </div>
        </div>
      </div>

      <div class="columns">
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Carrer
              </p>
            </header>
            <div class="card-content">
              <div class="content">
                <ul>
                  <li>Misoca Inc. / Web Application Developer / 2017 - now</li>
                  <li>Arc co.,ltd. / Web Application Developer / 2015 - 2017</li>
                  <li>Denso Corporation. / Testing Enginner / 2013 - 2015</li>
                  <li>Nagoya Institute of Technology. / Department of Scientific and Engineering Simulation. / 2011 - 2013</li>
                  <li>Nagoya Institute of Technology. / Computer Science. / 2007 - 2011</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  import MyIcon from '~/components/MyIcon.vue'
  import SocialTag from '~/components/SocialTag.vue'

  export default {
    components: {MyIcon, SocialTag}
  }
</script>

<style>
  h2 {
    margin-top: 10px;
  }

  li {
    margin-bottom: 3px;
  }

  section div.left-side {
    border-right: 10px solid white;
  }

  section:nth-child(3n+2) div.left-side {
    border-right-color: #85d6ff;
  }

  section:nth-child(3n+1) div.left-side {
    border-right-color: #ffe893;
  }

  section:nth-child(3n+0) div.left-side {
    border-right-color: #ff98be;
  }
</style>

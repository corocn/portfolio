<template lang="pug">
div
  section.hero.is-dark
    .hero-body
      .container.has-text-centered
        my-icon
        h1.title.is-1 corocn
        h2.title.is-4 Takahiro Tsuchiya

  section.section
    .container.has-text-centered
      h2.title Social Accounts
      div
        social-tag(name='twitter', href='https://twitter.com/corocn')
        social-tag(name='github', href='https://github.com/corocn')
        social-tag(name='facebook', href='https://www.facebook.com/takahiro.tsuchiya.1217')
        social-tag(name='book', href='http://blog.corocn.jp')

  section.section
    .container.has-text-centered
      h2.title.is-3 Personal Information
      div
        | インターネットではころちゃん・ころさんと呼ばれている。
        | 岐阜県出身・在住。情報系の大学で音声認識を選考し、
        | 大学院卒業後は大手自動車部品メーカーにてカーナビゲーションシステムの音声認識機能の開発に携わる。
        | その後、Web系SIerに転職、小規模Webシステムの開発でフロントエンド、バックエンド、インフラまで1人で担当していた。
        | 現在はクラウド請求書のWebサービスをしている。最近の興味は認可・認証周りの技術を触って遊んでいる。
  
  section.section
    .container.has-text-centered
      h2.title Interest
      .tags
        .tag.is-medium Web Application
        .tag.is-medium Authentication
        .tag.is-medium Speech Recognition

      .notification
        | ウェブアプリ全般、認可・認証、音声認識に興味があります。インターネットが好きです。

  section.section
    .container.has-text-centered
      h2.title Computer Skills

      .subcontainer
        h3.title.is-4 WEB BACKEND
        .tags
          .tag.is-medium Ruby
          .tag.is-medium Rails
          .tag.is-medium PHP
          .tag.is-medium CakePHP
          .tag.is-medium MySQL
          .tag.is-medium AWS

        .notification
          | Ruby + AWS, Heroku 2年、PHP + AWS, VPS 3年ほど。PHPはわりとレガシー、最近はRubyばかり。

      .subcontainer
        h3.title.is-4 WEB FRONTEND
        .tags
          .tag.is-medium React
          .tag.is-medium Redux
          .tag.is-medium Vue
          .tag.is-medium Vuex
          .tag.is-medium Nuxt 

        .notification
          | React、Vueそれぞれ1年程度。デザインスキルとセンスがない。

      .subcontainer
        h3.title.is-4 MACHINE LEARNING & VOICE UI
        .tags
          .tag.is-medium Speech Recognition
          .tag.is-medium Julius
          .tag.is-medium MMDAgent
          .tag.is-medium WFST

        .notification
          | 音声認識、特に認識エンジン周りがちょっと分かる。
          | 学生のときにJuliusという国産音声認識エンジンのメンテを手伝っていた。
          | MMDAgentという対話エージェントのiOS化の技術協力もやった。
          | 基本的に大学での研究とその延長。

  section.section
    .container.has-text-centered
      h2.title Employment History

      .subcontainer
        h3.title.is-4 2017 - now
        .notification
          | Misoca Inc. / Web application engineer 

      .subcontainer
        h3.title.is-4 2015 - 2017
        .notification
          | Arc co.,ltd. / Web application engineer 

      .subcontainer
        h3.title.is-4 2013 - 2015
        .notification
          | Denso Corporation. / Vehicle development, Testing enginner
           
  section.section
    .container.has-text-centered
      h2.title Education History

      .subcontainer
        h3.title.is-4 2011 - 2013
        .notification
          | Nagoya Institute of Technology / Department of Scientific and Engineering Simulation.

      .subcontainer
        h3.title.is-4 2007 - 2011
        .notification
          | Nagoya Institute of Technology / Computer Science

  section.section
    .container.has-text-centered
      h2.title Awards
      .subcontainer
        h3.title.is-4 2011
        .notification
          | Nagoya Institute of Technology Award

  section.section
    .container.has-text-centered
      h2.title Publications
      .subcontainer
        h3.title.is-4 2018
        .notification
          | "Auth0"でつくる！認証付きSPA at 
          a(href="https://techbookfest.org/event/tbf04")
            | TechBookFest4

          div
            a(href="https://techbookfest.org/event/tbf04/circle/21030001")
              | Circle Page
            | , 
            a(href="http://blog.corocn.jp/entry/2018/04/01/231815")
              | Blog Post
          
  section.section
    .container.has-text-centered
      h2.title Contact
      div
        social-tag(name='twitter', href='https://twitter.com/corocn')
        social-tag(name='facebook', href='https://www.facebook.com/takahiro.tsuchiya.1217')
        social-tag(name='envelope', href='mailto:crsk.plmzh@gmail.com')

</template>

<script>
  import MyIcon from '~/components/MyIcon.vue'
  import SocialTag from '~/components/SocialTag.vue'

  export default {
    components: {MyIcon, SocialTag}
  }
</script>

<style>
.container {
  max-width: 480px;
  text-align: center;
}

.subcontainer {
  margin-top: 30px;
}

.notification {
  background-color: white;
}

.is-dark {
  background-color: #17256f;
}

.tags {
  display: flex;
  justify-content: center;
}
</style>

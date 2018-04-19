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
      .notification
        | インターネットではころちゃん・ころさんと呼ばれている。
        | 岐阜県出身・在住。情報系の大学で音声認識を専攻し、
        | 大学院卒業後は大手自動車部品メーカーにてカーナビゲーションシステムの音声認識機能の開発に携わる。
        | その後、Web系SIerに転職、小規模Webシステムの開発でフロントエンド、バックエンド、インフラまで1人で担当していた。
        | 現在はクラウド請求書のWebサービスをしている。最近はモダンフロントエンドと認可・認証周りの技術を触って遊んでいる。
  
      .notification.en
        | I go by the name "Corochan" on the Internet. I was born and live in Gifu, Japan. 
        | At university, I studied computer science and majored in speech recognition.
        | After university, I was involved in developing a voice recognition system for a car navigation system at a major automobile parts maker.
        | After that position, I developed infrastructure, front-end, and back-end for small-scale web applications at a systems integration company.
        | After that university, involved in developing a voice recognition system on a car navigation at a major automobile parts maker.
        | Now, I am developing a cloud invoicing service.
        | Outside of work, I’ve been developing skills with modern front-end and authentication methods.

  section.section
    .container.has-text-centered
      h2.title Interest
      .tags
        .tag.is-medium Web Application
        .tag.is-medium Authentication
        .tag.is-medium Speech Recognition

      .notification
        | ウェブアプリ全般、認可・認証、音声認識に興味があります。インターネットが好きです。

      .notification.en
        | I love Internet.

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
          | Ruby + AWS, Heroku about 2 years, PHP + AWS, VPS about 3 years. My PHP skill is becoming rusty. Recently, I became a Rubyist.


      .subcontainer
        h3.title.is-4 WEB FRONTEND
        .tags
          .tag.is-medium React
          .tag.is-medium Redux
          .tag.is-medium Vue
          .tag.is-medium Vuex
          .tag.is-medium Nuxt 

        .notification
          | React and Vue about 1 year for each. I have little to no design skill.

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

        .notification.en
          | I have a little understanding about speech recognition and recognition engines. 
          | As a student, I helped maintain Julius (high-performance, small-footprint large vocabulary continuous speech recognition engine.).
          | Also, I was technical support in porting MMDAgent, which is a dialogue agent on Android, to an iOS application.
          | Basically, it was my study at university, and continues to be my interest.

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
          | "Auth0"でつくる！認証付きSPA (Auth0 fan-book, which is an integration guide for Auth0, Nuxt and Rails)
          
          div
          | at 
          a(href="https://techbookfest.org/event/tbf04")
            | TechBookFest4
          div
            a(href="https://techbookfest.org/event/tbf04/circle/21030001")
              | Circle Page
            | , 
            a(href="http://blog.corocn.jp/entry/2018/04/01/231815")
              | Blog Post

        .notification
          

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

.hero.is-dark {
  background-color: #17256f;
}

.tags {
  display: flex;
  justify-content: center;
}
</style>

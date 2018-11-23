<template>
  <div class="profile">
    <section id="about">
      <md-card>
        <md-card-header>
          <div class="md-title">About me</div>
          <div class="md-subhead">私について</div>
        </md-card-header>
        <md-card-content>
          <p><b>ソフトウェアエンジニア</b></p>
          <p><b>所属</b>: 東京大学大学院 学際情報学府 M2</p>
          <p><b>専門</b>: Human Computer Interaction, IoT, Blockchain</p>
          <p><b>血液型</b>: AB</p>
          <p>
            怪しいものを作りがちな無職<br />
            最近はブロックチェーンを使ったアプリを作っています。
          </p>
        </md-card-content>
      </md-card>
    </section>

    <section id="skills">
      <md-card>
        <md-card-header>
          <div class="md-title">Skills</div>
          <div class="md-subhead">技術</div>
        </md-card-header>
        <md-card-content>
          <p>主に Web アプリケーションを作っています。</p>
          <div class="subsection">
            <p><b>最近使っているもの</b></p>
            <md-chip>Python</md-chip>
            <md-chip>Django</md-chip>
            <md-chip>JavaScript</md-chip>
            <md-chip>Vue.js</md-chip>
            <md-chip>Nuxt.js</md-chip>
            <md-chip>Vuex</md-chip>
            <md-chip>Ionic</md-chip>
            <md-chip>Solidity</md-chip>
            <md-chip>Netlify</md-chip>
            <md-chip>Heroku</md-chip>
            <md-chip>GCP</md-chip>
          </div>
          <div class="subsection">
            <p><b>資格</b></p>
            <ul>
              <li>応用情報技術者 (情報処理推進機構 IPA)</li>
            </ul>
          </div>
        </md-card-content>
      </md-card>
    </section>

    <section id="products">
      <md-card>
        <md-card-header>
          <div class="md-title">Products</div>
          <div class="md-subhead">今公開しているサービス</div>
        </md-card-header>
        <md-card-content>
          <ul>
            <li>
              <b>スパランドットコム</b><br />
              <a href="https://srandom.com/" target="_blank" rel="noopener"
                >https://srandom.com/</a
              ><br />
              Twitter:
              <a
                href="https://twitter.com/srandomcom"
                target="_blank"
                rel="noopener"
                >@srandomcom</a
              ><br />
              ポップンミュージックのスパラン愛好家のためのクリア状況管理サイト<br />
              <md-chip>Python</md-chip>
              <md-chip>Django</md-chip>
            </li>
            <li>
              <b>匣</b><br />
              <a
                href="https://hako-chat.herokuapp.com/"
                target="_blank"
                rel="noopener"
                >https://hako-chat.herokuapp.com/</a
              ><br />
              アカウント無しですぐに使える匿名プライベートチャットサービス<br />
              <md-chip>Python</md-chip>
              <md-chip>Django</md-chip>
              <md-chip>Heroku</md-chip>
            </li>
            <li style="margin-bottom: 30px">
              <b>Web3 Online Tools</b><br />
              <a
                href="https://web3-tools.netlify.com/"
                target="_blank"
                rel="noopener"
                >https://web3-tools.netlify.com/</a
              ><br />
              Ethereum アプリケーション開発者のためのオンラインツール<br />
              <md-chip>Vue.js</md-chip>
              <md-chip>Web3.js</md-chip>
              <md-chip>Netlify</md-chip>
            </li>
            <li style="margin-bottom: 30px">
              <b>ドミニオン計算機</b><br />
              <a
                href="https://dominion-calc.netlify.com/"
                target="_blank"
                rel="noopener"
                >https://dominion-calc.netlify.com/</a
              ><br />
              ドミニオンの勝利点を計算するプログレッシブウェブアプリ<br />
              <md-chip>Vue.js</md-chip>
              <md-chip>Nuxt.js</md-chip>
              <md-chip>Vuex</md-chip>
              <md-chip>PWA</md-chip>
              <md-chip>Netlify</md-chip>
            </li>
          </ul>
          <p>その他ここに載せられないような怪しいもの多数</p>
        </md-card-content>
      </md-card>
    </section>

    <section id="work-experience">
      <md-card>
        <md-card-header>
          <div class="md-title">Work Experience</div>
          <div class="md-subhead">これまでにお世話になったところ</div>
        </md-card-header>
        <md-card-content>
          <ul>
            <li>
              2018/06:<br />
              <b>株式会社メルカリ / Mercari, Inc.</b><br />
              ソフトウェアエンジニア (インターンシップ)
            </li>
            <li>
              2017/12:<br />
              <b>任天堂株式会社 / Nintendo Co., Ltd.</b><br />
              ネットワーク開発コース (インターンシップ)
            </li>
            <li>
              2017/10:<br />
              <b>株式会社サイバーエージェント / CyberAgent, Inc.</b><br />
              サーバーサイドエンジニア (インターンシップ)
            </li>
            <li>
              2017/08:<br />
              <b>株式会社コロプラ / COLOPL, Inc.</b><br />
              サーバーサイドエンジニア (インターンシップ)
            </li>
          </ul>
        </md-card-content>
      </md-card>
    </section>

    <section id="hobby">
      <md-card>
        <md-card-header>
          <div class="md-title">Hobby</div>
          <div class="md-subhead">好きなこと</div>
        </md-card-header>
        <md-card-content>
          音ゲー(ポップン、ビートマニア)とかCSゲーム(主にアクションとRPG)をやります。<br />
          近年ハマったのはメタルギアソリッドシリーズと軌跡シリーズです。
        </md-card-content>
      </md-card>
    </section>

    <section id="links">
      <md-card>
        <md-card-header>
          <div class="md-title">Links</div>
          <div class="md-subhead">お気軽にフォローしてください</div>
        </md-card-header>
        <md-card-content>
          <ul>
            <li>
              <b>Blog</b><br />
              <a href="https://blog.sapuri.io" target="_blank" rel="noopener"
                >https://blog.sapuri.io</a
              >
            </li>
            <li>
              <b>Twitter</b><br />
              <a
                href="https://twitter.com/sapuri_tappuri"
                target="_blank"
                rel="noopener"
                >https://twitter.com/sapuri_tappuri</a
              >
            </li>
            <li>
              <b>Mastodon</b><br />
              <a href="https://mstdn.jp/@sapuri" target="_blank" rel="noopener"
                >https://mstdn.jp/@sapuri</a
              >
            </li>
            <li>
              <b>GitHub</b><br />
              <a href="https://github.com/sapuri" target="_blank" rel="noopener"
                >https://github.com/sapuri</a
              >
            </li>
            <li>
              <b>Qiita</b><br />
              <a href="https://qiita.com/sapuri" target="_blank" rel="noopener"
                >https://qiita.com/sapuri</a
              >
            </li>
          </ul>
        </md-card-content>
      </md-card>
    </section>
  </div>
</template>

<script>
import Vue from "vue";
import { MdCard, MdChips } from "vue-material/dist/components";

Vue.use(MdCard);
Vue.use(MdChips);

export default {
  name: "Profile",
  props: {
    title: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
ul
  list-style-type none
  padding 0

li
  margin 0 10px

a
  font-weight bold

ul.list-inline > li
  display inline-block

section
  padding 20px

.subsection:not(:last-child)
  margin-bottom 30px

li:not(:last-child)
  margin-bottom 30px
</style>

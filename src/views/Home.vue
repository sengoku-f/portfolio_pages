<template>
  <div class="container">
    <img id="avatar" alt="avatar" src="./../assets/images/icon.jpg" />
    <h1>Donxj</h1>
    <h2>👨‍🎨 👨‍💻 🙋‍♂️</h2>

    <p>UI 设计师</p>
    <!-- <p>
      * creator of
      <a href="https://dowww.spencerwoo.com/">Dev on Windows with WSL</a>,
      <a href="https://api.spencerwoo.com/substats">Substats</a>, and
      <a href="https://bithesis.spencerwoo.com">BIThesis</a>
    </p> -->

    <hr id="top-hr" />
    <h3>🎉 Where to find me:</h3>
    <div id="card-container">
      <Card
        msg="画廊 ART"
        backgroundColor="#ca2c2a"
        description="✏️ 我的艺术画廊"
        textColor="#FFFFFF"
        icon="art.svg"
        link="https://art.donxj.com"
      />
      <Card
        msg="博客 Blog"
        backgroundColor="#0083c0"
        description="📒 从头开始（咕咕咕）"
        textColor="#FFFFFF"
        icon="netlify.png"
        link="https://blog.donxj.com"
      />
      <Card
        msg="GitHub"
        backgroundColor="#24292E"
        description="📦 我的仓库"
        textColor="#FFFFFF"
        icon="github.png"
        link="https://github.com/"
      />
    </div>

    <!-- <div id="others">
      <hr />
      <h3>你还可以在这些地方偶尔发现一只我：</h3>
      <div class="social-media">
        <div class="social-media-card">
          <img class="media-icon" src="@/assets/images/weibo.png" alt="weibo" />
          <span>
            Weibo:
            <a href="https://weibo.com/spencerwoo">@SpencerWoo</a>
          </span>
        </div>
        <div class="social-media-card">
          <img class="media-icon" src="@/assets/images/twitter.png" alt="twitter" />
          <span>
            Twitter:
            <a href="https://twitter.com/realSpencerWoo">@realSpencerWoo</a>
          </span>
        </div>
        <div class="social-media-card">
          <img class="media-icon" src="@/assets/images/airplane.png" alt="telegram" />
          <span>
            Telegram Channel:
            <a href="https://t.me/realSpencerWoo">@realSpencerWoo</a>
          </span>
        </div>
      </div>

      <p>🧨 感谢大哥的关注！给您拜年了！干杯 🍻</p>

      <hr />

      <h3>Want to use this template on your website?</h3>
      <p>
        想要用我的模板搭建自己的 Portfolio？还请加上设计来源，比如：
      </p>
      <a id="copyright" href="https://github.com/spencerwooo/portfolio">
        <img
          src="https://img.shields.io/badge/Designed%20by-github.com%2Fspencerwooo-black?logo=github&style=for-the-badge&labelColor=24292e"
          alt="copyright"
        />
      </a>
    </div> -->
  </div>
</template>

<script>
import Card from '@/components/Card.vue'

export default {
  components: {
    Card,
  },
}
</script>

<style lang="css" scoped>
#copyright:hover {
  border: none;
}
</style>

<template>
  <div class="container">
    <h1>👓</h1>
    <h1>About</h1>
    <p>Hi, I'm Donxj 👋</p>

    <hr id="top-hr" />
    <div class="article">
      <p>
        大家好，我是 Donxj，毕业于广州商学院艺术设计学院 视觉传达 专业，目前我的专业方向是 UI 设计与动画设计
        <!-- 我将于 2021 年初（淦，被迫 gap (⊙x⊙;)）前往英国
        <a href="https://www.gla.ac.uk/">UofG</a> 攻读
        <a href="https://www.gla.ac.uk/postgraduate/taught/computingsciencemsc/">MSc in Computing Science</a -->
        >。给大家鞠躬了。🙇
      </p>

      <h2>我的项目</h2>
      <p>
        我所做过的项目几乎都记录于
        <a href="https://blog.donxj.com/about/">Blog</a> 上面，欢迎大家浏览，笔芯 (✿◡‿◡)
      </p>

      <GitHubCard
        title="🥇 小鹏汽车数字化触控屏"
        link="https://blog.donxj.com/2020/07/12/小鹏汽车/"
        :info="dowwwInfo"
        :loading="loading"
      >
        <p>
          小鹏汽车数字化触控屏：通过在显示屏上操作，360看车外观、内饰，选配颜色、配置、性能。了解小鹏汽车的充电、使用性能。并在后台进行充一管理、数据收集、更新。与CRM系统对接，获取有用数据，并应用到互动设备。
        </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/2020/07/12/小鹏汽车/">小鹏汽车数字化触控屏</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 上汽荣威门店数字化软件"
        link="https://blog.donxj.com/2020/05/19/上汽荣威/"
        :info="substatsInfo"
        :loading="loading"
      >
        <p>
          使用数字化软件优化客户在展厅中的每一触点，打造深度互动、有参与感的展厅体验之旅，使客户体验及购买意向持续发酵并促成下订。
          </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/2020/05/19/上汽荣威/">上汽荣威门店数字化软件</a>
        </p>
      </GitHubCard>

      <!-- <GitHubCard
        title="🥇 The Fully Anonymous Teaching Evaluation System"
        link="https://github.com/SecureCats/Evaluation_BackEnd"
        :info="fatesInfo"
        :loading="loading"
      >
        <p>
          Secure Cats 团队作品：基于零知识证明和 CL 签名的匿名课程评价系统。这一评教系统参加了「2019
          年大学生信息安全竞赛 —— 作品赛」，荣获国家级二等奖。推荐阅读：
          <a href="https://medium.com/spencerweekly/recap-on-fates-d9d17a6a7827"
            >什么时候「匿名」才是合理的？| 匿名评教平台复盘</a
          >
        </p>
      </GitHubCard> -->

      <!-- <GitHubCard
        title="🎫 少数派作者名片 | 一个 JSBox 小组件"
        link="https://github.com/spencerwooo/jsbox-sspai-namecard"
        :info="sspaiCardInfo"
        :loading="loading"
      >
        <p>
          适合新版本少数派的作者名片，搭建在 JSBox 上。推荐阅读：
          <a href="https://sspai.com/post/55562">新版少数派网站的作者成就墙好好看啊，于是我用它写了一个 JSBox 小插件</a>
        </p>
      </GitHubCard> -->

      <!-- <GitHubCard
        title="🎃 我的 dotfiles"
        link="https://github.com/spencerwooo/dotfiles"
        :info="dotfilesInfo"
        :loading="loading"
      >
        <p>我的各种配置清单。从终端到 Vim，从 macOS 到 Windows，应有尽有。</p>
      </GitHubCard> -->

      <h2>我的设备</h2>
      <ul>
        <!-- <li>
          主力台式机：Intel® NUC Kit NUC8I5BEK
          <ul>
            <li>
              配置清单：
              <ul>
                <li>CPU: Intel® Core™ i5-8295U</li>
                <li>RAM: ADATA 16GB (8GB×2) DDR4 2666MHz</li>
                <li>M.2 SSD: SAMSUNG PM981 M.2 NVME 256GB</li>
              </ul>
            </li>
            <li>
              介绍：
              <a href="https://sspai.com/post/54788">性能强劲的「迷你台式机」，Intel NUC 一周使用体验</a>
            </li>
          </ul>
        </li> -->
        <!-- <li>
          ThinkPad X1 Carbon 7th Gen：<a href="https://sspai.com/post/45742"
            >迁移到 Windows 后，我如何找回熟悉的 macOS 体验</a
          >
        </li> -->
        <li>15.6" MacBook Pro</li>
        <!-- <li>
          Sony 1000XM3： <a href="https://sspai.com/post/47794">降噪、音质、续航一网打尽：索尼 1000XM3 降噪耳机体验</a>
        </li> -->
        <li>iPhone 8 Plus RED</li>
        <li>iPad Pro 11" 2020</li>
        <li>AirPods Pro</li>
      </ul>

      <h2>联系我</h2>
      <!-- <p>
        欢迎大家直接订阅我的发布，详情请参考：
        <router-link to="/subscribe">Spencer Woo - Subscribe</router-link>
      </p> -->
      <p>我的联系方式：</p>
      <ul>
        <li>
          📫 邮箱：
          <a href="mailto:i.donxj@gmail.com">i.donxj@gmail.com</a>
        </li>
        <li>📍 Haizhu, Guangzhou, China</li>
      </ul>
    </div>
  </div>
</template>

<script>
import GitHubCard from '@/components/GitHubCard.vue'

export default {
  components: {
    GitHubCard,
  },
  data() {
    return {
      loading: true,
      dowwwInfo: {
        stargazers_count: 0,
        forks_count: 0,
      },
      substatsInfo: {
        stargazers_count: 0,
        forks_count: 0,
      },
      fatesInfo: {
        stargazers_count: 0,
        forks_count: 0,
      },
      sspaiCardInfo: {
        stargazers_count: 0,
        forks_count: 0,
      },
      dotfilesInfo: {
        stargazers_count: 0,
        forks_count: 0,
      },
    }
  },
  mounted() {
    const githubApiUrl = 'https://api.github.com/repos'

    const dowwwAxios = this.axios.get(`${githubApiUrl}/spencerwooo/dowww`)
    const substatsAxios = this.axios.get(`${githubApiUrl}/spencerwooo/Substats`)
    const fatesAxios = this.axios.get(`${githubApiUrl}/SecureCats/Evaluation_BackEnd`)
    const sspaiCardAxios = this.axios.get(`${githubApiUrl}/spencerwooo/jsbox-sspai-namecard`)
    const dotfilesAxios = this.axios.get(`${githubApiUrl}/spencerwooo/dotfiles`)

    this.axios
      .all([dowwwAxios, substatsAxios, fatesAxios, sspaiCardAxios, dotfilesAxios])
      .then(
        this.axios.spread((...resp) => {
          this.loading = false
          this.dowwwInfo = resp[0].data
          this.substatsInfo = resp[1].data
          this.fatesInfo = resp[2].data
          this.sspaiCardInfo = resp[3].data
          this.dotfilesInfo = resp[4].data
        }),
      )
      .catch(err => {
        this.loading = false
        // eslint-disable-next-line no-console
        console.error(err)
      })
  },
}
</script>

<style lang="css" scoped>
h2 {
  font-weight: 700;
  font-size: 20px;
  padding: 10px 0;
}

ul {
  padding-left: 15px;
  line-height: 30px;
  margin: 0;
}

p {
  line-height: 30px;
}
</style>

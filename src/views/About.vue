<template>
  <div class="container">
    <h1>👓</h1>
    <h1>About</h1>
    <p>Hi, I'm Donxj 👋</p>

    <hr id="top-hr" />
    <div class="article">
      <p>
        大家好，我是董行健，毕业于广州商学院艺术设计学院『视觉传达』专业，目前我的专业方向是 UI 设计与动画设计。同时写写 Python 代码工具。
        <!-- 我将于 2021 年初（淦，被迫 gap (⊙x⊙;)）前往英国
        <a href="https://www.gla.ac.uk/">UofG</a> 攻读
        <a href="https://www.gla.ac.uk/postgraduate/taught/computingsciencemsc/">MSc in Computing Science</a> -->
        给大家鞠躬了。🙇
      </p>

      <h2>我的项目</h2>
      <p>
        我所做过的项目几乎都记录于
        <a href="https://blog.donxj.com/about/">我的 Blog</a> 上面，欢迎大家浏览，笔芯 (✿◡‿◡)
      </p>

      <GitHubCard
        title="📽 REALURL API"
        link="https://api.donxj.com/geturl"
        :info="dotfilesInfo"
        :loading="loading"
      >
        <p>一个用于获取国内主流直播真实流媒体链接。由 Flask 支持，托管在 <a href="https://www.aliyun.com/product/fc">Aliyun Function Compute</a> 上。并且后端提供了 POST 请求方式方便程序调用。</p>
        <p>
          HOME：<a href="https://api.donxj.com/mktext">REALURL</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 MKTEXT API"
        link="https://api.donxj.com/mktext"
        :info="dowwwInfo"
        :loading="loading"
      >
        <p>
          因为『<a href="https://blog.donxj.com/腾讯公益-H5-微信小程序/">重返秦俑本色</a>』中有用户输入名字然后生成印章海报的功能需求，所以开发了个 <a href="https://api.donxj.com/mktext">API</a>。主要使用 Python 进行实现的，使用 Python 的 Python Imaging Library 库进行文字图片处理，用 Flask 搭建 Web 应用框架，最后部署到阿里云服务器进行使用。期间还需要申请域名，申请域名 ssl 证书进行 https 加密。推荐阅读：
          <a href="https://blog.donxj.com/腾讯公益-H5-微信小程序/#个人开发的-API">从文字生成印章图片</a>
        </p>
        <p>
          API 项目主页：<a href="https://api.donxj.com/mktext">HOME | MKTEXT API</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 腾讯公益 H5 + 微信小程序"
        link="https://blog.donxj.com/腾讯公益-H5-微信小程序/"
        :info="fatesInfo"
        :loading="loading"
      >
        <p>
          2020我是创益人-海洋天堂计划，『漫游星星的秘密』H5、『暖暖骑士团』H5和『重返秦俑本色』微信小程序
        </p>
        <p>
          『
        <a href="https://gongyi3test.tencent-cloud.net/mystar20/">
          漫游星星的秘密
        </a>
        』H5，我们希望唤醒更多公众，关注并参与到关怀自闭症儿童的公益事业中来。让公众进一步从正面、积极的角度了解自闭症儿童，感受Ta们的不一样。进一步传达壹基金海洋天堂计划陪伴、温暖，尽我所能，人人公益的愿景
        </p>
        <p>
          『
        <a href="https://gongyi3test.tencent-cloud.net/nnqst20/">
          暖暖骑士团
        </a>
        』H5，经过 “免费午餐小善大爱”项目，过去7年的不断努力，贫困儿童的营养问题虽已得到一定改善，但我们希望这份爱与关怀能继续传递
        </p>
        <p>
          『
        <a href="https://cdn.donxj.com/blog/腾讯公益-H5-微信小程序/重返秦俑本色/小程序二维码.jpg_auto">
          重返秦俑本色
        </a>
        』微信小程序通过强交互的小程序（小游戏），让更多人特别是年轻人，愿意主动了解和传播秦兵马俑的文化历史，呈现秦文化内涵，并能够引发大众关注。
        </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/腾讯公益-H5-微信小程序/">2020我是创益人-海洋天堂计划</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 小鹏汽车数字化触控屏（第二期）"
        link="https://blog.donxj.com/小鹏汽车/"
        :info="dowwwInfo"
        :loading="loading"
      >
        <p>
          小鹏汽车数字化触控屏：通过在显示屏上操作，360看车外观、内饰，选配颜色、配置、性能。了解小鹏汽车的充电、使用性能。并在后台进行充一管理、数据收集、更新。与CRM系统对接，获取有用数据，并应用到互动设备。
        </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/小鹏汽车/">小鹏汽车数字化触控屏</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 上汽荣威门店数字化软件"
        link="https://blog.donxj.com/上汽荣威/"
        :info="substatsInfo"
        :loading="loading"
      >
        <p>
          使用数字化软件优化客户在展厅中的每一触点，打造深度互动、有参与感的展厅体验之旅，使客户体验及购买意向持续发酵并促成下订。
          </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/上汽荣威/">上汽荣威门店数字化软件</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 解放碑商圈 3D 商圈客流洞察"
        link="https://blog.donxj.com/解放碑商圈-3D-数据可视化大屏/"
        :info="substatsInfo"
        :loading="loading"
      >
        <p>
          以3D可视化数据大屏呈现商圈客流洞察，用户通过数据大屏可以直观了解商圈当前客流情况，商圈内客群画像。通过该数据大屏可助力商圈管理者实时了解商圈客流情况，及时应对客流异常。
          </p>
        <p>
          详情信息：<a href="https://blog.donxj.com/解放碑商圈-3D-数据可视化大屏/">解放碑商圈 3D 商圈客流洞察</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🥇 长城 WEY来 微信小程序"
        link="https://cdn.donxj.com/blog/长城-WEY来微信小程序/组合.jpg_auto"
        :info="substatsInfo"
        :loading="loading"
      >
        <p>
          2019长城国际车展，使用微信小程序优化客户在展厅中的互动体验，相比于 H5，小程序可以实现讯息无中断，搭载更多功能。
          </p>
        <p>
          详情信息：<a href="https://cdn.donxj.com/blog/长城-WEY来微信小程序/组合.jpg_auto">长城 WEY来 微信小程序</a>
        </p>
      </GitHubCard>

      <GitHubCard
        title="🛠 实用工具合集 | Windows Automator"
        link="https://github.com/sengoku-f/Win-Automator/"
        :info="sspaiCardInfo"
        :loading="loading"
      >
        <p>
          为提供自身的工作效率而写一些自用的小工具。推荐阅读：
          <a href="https://blog.donxj.com/Windows-工具合集/">解放生产力，自动化的工具如何提高我的工作效率</a>
        </p>
      </GitHubCard>

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
        <li>iPhone 12 Pro Max</li>
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
        <li>
          🌟 微信：xchacha20 
          <a href="https://cdn.donxj.com/blog/img/wechat_qr_code.jpg_auto">[点击查看二维码]</a>
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

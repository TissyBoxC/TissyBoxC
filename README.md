<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/brand-avatar.png" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/brand-avatar.png" />
  <img src="./assets/brand-avatar.png" alt="如此萌屋" width="210" />
</picture>

<h1>如此萌屋 · 芽系列</h1>

**把复杂的工程藏在可爱的外表后面**

`AI 早教陪伴` · `儿童隐私优先` · `模块化硬件` · `多端协同`

[![芽系列主站](https://img.shields.io/badge/%E8%8A%BD%E7%B3%BB%E5%88%97-%E5%88%9D%E8%8A%BD-ff8fb8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TissyBoxC/sprout-platform)
[![孩子第一](https://img.shields.io/badge/%E5%84%BF%E7%AB%A5%E9%9A%90%E7%A7%81-%E4%BC%98%E5%85%88-ffb9d1?style=for-the-badge&logo=checkmarx&logoColor=white)](#-设计原则)
[![技术栈](https://img.shields.io/badge/Go%20%C2%B7%20Flutter%20%C2%B7%20Vue%203%20%C2%B7%20ESP32--S3-ffd6e7?style=for-the-badge&labelColor=fff5f8)](#-技术栈)

<sub>可爱是外壳，可靠、安全、可维护才是内核。</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffd6e7,45:ffb6c1,100:ff8fb8&height=100&section=header&text=%E5%A6%82%E6%AD%A4%E8%90%8C%E5%B1%8B%20%C2%B7%20%E8%8A%BD%E7%B3%BB%E5%88%97&fontColor=6b4f5a&fontSize=28&fontAlignY=38" alt="如此萌屋 · 芽系列" />

## 关于我

我是 **TissyBoxC**，正在把“AI 早教陪伴机器人”做成一套真正能被阅读、被维护、被逐步扩展的工程系统。

“如此萌屋”不是一个只卖外形的玩具概念。我希望孩子面对的是有温度、有边界的伙伴，家长拿到的是清楚透明的控制权，开发者看到的是模块边界稳定、安全默认值可靠、可以持续演进的产品底座。

> 所有能力默认关闭或采用最保守配置。社交、摄像头、麦克风上传和数据采集必须由监护人主动开启。

## 正在建造

<table>
<tr>
<td width="50%" valign="top">

### [sprout-platform](https://github.com/TissyBoxC/sprout-platform)

**平台与体验中枢**

Flutter 家长端、Vue 3 管理端、Go 业务服务、实时语音网关和共享契约都收纳在这里。

`Go` `Flutter` `Vue 3` `PostgreSQL` `Redis`

</td>
<td width="50%" valign="top">

### [sprout-firmware](https://github.com/TissyBoxC/sprout-firmware)

**设备固件与能力组合**

ESP32-S3 N16R8 固件。音频、显示、摄像头、动作等能力都按模块拆开，可以在构建时按需增删。

`ESP-IDF` `PlatformIO` `FreeRTOS`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [sprout-sub2api-fork](https://github.com/TissyBoxC/sprout-sub2api-fork)

**儿童场景 AI 模型网关**

负责模型路由、账号池、配额、审计和儿童安全策略。设备端永远拿不到上游模型密钥。

`Go` `OpenAI Compatible` `Content Safety` `Observability`

</td>
</tr>
</table>

## 设计原则

<div align="center">

| 先保护 | 先默认安全 | 先模块化 | 先讲清楚 |
| :---: | :---: | :---: | :---: |
| 儿童隐私、心理安全、人身安全优先 | 能力默认关闭，由监护人主动开启 | 一个功能一个模块，可独立增删验证 | 用户看到的每个字都要有下一步 |

</div>

## 技术栈

<div align="center">

![Go](https://img.shields.io/badge/Go-1.27-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-Dart-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-ESP32--S3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

## 我在做什么

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TissyBoxC&theme=github_dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TissyBoxC&theme=github" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TissyBoxC&theme=github" alt="TissyBoxC 的 GitHub 动态" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=TissyBoxC&show_icons=true&hide_border=true&hide_title=true&bg_color=00000000&text_color=ffb6c1&icon_color=ff8fb8&title_color=ff8fb8" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=TissyBoxC&show_icons=true&hide_border=true&hide_title=true&bg_color=00000000&text_color=6b4f5a&icon_color=ff8fb8&title_color=d95784" />
  <img src="https://github-readme-stats.vercel.app/api?username=TissyBoxC&show_icons=true&hide_border=true&hide_title=true&bg_color=00000000&text_color=6b4f5a&icon_color=ff8fb8&title_color=d95784" alt="TissyBoxC 的 GitHub 统计" height="170" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=TissyBoxC&layout=compact&hide_border=true&bg_color=00000000&text_color=ffb6c1&title_color=ff8fb8" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=TissyBoxC&layout=compact&hide_border=true&bg_color=00000000&text_color=6b4f5a&title_color=d95784" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TissyBoxC&layout=compact&hide_border=true&bg_color=00000000&text_color=6b4f5a&title_color=d95784" alt="主要编程语言" height="170" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=TissyBoxC&hide_border=true&background=00000000&ring=ff8fb8&fire=ffb6c1&currStreakLabel=ffb6c1&sideLabels=ffb6c1&dates=ffb6c1" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=TissyBoxC&hide_border=true&background=00000000&ring=ff8fb8&fire=d95784&currStreakLabel=d95784&sideLabels=6b4f5a&dates=9b7484" />
  <img src="https://streak-stats.demolab.com?user=TissyBoxC&hide_border=true&background=00000000&ring=ff8fb8&fire=d95784&currStreakLabel=d95784&sideLabels=6b4f5a&dates=9b7484" alt="连续提交统计" width="100%" />
</picture>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://ghchart.rshah.org/ff8fb8/TissyBoxC" />
  <source media="(prefers-color-scheme: light)" srcset="https://ghchart.rshah.org/ff8fb8/TissyBoxC" />
  <img src="https://ghchart.rshah.org/ff8fb8/TissyBoxC" alt="GitHub 贡献热力图" width="100%" />
</picture>

</div>

## 一点点可爱，很多很多认真

<div align="center">

`让孩子放心地说话` &nbsp;·&nbsp; `让家长清楚地掌控` &nbsp;·&nbsp; `让开发者安心地维护`

<br />

![Profile Views](https://komarev.com/ghpvc/?username=TissyBoxC&color=ff8fb8&style=for-the-badge&label=%E8%AE%BF%E9%97%AE%E9%87%8F)

<sub>愿每一次技术选择，都对得起孩子的信任。</sub>

</div>

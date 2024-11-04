---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "HUHST CAS"
  text: "湖南人文 CAS 协会"
  tagline: "湖南人文科技学院 ACM 集训队"
  image:
    src: /icpc.png
    alt: icpc
  actions:
    - theme: brand
      text: ACM，启动！
      link: /basic/
    - theme: alt
      text: 关于我们
      link: /about/introduction

features:
  - icon: 😎
    title: 我们是？
    details: 我们是湖南人文科技学院 CAS 协会以及 ACM 集训队，为同学们提供算法交流、训练平台、软件开发交流等。多次代表学校出征程序设计竞赛（ICPC/CCPC、湖南程序设计省赛、蓝桥杯、天梯赛等）。
  - icon: 🚀
    title: 我们氛围超棒
    details: 承担队内管理职责的均为学长学姐，氛围相当自由。我们鼓励队员们自由交流，分享自己的学习经验，共同进步。
  - icon: 🎉
    title: 欢迎加入我们
    details: 我们随时欢迎感兴趣的同学加入我们！QQ群：CAS协会对外交流群 166165751 。欢迎大家加入我们，一起学习，一起进步！
---

<!-- From `https://github.com/vuejs/vitepress/blob/main/docs/index.md` -->

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(0deg, #4B82C3 20%, #FFD51E 55%, #B12B1A 80%);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe50 50%, #47caff50 50%);
  --vp-home-hero-image-filter: blur(44px);
}

:root.dark {
  --vp-home-hero-image-background-image: none;
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>

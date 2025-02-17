---
title: 远程兼职一年后
datePublishedAt: 2023-07-09T16:00:00.000Z
summary: 不知不觉，我已经工作一年了。回想起来，有些东西是值得被记录下来的。
slug: work-one-year
disableAISummary: true
cover: ""
tags:
  - Review
---

## 故事的开始

去年过年的时候，我接到了一个外包，基本上就是爬数据，写后端，写网页。当时我还只会写一点安卓，不会写前端，后端的话也只会写一点 Python 或者 Java。好在时间并不紧张，我照着 [深入浅出现代 Web 编程][] 边学边写，完成了任务。是的，我一开始用的是 React，用 [mui][] 作为组件库。

## 开始入门

在去年三月份的时候，我偶然间看到 [Anthony Fu][] 在 b 站的 [第一次直播][]。直播里，我第一次了解到原子化 CSS 以及 Vue 和 Vite 生态中的各种插件。直播后，我沿着他的 [Vue 起手模板][vitesse] 和 [博客][antfu.me] 中涉及到的技术去学习前端。也没个特定顺序，就只是学些自己感兴趣的东西。

## 接触开源

到了六月份，我接触到 [memos][] 这个开源项目，并修复了我处理的 [第一个 issue][]。后面我日常修复一些 bug，实现一些小功能。在十月份我联系了作者，[Steven][] 人特别好，很欢迎大家去参与开源。他拉我进了组织，从他的代码中我学习到了很多。可惜的是，随着今年兼职和学校方面的事情变多，提交 PR 的次数也越来越少了。

## 找工作

受疫情影响，上半年的时候我一直在家里，就只是不断学习和做一些别的事情。等快到暑假，大概是在家待得太久了，家里人开始催我出去找个工作。最开始的时候是让一个认识的人推荐一个小公司的职位，不过工资太低，去干活啥基本啥都存不下来，而且后来也没招我。

去年 7 月 10 号中午，偶然在 V2EX 上看到 [祥岩][] 发的一个 [招聘帖][]。从技术栈和工作条件来看，这份工作很适合我，于是我直接加了微信。简历是放在我的个人网站上的，我就直接把链接发给他。

神奇的是，我们只是在微信上简单交流了一下，晚上他就发了 offer 给我，拉我进了 GitHub 组织和飞书。是的，没有技术面试，没有合同，我一度以为是骗子。因为我还看到他另外一篇很不靠谱的帖子，「[大家好，我开始了一项公开创业计划，目标是九个月获得五千万元投资][]」。（不出意外，这个计划失败了）

不过很快，这种疑虑就被我打消了，因为我开始了我的工作，写数据可视化工具的网页。同时，我做好了准备，只要一个月内没有发工资，我就跑路，这样也不会亏什么。

## 一些工作中的体验

1. 最初的时候，我很担心自己的能力不足以支持我完成任务，后来就不会了。
1. 我是完全远程兼职的，大约是每周工作五天，每天工作四个小时。
   不过我可以在任何时间工作，也不会有时间考核，很多时候完成任务所需要的时间都不足这个时长。
1. 工作内容完全不限于前端，可能去写爬虫了，可能去搞定自动部署了。
   大多数都是我乐于完成的任务，不会有需要在技术选择上妥协吃屎的地方。
1. 在学校有一笔稳定的收入真的很好，我每个月会有五千块钱。
   换了一台笔记本，给我妈买了一台手机，到现在也还存了接近五万块。
1. 通过不断学习，不断将新的技术应用到工作中，我感觉自己的能力在不断提升。

## 认识了很有意思的李书

在刚进入团队的时候，除了祥岩，就只有我和 [李书][] 了。李书是负责写后端的，他很怪，既很深的理解函数式编程和类型系统，又会在代码里坚持使用中文变量 和 var。他还懂得数学和心理学哲学方面的知识，自己的图书馆里有很多我不想看，也看不明白的书。在他的推荐下，我看完了阿德勒的两部曲，受益匪浅。

我们之间的一些共通特点将我们一起聚集到这个团队，所以我们很自然的成为了好朋友。即使我们不处在一个城市，这也不妨碍我们时常聊天几个小时。下面是李书当时离职发的小作文，我觉得应该很多人会觉得他很酷很好。

[img_v2_fcc096eb-f378-49ad-9b4d-9957819772eg.jpg](https://s2.loli.net/2023/08/07/jf7ZLmvXduq342F.jpg)

## 从 Vue.js 到 React

如你所见，在招聘的那个帖子里，关于前端框架的选择是 Vue.js。但是在几个项目之后，就换到了 React，主要有如下几点考虑。

- [volar][] 的体验不佳，经常需要 reload；相对比写 React 的 tsx 不需要安装额外的插件，也更加稳定。
  - volar 具体的体验可以看 [这条推](https://twitter.com/isukkaw/status/1688077064359079936)
- React 的生态更加好，比如 [radix-ui][] 和 [framer-motion][]。

基于同样的 DX 考虑，也把原本祥岩配置的一套 eslint 给换了，因为它严重影响保存代码时的性能。

所以，你可以感受到，大家的关系与其说是雇佣关系，不如说是伙伴，我们每个人都有提出自己的想法和决策的权利。

## 小插曲，认识 zeabur

远程兼职的生活，让我对于去公司 996 赚钱的想法越来越淡，我希望可以在毕业后继续这样的生活，但是现在我还没有解决经济问题。今年上半年一个偶然的机会，看到了 [zeabur][] 在招前端实习。我想，如果我能再找到这一份工作，就不需要再担心了。

就和这份工作一样，联系上微信发了简历之后，我和 zeabur 的两位创始人[沅霖][] 和 [宇航][] 在北京的一家咖啡馆见了面。聊了一会，并一起在咖啡馆写了会代码，就加入了。

zeabur 也是一个很酷的公司，团队里的人都很厉害。不过很可惜，加入后一周多，我因为需要投入更多时间推进自己的小论文，时间上实在是不够，就退出了。

## 现在的情况

和去年只有我，祥岩，李书三个人不同，现在我们 [团队][] 已经有了七个人，业务也在不断扩展。如果你对我们的工作感兴趣，可以查阅我们的 [Grow in Public][] 文档来了解更多。

研二的这个暑假，没有学校的事情需要处理，但是总共只有三周时间，第一周在家里，后面两周去了湖北。我算是体验了一点数字游民的感觉，带上电脑，可以去任何地方。睡觉睡到自然醒，随便出去找点吃的，无聊的时候刷刷 Twitter，看看视频，在任何时间写一点代码就好。

![IMG_20230805_134548.jpg](https://s2.loli.net/2023/08/05/VIr9hGaWwMD1BYm.jpg)

[深入浅出现代 Web 编程]: https://fullstackopen.com/zh
[mui]: https://mui.com
[Anthony Fu]: https://antfu.me
[第一次直播]: https://www.bilibili.com/video/BV1ia411b7jY
[vitesse]: https://github.com/antfu/vitesse
[antfu.me]: https://github.com/antfu/antfu.me
[memos]: https://github.com/usememos/memos
[第一个 issue]: https://github.com/usememos/memos/issues/90
[Steven]: https://github.com/boojack
[祥岩]: https://twitter.com/kxycigaret
[招聘帖]: https://www.v2ex.com/t/865194
[大家好，我开始了一项公开创业计划，目标是九个月获得五千万元投资]: https://www.v2ex.com/t/864079
[李书]: https://github.com/lsby
[volar]: https://volarjs.github.io
[radix-ui]: https://www.radix-ui.com
[framer-motion]: https://www.framer.com/motion
[zeabur]: https://zeabur.com/zh-CN
[沅霖]: https://twitter.com/yuaanlin
[宇航]: https://twitter.com/CoooolXyh
[团队]: https://github.com/planet-matrix
[Grow in Public]: https://datadata.feishu.cn/wiki/ZSrDw1ioji9vPIkfSrNcJBREnWd

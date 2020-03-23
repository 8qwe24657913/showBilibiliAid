# showBilibiliAid

在 bilibili 视频播放页显示视频 av 号

为什么需要这个脚本？

- [bilibili 将 av 号改为 bv 号](https://www.bilibili.com/blackboard/activity-BV-PC.html)，且视频播放页不再显示 av 号

- 许多之前的设施（如旧版客户端、第三方网站等）仍需要 av 号才能继续运行

- 纯数字的 av 号比数字和大小写字母混杂的 bv 号更容易记忆

  比如你在周刊排行榜（现在没法直接点击跳转了）里看到一个视频， [av82054919](https://www.bilibili.com/video/av82054919)，想要进去看一眼，你也许会扫一眼 av 号并输到地址栏，但如果你看到的是 [BV1XJ41157tQ](https://www.bilibili.com/video/BV1XJ41157tQ) 呢？想一次记住就没那么容易了吧？

当然，这个脚本随时可能因为 bilibili 对页面内容进行暗改或是干脆停止将 bv 号映射到 av 号而失效，用一天是一天（

PS：想要在由 vue 控制的地方额外插个元素进去还真是个技术活……


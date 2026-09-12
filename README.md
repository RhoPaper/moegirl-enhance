# 萌娘百科优化 - PaperFork

一个用于 [萌娘百科](https://zh.moegirl.org.cn/) 的 UserScript，专注于净化页面、去除广告，并为页面换上更好看的自定义背景。

> 本项目是 [萌娘百科优化](https://greasyfork.org/zh-CN/scripts/577883)（作者 [jianh-ai](https://greasyfork.org/zh-CN/users/1275918-jianh-ai)）的 Fork 版本，在原脚本基础上进行了调整与增强。原项目同样基于 MIT 协议开源，在此致谢。

## ✨ 功能

- **去除广告与追踪脚本**：拦截并移除 Google Analytics、Google Tag Manager、Google AdSense、DoubleClick 等脚本与全屏广告。
- **自动关闭广告**：自动点击页面中的广告关闭按钮，清理「推广 / 加载中」等推广块。
- **隐藏冗余元素**：隐藏 App 引导、通知条、悬浮卡片等干扰性组件。
- **自定义背景**：
  - 默认从随机图片 API 拉取背景。
  - 优先使用条目自带的角色立绘（commons 大图）作为专属背景。
  - 背景固定、铺满、居中。
- **毛玻璃卡片**：正文与侧栏卡片使用半透明 + 背景模糊效果，并适配系统/站点的暗色主题。

## 📦 安装

1. 安装用户脚本管理器：[Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/)。
2. 安装脚本：
   - 在本仓库中打开 [`萌娘百科优化-PaperFork-0.0.1.user.js`](./萌娘百科优化-PaperFork-0.0.1.user.js)，用户脚本管理器会自动提示安装；
   - 或将文件内容复制到管理器中新建脚本。
3. 打开 [萌娘百科](https://zh.moegirl.org.cn/) 即可生效。

## ⚙️ 配置

脚本顶部的 `BG_API` 常量用于配置随机背景图 API，可自行替换为其他图片接口：

```js
const BG_API = 'https://t.alcy.cc/moe';
```

## 📄 许可证

本项目基于 [MIT License](./LICENSE) 开源，与原项目一致。

## 🔗 相关链接

- 原项目（Greasy Fork）：<https://greasyfork.org/zh-CN/scripts/577883>
- 原项目作者：<https://greasyfork.org/zh-CN/users/1275918-jianh-ai>

## ⚠️ 免责声明

本脚本仅用于改善个人浏览体验，所有内容版权归原网站及原作者所有。使用本脚本产生的一切后果由使用者自行承担。

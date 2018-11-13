# Anymusic_docs

该项目灵感来自 [listen1](https://github.com/listen1) 项目

但是 listen1 并不满足个人强定制需求，且前后端不分离，遂有此项目

## 个人需求

个人对一个音乐播放器主要有如下两点需求：

- 能够进行关键字搜索，且搜索结果能够按序播放
- 创建歌单，添加歌曲

## 其他细节

关于 anymusic 实现的其他主要细节：

- 无注册、登录步骤，已创建的歌单保存在本地，尽量保证轻量级实现
- 支持三大平台搜索（网易云，虾米，QQ）

## 接口

各种实现均采用前后端分离，后端 api 由 [anymusic/api](https://github.com/anymusic/api) 项目提供

## 可能的实现

该项目为长期个人学习项目，带有极大的个人感情色彩，预计可能会有的实现如下：

- [ ] React
  - [ ] Redux
  - [ ] Redux + React-Redux
  - [ ] Mobx
  - [ ] Next.js
- [ ] Vue
  - [ ] SPA
  - [ ] Nuxt.js
- [ ] Electron-React
- [ ] Electron-Vue
- [ ] 小程序
- [ ] React-Native
- [ ] Weex

其他还有一些实现，比如 PWA，[nuxt+electron](https://github.com/nuxt-community/electron-template)，TypeScript 版本，学有余力，可以研究下

## 最后

我也不知道什么时候能实现如上这些，现在是 2018/11/13，嗯，期待五年内吧，也有可能永远实现不了吧，谁知道呢
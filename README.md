# electron-vite-vue-element-plus

🥳 Really simple `Electron` + `Vue` + `Vite` + `Element-plus` boilerplate.

[![GitHub Build](https://github.com/electron-vite/electron-vite-vue/actions/workflows/build.yml/badge.svg)](https://github.com/electron-vite/electron-vite-vue/actions/workflows/build.yml)
[![GitHub Discord](https://img.shields.io/badge/chat-discord-blue?logo=discord)](https://discord.gg/sRqjYpEAUK)

## Features

📦 Out of the box
🌱 Extensible, really simple directory structure  
💪 Support using Node.js API in Electron-Renderer  
🔩 Support C/C++ native addons  
🖥 It's easy to implement multiple windows  

## Quick Setup

```sh
# clone the project
git clone https://github.com/captainIT/electron-vite-vue-sth.git

# enter the project directory
cd electron-vite-vue-sth

# install dependency
npm install

# develop
npm run dev
```

## Directory

```diff
+ ├─┬ electron
+ │ ├─┬ main
+ │ │ └── index.ts    entry of Electron-Main
+ │ └─┬ preload
+ │   └── index.ts    entry of Preload-Scripts
  ├─┬ src
  │ └── main.ts       entry of Electron-Renderer
  ├── index.html
  ├── package.json
  └── vite.config.ts
```

## enhance

* @iconify-json/ep
[Vue3！Element Plus 如何像 Element UI 一样使用 Icon?](https://zhuanlan.zhihu.com/p/507462743?utm_id=0)

* 支持多语言切换

* 支持electron-store   [对比localStorage优点](https://github.com/sindresorhus/electron-store/issues/17#issuecomment-307561288)
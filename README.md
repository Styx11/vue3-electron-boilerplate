# Vue3-election-boilerplate
> election boilerplate with vue3

## 技术栈选型
* Vue, Vue-Router, Vuex
* Ant-Design-Vue
* TypeScript
* Electron
* Less

## 文件结构
```
.
├── LICENSE
├── README.md
├── package.json
├── tsconfig.json
└── views                # 渲染进程相关资源
    ├── README.md
    ├── babel.config.js
    ├── config           # webpack 配置
    ├── dist
    ├── env              # 环境文件
    ├── package.json
    ├── public
    ├── scripts          # 命令文件
    ├── src              # 页面资源
    ├── test             # Jest 测试相关
    ├── tsconfig.json
    └── yarn.lock
```
## Build
```sh
yarn install
yarn test to run tests.
yarn webpack-dev-server for development mode.
```

## LICENSE
MIT.
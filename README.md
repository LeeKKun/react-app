## Start

> Typescript + React 初始化项目，配备有简易 Vite 与 Webpack，可自行选择移出。`package.json` 中 `scripts` 配置有不同的启动命令，使用方式见下方。

项目默认配置有 eslint 如果不需要自行移除，src 目录中有建议 demo 可供初学，有问题欢迎探讨。

## 安装依赖

```bash
yarn
```

## 开发必读

开发依赖环境 Node 14+，默认端口 8080。

最好给编辑器安装上 EditorConfig, ESLint, Prettier 方便开发。

项目会在 `git commit` 时进行 Prettier 与 ESLint 格式代码，如果未通过请遵守 ESLint 规范，请修复后重新 `commit` ，情况紧急可以在 `git commit` 时加 `--no-verify` 命令不校验直接提交。

## 启动本地开发服务

```bash
yarn dev # Webpack
# or
yarn dev-v # Vite
```

## 打包编译

默认输出 dist 文件夹

```bash
yarn build # Webpack
# or
yarn build-v # Vite
```

## 检查代码格式

配置文件 `.eslintrc` 参考官网 https://eslint.org/

```bash
yarn lint
```

## 格式化代码

配置文件 `.perttierrc` 参考官网 https://prettier.io/

```bash
yarn prettier
```

## 备注

> public 目录内的资源都会按照原路径 Copy 至 dist 目录。

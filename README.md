# redMonkey-dist

`redMonkey` 的**构建产物**发布仓库（源码在私有仓库 `shenzhuangzhi1/redMonkey`，通过 GitHub Actions 自动构建并推送到这里）。

## 安装 / 更新地址

```
https://raw.githubusercontent.com/shenzhuangzhi1/redMonkey-dist/main/xhs-helper-vue.user.js
```

- 首次：浏览器打开上面的链接，Tampermonkey 会弹出安装页
- 之后：脚本内置 `@updateURL`，Tampermonkey 会按自己的更新周期自动检查并升级
- 手动检查更新：Tampermonkey 面板 → 已安装脚本 → 检查更新

## 说明

- 本仓库只放构建产物，不放源码
- 每次源码仓库 `master` 有新提交，Actions 会用 `package.json` 的版本号重新构建并覆盖此文件
- 版本号必须递增，Tampermonkey 才会认为是新版本

## Fork 说明
本项目Fork自[乾坤官方GitHub Repo](https://github.com/umijs/qiankun.git)，增加主应用的服务端SSR特性，主要应用于以Nuxt.js作为主应用的SSR的服务端渲染场景，其他服务端渲染框架暂时不考虑兼容性问题。

为了保持项目源同官方代码一直，增加如下操作步骤：

```bash
## 1. 增加upstream源
git remote add upstream https://github.com/umijs/qiankun.git

## 2. 获取官方最新
[master]> git fetch upstream

## 3. 合并官方最新到本地分支
[master]> git merge upstream/master

## 4. 更新fork的远程仓库
[master]> git push origin master

```
# hexo blog

生成静态文件, 部署到仓库`yangjinjie.github.io`, `master分支`

## 克隆源代码

```shell
git clone -b source-code git@github.com:yangjinjie/yangjinjie.github.io.git
```

## 安装依赖

```shell
# 根据package.json内容, 自动安装依赖
npm install
# 安装依赖的时候会自动将依赖写入到 package.json 文件中
# npm install hexo-deployer-git --save
```

## 部署

```shell
# 清空静态页面
hexo clean
# 生成静态页面
hexo generate
# 部署
hexo deploy
```

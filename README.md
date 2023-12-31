# vue-element-admin-mock

> this is a vue+element+admin+mock project 
> 使用 mockjs 模拟数据实现

## 模板使用 - vue-element-admin

[模板仓库](https://github.com/PanJiaChen/vue-element-admin)

[模板线上地址](http://panjiachen.github.io/vue-admin-template)

[模板国内访问](https://panjiachen.gitee.io/vue-admin-template)

[模板中文文档](https://mvvcc.com/vue-element-admin-site/zh/)

## Build Setup

```bash
# 克隆项目
git clone https://github.com/Zu-Yang/vue-element-admin-mock.git

# 进入项目目录
cd vue-element-admin-mock

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## Build

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## Advanced

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis
npm run preview -- --report

# code format check
npm run lint

# code format check and auto fix
npm run lint -- --fix
```
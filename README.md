# 简介
vue-element-perfect 是一个后台前端解决方案, 基于Vue3.0+TS+Element-plus实现。它使用了最新的前端技术栈、动态路由，权限验证，并且有着丰富的组件。

## 效果预览

预览地址 [项目预览地址](https://yuanzbz.gitee.io/vue-admin-perfect)

附上github地址 [vue-admin-perfect](https://github.com/zouzhibin/vue-admin-perfect)

## 目录结构介绍

```

├─assets    放置一些静态文件
├─components 放置组件
├─layout 首页布局
│  ├─components
│  │  ├─Sidebar 侧边栏配置
│  │  ├─TagsView 标签栏配置
│  │  └─UHeader 头部内容配置
│  └─hooks
├─router   路由配置
├─store    数据存储
├─styles   样式文件
├─utils   工具方法
└─views    页面配置方法
└─permission  路由拦截 权限配置
```

## 技术栈
vue3.0 + Typescript + vuex + vue-router + Element-Plus scss

## 开发
```
# 克隆项目
git clone https://github.com/zouzhibin/vue-admin-perfect.git

# 安装依赖
yarn install

# 本地开发 启动项目
yarn serve
```

### 发布
```
yarn build
```


# Antd-admin-layout

## 描述
这是一个基于Ant Design的管理后台布局，省去了复杂的页面组件，纯粹是为了方便移植。

如果您对`React`,`Antd`以及`Umijs`比较熟悉，您可以在此基础上快速地扩展功能。

支持[亮|暗]两种侧边栏肤色

## 技术栈
- React
- Ant Design/Ant Design Pro
- Umijs
- Dva
- React-redux

## 代码目录结构

> 结构比较简单，所以这里就没有添加说明。

```shell script
$ tree -I node_modules -L 9 -a
.
|-- .env
|-- .gitignore
|-- config
|   `-- config.js
|-- package.json
`-- src
    |-- document.ejs
    |-- layouts
    |   `-- BasicLayout
    |       |-- Content
    |       |   |-- index.js
    |       |   `-- index.less
    |       |-- Footer
    |       |   |-- index.js
    |       |   `-- index.less
    |       |-- Header
    |       |   |-- index.js
    |       |   `-- index.less
    |       |-- Sider
    |       |   |-- index.js
    |       |   `-- index.less
    |       |-- components
    |       |   |-- Header
    |       |   |   |-- icons.js
    |       |   |   |-- rightContent.js
    |       |   |   `-- rightContent.less
    |       |   `-- Sider
    |       |       |-- components
    |       |       |   |-- Logo
    |       |       |   |   |-- index.js
    |       |       |   |   `-- index.less
    |       |       |   `-- SiderMenu
    |       |       |       |-- index.js
    |       |       |       `-- index.less
    |       |       |-- siderbar.js
    |       |       |-- siderdrawer.js
    |       |       `-- siderdrawer.less
    |       |-- index.js
    |       |-- index.less
    |       `-- layout-global.less
    |-- models
    |   `-- layout.js
    `-- pages
        |-- .umi
        |   |-- dva.js
        |   |-- history.js
        |   |-- polyfills.js
        |   |-- router.js
        |   |-- umi.js
        |   `-- umiExports.ts
        |-- Dashboard
        |   |-- Project1
        |   |   |-- index.js
        |   |   `-- index.less
        |   |-- Project2
        |   |   |-- index.js
        |   |   `-- index.less
        |   `-- index.js
        |-- Errors
        |   `-- NotFound
        |       `-- index.js
        |-- User
        |   |-- UserList
        |   |   |-- index.js
        |   |   `-- index.less
        |   |-- UserRegister
        |   |   |-- index.js
        |   |   `-- index.less
        |   `-- index.js
        `-- components

29 directories, 52 files

```

## 快速使用
### 1. 安装 nodejs
首先确保您已经安装了 `nodejs` 环境，下面是 `nodejs` 官网下载链接。

[download and install nodejs](https://nodejs.org/zh-cn/)

### 2. 安装 umijs

> 如果您在代码中的 `package.json` 中指定`umi`依赖，这步可以跳过。

```shell script
npm install umi@^2.0.0 -g
```

### 3. 克隆代码
```shell script
git clone https://github.com/gogo-fast/antd-admin-layout.git
cd antd-admin-layout
```

### 4. 安装依赖
```shell script
npm install
```

### 5. 启动本地服务
```shell script
npm run start
```
or
```shell script
npm start
```

## 访问本地服务
`http://localhost:8000`

> Modify file `.env` to set listening host and port.

- Pc full screen

<div  align=center>
<img src="https://github.com/gogo-fast/pictures/blob/master/antd-admin-layout/1590146478910.png" width = "900"  alt="全屏" />
</div>

# aims-website


这个仓库是用来管理 aims 前端框架的低代码生成页面配置文件

## 框架介绍
前端低代码框架，通过 JSON 配置就能生成各种后台页面，极大减少开发成本，甚至可以不需要了解前端。

- 仓库: https://github.com/baidu/amis
- 官网：https://baidu.github.io/amis

## 仓库结构

```shell
  .
  ├── page/               # 存储页面配置json文件
  ├── .gitignore
  ├── LICENSE
  └── README.md
```

- page/ 目录用于存储页面配置文件，每个配置文件对应一个页面的配置。
- src/ 目录包含了框架的源代码，包括组件、样式和工具。
- .gitignore 用于配置不需要被 Git 跟踪的文件或目录。
- LICENSE 文件包含了本仓库的开源许可证。
- README.md 是本文件，用于说明本仓库的作用和使用方法。


## 如何使用
克隆本仓库到本地。

```shell
 git clone https://github.com/Zzl615/aims-website.git
```
打开 config/ 目录，选择需要的页面配置文件，将其复制到你的项目中。

在你的项目中使用 AIMS 前端框架，通过配置文件进行页面构建。


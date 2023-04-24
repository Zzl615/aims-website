# aims-website


这个仓库是用来管理 aims 前端框架的低代码生成页面配置。这个框架旨在帮助开发者快速开发并部署 Web 应用程序，减少繁琐的代码编写过程。

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

- config/ 目录用于存储页面配置文件，每个配置文件对应一个页面的配置。
- src/ 目录包含了框架的源代码，包括组件、样式和工具。
- .gitignore 用于配置不需要被 Git 跟踪的文件或目录。
- LICENSE 文件包含了本仓库的开源许可证。
- README.md 是本文件，用于说明本仓库的作用和使用方法。


## 如何使用
克隆本仓库到本地。

```shell
 git clone https://github.com/your-username/aims-low-code-config.git
```
打开 config/ 目录，选择需要的页面配置文件，将其复制到你的项目中。

在你的项目中使用 AIMS 前端框架，通过配置文件进行页面构建。

## 贡献方式

如果您对该项目有任何改进或修复的建议，请通过以下方式参与贡献：
1. Fork 该仓库。
2. 在您的本地环境中克隆该仓库。

```
git clone https://github.com/your-username/aims-low-code-config.git
```
3. 在您的本地环境中进行修改。


我们会审核您的 Pull Request，并在必要时与您进行沟通。

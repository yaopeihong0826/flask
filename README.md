# Web期末大作业-后端部分

此篇readme帮助你阅读理解项目整个后端的编写过程以及后端所完成内容

----
## 目录
* [简介](#jump1)
* [项目的主要步骤](#jump2)
* [项目布局](#jump3)
* [运行](#jump4)
----

## <span id="jump1">1. 简介</span>
在后端我们所完成的内容主要是能够创建一个名为 Flaskr 的基本博客应用程序。用户将能够注册、登录、创建帖子以及编辑或删除自己的帖子。

## <span id="jump2">2. 项目的主要步骤</span>
### (1)、配置Python虚拟环境  
### (2)、完成项目所做的内容
* 应用程序设置
* 定义和访问数据库
* 蓝图和视图
* 模板
* 静态文件
* 博客蓝图
* 使项目可安装
* 测试覆盖率
* 部署到生产
### (3)、项目目录包括如下内容：
* flaskr/，包含您的应用程序代码和文件的Python包。
* tests/，包含测试模块的目录。
* venv/，安装火焰和其他附属物的Python虚拟环境。
* 安装文件告诉Python如何安装您的项目。
* 版本控制配置，如git。无论大小，您都应该养成对所有项目使用某种版本控制的习惯。
* 将来可能会添加任何其他项目文件。

## <span id="jump3">3. 项目布局</span>
布局主要包括以下四个内容：
* 用户注册页面
* 用户登录页面
* 当前用户可对自己的博客内容进行修改
* 能够展现出用户的博客内容

## <span id="jump4">4. 运行</span>
运行：（即Gitpod打开本项目具体所需步骤）
* pip install flask
* export FLASK_APP=flaskr
* export FLASK_ENV=development
* pip install waitress
* waitress-serve --call 'flaskr:create_app'
* open browser

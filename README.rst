====
vela
====

简介
====

vela是一个项目管理和质量控制相关文档管理项目，用来管理QA团队的非项目类文档，包括以下类型：

    * 项目管理
        * 项目管理相关理论
        * 项目管理规范
        * 项目管理流程定义
        * 项目管理关键实践
        * 项目管理工具的基本使用和维护
    * 质量控制
        * 质量控制相关理论
        * 质量控制工作指导和规范
        * 测试相关理论
        * 测试所需技术知识和原则
        * 质量控制工作所需工具的原理、使用和维护
        * 质量控制工具的设计

文档生成
======

按照以下步骤安装配置所需工具，然后生成可读文档。

安装Python
---------

如果没有安装过Python，从 `Python Download <https://www.python.org/downloads/>`_ 页面下载并安装Python。

安装PyPI
------

如果没有安装过安装PyPI，根据`PyPI Installation <https://pip.pypa.io/en/latest/installing/>`_ 的内容安装Pip。

安装Sphinx
---------

使用Pip安装Sphinx ::

$ pip install Sphinx

生成可读文档
----------

在项目的顶级目录，执行 ::

$ make html

然后可以使用浏览器访问项目目录下的 ::

build/html/index.html

文件，以及文件中的链接来查看所有的项目文档。
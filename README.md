<!-- markdownlint-disable -->
<h1 align="center">
    Python资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>Python开源工具库资源大全，按应用方向划分并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-690-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-python-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-python-resources?color=green&label=updated"></a>
</p>

本资源清单包含690个python相关的开源工具资源，这些热门工具总共分成91个不同的应用领域，目前在github上已经收到2.8M个点赞。所有的工具(github项目)每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-python](https://github.com/vinta/awesome-python)，欢迎大家提PR丰富本清单。
## 目录

- [管理面板](#管理面板) _9 个项目_
- [算法和设计模式](#算法和设计模式) _7 个项目_
- [ASGI服务器](#ASGI服务器) _2 个项目_
- [网络](#网络) _4 个项目_
- [音频](#音频) _13 个项目_
- [验证](#验证) _9 个项目_
- [构建工具](#构建工具) _5 个项目_
- [内置类的增强版实现](#内置类的增强版实现) _5 个项目_
- [CMS](#CMS) _8 个项目_
- [缓存](#缓存) _7 个项目_
- [聊天工具](#聊天工具) _1 个项目_
- [代码分析和Lint工具](#代码分析和Lint工具) _20 个项目_
- [命令行工具](#命令行工具) _12 个项目_
- [命令行工具](#命令行工具) _16 个项目_
- [兼容性](#兼容性) _3 个项目_
- [计算机视觉](#计算机视觉) _7 个项目_
- [并发和并行](#并发和并行) _5 个项目_
- [配置](#配置) _5 个项目_
- [密码学](#密码学) _4 个项目_
- [科学计算和数据分析](#科学计算和数据分析) _6 个项目_
- [数据验证](#数据验证) _7 个项目_
- [数据可视化](#数据可视化) _14 个项目_
- [数据库](#数据库) _3 个项目_
- [数据库驱动](#数据库驱动) _17 个项目_
- [日期和时间](#日期和时间) _10 个项目_
- [调试工具](#调试工具) _18 个项目_
- [深度学习](#深度学习) _7 个项目_
- [DevOps工具](#DevOps工具) _13 个项目_
- [分布式计算](#分布式计算) _7 个项目_
- [分发](#分发) _8 个项目_
- [文档](#文档) _4 个项目_
- [下载器](#下载器) _5 个项目_
- [电子商务](#电子商务) _10 个项目_
- [Emacs-Python开发环境](#Emacs-Python开发环境) _10 个项目_
- [电子邮件](#电子邮件) _6 个项目_
- [企业级应用集成](#企业级应用集成) _1 个项目_
- [环境管理](#环境管理) _2 个项目_
- [文件](#文件) _7 个项目_
- [外来函数接口](#外来函数接口) _4 个项目_
- [表单](#表单) _6 个项目_
- [函数式编程](#函数式编程) _7 个项目_
- [图形用户界面](#图形用户界面) _16 个项目_
- [GraphQL](#GraphQL) _4 个项目_
- [游戏开发](#游戏开发) _9 个项目_
- [地理位置](#地理位置) _5 个项目_
- [HTML处理](#HTML处理) _11 个项目_
- [HTTP](#HTTP) _6 个项目_
- [硬件](#硬件) _7 个项目_
- [图像处理](#图像处理) _15 个项目_
- [高性能](#高性能) _13 个项目_
- [交互式解析器](#交互式解析器) _4 个项目_
- [国际化](#国际化) _2 个项目_
- [任务调度](#任务调度) _11 个项目_
- [日志](#日志) _5 个项目_
- [机器学习](#机器学习) _9 个项目_
- [微软的Windows平台](#微软的Windows平台) _5 个项目_
- [杂项](#杂项) _6 个项目_
- [自然语言处理](#自然语言处理) _13 个项目_
- [网络可视化和SDN](#网络可视化和SDN) _3 个项目_
- [动态消息](#动态消息) _2 个项目_
- [ORM](#ORM) _13 个项目_
- [包管理](#包管理) _5 个项目_
- [包仓库](#包仓库) _4 个项目_
- [渗透测试](#渗透测试) _3 个项目_
- [权限](#权限) _2 个项目_
- [进程](#进程) _3 个项目_
- [推荐系统](#推荐系统) _8 个项目_
- [重构](#重构) _3 个项目_
- [RESTfulAPI](#RESTfulAPI) _13 个项目_
- [机器人](#机器人) _2 个项目_
- [RPC服务器](#RPC服务器) _1 个项目_
- [科学计算和数据分析](#科学计算和数据分析) _21 个项目_
- [搜索](#搜索) _5 个项目_
- [序列化](#序列化) _4 个项目_
- [Serverless框架](#Serverless框架) _2 个项目_
- [命令行工具](#命令行工具) _1 个项目_
- [特殊文本格式处理](#特殊文本格式处理) _17 个项目_
- [静态站点生成器](#静态站点生成器) _5 个项目_
- [标记](#标记) _1 个项目_
- [队列](#队列) _5 个项目_
- [模板引擎](#模板引擎) _3 个项目_
- [测试](#测试) _30 个项目_
- [文本处理](#文本处理) _22 个项目_
- [第三方API](#第三方API) _7 个项目_
- [URL处理](#URL处理) _4 个项目_
- [Video](#Video) _3 个项目_
- [Web资源管理](#Web资源管理) _7 个项目_
- [网络](#网络) _9 个项目_
- [HTML处理](#HTML处理) _8 个项目_
- [Web框架](#Web框架) _8 个项目_
- [WebSocket](#WebSocket) _3 个项目_
- [WSGI服务器](#WSGI服务器) _5 个项目_

## 图标解释
- 🥇🥈🥉&nbsp; 综合项目质量分
- ⭐️&nbsp; github上star的数量
- 🐣&nbsp; 小于6个月的新项目
- 💤&nbsp; 非活跃项目(6个月未更新)
- 💀&nbsp; 沉寂项目(12个月未更新)
- 📈📉&nbsp; 项目趋势(向上or向下)
- ➕&nbsp; 最近添加的项目
- ❗️&nbsp; 警告(例如 项目没有license)
- 👨‍💻&nbsp; 项目的开发贡献者数量
- 🔀&nbsp; 项目被fork的数量
- 📋&nbsp; 项目issue的数量
- ⏱️&nbsp; 项目包上次更新时间
- 📥&nbsp; 工具库被下载次数
- 📦&nbsp; 项目依赖的工具库数量

<br>

## 管理面板

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理界面库。_

🔗&nbsp;<b><a href="https://grappelliproject.com/">django-grappelli</a></b>  - 拥有绚丽外观的 Django Admin 界面。

🔗&nbsp;<b><a href="https://djangosuit.com/">django-suit</a></b>  - Django 管理界面的一个替代品 (仅对于非商业用途是免费的)。

<details><summary><b><a href="https://github.com/flask-admin/flask-admin">flask-admin</a></b> (🥇33 ·  ⭐ 4.9K) - 一个用于 Flask 的简单可扩展的管理界面框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/flask-admin/flask-admin) (👨‍💻 340 · 🔀 1.4K · 📦 13K · 📋 1.3K - 26% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/flask-admin/flask-admin
	```
- [PyPi](https://pypi.org/project/flask-admin) (📥 1.8M / month):
	```
	pip install flask-admin
	```
- [Conda](https://anaconda.org/conda-forge/flask-admin) (📥 120K · ⏱️ 17.04.2021):
	```
	conda install -c conda-forge flask-admin
	```
</details>
<details><summary><b><a href="https://github.com/mher/flower">flower</a></b> (🥈29 ·  ⭐ 5K) - 一个对 Celery 集群进行实时监控和提供 web 管理界面的工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mher/flower) (👨‍💻 180 · 🔀 840 · 📦 7.2K · 📋 800 - 8% open · ⏱️ 25.11.2021):

	```
	git clone https://github.com/mher/flower
	```
- [PyPi](https://pypi.org/project/flower) (📥 870K / month):
	```
	pip install flower
	```
- [Conda](https://anaconda.org/conda-forge/flower) (📥 100K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge flower
	```
</details>
<details><summary><b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥈26 ·  ⭐ 3.2K · 💀) - 具有改进功能的现代响应式 Django 管理界面模板。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/geex-arts/django-jet) (👨‍💻 29 · 🔀 640 · 📦 2.5K · 📋 330 - 63% open · ⏱️ 21.05.2019):

	```
	git clone https://github.com/geex-arts/django-jet
	```
- [PyPi](https://pypi.org/project/django-jet) (📥 33K / month):
	```
	pip install django-jet
	```
- [Conda](https://anaconda.org/conda-forge/django-jet):
	```
	conda install -c conda-forge django-jet
	```
</details>
<details><summary><b><a href="https://github.com/ajenti/ajenti">ajenti</a></b> (🥉22 ·  ⭐ 6.6K) - 一个你的服务器值得拥有的管理面板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ajenti/ajenti) (👨‍💻 18 · 🔀 740 · 📦 23 · 📋 1.1K - 1% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/ajenti/ajenti
	```
- [PyPi](https://pypi.org/project/ajenti) (📥 300 / month):
	```
	pip install ajenti
	```
- [Conda](https://anaconda.org/conda-forge/ajenti):
	```
	conda install -c conda-forge ajenti
	```
</details>
<details><summary><b><a href="https://github.com/sshwsfc/xadmin">django-xadmin</a></b> (🥉21 ·  ⭐ 4.6K · 💀) - Django admin 的一个替代品，具有很多不错的功能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sshwsfc/xadmin) (👨‍💻 51 · 🔀 1.4K · 📦 760 · 📋 560 - 65% open · ⏱️ 03.04.2019):

	```
	git clone https://github.com/sshwsfc/xadmin
	```
- [PyPi](https://pypi.org/project/xadmin) (📥 500 / month):
	```
	pip install xadmin
	```
- [Conda](https://anaconda.org/conda-forge/xadmin):
	```
	conda install -c conda-forge xadmin
	```
</details>
<details><summary><b><a href="https://github.com/wooey/Wooey">wooey</a></b> (🥉20 ·  ⭐ 1.7K) - 一个 Django 应用，可以为 Python 脚本创建 web 用户界面。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wooey/Wooey) (👨‍💻 22 · 🔀 170 · 📦 31 · 📋 200 - 27% open · ⏱️ 09.08.2021):

	```
	git clone https://github.com/wooey/wooey
	```
- [PyPi](https://pypi.org/project/wooey):
	```
	pip install wooey
	```
- [Conda](https://anaconda.org/conda-forge/wooey):
	```
	conda install -c conda-forge wooey
	```
</details>
<details><summary><b><a href="https://github.com/jet-admin/jet-bridge">jet-bridge</a></b> (🥉15 ·  ⭐ 1.1K) - 管理面板框架，适用于任何具有良好 UI 的应用（例如 Django）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jet-admin/jet-bridge) (👨‍💻 4 · 🔀 100 · 📋 11 - 63% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/jet-admin/jet-bridge
	```
- [PyPi](https://pypi.org/project/jet-bridge) (📥 320 / month):
	```
	pip install jet-bridge
	```
- [Conda](https://anaconda.org/conda-forge/jet-bridge):
	```
	conda install -c conda-forge jet-bridge
	```
</details>
<br>

## 算法和设计模式

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_数据结构、算法和设计模式的 Python 实现。也可以参考 [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) 。_

<details><summary><b><a href="https://github.com/TheAlgorithms/Python">TheAlgorithms</a></b> (🥇29 ·  ⭐ 130K) - 所有算法的 Python 实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TheAlgorithms/Python) (👨‍💻 820 · 🔀 33K · 📋 880 - 1% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/TheAlgorithms/Python
	```
- [PyPi](https://pypi.org/project/Python):
	```
	pip install Python
	```
- [Conda](https://anaconda.org/conda-forge/Python) (📥 42M · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge Python
	```
</details>
<details><summary><b><a href="https://github.com/pytransitions/transitions">transitions</a></b> (🥈27 ·  ⭐ 4.1K) - 轻量级的，面向对象的有限状态机实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytransitions/transitions) (👨‍💻 70 · 🔀 460 · 📦 2K · 📋 390 - 2% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/pytransitions/transitions
	```
- [PyPi](https://pypi.org/project/transitions):
	```
	pip install transitions
	```
- [Conda](https://anaconda.org/conda-forge/transitions) (📥 110K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge transitions
	```
</details>
<details><summary><b><a href="https://github.com/keon/algorithms">algorithms</a></b> (🥈24 ·  ⭐ 20K) - 数据结构和算法的简单示例。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keon/algorithms) (👨‍💻 180 · 🔀 3.8K · 📦 55 · 📋 140 - 35% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/keon/algorithms
	```
- [PyPi](https://pypi.org/project/algorithms) (📥 720 / month):
	```
	pip install algorithms
	```
- [Conda](https://anaconda.org/conda-forge/algorithms) (📥 450 · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge algorithms
	```
</details>
<details><summary><b><a href="https://github.com/faif/python-patterns">python-patterns</a></b> (🥉16 ·  ⭐ 30K) - 一个 Python 设计模式集合。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/faif/python-patterns) (👨‍💻 120 · 🔀 5.8K · 📋 74 - 16% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/faif/python-patterns
	```
- [PyPi](https://pypi.org/project/python-patterns):
	```
	pip install python-patterns
	```
- [Conda](https://anaconda.org/conda-forge/python-patterns):
	```
	conda install -c conda-forge python-patterns
	```
</details>
<details><summary><b><a href="https://github.com/prabhupant/python-ds">python-ds</a></b> (🥉16 ·  ⭐ 1.5K) - 用于面试的数据结构和算法的集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/prabhupant/python-ds) (👨‍💻 100 · 🔀 450 · 📋 84 - 21% open · ⏱️ 24.10.2021):

	```
	git clone https://github.com/prabhupant/python-ds
	```
- [PyPi](https://pypi.org/project/python-ds) (📥 19 / month):
	```
	pip install python-ds
	```
- [Conda](https://anaconda.org/conda-forge/python-ds):
	```
	conda install -c conda-forge python-ds
	```
</details>
<details><summary><b><a href="https://github.com/tylerlaberge/PyPattyrn">PyPattyrn</a></b> (🥉15 ·  ⭐ 1.4K · 💀) - 一个简单而有效的库，用于实现常见的设计模式。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tylerlaberge/PyPattyrn) (👨‍💻 4 · 🔀 110 · 📦 17 · ⏱️ 09.02.2020):

	```
	git clone https://github.com/tylerlaberge/PyPattyrn
	```
- [PyPi](https://pypi.org/project/PyPattyrn):
	```
	pip install PyPattyrn
	```
- [Conda](https://anaconda.org/conda-forge/PyPattyrn):
	```
	conda install -c conda-forge PyPattyrn
	```
</details>
<details><summary><b><a href="https://github.com/grantjenks/python-sortedcontainers">sortedcontainers</a></b> (🥉14 ·  ⭐ 2.4K) - 排序集合的快速的纯 Python 实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/grantjenks/python-sortedcontainers) (👨‍💻 20 · 🔀 160 · 📋 140 - 11% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/grantjenks/python-sortedcontainers
	```
- [PyPi](https://pypi.org/project/python-sortedcontainers):
	```
	pip install python-sortedcontainers
	```
- [Conda](https://anaconda.org/conda-forge/python-sortedcontainers):
	```
	conda install -c conda-forge python-sortedcontainers
	```
</details>
<br>

## ASGI 服务器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_兼容 ASGI 的 web 服务器。_

<details><summary><b><a href="https://github.com/encode/uvicorn">uvicorn</a></b> (🥇30 ·  ⭐ 4.7K) - 使用 uvloop 和 httptools 实现的闪电般快速的 ASGI 服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/uvicorn) (👨‍💻 120 · 🔀 370 · 📦 46K · 📋 550 - 12% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/encode/uvicorn
	```
- [PyPi](https://pypi.org/project/uvicorn):
	```
	pip install uvicorn
	```
- [Conda](https://anaconda.org/conda-forge/uvicorn) (📥 720K · ⏱️ 08.12.2021):
	```
	conda install -c conda-forge uvicorn
	```
</details>
<details><summary><b><a href="https://github.com/django/daphne">daphne</a></b> (🥉24 ·  ⭐ 1.7K) - 用于 ASGI 和 ASGI-HTTP 的，支持 HTTP，HTTP2 和 WebSocket 协议的服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django/daphne) (👨‍💻 57 · 🔀 200 · 📦 12K · 📋 270 - 13% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/django/daphne
	```
- [PyPi](https://pypi.org/project/daphne):
	```
	pip install daphne
	```
- [Conda](https://anaconda.org/conda-forge/daphne) (📥 72K · ⏱️ 07.04.2021):
	```
	conda install -c conda-forge daphne
	```
</details>
<br>

## 网络

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于网络编程的库。_

🔗&nbsp;<b><a href="https://github.com/timofurrer/awesome-asyncio">awesome-asyncio</a></b> ( ⭐ 3.3K)  - A curated list of awesome Python asyncio frameworks, libraries, software..

🔗&nbsp;<b><a href="https://twistedmatrix.com/trac/">Twisted</a></b>  - 一个事件驱动的网络引擎。

<details><summary><b><a href="https://github.com/MagicStack/uvloop">uvloop</a></b> (🥇32 ·  ⭐ 8.3K) - Ultra fast asyncio event loop. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/MagicStack/uvloop) (👨‍💻 42 · 🔀 420 · 📥 350 · 📦 31K · 📋 270 - 18% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/MagicStack/uvloop
	```
- [PyPi](https://pypi.org/project/uvloop) (📥 3.7M / month):
	```
	pip install uvloop
	```
- [Conda](https://anaconda.org/conda-forge/uvloop) (📥 410K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge uvloop
	```
</details>
<details><summary><b><a href="https://github.com/python-trio/trio">trio</a></b> (🥉27 ·  ⭐ 4.4K) - 异步并发和 I/O 友好的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-trio/trio) (👨‍💻 130 · 🔀 250 · 📦 3.5K · 📋 650 - 39% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/python-trio/trio
	```
- [PyPi](https://pypi.org/project/trio) (📥 2.6M / month):
	```
	pip install trio
	```
- [Conda](https://anaconda.org/conda-forge/trio) (📥 640K · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge trio
	```
</details>
<br>

## 音频

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来操作音频的库_

🔗&nbsp;<b><a href="http://bspaans.github.io/python-mingus/">mingus</a></b>  - 一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。

<details><summary><b><a href="https://github.com/jiaaro/pydub">pydub</a></b> (🥇30 ·  ⭐ 5.8K) - 通过简单、简洁的高层接口来操作音频文件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 90 · 🔀 770 · 📦 10K · 📋 450 - 43% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 890K / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 20K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/beets">beets</a></b> (🥇29 ·  ⭐ 11K) - 一个音乐库管理器和 <a href="https://musicbrainz.org/">MusicBrainz</a> 标记器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/beets) (👨‍💻 480 · 🔀 1.6K · 📥 7K · 📦 230 · 📋 2.4K - 18% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/beetbox/beets
	```
- [PyPi](https://pypi.org/project/beets):
	```
	pip install beets
	```
- [Conda](https://anaconda.org/conda-forge/beets):
	```
	conda install -c conda-forge beets
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈27 ·  ⭐ 380) - 交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 21 · 🔀 89 · 📦 6.9K · 📋 75 - 38% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 500K / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 370K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/nicfit/eyeD3">eyeD3</a></b> (🥈25 ·  ⭐ 340) - 一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicfit/eyeD3) (👨‍💻 22 · 🔀 47 · 📥 2.1K · 📦 1.6K · 📋 170 - 24% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/nicfit/eyeD3
	```
- [PyPi](https://pypi.org/project/eyeD3) (📥 31K / month):
	```
	pip install eyeD3
	```
- [Conda](https://anaconda.org/conda-forge/eyeD3):
	```
	conda install -c conda-forge eyeD3
	```
</details>
<details><summary><b><a href="https://github.com/quodlibet/mutagen">mutagen</a></b> (🥈24 ·  ⭐ 910) - 一个用来处理音频元数据的 Python 模块。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/quodlibet/mutagen) (👨‍💻 35 · 🔀 120 · 📥 49K · 📦 5.9K · 📋 460 - 18% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/quodlibet/mutagen
	```
- [PyPi](https://pypi.org/project/mutagen):
	```
	pip install mutagen
	```
- [Conda](https://anaconda.org/conda-forge/mutagen) (📥 110K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge mutagen
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥉20 ·  ⭐ 4.5K) - 音频特征提取，分类，分段和应用。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 25 · 🔀 1K · 📦 250 · 📋 280 - 58% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis):
	```
	pip install pyAudioAnalysis
	```
- [Conda](https://anaconda.org/conda-forge/pyAudioAnalysis):
	```
	conda install -c conda-forge pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉20 ·  ⭐ 800) - Keras 音频处理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 140 · 📥 19 · 📦 1.3K · 📋 93 - 11% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre):
	```
	pip install kapre
	```
- [Conda](https://anaconda.org/conda-forge/kapre):
	```
	conda install -c conda-forge kapre
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥉19 ·  ⭐ 4.9K) - 音频音乐分析 Python 库。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 92 · 🔀 760 · 📋 920 - 3% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 420K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/worldveil/dejavu">dejavu</a></b> (🥉18 ·  ⭐ 5.6K · 💀) - 音频指纹提取和识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/worldveil/dejavu) (👨‍💻 23 · 🔀 1.2K · 📦 19 · 📋 200 - 36% open · ⏱️ 03.06.2020):

	```
	git clone https://github.com/worldveil/dejavu
	```
- [PyPi](https://pypi.org/project/dejavu) (📥 92 / month):
	```
	pip install dejavu
	```
- [Conda](https://anaconda.org/conda-forge/dejavu):
	```
	conda install -c conda-forge dejavu
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉18 ·  ⭐ 500) - 一个用来读取 MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 21 · 🔀 82 · 📦 450 · 📋 85 - 11% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag):
	```
	pip install tinytag
	```
- [Conda](https://anaconda.org/conda-forge/tinytag):
	```
	conda install -c conda-forge tinytag
	```
</details>
<details><summary><b><a href="https://github.com/Parisson/TimeSide">TimeSide</a></b> (🥉18 ·  ⭐ 310 · 💤) - 开源 web 音频处理框架。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Parisson/TimeSide) (👨‍💻 19 · 🔀 53 · 📦 15 · 📋 200 - 26% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/Parisson/TimeSide
	```
- [PyPi](https://pypi.org/project/TimeSide) (📥 240 / month):
	```
	pip install TimeSide
	```
- [Conda](https://anaconda.org/conda-forge/TimeSide):
	```
	conda install -c conda-forge TimeSide
	```
</details>
<details><summary><b><a href="https://github.com/sergree/matchering">matchering</a></b> (🥉15 ·  ⭐ 530) - 用于音频母带制作的库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sergree/matchering) (👨‍💻 3 · 🔀 64 · 📦 4 · 📋 32 - 34% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/sergree/matchering
	```
- [PyPi](https://pypi.org/project/matchering):
	```
	pip install matchering
	```
- [Conda](https://anaconda.org/conda-forge/matchering):
	```
	conda install -c conda-forge matchering
	```
</details>
<br>

## 验证

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_实现验证方案的库。_

<details><summary><b><a href="https://github.com/oauthlib/oauthlib">oauthlib</a></b> (🥇36 ·  ⭐ 2.3K) - 一个 OAuth 请求-签名逻辑通用、 完整的实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oauthlib/oauthlib) (👨‍💻 180 · 🔀 420 · 📦 190K · 📋 340 - 21% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/idan/oauthlib
	```
- [PyPi](https://pypi.org/project/oauthlib) (📥 57M / month):
	```
	pip install oauthlib
	```
- [Conda](https://anaconda.org/conda-forge/oauthlib) (📥 3.9M · ⏱️ 01.06.2021):
	```
	conda install -c conda-forge oauthlib
	```
</details>
<details><summary><b><a href="https://github.com/jpadilla/pyjwt">pyjwt</a></b> (🥈35 ·  ⭐ 4.1K) - JSON Web 令牌草案 01。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jpadilla/pyjwt) (👨‍💻 110 · 🔀 520 · 📦 170K · 📋 330 - 21% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/jpadilla/pyjwt
	```
- [PyPi](https://pypi.org/project/pyjwt) (📥 60M / month):
	```
	pip install pyjwt
	```
- [Conda](https://anaconda.org/conda-forge/pyjwt) (📥 5M · ⏱️ 06.12.2021):
	```
	conda install -c conda-forge pyjwt
	```
</details>
<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥈31 ·  ⭐ 6.9K) - Django 的验证应用。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 570 · 🔀 2.4K · 📦 79K · 📋 1.8K - 13% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth):
	```
	pip install django-allauth
	```
- [Conda](https://anaconda.org/conda-forge/django-allauth) (📥 68K · ⏱️ 23.12.2019):
	```
	conda install -c conda-forge django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/joestump/python-oauth2">python-oauth2</a></b> (🥈26 ·  ⭐ 2.9K · 💀) - 一个完全测试的抽象接口。用来创建 OAuth 客户端和服务端。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joestump/python-oauth2) (👨‍💻 42 · 🔀 800 · 📦 8.9K · 📋 130 - 37% open · ⏱️ 12.02.2018):

	```
	git clone https://github.com/joestump/python-oauth2
	```
- [PyPi](https://pypi.org/project/python-oauth2) (📥 53K / month):
	```
	pip install python-oauth2
	```
- [Conda](https://anaconda.org/conda-forge/python-oauth2) (📥 84K · ⏱️ 28.06.2019):
	```
	conda install -c conda-forge python-oauth2
	```
</details>
<details><summary><b><a href="https://github.com/lepture/authlib">authlib</a></b> (🥉25 ·  ⭐ 2.9K) - 一个强大的Python库，用来构建 OAuth 和 OpenID 服务端。包括：JWS, JWK, JWA, JWT。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lepture/authlib) (👨‍💻 70 · 🔀 280 · 📋 290 - 9% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/lepture/authlib
	```
- [PyPi](https://pypi.org/project/authlib) (📥 3.9M / month):
	```
	pip install authlib
	```
- [Conda](https://anaconda.org/conda-forge/authlib) (📥 68K · ⏱️ 18.10.2021):
	```
	conda install -c conda-forge authlib
	```
</details>
<details><summary><b><a href="https://github.com/omab/python-social-auth">python-social-auth</a></b> (🥉25 ·  ⭐ 2.8K · 💀) - 一个设置简单的社会化验证方式。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/omab/python-social-auth) (👨‍💻 280 · 🔀 1.1K · 📦 5.2K · 📋 660 - 2% open · ⏱️ 04.02.2017):

	```
	git clone https://github.com/omab/python-social-auth
	```
- [PyPi](https://pypi.org/project/python-social-auth) (📥 37K / month):
	```
	pip install python-social-auth
	```
- [Conda](https://anaconda.org/conda-forge/python-social-auth):
	```
	conda install -c conda-forge python-social-auth
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥉24 ·  ⭐ 2.4K · 📈) - 为 Django 用户准备的 OAuth2。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-oauth-toolkit) (👨‍💻 190 · 🔀 610 · 📋 650 - 18% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/evonove/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 350K / month):
	```
	pip install django-oauth-toolkit
	```
- [Conda](https://anaconda.org/conda-forge/django-oauth-toolkit):
	```
	conda install -c conda-forge django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/davedoesdev/python-jwt">python-jwt</a></b> (🥉18 ·  ⭐ 190) - 一个用来生成和验证 JSON Web 令牌的模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davedoesdev/python-jwt) (👨‍💻 5 · 🔀 23 · ⏱️ 16.11.2021):

	```
	git clone https://github.com/davedoesdev/python-jwt
	```
- [PyPi](https://pypi.org/project/python-jwt) (📥 180K / month):
	```
	pip install python-jwt
	```
- [Conda](https://anaconda.org/conda-forge/python-jwt):
	```
	conda install -c conda-forge python-jwt
	```
</details>
<details><summary><b><a href="https://github.com/mpdavis/python-jose">python-jose</a></b> (🥉16 ·  ⭐ 990) - python 版 JOSE 实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mpdavis/python-jose) (🔀 180 · 📋 120 - 39% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/mpdavis/python-jose/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 构建工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_将源码编译成软件。_

🔗&nbsp;<b><a href="http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html">BitBake</a></b>  - 针对嵌入式 Linux 的类似 make 的构建工具。

🔗&nbsp;<b><a href="http://www.buildout.org/en/latest/">buildout</a></b>  - 一个构建系统，从多个组件来创建，组装和部署应用。

🔗&nbsp;<b><a href="http://www.scons.org/">SCons</a></b>  - 软件构建工具。

<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥇22 ·  ⭐ 1.3K) - 纯 Python 实现的持续化构建工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 36 · 🔀 220 · 📋 490 - 16% open · ⏱️ 08.11.2021):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder):
	```
	pip install pybuilder
	```
- [Conda](https://anaconda.org/conda-forge/pybuilder) (📥 8.5K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/platformio/platformio-core">PlatformIO</a></b> (🥉20 ·  ⭐ 5.6K) - 多平台命令行构建工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/platformio/platformio-core) (👨‍💻 55 · 🔀 590 · 📋 3.6K - 4% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/platformio/platformio-core
	```
- [PyPi](https://pypi.org/project/platformio-core):
	```
	pip install platformio-core
	```
- [Conda](https://anaconda.org/conda-forge/platformio-core):
	```
	conda install -c conda-forge platformio-core
	```
</details>
<br>

## 内置类的增强版实现

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_一些 Python 内置类的增强版实现库。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/dataclasses.html">dataclasses</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

<details><summary><b><a href="https://github.com/python-attrs/attrs">attrs</a></b> (🥇29 ·  ⭐ 3.8K) - 一个在类定义时可替换 `__init__`, `__eq__`, `__repr__`等方法的样板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-attrs/attrs) (👨‍💻 110 · 🔀 280 · 📦 320K · 📋 510 - 18% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/python-attrs/attrs
	```
- [PyPi](https://pypi.org/project/attrs):
	```
	pip install attrs
	```
- [Conda](https://anaconda.org/conda-forge/attrs) (📥 12M · ⏱️ 07.05.2021):
	```
	conda install -c conda-forge attrs
	```
</details>
<details><summary><b><a href="https://github.com/jab/bidict">bidict</a></b> (🥈23 ·  ⭐ 960) - 高效的 Pythonic 的双向映射数据结构和相关功能。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/jab/bidict) (👨‍💻 11 · 🔀 43 · 📦 5.5K · 📋 47 - 6% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jab/bidict
	```
- [PyPi](https://pypi.org/project/bidict):
	```
	pip install bidict
	```
- [Conda](https://anaconda.org/conda-forge/bidict) (📥 110K · ⏱️ 23.10.2021):
	```
	conda install -c conda-forge bidict
	```
</details>
<details><summary><b><a href="https://github.com/cdgriffith/Box">Box</a></b> (🥉16 ·  ⭐ 1.8K) - 具有高级点符号访问权限的 Python 字典。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cdgriffith/Box) (🔀 73 · 📥 30 · 📋 130 - 15% open · ⏱️ 22.08.2021):

	```
	git clone https://github.com/cdgriffith/Box
	```
- [PyPi](https://pypi.org/project/Box):
	```
	pip install Box
	```
- [Conda](https://anaconda.org/conda-forge/Box):
	```
	conda install -c conda-forge Box
	```
</details>
<details><summary><b><a href="https://github.com/carlosescri/DottedDict">DottedDict</a></b> (🥉14 ·  ⭐ 130 · 💀) - 提供一种使用点路径符号访问列表和字典的方法的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carlosescri/DottedDict) (👨‍💻 3 · 🔀 14 · 📥 60 · 📦 49 · 📋 9 - 77% open · ⏱️ 30.10.2015):

	```
	git clone https://github.com/carlosescri/DottedDict
	```
- [PyPi](https://pypi.org/project/DottedDict):
	```
	pip install DottedDict
	```
- [Conda](https://anaconda.org/conda-forge/DottedDict):
	```
	conda install -c conda-forge DottedDict
	```
</details>
<br>

## CMS

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_内容管理系统。_

🔗&nbsp;<b><a href="https://www.django-cms.org/en/">django-cms</a></b>  - 一个开源的，企业级 CMS，基于 Django。

🔗&nbsp;<b><a href="https://plone.org/">plone</a></b>  - 一个构建于开源应用服务器 Zope 之上的 CMS。

🔗&nbsp;<b><a href="https://wagtail.io/">wagtail</a></b>  - 一个 Django 内容管理系统。

<details><summary><b><a href="https://github.com/indico/indico">indico</a></b> (🥇23 ·  ⭐ 1.3K) - 一个功能丰富的事件管理系统，由 @[CERN](https://en.wikipedia.org/wiki/CERN) 开发。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/indico/indico) (👨‍💻 120 · 🔀 310 · 📥 2.9K · 📋 3.2K - 18% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/indico/indico
	```
- [PyPi](https://pypi.org/project/indico) (📥 300 / month):
	```
	pip install indico
	```
- [Conda](https://anaconda.org/conda-forge/indico):
	```
	conda install -c conda-forge indico
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥈22 ·  ⭐ 4.4K) - 一个强大的，持续的，灵活的内容管理平台。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 320 · 🔀 1.5K · 📋 1K - 3% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine):
	```
	pip install mezzanine
	```
- [Conda](https://anaconda.org/conda-forge/mezzanine):
	```
	conda install -c conda-forge mezzanine
	```
</details>
<details><summary><b><a href="https://github.com/Kotti/Kotti">Kotti</a></b> (🥉16 ·  ⭐ 370) - 一个高级的，Python 范的 web 应用框架，基于 Pyramid 构建。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Kotti/Kotti) (👨‍💻 64 · 🔀 110 · 📦 220 · 📋 210 - 19% open · ⏱️ 02.09.2021):

	```
	git clone https://github.com/Kotti/Kotti
	```
- [PyPi](https://pypi.org/project/Kotti):
	```
	pip install Kotti
	```
- [Conda](https://anaconda.org/conda-forge/Kotti):
	```
	conda install -c conda-forge Kotti
	```
</details>
<details><summary><b><a href="https://github.com/quokkaproject/quokka">quokka</a></b> (🥉14 ·  ⭐ 2.2K · 💀) - 灵活，可扩展的小型 CMS，基于 Flask 和 MongoDB。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/quokkaproject/quokka) (👨‍💻 9 · 🔀 440 · 📋 420 - 15% open · ⏱️ 06.03.2019):

	```
	git clone https://github.com/rochacbruno/quokka
	```
- [PyPi](https://pypi.org/project/quokka) (📥 74 / month):
	```
	pip install quokka
	```
- [Conda](https://anaconda.org/conda-forge/quokka):
	```
	conda install -c conda-forge quokka
	```
</details>
<details><summary><b><a href="https://github.com/feincms/feincms">feincms</a></b> (🥉12 ·  ⭐ 820) - 基于 Django 构建的最先进的内容管理系统之一。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/feincms/feincms) (👨‍💻 140 · 🔀 220 · 📋 440 - 8% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/feincms/feincms
	```
- [PyPi](https://pypi.org/project/feincms):
	```
	pip install feincms
	```
- [Conda](https://anaconda.org/conda-forge/feincms):
	```
	conda install -c conda-forge feincms
	```
</details>
<br>

## 缓存

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_缓存数据的库。_

🔗&nbsp;<b><a href="http://dogpilecache.readthedocs.io/en/latest/">dogpile.cache</a></b>  - dogpile.cache 是 Beaker 的下一代替代品，由同一作者开发。

🔗&nbsp;<b><a href="https://pypi.org/project/HermesCache/">HermesCache</a></b>  - Python 缓存库，具有基于标签的失效和 dogpile effect 保护功能。

🔗&nbsp;<b><a href="http://www.grantjenks.com/docs/diskcache/">python-diskcache</a></b>  - SQLite 和文件支持的缓存后端，具有比 memcached 和 redis 更快的查找速度。

<details><summary><b><a href="https://github.com/Suor/django-cacheops">django-cacheops</a></b> (🥇26 ·  ⭐ 1.5K) - 具有自动颗粒化事件驱动失效功能的 ORM。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/django-cacheops) (👨‍💻 59 · 🔀 180 · 📦 620 · 📋 290 - 6% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/Suor/django-cacheops
	```
- [PyPi](https://pypi.org/project/django-cacheops) (📥 150K / month):
	```
	pip install django-cacheops
	```
- [Conda](https://anaconda.org/conda-forge/django-cacheops):
	```
	conda install -c conda-forge django-cacheops
	```
</details>
<details><summary><b><a href="https://github.com/lericson/pylibmc">pylibmc</a></b> (🥈25 ·  ⭐ 450) - <a href="http://libmemcached.org/libMemcached.html">libmemcached</a> 接口的 Python 封装。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lericson/pylibmc) (👨‍💻 49 · 🔀 120 · 📦 3.7K · 📋 190 - 12% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/lericson/pylibmc
	```
- [PyPi](https://pypi.org/project/pylibmc) (📥 150K / month):
	```
	pip install pylibmc
	```
- [Conda](https://anaconda.org/conda-forge/pylibmc) (📥 170K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge pylibmc
	```
</details>
<details><summary><b><a href="https://github.com/bbangert/beaker">beaker</a></b> (🥉24 ·  ⭐ 480) - 一个缓存和会话库，可以用在 web 应用和独立 Python 脚本和应用上。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/bbangert/beaker) (👨‍💻 86 · 🔀 130 · 📦 3.2K · 📋 120 - 54% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/bbangert/beaker
	```
- [PyPi](https://pypi.org/project/beaker) (📥 250K / month):
	```
	pip install beaker
	```
- [Conda](https://anaconda.org/conda-forge/beaker) (📥 56K · ⏱️ 27.08.2019):
	```
	conda install -c conda-forge beaker
	```
</details>
<details><summary><b><a href="https://github.com/django-cache-machine/django-cache-machine">django-cache-machine</a></b> (🥉22 ·  ⭐ 820 · 💀) - Django 模型的自动缓存和失效。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-cache-machine/django-cache-machine) (👨‍💻 26 · 🔀 150 · 📦 220 · 📋 71 - 21% open · ⏱️ 25.11.2019):

	```
	git clone https://github.com/django-cache-machine/django-cache-machine
	```
- [PyPi](https://pypi.org/project/django-cache-machine) (📥 10K / month):
	```
	pip install django-cache-machine
	```
- [Conda](https://anaconda.org/conda-forge/django-cache-machine):
	```
	conda install -c conda-forge django-cache-machine
	```
</details>
<br>

## 聊天工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_聊天机器人开发相关的库。_

<details><summary><b><a href="https://github.com/errbotio/errbot">errbot</a></b> (🥇19 ·  ⭐ 2.6K) - 实现 ChatOps 的最简单最受欢迎的聊天机器人。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/errbotio/errbot) (🔀 540 · 📦 240 · 📋 740 - 8% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/errbotio/errbot/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 代码分析和 Lint 工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_进行代码分析、解析和操作代码库的库和工具。_

🔗&nbsp;<b><a href="https://pypi.org/project/flake8/">flake8</a></b>  - 模块化源码检查工具，提供与 `pycodestyle`、`pyflakes` 、McCabe 相关的装饰器。

🔗&nbsp;<b><a href="https://github.com/DmytroLitvinov/awesome-flake8-extensions">awesome-flake8-extensions</a></b> ( ⭐ 690)  - A curated awesome list of flake8 extensions. Feel free to..

🔗&nbsp;<b><a href="https://www.pylint.org/">pylint</a></b>  - 一个完全可定制的源码分析器。

🔗&nbsp;<b><a href="https://github.com/typeddjango/awesome-python-typing">awesome-python-typing</a></b> ( ⭐ 920)  - Collection of awesome Python types, stubs, plugins, and tools to..

🔗&nbsp;<b><a href="http://mypy-lang.org/">mypy</a></b>  - 在编译期间检查变量类型。

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇34 ·  ⭐ 24K) - 一个坚定的 Python 代码格式化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 290 · 🔀 1.5K · 📥 19K · 📦 100K · 📋 1.8K - 19% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/python/black
	```
- [PyPi](https://pypi.org/project/black) (📥 9.9M / month):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 2.7M · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥇33 ·  ⭐ 4.4K) - 用于纠正包导入顺序的 Python 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 250 · 🔀 420 · 📦 210K · 📋 1K - 3% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/timothycrosley/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 17M / month):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 2.7M · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈31 ·  ⭐ 1.7K) - 有史以来最严格的 Python 代码审查工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 160 · 🔀 310 · 📦 880 · 📋 990 - 7% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 140K / month):
	```
	pip install wemake-python-styleguide
	```
- [Conda](https://anaconda.org/conda-forge/wemake-python-styleguide):
	```
	conda install -c conda-forge wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥈29 ·  ⭐ 12K) - Google 的 Python 代码格式化工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 130 · 🔀 800 · 📦 27K · 📋 720 - 46% open · ⏱️ 08.11.2021):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 1.7M / month):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 910K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈26 ·  ⭐ 2K) - 用于发现和分析无效 Python 代码的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 29 · 🔀 92 · 📦 1.3K · 📋 150 - 9% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 190K / month):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 51K · ⏱️ 11.08.2020):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/klen/pylama">pylama</a></b> (🥈25 ·  ⭐ 840) - Python 和 JavaScript 的代码审查工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/klen/pylama) (👨‍💻 42 · 🔀 81 · 📦 3.1K · 📋 120 - 27% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/klen/pylama
	```
- [PyPi](https://pypi.org/project/pylama) (📥 110K / month):
	```
	pip install pylama
	```
- [Conda](https://anaconda.org/conda-forge/pylama) (📥 72K · ⏱️ 18.05.2019):
	```
	conda install -c conda-forge pylama
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥉22 ·  ⭐ 5.7K) - 性能类型检查。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 190 · 🔀 350 · 📋 280 - 25% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 26K / month):
	```
	pip install pyre-check
	```
- [Conda](https://anaconda.org/conda-forge/pyre-check):
	```
	conda install -c conda-forge pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/gak/pycallgraph">pycallgraph</a></b> (🥉22 ·  ⭐ 1.6K · 💀) - 这个库可以把你的 Python 应用的流程(调用图)进行可视化。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/gak/pycallgraph) (👨‍💻 23 · 🔀 260 · 📦 330 · 📋 160 - 30% open · ⏱️ 28.02.2018):

	```
	git clone https://github.com/gak/pycallgraph
	```
- [PyPi](https://pypi.org/project/pycallgraph) (📥 25K / month):
	```
	pip install pycallgraph
	```
- [Conda](https://anaconda.org/conda-forge/pycallgraph):
	```
	conda install -c conda-forge pycallgraph
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥉22 ·  ⭐ 1.6K) - 分析 Python 代码的工具。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 78 · 🔀 140 · 📋 290 - 18% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 390K / month):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 27K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥉19 ·  ⭐ 3.6K) - 通过收集运行时的类型来为 Python 生成静态类型注释的系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 37 · 🔀 130 · 📦 160 · 📋 150 - 23% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/MonkeyType) (📥 30K / month):
	```
	pip install MonkeyType
	```
- [Conda](https://anaconda.org/conda-forge/MonkeyType) (📥 37K · ⏱️ 22.05.2021):
	```
	conda install -c conda-forge MonkeyType
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥉19 ·  ⭐ 3.3K) - 语言独立和易于扩展的代码分析应用程序。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (🔀 1.3K · 📥 150 · 📦 10 · 📋 3K - 21% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/coala/coala/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/python/typeshed">typeshed</a></b> (🥉19 ·  ⭐ 2.5K) - 带有静态类型的Python库存根的集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python/typeshed) (👨‍💻 1K · 🔀 1.2K · 📋 1.5K - 9% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/python/typeshed
	```
- [PyPi](https://pypi.org/project/typeshed):
	```
	pip install typeshed
	```
- [Conda](https://anaconda.org/conda-forge/typeshed):
	```
	conda install -c conda-forge typeshed
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥉18 ·  ⭐ 3.5K) - 检查和推断 Python 代码中的类型，无需添加注解。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 71 · 🔀 210 · 📋 470 - 20% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 150K / month):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 65K · ⏱️ 16.12.2021):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/scottrogowski/code2flow">code2flow</a></b> (🥉17 ·  ⭐ 1.6K) - 把你的 Python 和 JavaScript 代码转换为流程图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/scottrogowski/code2flow) (👨‍💻 7 · 🔀 160 · 📦 5 · 📋 27 - 11% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/scottrogowski/code2flow
	```
- [PyPi](https://pypi.org/project/code2flow) (📥 520 / month):
	```
	pip install code2flow
	```
- [Conda](https://anaconda.org/conda-forge/code2flow):
	```
	conda install -c conda-forge code2flow
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉16 ·  ⭐ 1.3K) - 自动生成符合 PEP-484 的注解。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 17 · 🔀 54 · 📦 66 · 📋 59 - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate):
	```
	pip install pyannotate
	```
- [Conda](https://anaconda.org/conda-forge/pyannotate):
	```
	conda install -c conda-forge pyannotate
	```
</details>
<br>

## 命令行工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于创建命令行程序的库。_

🔗&nbsp;<b><a href="http://builtoncement.com/">cement</a></b>  - Python 的命令行程序框架。

🔗&nbsp;<b><a href="http://click.pocoo.org/dev/">click</a></b>  - 一个通过组合的方式来创建精美命令行界面的包。

🔗&nbsp;<b><a href="https://docs.openstack.org/developer/cliff/">cliff</a></b>  - 一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。

🔗&nbsp;<b><a href="http://docopt.org/">docopt</a></b>  - Python 风格的命令行参数解析器。

🔗&nbsp;<b><a href="https://pypi.org/project/colorama/">colorama</a></b>  - 跨平台彩色终端文本。

<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇32 ·  ⭐ 21K) - 一个可在循环和命令行中使用的快速、可扩展的进度条。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 110 · 🔀 1K · 📥 8.1K · 📦 230K · 📋 800 - 32% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 9.1M · ⏱️ 20.09.2021):
	```
	conda install -c conda-forge tqdm
	```
</details>
<details><summary><b><a href="https://github.com/willmcgugan/rich">rich</a></b> (🥈31 ·  ⭐ 32K) - 一个在终端中支持富文本和格式美化的 Python 库， 同时提供了`RichHandler`日志处理程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willmcgugan/rich) (👨‍💻 140 · 🔀 1K · 📦 9.6K · 📋 620 - 3% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/willmcgugan/rich
	```
- [PyPi](https://pypi.org/project/rich):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 550K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/google/python-fire">python-fire</a></b> (🥈26 ·  ⭐ 21K) - Google 出品的一个基于 Python 类的构建命令行界面的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/python-fire) (👨‍💻 46 · 🔀 1.2K · 📦 10K · 📋 240 - 40% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/google/python-fire
	```
- [PyPi](https://pypi.org/project/python-fire) (📥 250 / month):
	```
	pip install python-fire
	```
- [Conda](https://anaconda.org/conda-forge/python-fire):
	```
	conda install -c conda-forge python-fire
	```
</details>
<details><summary><b><a href="https://github.com/peterbrittain/asciimatics">asciimatics</a></b> (🥉25 ·  ⭐ 2.9K) - 跨平台，全屏终端包（即鼠标/键盘输入和彩色，定位文本输出），完整的复杂动画和特殊效果的高级 API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/peterbrittain/asciimatics) (👨‍💻 37 · 🔀 210 · 📦 570 · 📋 260 - 6% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/peterbrittain/asciimatics
	```
- [PyPi](https://pypi.org/project/asciimatics):
	```
	pip install asciimatics
	```
- [Conda](https://anaconda.org/conda-forge/asciimatics) (📥 83K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge asciimatics
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉21 ·  ⭐ 2.9K) - 一款新的进度条，具有实时吞吐量信息以及非常酷的动画。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (🔀 130 · 📦 510 · 📋 90 - 26% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 21K / month):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 11K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/prompt-toolkit/python-prompt-toolkit">python-prompt-toolkit</a></b> (🥉18 ·  ⭐ 7.4K) - 一个用于构建强大的交互式命令行程序的库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/prompt-toolkit/python-prompt-toolkit) (👨‍💻 200 · 🔀 580 · 📋 930 - 45% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/jonathanslenders/python-prompt-toolkit
	```
- [PyPi](https://pypi.org/project/python-prompt-toolkit):
	```
	pip install python-prompt-toolkit
	```
- [Conda](https://anaconda.org/conda-forge/python-prompt-toolkit):
	```
	conda install -c conda-forge python-prompt-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/glamp/bashplotlib">bashplotlib</a></b> (🥉17 ·  ⭐ 1.6K · 💤) - 在终端中进行基本绘图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/glamp/bashplotlib) (👨‍💻 20 · 🔀 84 · 📦 140 · 📋 28 - 60% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/glamp/bashplotlib
	```
- [PyPi](https://pypi.org/project/bashplotlib):
	```
	pip install bashplotlib
	```
- [Conda](https://anaconda.org/conda-forge/bashplotlib) (📥 2.8K · ⏱️ 08.09.2018):
	```
	conda install -c conda-forge bashplotlib
	```
</details>
<br>

## 命令行工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于创建命令行程序的库。_

<details><summary><b><a href="https://github.com/httpie/httpie">httpie</a></b> (🥇33 ·  ⭐ 53K) - 一个命令行 HTTP 客户端，cURL 的替代品，易用性更好。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/httpie/httpie) (👨‍💻 140 · 🔀 3.2K · 📦 9.7K · 📋 720 - 15% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/jakubroztocil/httpie
	```
- [PyPi](https://pypi.org/project/httpie) (📥 190K / month):
	```
	pip install httpie
	```
- [Conda](https://anaconda.org/conda-forge/httpie) (📥 69K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge httpie
	```
</details>
<details><summary><b><a href="https://github.com/nvbn/thefuck">thefuck</a></b> (🥇29 ·  ⭐ 65K) - 修正你之前的命令行指令。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nvbn/thefuck) (👨‍💻 180 · 🔀 2.9K · 📦 310 · 📋 620 - 30% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/nvbn/thefuck
	```
- [PyPi](https://pypi.org/project/thefuck) (📥 5.8K / month):
	```
	pip install thefuck
	```
- [Conda](https://anaconda.org/conda-forge/thefuck):
	```
	conda install -c conda-forge thefuck
	```
</details>
<details><summary><b><a href="https://github.com/dbcli/pgcli">pgcli</a></b> (🥇29 ·  ⭐ 10K) - 支持自动补全和语法高亮的 Postgres 命令行工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dbcli/pgcli) (👨‍💻 160 · 🔀 440 · 📦 370 · 📋 610 - 20% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/dbcli/pgcli
	```
- [PyPi](https://pypi.org/project/pgcli) (📥 160K / month):
	```
	pip install pgcli
	```
- [Conda](https://anaconda.org/conda-forge/pgcli) (📥 110K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge pgcli
	```
</details>
<details><summary><b><a href="https://github.com/cookiecutter/cookiecutter">cookiecutter</a></b> (🥈25 ·  ⭐ 16K) - 从 cookiecutters（项目模板）创建项目的一个命令行工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cookiecutter/cookiecutter) (👨‍💻 260 · 🔀 1.5K · 📋 680 - 26% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/audreyr/cookiecutter
	```
- [PyPi](https://pypi.org/project/cookiecutter):
	```
	pip install cookiecutter
	```
- [Conda](https://anaconda.org/conda-forge/cookiecutter) (📥 230K · ⏱️ 17.05.2021):
	```
	conda install -c conda-forge cookiecutter
	```
</details>
<details><summary><b><a href="https://github.com/dbcli/mycli">mycli</a></b> (🥈25 ·  ⭐ 10K · 💤) - 支持自动补全和语法高亮的 MySQL 命令行客户端<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dbcli/mycli) (👨‍💻 95 · 🔀 600 · 📦 220 · 📋 570 - 28% open · ⏱️ 09.05.2021):

	```
	git clone https://github.com/dbcli/mycli
	```
- [PyPi](https://pypi.org/project/mycli) (📥 26K / month):
	```
	pip install mycli
	```
- [Conda](https://anaconda.org/conda-forge/mycli) (📥 22K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge mycli
	```
</details>
<details><summary><b><a href="https://github.com/laixintao/iredis">iredis</a></b> (🥈22 ·  ⭐ 1.7K) - 支持自动补全和高亮显示的 redis 命令行工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/laixintao/iredis) (👨‍💻 25 · 🔀 76 · 📥 7.5K · 📋 190 - 30% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/laixintao/iredis
	```
- [PyPi](https://pypi.org/project/iredis) (📥 1.1K / month):
	```
	pip install iredis
	```
- [Conda](https://anaconda.org/conda-forge/iredis):
	```
	conda install -c conda-forge iredis
	```
</details>
<details><summary><b><a href="https://github.com/gleitz/howdoi">howdoi</a></b> (🥈21 ·  ⭐ 9.2K) - 通过命令行获取即时的编程问题解答。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gleitz/howdoi) (👨‍💻 79 · 🔀 810 · 📦 380 · 📋 240 - 7% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/gleitz/howdoi
	```
- [PyPi](https://pypi.org/project/howdoi):
	```
	pip install howdoi
	```
- [Conda](https://anaconda.org/conda-forge/howdoi):
	```
	conda install -c conda-forge howdoi
	```
</details>
<details><summary><b><a href="https://github.com/tmux-python/tmuxp">tmuxp</a></b> (🥉20 ·  ⭐ 3.3K) -  <a href="https://github.com/tmux/tmux">tmux</a> 会话管理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tmux-python/tmuxp) (👨‍💻 61 · 🔀 200 · 📋 280 - 20% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/tony/tmuxp
	```
- [PyPi](https://pypi.org/project/tmuxp):
	```
	pip install tmuxp
	```
- [Conda](https://anaconda.org/conda-forge/tmuxp):
	```
	conda install -c conda-forge tmuxp
	```
</details>
<details><summary><b><a href="https://github.com/donnemartin/saws">saws</a></b> (🥉19 ·  ⭐ 4.9K) - 一个加强版的 AWS 命令行。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/donnemartin/saws) (👨‍💻 8 · 🔀 260 · 📦 36 · 📋 91 - 31% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/donnemartin/saws
	```
- [PyPi](https://pypi.org/project/saws) (📥 420 / month):
	```
	pip install saws
	```
- [Conda](https://anaconda.org/conda-forge/saws) (📥 19K · ⏱️ 16.03.2020):
	```
	conda install -c conda-forge saws
	```
</details>
<details><summary><b><a href="https://github.com/dbcli/litecli">litecli</a></b> (🥉19 ·  ⭐ 1.5K) - 支持自动补全和语法高亮的 SQLite 命令行工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dbcli/litecli) (👨‍💻 20 · 🔀 51 · 📦 130 · 📋 71 - 32% open · ⏱️ 11.09.2021):

	```
	git clone https://github.com/dbcli/litecli
	```
- [PyPi](https://pypi.org/project/litecli) (📥 7.3K / month):
	```
	pip install litecli
	```
- [Conda](https://anaconda.org/conda-forge/litecli):
	```
	conda install -c conda-forge litecli
	```
</details>
<details><summary><b><a href="https://github.com/mooz/percol">percol</a></b> (🥉18 ·  ⭐ 3.1K · 💀) - 向 UNIX shell 传统管道概念中加入交互式选择功能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mooz/percol) (👨‍💻 36 · 🔀 140 · 📦 29 · 📋 65 - 55% open · ⏱️ 23.07.2019):

	```
	git clone https://github.com/mooz/percol
	```
- [PyPi](https://pypi.org/project/percol) (📥 1.8K / month):
	```
	pip install percol
	```
- [Conda](https://anaconda.org/conda-forge/percol):
	```
	conda install -c conda-forge percol
	```
</details>
<details><summary><b><a href="https://github.com/cloudnativelabs/kube-shell">kube-shell</a></b> (🥉18 ·  ⭐ 2K · 💀) - K8S 命令行集成的 shell 工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cloudnativelabs/kube-shell) (👨‍💻 6 · 🔀 160 · 📥 520 · 📦 13 · 📋 69 - 82% open · ⏱️ 19.09.2018):

	```
	git clone https://github.com/cloudnativelabs/kube-shell
	```
- [PyPi](https://pypi.org/project/kube-shell) (📥 480 / month):
	```
	pip install kube-shell
	```
- [Conda](https://anaconda.org/conda-forge/kube-shell):
	```
	conda install -c conda-forge kube-shell
	```
</details>
<details><summary><b><a href="https://github.com/copier-org/copier">copier</a></b> (🥉18 ·  ⭐ 460) - 用于呈现项目模板的库和命令行实用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/copier-org/copier) (👨‍💻 24 · 🔀 44 · 📦 34 · 📋 220 - 13% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/pykong/copier
	```
- [PyPi](https://pypi.org/project/copier):
	```
	pip install copier
	```
- [Conda](https://anaconda.org/conda-forge/copier):
	```
	conda install -c conda-forge copier
	```
</details>
<details><summary><b><a href="https://github.com/facebook/PathPicker">PathPicker</a></b> (🥉17 ·  ⭐ 4.7K) - 从 bash 输出中选出文件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/PathPicker) (👨‍💻 74 · 🔀 260 · 📥 44K · 📋 160 - 9% open · ⏱️ 05.07.2021):

	```
	git clone https://github.com/facebook/PathPicker
	```
- [PyPi](https://pypi.org/project/PathPicker):
	```
	pip install PathPicker
	```
- [Conda](https://anaconda.org/conda-forge/PathPicker):
	```
	conda install -c conda-forge PathPicker
	```
</details>
<details><summary><b><a href="https://github.com/sloria/doitlive">doitlive</a></b> (🥉13 ·  ⭐ 3.1K · 💤) - 一个用来在终端中进行现场演示的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/doitlive) (👨‍💻 16 · 🔀 90 · 📦 16 · 📋 47 - 27% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/sloria/doitlive
	```
- [PyPi](https://pypi.org/project/doitlive):
	```
	pip install doitlive
	```
- [Conda](https://anaconda.org/conda-forge/doitlive):
	```
	conda install -c conda-forge doitlive
	```
</details>
<details><summary><b><a href="https://github.com/timofurrer/try">try</a></b> (🥉13 ·  ⭐ 610 · 💀) - 一个极其简单的命令行工具，用来试用 python 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timofurrer/try) (👨‍💻 3 · 🔀 29 · 📦 4 · 📋 12 - 25% open · ⏱️ 04.12.2019):

	```
	git clone https://github.com/timofurrer/try
	```
- [PyPi](https://pypi.org/project/try):
	```
	pip install try
	```
- [Conda](https://anaconda.org/conda-forge/try):
	```
	conda install -c conda-forge try
	```
</details>
<br>

## 兼容性

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_帮助从 Python 2 向 Python 3 迁移的库。_

🔗&nbsp;<b><a href="http://python-future.org/index.html">python-future</a></b>  - 这就是 Python 2 和 Python 3 之间丢失的那个兼容性层。

🔗&nbsp;<b><a href="https://pypi.org/project/six/">six</a></b>  - Python 2 和 3 的兼容性工具。

<details><summary><b><a href="https://github.com/PyCQA/modernize">modernize</a></b> (🥇17 ·  ⭐ 270 · 💤) - 使 Python 代码更加现代化以便最终迁移到 Python 3。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/PyCQA/modernize) (👨‍💻 32 · 🔀 44 · 📋 130 - 34% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/PyCQA/modernize
	```
- [PyPi](https://pypi.org/project/modernize) (📥 29K / month):
	```
	pip install modernize
	```
- [Conda](https://anaconda.org/conda-forge/modernize) (📥 24K · ⏱️ 04.10.2020):
	```
	conda install -c conda-forge modernize
	```
</details>
<br>

## 计算机视觉

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_计算机视觉相关库。_

🔗&nbsp;<b><a href="https://opencv.org/">OpenCV</a></b>  - 开源计算机视觉库。

<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇30 ·  ⭐ 13K) - 支持40多种语言的即用型 OCR。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 90 · 🔀 1.7K · 📥 900K · 📦 760 · 📋 470 - 30% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/EasyOCR) (📥 120K / month):
	```
	pip install EasyOCR
	```
- [Conda](https://anaconda.org/conda-forge/EasyOCR):
	```
	conda install -c conda-forge EasyOCR
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈25 ·  ⭐ 43K) - 简单的面部识别库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 47 · 🔀 12K · 📥 450 · 📋 1.2K - 53% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 51K / month):
	```
	pip install face_recognition
	```
- [Conda](https://anaconda.org/conda-forge/face_recognition) (📥 3.9K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈25 ·  ⭐ 1.6K) - 另一个简单的，兼容 Pillow 的 `tesseract-ocr` API 装饰器，可用于 OCR。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 26 · 🔀 200 · 📦 580 · 📋 230 - 31% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 62K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">pytesseract</a></b> (🥉24 ·  ⭐ 3.9K) - <a href="https://github.com/tesseract-ocr">Google Tesseract OCR</a> 的另一包装库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 38 · 🔀 560 · 📋 280 - 3% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 780K / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 480K · ⏱️ 05.06.2021):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/sightmachine/SimpleCV">SimpleCV</a></b> (🥉23 ·  ⭐ 2.5K · 💀) - 一个用来创建计算机视觉应用的开源框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/sightmachine/SimpleCV) (👨‍💻 100 · 🔀 750 · 📦 340 · 📋 330 - 22% open · ⏱️ 07.04.2015):

	```
	git clone https://github.com/sightmachine/SimpleCV
	```
- [PyPi](https://pypi.org/project/SimpleCV) (📥 1.3K / month):
	```
	pip install SimpleCV
	```
- [Conda](https://anaconda.org/conda-forge/SimpleCV):
	```
	conda install -c conda-forge SimpleCV
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥉22 ·  ⭐ 5.6K) - PyTorch 的开源差异化计算机视觉库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kornia/kornia) (🔀 540 · 📥 170 · 📦 860 · 📋 500 - 22% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/kornia/kornia/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 并发和并行

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用以进行并发和并行操作的库。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/concurrent.futures.html">concurrent.futures</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="http://eventlet.net/">eventlet</a></b>  - 支持 WSGI 的异步框架。

🔗&nbsp;<b><a href="http://www.gevent.org/">gevent</a></b>  - 使用 <a href="https://github.com/python-greenlet/greenlet">greenlet</a> 且基于协程的 Python 网络库。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/multiprocessing.html">multiprocessing</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

<details><summary><b><a href="https://github.com/soravux/scoop">scoop</a></b> (🥇15 ·  ⭐ 530 · 💀) - 支持在 Python 中进行可伸缩并行操作。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/soravux/scoop) (👨‍💻 18 · 🔀 81 · 📦 210 · 📋 72 - 43% open · ⏱️ 07.12.2019):

	```
	git clone https://github.com/soravux/scoop
	```
- [PyPi](https://pypi.org/project/scoop):
	```
	pip install scoop
	```
- [Conda](https://anaconda.org/conda-forge/scoop):
	```
	conda install -c conda-forge scoop
	```
</details>
<br>

## 配置

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来保存和解析配置的库。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/configparser.html">configparser</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://profig.readthedocs.io/en/latest/">profig</a></b>  - 通过多种格式进行配置，具有数值转换功能。

<details><summary><b><a href="https://github.com/henriquebastos/python-decouple">python-decouple</a></b> (🥇30 ·  ⭐ 2K) - 将设置和代码完全隔离。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/henriquebastos/python-decouple) (👨‍💻 29 · 🔀 140 · 📥 5 · 📦 54K · 📋 72 - 9% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/henriquebastos/python-decouple
	```
- [PyPi](https://pypi.org/project/python-decouple) (📥 580K / month):
	```
	pip install python-decouple
	```
- [Conda](https://anaconda.org/conda-forge/python-decouple) (📥 34K · ⏱️ 05.01.2021):
	```
	conda install -c conda-forge python-decouple
	```
</details>
<details><summary><b><a href="https://github.com/DiffSK/configobj">configobj</a></b> (🥉25 ·  ⭐ 260 · 💀) - INI 文件解析器，带验证功能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/DiffSK/configobj) (👨‍💻 22 · 🔀 63 · 📦 17K · 📋 140 - 48% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/DiffSK/configobj
	```
- [PyPi](https://pypi.org/project/configobj) (📥 1.6M / month):
	```
	pip install configobj
	```
- [Conda](https://anaconda.org/conda-forge/configobj) (📥 330K · ⏱️ 29.07.2018):
	```
	conda install -c conda-forge configobj
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hydra">hydra</a></b> (🥉22 ·  ⭐ 5.2K) - 一个优雅地配置复杂应用程序的框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hydra) (👨‍💻 83 · 🔀 380 · 📦 5 · 📋 950 - 10% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/facebookresearch/hydra
	```
- [PyPi](https://pypi.org/project/hydra) (📥 8.1K / month):
	```
	pip install hydra
	```
- [Conda](https://anaconda.org/conda-forge/hydra) (📥 9K · ⏱️ 18.01.2021):
	```
	conda install -c conda-forge hydra
	```
</details>
<br>

## 密码学

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_ [cryptography](https://cryptography.io/en/latest/)：这个软件包意在提供密码学基本内容和方法提供给 Python 开发者。 [hashids](https://github.com/davidaurelio/hashids-python)：在 Python 中实现 [hashids](http://hashids.org/) 。_

🔗&nbsp;<b><a href="https://cryptography.io/en/latest/">cryptography</a></b>  - A package designed to expose cryptographic primitives and recipes to Python developers.

🔗&nbsp;<b><a href="https://passlib.readthedocs.io/en/stable/">passlib</a></b>  - 安全密码存储／哈希库。

<details><summary><b><a href="https://github.com/paramiko/paramiko">paramiko</a></b> (🥇30 ·  ⭐ 7.4K) - SSHv2 协议的 Python (2.6+, 3.3+) ，提供客户端和服务端的功能。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/paramiko/paramiko) (👨‍💻 160 · 🔀 1.7K · 📦 51K · 📋 1.3K - 53% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/paramiko/paramiko
	```
- [PyPi](https://pypi.org/project/paramiko) (📥 21M / month):
	```
	pip install paramiko
	```
- [Conda](https://anaconda.org/conda-forge/paramiko) (📥 1.5M · ⏱️ 29.11.2021):
	```
	conda install -c conda-forge paramiko
	```
</details>
<details><summary><b><a href="https://github.com/pyca/pynacl">pynacl</a></b> (🥉21 ·  ⭐ 830) - 网络和密码学(NaCl) 库的 Python 绑定。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pyca/pynacl) (👨‍💻 62 · 🔀 190 · 📋 270 - 16% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/pyca/pynacl
	```
- [PyPi](https://pypi.org/project/pynacl) (📥 23M / month):
	```
	pip install pynacl
	```
- [Conda](https://anaconda.org/conda-forge/pynacl) (📥 2M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge pynacl
	```
</details>
<br>

## 科学计算和数据分析

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行科学计算和数据分析的库。_

🔗&nbsp;<b><a href="https://orange.biolab.si/">Orange</a></b>  - 通过可视化编程或 Python 脚本进行数据挖掘，数据可视化，分析和机器学习。

🔗&nbsp;<b><a href="http://pandas.pydata.org/">Pandas</a></b>  - 提供高性能，易用的数据结构和数据分析工具。

<details><summary><b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥇26 ·  ⭐ 3K · 💀) - NumPy 和 Pandas 的大数据接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/blaze/blaze) (👨‍💻 64 · 🔀 350 · 📦 8K · 📋 750 - 33% open · ⏱️ 15.08.2019):

	```
	git clone https://github.com/blaze/blaze
	```
- [PyPi](https://pypi.org/project/blaze) (📥 11K / month):
	```
	pip install blaze
	```
- [Conda](https://anaconda.org/conda-forge/blaze) (📥 200K · ⏱️ 15.07.2018):
	```
	conda install -c conda-forge blaze
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/aws-data-wrangler">AWS Data Wrangler</a></b> (🥈20 ·  ⭐ 2.4K) - AWS 平台上使用的 Pandas。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/awslabs/aws-data-wrangler) (👨‍💻 87 · 🔀 380 · 📥 110K · 📋 560 - 5% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/awslabs/aws-data-wrangler
	```
- [PyPi](https://pypi.org/project/aws-data-wrangler):
	```
	pip install aws-data-wrangler
	```
- [Conda](https://anaconda.org/conda-forge/aws-data-wrangler):
	```
	conda install -c conda-forge aws-data-wrangler
	```
</details>
<details><summary><b><a href="https://github.com/mining/mining">Open Mining</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - 使用 Python 挖掘商业情报 (BI) (Pandas web 接口)。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mining/mining) (👨‍💻 14 · 🔀 220 · 📦 7 · 📋 180 - 36% open · ⏱️ 02.12.2016):

	```
	git clone https://github.com/mining/mining
	```
- [PyPi](https://pypi.org/project/mining) (📥 68 / month):
	```
	pip install mining
	```
- [Conda](https://anaconda.org/conda-forge/mining):
	```
	conda install -c conda-forge mining
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉15 ·  ⭐ 1.2K) - 在使用 PySpark 时，让敏捷数据科学工作流程变得简单。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 23 · 🔀 200 · 📋 220 - 13% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/ironmussa/Optimus
	```
- [PyPi](https://pypi.org/project/Optimus):
	```
	pip install Optimus
	```
- [Conda](https://anaconda.org/conda-forge/Optimus):
	```
	conda install -c conda-forge Optimus
	```
</details>
<br>

## 数据验证

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_数据验证库。多用于表单验证。_

🔗&nbsp;<b><a href="https://docs.pylonsproject.org/projects/colander/en/latest/">colander</a></b>  - 一个用于对从 XML, JSON，HTML 表单获取的数据或其他同样简单的序列化数据进行验证和反序列化的系统。

<details><summary><b><a href="https://github.com/Julian/jsonschema">jsonschema</a></b> (🥇30 ·  ⭐ 3.5K) - <a href="http://json-schema.org/">JSON Schema</a> 的 python 实现，用于 JSON 数据的验证。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Julian/jsonschema) (👨‍💻 96 · 🔀 480 · 📦 190K · 📋 620 - 9% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/Julian/jsonschema
	```
- [PyPi](https://pypi.org/project/jsonschema):
	```
	pip install jsonschema
	```
- [Conda](https://anaconda.org/conda-forge/jsonschema) (📥 9M · ⏱️ 20.12.2021):
	```
	conda install -c conda-forge jsonschema
	```
</details>
<details><summary><b><a href="https://github.com/alecthomas/voluptuous">voluptuous</a></b> (🥇30 ·  ⭐ 1.7K) - 一个 Python 数据验证库。主要是为了验证传入 Python 的 JSON，YAML 等数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alecthomas/voluptuous) (👨‍💻 87 · 🔀 190 · 📦 4.1K · 📋 230 - 16% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/alecthomas/voluptuous
	```
- [PyPi](https://pypi.org/project/voluptuous) (📥 1.4M / month):
	```
	pip install voluptuous
	```
- [Conda](https://anaconda.org/conda-forge/voluptuous) (📥 140K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge voluptuous
	```
</details>
<details><summary><b><a href="https://github.com/pyeve/cerberus">Cerberus</a></b> (🥈27 ·  ⭐ 2.6K · 💤) - 一个映射验证器（mappings-validator）。支持多种规则，提供归一化功能，可以方便地定制为 Python 风格的 schema 定义。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/pyeve/cerberus) (👨‍💻 62 · 🔀 210 · 📦 10K · 📋 320 - 10% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/pyeve/cerberus
	```
- [PyPi](https://pypi.org/project/cerberus):
	```
	pip install cerberus
	```
- [Conda](https://anaconda.org/conda-forge/cerberus) (📥 170K · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge cerberus
	```
</details>
<details><summary><b><a href="https://github.com/keleshev/schema">schema</a></b> (🥈27 ·  ⭐ 2.5K) - 一个用于对 Python 数据结构进行验证的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keleshev/schema) (👨‍💻 62 · 🔀 170 · 📦 3.4K · 📋 130 - 49% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/keleshev/schema
	```
- [PyPi](https://pypi.org/project/schema):
	```
	pip install schema
	```
- [Conda](https://anaconda.org/conda-forge/schema) (📥 38K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge schema
	```
</details>
<details><summary><b><a href="https://github.com/schematics/schematics">Schematics</a></b> (🥉24 ·  ⭐ 2.5K) - 数据结构验证。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/schematics/schematics) (👨‍💻 120 · 🔀 280 · 📦 1K · 📋 320 - 27% open · ⏱️ 17.08.2021):

	```
	git clone https://github.com/schematics/schematics
	```
- [PyPi](https://pypi.org/project/schematics) (📥 160K / month):
	```
	pip install schematics
	```
- [Conda](https://anaconda.org/conda-forge/schematics) (📥 23K · ⏱️ 17.07.2019):
	```
	conda install -c conda-forge schematics
	```
</details>
<details><summary><b><a href="https://github.com/podio/valideer">valideer</a></b> (🥉18 ·  ⭐ 250 · 💀) - 轻量级可扩展的数据验证和适配库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/podio/valideer) (👨‍💻 7 · 🔀 20 · 📦 50 · 📋 15 - 26% open · ⏱️ 07.03.2018):

	```
	git clone https://github.com/podio/valideer
	```
- [PyPi](https://pypi.org/project/valideer) (📥 13K / month):
	```
	pip install valideer
	```
- [Conda](https://anaconda.org/conda-forge/valideer) (📥 17K · ⏱️ 06.07.2018):
	```
	conda install -c conda-forge valideer
	```
</details>
<br>

## 数据可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_进行数据可视化的库。 参见：[awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization)。_

🔗&nbsp;<b><a href="https://plot.ly/products/dash/">Dash</a></b>  - 构建在 Flask、React 和 Plotly之上，旨在用于分析 Web 应用程序。

🔗&nbsp;<b><a href="https://github.com/ucg8j/awesome-dash">awesome-dash</a></b> ( ⭐ 1.4K)  - A curated list of awesome Dash (plotly) resources.

🔗&nbsp;<b><a href="http://matplotlib.org/">Matplotlib</a></b>  - 一个 Python 2D 绘图库。

🔗&nbsp;<b><a href="http://www.pygal.org/en/latest/">Pygal</a></b>  - 一个 Python SVG 图表创建工具。

🔗&nbsp;<b><a href="https://pypi.org/project/pygraphviz/">PyGraphviz</a></b>  -  <a href="http://www.graphviz.org/">Graphviz</a> 的 Python 接口。

🔗&nbsp;<b><a href="http://www.pyqtgraph.org/">PyQtGraph</a></b>  - 交互式实时 2D/3D/ 图像绘制及科学/工程学组件。

<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇38 ·  ⭐ 9K) - 使用 Matplotlib 进行统计数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 160 · 🔀 1.5K · 📥 210 · 📦 130K · 📋 1.9K - 4% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 6.5M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 3.2M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥈33 ·  ⭐ 7.1K) - 用于 Python 的声明式统计可视化库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 130 · 🔀 600 · 📦 20K · 📋 1.6K - 14% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 3.9M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 1M · ⏱️ 01.04.2020):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥈30 ·  ⭐ 16K) - 用 Python 进行交互式 web 绘图。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 590 · 🔀 3.8K · 📦 42K · 📋 6.8K - 10% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 6.3M · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/SciTools/cartopy">Cartopy</a></b> (🥉28 ·  ⭐ 980) - 具有 matplotlib 支持的 python 制图库。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/SciTools/cartopy) (👨‍💻 110 · 🔀 300 · 📦 2.1K · 📋 1K - 26% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/SciTools/cartopy
	```
- [PyPi](https://pypi.org/project/cartopy) (📥 120K / month):
	```
	pip install cartopy
	```
- [Conda](https://anaconda.org/conda-forge/cartopy) (📥 1.9M · ⏱️ 20.11.2021):
	```
	conda install -c conda-forge cartopy
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥉27 ·  ⭐ 2.9K) - 基于ggplot2的Python图形语法。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 89 · 🔀 150 · 📦 2.8K · 📋 460 - 17% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 190K / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 140K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥉26 ·  ⭐ 3.2K) - Jupyter Notebook的交互式绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 55 · 🔀 430 · 📦 28 · 📋 550 - 35% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/bloomberg/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 910K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge bqplot
	```
</details>
<details><summary><b><a href="https://github.com/mingrammer/diagrams">diagrams</a></b> (🥉24 ·  ⭐ 16K) - 用图表作为代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mingrammer/diagrams) (👨‍💻 97 · 🔀 870 · 📋 310 - 56% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/mingrammer/diagrams
	```
- [PyPi](https://pypi.org/project/diagrams) (📥 55K / month):
	```
	pip install diagrams
	```
- [Conda](https://anaconda.org/conda-forge/diagrams) (📥 100K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge diagrams
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥉24 ·  ⭐ 2.8K) - 基于 OpenGL 的高性能科学可视化工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 170 · 🔀 570 · 📦 650 · 📋 1.3K - 20% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy) (📥 46K / month):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 200K · ⏱️ 24.11.2021):
	```
	conda install -c conda-forge vispy
	```
</details>
<br>

## 数据库

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Python 实现的数据库。_

<details><summary><b><a href="https://github.com/msiemens/tinydb">tinydb</a></b> (🥇24 ·  ⭐ 4.7K) - 一个微型的，面向文档型数据库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/msiemens/tinydb) (👨‍💻 71 · 🔀 410 · 📋 270 - 2% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/msiemens/tinydb
	```
- [PyPi](https://pypi.org/project/tinydb) (📥 300K / month):
	```
	pip install tinydb
	```
- [Conda](https://anaconda.org/conda-forge/tinydb) (📥 150K · ⏱️ 23.09.2021):
	```
	conda install -c conda-forge tinydb
	```
</details>
<details><summary><b><a href="https://github.com/zopefoundation/ZODB">ZODB</a></b> (🥉22 ·  ⭐ 510) - 一个 Python 原生对象数据库。一个键值和对象图数据库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/zopefoundation/ZODB) (👨‍💻 120 · 🔀 70 · 📦 780 · 📋 140 - 37% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/zopefoundation/ZODB
	```
- [PyPi](https://pypi.org/project/ZODB) (📥 51K / month):
	```
	pip install ZODB
	```
- [Conda](https://anaconda.org/conda-forge/ZODB) (📥 46K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge ZODB
	```
</details>
<details><summary><b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉20 ·  ⭐ 620 · 💀) - 一个简单，轻量级键值储存数据库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/patx/pickledb) (👨‍💻 12 · 🔀 100 · 📦 790 · 📋 54 - 27% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/patx/pickledb
	```
- [PyPi](https://pypi.org/project/pickledb) (📥 14K / month):
	```
	pip install pickledb
	```
- [Conda](https://anaconda.org/conda-forge/pickledb) (📥 2.5K · ⏱️ 17.04.2019):
	```
	conda install -c conda-forge pickledb
	```
</details>
<br>

## 数据库 Drivers

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来连接和操作数据库的库。_

🔗&nbsp;<b><a href="https://github.com/dhamaniasad/awesome-postgres">awesome-postgres</a></b> ( ⭐ 7.5K)  - A curated list of awesome PostgreSQL software, libraries, tools and..

🔗&nbsp;<b><a href="http://initd.org/psycopg/">psycopg2</a></b>  - Python 中最流行的 PostgreSQL 适配器。

🔗&nbsp;<b><a href="https://github.com/planetopendata/awesome-sqlite">awesome-sqlite</a></b> ( ⭐ 160)  - A collection of awesome sqlite tools, scripts, books, etc.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/sqlite3.html">sqlite3</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://pymssql.readthedocs.io/en/latest/">pymssql</a></b>  - 一个简单的 Microsoft SQL Server 数据库接口。

🔗&nbsp;<b><a href="https://py2neo.org/">py2neo</a></b>  - Neo4j restful 接口的 Python 封装客户端。

<details><summary><b><a href="https://github.com/redis/redis-py">redis-py</a></b> (🥇35 ·  ⭐ 9.9K · 📈) - Redis 的 Python 客户端。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/redis/redis-py) (👨‍💻 290 · 🔀 2K · 📦 130K · 📋 1K - 6% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/andymccurdy/redis-py
	```
- [PyPi](https://pypi.org/project/redis-py):
	```
	pip install redis-py
	```
- [Conda](https://anaconda.org/conda-forge/redis-py) (📥 540K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge redis-py
	```
</details>
<details><summary><b><a href="https://github.com/PyMySQL/PyMySQL">PyMySQL</a></b> (🥇31 ·  ⭐ 6.7K) - 纯 Python MySQL 驱动，兼容 mysql-python。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyMySQL/PyMySQL) (👨‍💻 110 · 🔀 1.3K · 📦 100K · 📋 590 - 3% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/PyMySQL/PyMySQL
	```
- [PyPi](https://pypi.org/project/PyMySQL) (📥 15M / month):
	```
	pip install PyMySQL
	```
- [Conda](https://anaconda.org/conda-forge/PyMySQL) (📥 430K · ⏱️ 09.01.2021):
	```
	conda install -c conda-forge PyMySQL
	```
</details>
<details><summary><b><a href="https://github.com/dpkp/kafka-python">kafka-python</a></b> (🥈30 ·  ⭐ 4.7K) - Apache Kafka Python 客户端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dpkp/kafka-python) (👨‍💻 210 · 🔀 1.2K · 📥 1.7K · 📦 8.7K · 📋 1.4K - 14% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/dpkp/kafka-python
	```
- [PyPi](https://pypi.org/project/kafka-python):
	```
	pip install kafka-python
	```
- [Conda](https://anaconda.org/conda-forge/kafka-python) (📥 260K · ⏱️ 30.09.2020):
	```
	conda install -c conda-forge kafka-python
	```
</details>
<details><summary><b><a href="https://github.com/mongodb/motor">motor</a></b> (🥈28 ·  ⭐ 1.8K) - 支持 MongoDB 的异步 Python 驱动程序。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mongodb/motor) (👨‍💻 35 · 🔀 160 · 📦 16K · ⏱️ 09.11.2021):

	```
	git clone https://github.com/mongodb/motor
	```
- [PyPi](https://pypi.org/project/motor):
	```
	pip install motor
	```
- [Conda](https://anaconda.org/conda-forge/motor) (📥 17K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge motor
	```
</details>
<details><summary><b><a href="https://github.com/datastax/python-driver">cassandra-driver</a></b> (🥈23 ·  ⭐ 1.3K) - The Python Driver for Apache Cassandra. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/datastax/python-driver) (👨‍💻 180 · 🔀 430 · 📦 3.4K · ⏱️ 23.11.2021):

	```
	git clone https://github.com/datastax/python-driver
	```
- [PyPi](https://pypi.org/project/python-driver):
	```
	pip install python-driver
	```
- [Conda](https://anaconda.org/conda-forge/python-driver):
	```
	conda install -c conda-forge python-driver
	```
</details>
<details><summary><b><a href="https://github.com/mymarilyn/clickhouse-driver">clickhouse-driver</a></b> (🥈23 ·  ⭐ 740) - Python driver with native interface for ClickHouse. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mymarilyn/clickhouse-driver) (👨‍💻 34 · 🔀 130 · 📦 430 · 📋 210 - 13% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/mymarilyn/clickhouse-driver
	```
- [PyPi](https://pypi.org/project/clickhouse-driver) (📥 490K / month):
	```
	pip install clickhouse-driver
	```
- [Conda](https://anaconda.org/conda-forge/clickhouse-driver) (📥 260K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge clickhouse-driver
	```
</details>
<details><summary><b><a href="https://github.com/mongodb/mongo-python-driver">pymongo</a></b> (🥉21 ·  ⭐ 3.5K) - MongoDB 的官方 Python 客户端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mongodb/mongo-python-driver) (👨‍💻 190 · 🔀 920 · ⏱️ 20.12.2021):

	```
	git clone https://github.com/mongodb/mongo-python-driver
	```
- [PyPi](https://pypi.org/project/mongo-python-driver):
	```
	pip install mongo-python-driver
	```
- [Conda](https://anaconda.org/conda-forge/mongo-python-driver):
	```
	conda install -c conda-forge mongo-python-driver
	```
</details>
<details><summary><b><a href="https://github.com/gmr/queries">queries</a></b> (🥉20 ·  ⭐ 240) - psycopg2 库的封装，用来和 PostgreSQL 进行交互。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gmr/queries) (👨‍💻 11 · 🔀 29 · 📦 100 · 📋 18 - 27% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/gmr/queries
	```
- [PyPi](https://pypi.org/project/queries) (📥 2.5K / month):
	```
	pip install queries
	```
- [Conda](https://anaconda.org/conda-forge/queries):
	```
	conda install -c conda-forge queries
	```
</details>
<details><summary><b><a href="https://github.com/python-happybase/happybase">happybase</a></b> (🥉18 ·  ⭐ 580 · 💤) - 一个为 Apache HBase 设计的，对开发者友好的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-happybase/happybase) (👨‍💻 19 · 🔀 150 · 📦 570 · 📋 200 - 10% open · ⏱️ 08.02.2021):

	```
	git clone https://github.com/wbolster/happybase
	```
- [PyPi](https://pypi.org/project/happybase):
	```
	pip install happybase
	```
- [Conda](https://anaconda.org/conda-forge/happybase) (📥 70K · ⏱️ 01.07.2019):
	```
	conda install -c conda-forge happybase
	```
</details>
<details><summary><b><a href="https://github.com/PyMySQL/mysqlclient">mysqlclient</a></b> (🥉17 ·  ⭐ 2K) - MySQL connector with Python 3 support ([mysql-.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyMySQL/mysqlclient) (👨‍💻 69 · 🔀 320 · 📥 5.2K · 📋 270 - 3% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/PyMySQL/mysqlclient-python
	```
- [PyPi](https://pypi.org/project/mysqlclient-python):
	```
	pip install mysqlclient-python
	```
- [Conda](https://anaconda.org/conda-forge/mysqlclient-python):
	```
	conda install -c conda-forge mysqlclient-python
	```
</details>
<details><summary><b><a href="https://github.com/plasticityai/supersqlite">SuperSQLite</a></b> (🥉16 ·  ⭐ 680 · 💀) - A supercharged SQLite library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plasticityai/supersqlite) (👨‍💻 2 · 🔀 21 · 📦 9 · 📋 6 - 83% open · ⏱️ 27.08.2019):

	```
	git clone https://github.com/plasticityai/supersqlite
	```
- [PyPi](https://pypi.org/project/supersqlite) (📥 210 / month):
	```
	pip install supersqlite
	```
- [Conda](https://anaconda.org/conda-forge/supersqlite):
	```
	conda install -c conda-forge supersqlite
	```
</details>
<br>

## 日期和时间

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_操作日期和时间的类库。_

🔗&nbsp;<b><a href="https://arrow.readthedocs.io/en/latest/">Arrow</a></b>  - 更好的 Python 日期时间操作类库。

🔗&nbsp;<b><a href="https://launchpad.net/pytz">pytz</a></b>  - 支持跨平台时区计算，并将 <a href="https://en.wikipedia.org/wiki/Tz_database">tz database</a> 引入 Python。

<details><summary><b><a href="https://github.com/dateutil/dateutil">dateutil</a></b> (🥇29 ·  ⭐ 1.7K) - Python 标准包 <a href="https://docs.python.org/3/library/datetime.html">datetime</a> 的扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dateutil/dateutil) (👨‍💻 130 · 🔀 380 · 📥 35K · 📦 620K · 📋 590 - 37% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dateutil/dateutil
	```
- [PyPi](https://pypi.org/project/dateutil):
	```
	pip install dateutil
	```
- [Conda](https://anaconda.org/conda-forge/dateutil):
	```
	conda install -c conda-forge dateutil
	```
</details>
<details><summary><b><a href="https://github.com/sdispater/pendulum">Pendulum</a></b> (🥈25 ·  ⭐ 4.6K) - 一个比 arrow 更具有明确的，可预测的行为的时间操作库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdispater/pendulum) (👨‍💻 70 · 🔀 260 · 📋 410 - 43% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/sdispater/pendulum
	```
- [PyPi](https://pypi.org/project/pendulum) (📥 6.8M / month):
	```
	pip install pendulum
	```
- [Conda](https://anaconda.org/conda-forge/pendulum) (📥 410K · ⏱️ 08.11.2020):
	```
	conda install -c conda-forge pendulum
	```
</details>
<details><summary><b><a href="https://github.com/timofurrer/maya">maya</a></b> (🥈24 ·  ⭐ 3.3K) - 人性化的时间处理库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timofurrer/maya) (👨‍💻 47 · 🔀 190 · 📦 850 · 📋 88 - 15% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/timofurrer/maya
	```
- [PyPi](https://pypi.org/project/maya):
	```
	pip install maya
	```
- [Conda](https://anaconda.org/conda-forge/maya) (📥 44K · ⏱️ 07.01.2019):
	```
	conda install -c conda-forge maya
	```
</details>
<details><summary><b><a href="https://github.com/myusuf3/delorean">delorean</a></b> (🥉20 ·  ⭐ 1.8K · 💤) - 解决 Python 中有关日期处理的棘手问题的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myusuf3/delorean) (🔀 120 · 📦 680 · 📋 61 - 40% open · ⏱️ 06.12.2020):

	```
	git clone https://github.com/myusuf3/delorean/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/zachwill/moment">moment</a></b> (🥉17 ·  ⭐ 690 · 💀) - 一个处理日期/时间的库，灵感来自 <a href="http://momentjs.com/">Moment.js</a>。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/zachwill/moment) (👨‍💻 4 · 🔀 38 · 📦 610 · 📋 35 - 8% open · ⏱️ 27.11.2020):

	```
	git clone https://github.com/zachwill/moment
	```
- [PyPi](https://pypi.org/project/moment):
	```
	pip install moment
	```
- [Conda](https://anaconda.org/conda-forge/moment) (📥 8.3K · ⏱️ 31.01.2019):
	```
	conda install -c conda-forge moment
	```
</details>
<details><summary><b><a href="https://github.com/KoffeinFlummi/Chronyk">Chronyk</a></b> (🥉16 ·  ⭐ 320 · 💀) - Python 3 的类库，用于解析手写格式的时间和日期。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KoffeinFlummi/Chronyk) (👨‍💻 3 · 🔀 13 · 📦 20 · 📋 9 - 44% open · ⏱️ 02.08.2015):

	```
	git clone https://github.com/KoffeinFlummi/Chronyk
	```
- [PyPi](https://pypi.org/project/Chronyk) (📥 320 / month):
	```
	pip install Chronyk
	```
- [Conda](https://anaconda.org/conda-forge/Chronyk):
	```
	conda install -c conda-forge Chronyk
	```
</details>
<details><summary><b><a href="https://github.com/shinux/PyTime">PyTime</a></b> (🥉11 ·  ⭐ 140) - 一个简单易用的 Python 模块，用于通过字符串来操作日期/时间。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shinux/PyTime) (👨‍💻 5 · 🔀 16 · 📦 21 · ⏱️ 31.08.2021):

	```
	git clone https://github.com/shinux/PyTime
	```
- [PyPi](https://pypi.org/project/PyTime):
	```
	pip install PyTime
	```
- [Conda](https://anaconda.org/conda-forge/PyTime):
	```
	conda install -c conda-forge PyTime
	```
</details>
<details><summary><b><a href="https://github.com/dirn/When.py">when.py</a></b> (🥉10 ·  ⭐ 190 · 💀) - 提供用户友好的函数来帮助用户进行常用的日期和时间操作。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dirn/When.py) (👨‍💻 5 · 🔀 18 · 📦 22 · ⏱️ 14.10.2017):

	```
	git clone https://github.com/dirn/When.py
	```
- [PyPi](https://pypi.org/project/When.py):
	```
	pip install When.py
	```
- [Conda](https://anaconda.org/conda-forge/When.py):
	```
	conda install -c conda-forge When.py
	```
</details>
<br>

## 调试工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行代码调试的库。_

<details><summary><b><a href="https://github.com/jazzband/django-debug-toolbar">django-debug-toolbar</a></b> (🥇31 ·  ⭐ 6.8K) - 为 Django 显示各种调试信息。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-debug-toolbar) (👨‍💻 250 · 🔀 830 · 📥 170 · 📦 46K · 📋 780 - 10% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 1.3M / month):
	```
	pip install django-debug-toolbar
	```
- [Conda](https://anaconda.org/conda-forge/django-debug-toolbar) (📥 130K · ⏱️ 16.12.2021):
	```
	conda install -c conda-forge django-debug-toolbar
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥇25 ·  ⭐ 7.7K) - Python 程序采样分析器，使用 Rust 实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 29 · 🔀 270 · 📥 7.2K · 📋 230 - 28% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 590K / month):
	```
	pip install py-spy
	```
- [Conda](https://anaconda.org/conda-forge/py-spy) (📥 200K · ⏱️ 18.12.2021):
	```
	conda install -c conda-forge py-spy
	```
</details>
<details><summary><b><a href="https://github.com/flask-debugtoolbar/flask-debugtoolbar">flask-debugtoolbar</a></b> (🥇25 ·  ⭐ 820 · 💀) - django-debug-toolbar 的 flask 版。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/flask-debugtoolbar/flask-debugtoolbar) (👨‍💻 38 · 🔀 120 · 📦 16K · 📋 90 - 30% open · ⏱️ 14.08.2020):

	```
	git clone https://github.com/mgood/flask-debugtoolbar
	```
- [PyPi](https://pypi.org/project/flask-debugtoolbar) (📥 110K / month):
	```
	pip install flask-debugtoolbar
	```
- [Conda](https://anaconda.org/conda-forge/flask-debugtoolbar) (📥 49K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge flask-debugtoolbar
	```
</details>
<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥈23 ·  ⭐ 1.5K) - IPython 启用的 <a href="https://docs.python.org/2/library/pdb.html">pdb</a>。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 49 · 🔀 130 · 📦 30K · 📋 170 - 34% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 220K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥈23 ·  ⭐ 1.3K) - 解析和分析 ELF 文件以及 DWARF 调试信息。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 80 · 🔀 410 · 📦 2.8K · 📋 170 - 32% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 80K · ⏱️ 27.10.2020):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdb++</a></b> (🥈22 ·  ⭐ 840) - 另一种 pdb 的替代。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 40 · 🔀 46 · 📦 2.5K · 📋 180 - 34% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/antocuni/pdb
	```
- [PyPi](https://pypi.org/project/pdb):
	```
	pip install pdb
	```
- [Conda](https://anaconda.org/conda-forge/pdb):
	```
	conda install -c conda-forge pdb
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥈21 ·  ⭐ 5.6K) - 通过一个简单的函数调用检查变量、表达式和程序执行情况。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 16 · 🔀 110 · 📋 80 - 28% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 130K / month):
	```
	pip install icecream
	```
- [Conda](https://anaconda.org/conda-forge/icecream) (📥 1.7K · ⏱️ 23.06.2021):
	```
	conda install -c conda-forge icecream
	```
</details>
<details><summary><b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥈21 ·  ⭐ 3.8K · 💤) - 视觉 Python 分析器。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nvdv/vprof) (👨‍💻 17 · 🔀 150 · 📦 86 · 📋 81 - 30% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/nvdv/vprof
	```
- [PyPi](https://pypi.org/project/vprof) (📥 3.9K / month):
	```
	pip install vprof
	```
- [Conda](https://anaconda.org/conda-forge/vprof):
	```
	conda install -c conda-forge vprof
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥈21 ·  ⭐ 2.3K) - 全屏，基于控制台的 Python 调试器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 80 · 🔀 180 · 📦 2.8K · 📋 270 - 45% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 110K · ⏱️ 21.08.2021):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/Kozea/wdb">wdb</a></b> (🥉19 ·  ⭐ 1.5K · 💀) - 一个奇异的 web 调试器，通过 WebSockets 工作。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Kozea/wdb) (👨‍💻 22 · 🔀 100 · 📦 110 · 📋 110 - 26% open · ⏱️ 16.09.2019):

	```
	git clone https://github.com/Kozea/wdb
	```
- [PyPi](https://pypi.org/project/wdb) (📥 6.3K / month):
	```
	pip install wdb
	```
- [Conda](https://anaconda.org/conda-forge/wdb):
	```
	conda install -c conda-forge wdb
	```
</details>
<details><summary><b><a href="https://github.com/dcramer/django-devserver">django-devserver</a></b> (🥉19 ·  ⭐ 1.3K · 💀) - 一个 Django 运行服务器的替代品。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dcramer/django-devserver) (👨‍💻 39 · 🔀 140 · 📦 330 · 📋 67 - 58% open · ⏱️ 05.03.2016):

	```
	git clone https://github.com/dcramer/django-devserver
	```
- [PyPi](https://pypi.org/project/django-devserver) (📥 6.8K / month):
	```
	pip install django-devserver
	```
- [Conda](https://anaconda.org/conda-forge/django-devserver):
	```
	conda install -c conda-forge django-devserver
	```
</details>
<details><summary><b><a href="https://github.com/rkern/line_profiler">line_profiler</a></b> (🥉18 ·  ⭐ 3.6K · 💀) - Line-by-line profiling. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rkern/line_profiler) (👨‍💻 14 · 🔀 240 · 📋 140 - 36% open · ⏱️ 23.04.2019):

	```
	git clone https://github.com/rkern/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 130K / month):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 220K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉18 ·  ⭐ 650) - 一个灵活的代码追踪工具包。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 9 · 🔀 35 · 📦 73 · 📋 85 - 41% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/python-hunter) (📥 4 / month):
	```
	pip install python-hunter
	```
- [Conda](https://anaconda.org/conda-forge/python-hunter):
	```
	conda install -c conda-forge python-hunter
	```
</details>
<details><summary><b><a href="https://github.com/uber-archive/pyflame">pyflame</a></b> (🥉17 ·  ⭐ 2.9K · 💀) - 用于 Python 的跟踪分析器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber-archive/pyflame) (👨‍💻 22 · 🔀 220 · 📋 77 - 31% open · ⏱️ 03.12.2019):

	```
	git clone https://github.com/uber/pyflame
	```
- [PyPi](https://pypi.org/project/pyflame) (📥 120 / month):
	```
	pip install pyflame
	```
- [Conda](https://anaconda.org/conda-forge/pyflame) (📥 16K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge pyflame
	```
</details>
<details><summary><b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉16 ·  ⭐ 67 · 💀) - Monitor Memory usage of Python code. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fabianp/memory_profiler) (👨‍💻 61 · 🔀 13 · ⏱️ 28.06.2018):

	```
	git clone https://github.com/fabianp/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 410K / month):
	```
	pip install memory_profiler
	```
- [Conda](https://anaconda.org/conda-forge/memory_profiler) (📥 150K · ⏱️ 19.12.2021):
	```
	conda install -c conda-forge memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">manhole</a></b> (🥉15 ·  ⭐ 320) - 调试UNIX套接字连接，并显示所有线程的堆栈跟踪和交互式提示。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 11 · 🔀 17 · 📦 79 · 📋 20 - 25% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/python-manhole) (📥 1 / month):
	```
	pip install python-manhole
	```
- [Conda](https://anaconda.org/conda-forge/python-manhole):
	```
	conda install -c conda-forge python-manhole
	```
</details>
<details><summary><b><a href="https://github.com/google/pyringe">pyringe</a></b> (🥉14 ·  ⭐ 1.6K · 💀) - 能够附加到 Python 进程并将代码注入Python进程的调试器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/pyringe) (🔀 70 · 📦 3 · 📋 24 - 62% open · ⏱️ 10.05.2014):

	```
	git clone https://github.com/google/pyringe
	```
- [PyPi](https://pypi.org/project/pyringe) (📥 42 / month):
	```
	pip install pyringe
	```
- [Conda](https://anaconda.org/conda-forge/pyringe):
	```
	conda install -c conda-forge pyringe
	```
</details>
<details><summary><b><a href="https://github.com/khamidou/lptrace">lptrace</a></b> (🥉11 ·  ⭐ 680 · 💀) - 为 Python 程序打造的 <a href="http://man7.org/linux/man-pages/man1/strace.1.html">strace</a>。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/khamidou/lptrace) (🔀 36 · 📦 2 · 📋 12 - 50% open · ⏱️ 24.02.2017):

	```
	git clone https://github.com/khamidou/lptrace
	```
- [PyPi](https://pypi.org/project/lptrace) (📥 330 / month):
	```
	pip install lptrace
	```
- [Conda](https://anaconda.org/conda-forge/lptrace):
	```
	conda install -c conda-forge lptrace
	```
</details>
<br>

## 深度学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_神经网络和深度学习相关框架。 也可以参考 [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)。_

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">tensorflow</a></b> (🥇44 ·  ⭐ 160K) - 谷歌开源的最受欢迎的深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 3.9K · 🔀 69K · 📦 170K · 📋 34K - 7% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 15M / month):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 3M · ⏱️ 08.12.2021):
	```
	conda install -c conda-forge tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈31 ·  ⭐ 9.5K) - 一个快速数值计算库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.4K · 📦 12K · 📋 2.7K - 21% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/Theano) (📥 220K / month):
	```
	pip install Theano
	```
- [Conda](https://anaconda.org/conda-forge/Theano) (📥 1.8M · ⏱️ 10.11.2021):
	```
	conda install -c conda-forge Theano
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">keras</a></b> (🥈29 ·  ⭐ 54K) - 以 tensorflow/theano/CNTK 为后端的深度学习封装库，快速上手神经网络。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1K · 🔀 18K · 📋 11K - 1% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 7.5M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 2M · ⏱️ 25.11.2021):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">pytorch</a></b> (🥈29 ·  ⭐ 53K) - 一个具有张量和动态神经网络，并有强大 GPU 加速能力的深度学习框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 3K · 🔀 14K · 📥 730 · 📋 24K - 31% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/pytorch) (📥 48K / month):
	```
	pip install pytorch
	```
- [Conda](https://anaconda.org/conda-forge/pytorch) (📥 310K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge pytorch
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">mxnet</a></b> (🥉28 ·  ⭐ 20K) - 一个高效和灵活的深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 970 · 🔀 6.5K · 📥 24K · 📋 9.4K - 18% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/dmlc/mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 310K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/conda-forge/mxnet):
	```
	conda install -c conda-forge mxnet
	```
</details>
<details><summary><b><a href="https://github.com/BVLC/caffe">caffe</a></b> (🥉23 ·  ⭐ 32K · 💀) - 一个 <a href="https://github.com/BVLC/caffe">Caffe</a> 的 python 接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/BVLC/caffe) (👨‍💻 310 · 🔀 14K · 📋 4.8K - 18% open · ⏱️ 13.02.2020):

	```
	git clone https://github.com/BVLC/caffe
	```
- [PyPi](https://pypi.org/project/caffe):
	```
	pip install caffe
	```
- [Conda](https://anaconda.org/conda-forge/caffe) (📥 75K · ⏱️ 27.06.2020):
	```
	conda install -c conda-forge caffe
	```
</details>
<details><summary><b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉15 ·  ⭐ 6.1K · 💀) - 游戏代理框架，可使用任意视频游戏作为深度学习沙箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SerpentAI/SerpentAI) (👨‍💻 7 · 🔀 700 · 📥 150 · ⏱️ 22.05.2020):

	```
	git clone https://github.com/SerpentAI/SerpentAI
	```
- [PyPi](https://pypi.org/project/SerpentAI) (📥 100 / month):
	```
	pip install SerpentAI
	```
- [Conda](https://anaconda.org/conda-forge/SerpentAI):
	```
	conda install -c conda-forge SerpentAI
	```
</details>
<br>

## DevOps 工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于 DevOps 的软件和库。_

🔗&nbsp;<b><a href="https://cloudinit.readthedocs.io/en/latest/">cloudinit</a></b>  - 一个多分发包，用于处理云实例的早期初始化。

🔗&nbsp;<b><a href="https://www.openstack.org/">OpenStack</a></b>  - 用于构建私有和公有云的开源软件。

🔗&nbsp;<b><a href="https://www.borgbackup.org/">BorgBackup</a></b>  - 具有压缩和加密功能的重复数据删除存档器。

🔗&nbsp;<b><a href="https://docs.docker.com/compose/">docker-compose</a></b>  -  使用 <a href="https://www.docker.com/">Docker</a> 的快速独立的开发环境。

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇36 ·  ⭐ 8K) - 一个跨平台进程和系统工具模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 170 · 🔀 1.1K · 📦 130K · 📋 1.5K - 12% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 33M / month):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 9.4M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible">ansible</a></b> (🥈33 ·  ⭐ 51K) - 一个非常简单的 IT 自动化平台。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ansible/ansible) (👨‍💻 6.5K · 🔀 21K · 📦 19K · 📋 30K - 3% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/ansible/ansible
	```
- [PyPi](https://pypi.org/project/ansible) (📥 5M / month):
	```
	pip install ansible
	```
- [Conda](https://anaconda.org/conda-forge/ansible) (📥 470K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge ansible
	```
</details>
<details><summary><b><a href="https://github.com/saltstack/salt">saltstack</a></b> (🥈30 ·  ⭐ 12K) - 基础设施自动化和管理系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/saltstack/salt) (👨‍💻 3.7K · 🔀 5K · 📥 16K · 📋 24K - 9% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/saltstack/salt
	```
- [PyPi](https://pypi.org/project/salt) (📥 120K / month):
	```
	pip install salt
	```
- [Conda](https://anaconda.org/conda-forge/salt) (📥 25K · ⏱️ 26.02.2019):
	```
	conda install -c conda-forge salt
	```
</details>
<details><summary><b><a href="https://github.com/Supervisor/supervisor">supervisor</a></b> (🥈29 ·  ⭐ 7.1K) - UNIX 的进程控制系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Supervisor/supervisor) (👨‍💻 160 · 🔀 1.1K · 📦 6.6K · 📋 1K - 10% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/Supervisor/supervisor
	```
- [PyPi](https://pypi.org/project/supervisor) (📥 970K / month):
	```
	pip install supervisor
	```
- [Conda](https://anaconda.org/conda-forge/supervisor) (📥 180K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge supervisor
	```
</details>
<details><summary><b><a href="https://github.com/nickstenning/honcho">honcho</a></b> (🥉26 ·  ⭐ 1.4K) - <a href="https://github.com/ddollar/foreman">Foreman</a> 的 Python 克隆版，用于管理基于 Procfile 的应用。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nickstenning/honcho) (👨‍💻 44 · 🔀 130 · 📦 3.2K · 📋 99 - 11% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/nickstenning/honcho
	```
- [PyPi](https://pypi.org/project/honcho) (📥 120K / month):
	```
	pip install honcho
	```
- [Conda](https://anaconda.org/conda-forge/honcho):
	```
	conda install -c conda-forge honcho
	```
</details>
<details><summary><b><a href="https://github.com/fabric/fabric">fabric</a></b> (🥉25 ·  ⭐ 13K) - 一个简单的，Python 风格的工具，用来进行远程执行和部署。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fabric/fabric) (👨‍💻 18 · 🔀 1.7K · 📋 1.7K - 23% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/fabric/fabric
	```
- [PyPi](https://pypi.org/project/fabric) (📥 1.1M / month):
	```
	pip install fabric
	```
- [Conda](https://anaconda.org/conda-forge/fabric) (📥 44K · ⏱️ 09.03.2021):
	```
	conda install -c conda-forge fabric
	```
</details>
<details><summary><b><a href="https://github.com/fabtools/fabtools">fabtools</a></b> (🥉22 ·  ⭐ 1.2K · 💀) - 一个用来编写超赞的 Fabric 文件的工具。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fabtools/fabtools) (👨‍💻 88 · 🔀 190 · 📦 280 · 📋 140 - 54% open · ⏱️ 16.09.2019):

	```
	git clone https://github.com/fabtools/fabtools
	```
- [PyPi](https://pypi.org/project/fabtools) (📥 2.8K / month):
	```
	pip install fabtools
	```
- [Conda](https://anaconda.org/conda-forge/fabtools):
	```
	conda install -c conda-forge fabtools
	```
</details>
<details><summary><b><a href="https://github.com/Fizzadar/pyinfra">pyinfra</a></b> (🥉21 ·  ⭐ 1.4K) - 一个通用的 CLI 工具包和 python 库，用于自动化的基础设施。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Fizzadar/pyinfra) (👨‍💻 60 · 🔀 260 · 📦 37 · 📋 510 - 17% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/Fizzadar/pyinfra
	```
- [PyPi](https://pypi.org/project/pyinfra) (📥 4.2K / month):
	```
	pip install pyinfra
	```
- [Conda](https://anaconda.org/conda-forge/pyinfra):
	```
	conda install -c conda-forge pyinfra
	```
</details>
<details><summary><b><a href="https://github.com/sebastien/cuisine">cuisine</a></b> (🥉20 ·  ⭐ 1.2K · 💀) - 为 Fabric 提供一系列高级函数。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sebastien/cuisine) (👨‍💻 57 · 🔀 160 · 📦 140 · 📋 100 - 23% open · ⏱️ 27.02.2018):

	```
	git clone https://github.com/sebastien/cuisine
	```
- [PyPi](https://pypi.org/project/cuisine) (📥 1.8K / month):
	```
	pip install cuisine
	```
- [Conda](https://anaconda.org/conda-forge/cuisine):
	```
	conda install -c conda-forge cuisine
	```
</details>
<br>

## 分布式计算

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_分布式计算相关的框架和库。_

🔗&nbsp;<b><a href="https://pypi.org/project/pyspark/">PySpark</a></b>  - Spark 的 Python API 。

<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇33 ·  ⭐ 15K) - 这个模块帮你构建批处理作业的复杂流水线。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 570 · 🔀 2.2K · 📦 1.6K · 📋 920 - 7% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 640K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/conda-forge/luigi) (📥 510K · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge luigi
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥈32 ·  ⭐ 9.3K) - 用于分析计算的灵活的并行计算库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 490 · 🔀 1.4K · 📦 32K · 📋 4K - 16% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 5.1M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 4.8M · ⏱️ 11.12.2021):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈27 ·  ⭐ 2.6K · 💀) - 在 Hadoop 或 Amazon Web Services 上运行 MapReduce 任务。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Yelp/mrjob) (👨‍💻 140 · 🔀 570 · 📦 900 · 📋 1.3K - 15% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Yelp/mrjob
	```
- [PyPi](https://pypi.org/project/mrjob) (📥 110K / month):
	```
	pip install mrjob
	```
- [Conda](https://anaconda.org/conda-forge/mrjob) (📥 420K · ⏱️ 24.12.2020):
	```
	conda install -c conda-forge mrjob
	```
</details>
<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥉26 ·  ⭐ 19K) - 一个用于并行和分布式 Python 的系统，它统一了机器学习生态系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (🔀 3.1K · 📦 3.6K · 📋 8.7K - 21% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/ray-project/ray/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/robinhood/faust">faust</a></b> (🥉26 ·  ⭐ 5.9K · 💀) - 一个 Python 流处理库，核心思想来源 <a href="https://kafka.apache.org/documentation/streams/">Kafka Streams</a>。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/robinhood/faust) (👨‍💻 93 · 🔀 490 · 📦 900 · 📋 460 - 48% open · ⏱️ 09.10.2020):

	```
	git clone https://github.com/robinhood/faust
	```
- [PyPi](https://pypi.org/project/faust) (📥 350K / month):
	```
	pip install faust
	```
- [Conda](https://anaconda.org/conda-forge/faust):
	```
	conda install -c conda-forge faust
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉21 ·  ⭐ 1.4K · 💤) - 运行针对事实数据流的 Python 代码。集成了 <a href="http://storm.apache.org/">Apache Storm</a>。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 41 · 🔀 210 · 📦 52 · 📋 320 - 19% open · ⏱️ 18.12.2020):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 4.8K / month):
	```
	pip install streamparse
	```
- [Conda](https://anaconda.org/conda-forge/streamparse):
	```
	conda install -c conda-forge streamparse
	```
</details>
<br>

## 分发

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_打包为可执行文件以便分发。_

🔗&nbsp;<b><a href="http://nuitka.net/">Nuitka</a></b>  - 将脚本、模块、包编译成可执行文件或扩展模块。

🔗&nbsp;<b><a href="http://pythonhosted.org/py2app/">py2app</a></b>  - 将 Python 脚本变为独立软件包（Mac OS X）。

🔗&nbsp;<b><a href="http://www.py2exe.org/">py2exe</a></b>  - 将 Python 脚本变为独立软件包（Windows）。

🔗&nbsp;<b><a href="http://pynsist.readthedocs.io/en/latest/">pynsist</a></b>  - 一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python 本身。

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">PyInstaller</a></b> (🥇26 ·  ⭐ 8.7K) - 将 Python 程序转换成独立的执行文件（跨平台）。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 420 · 🔀 1.6K · 📥 720K · 📋 4.4K - 6% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 650K / month):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 280K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥇26 ·  ⭐ 1.3K) - 一个用于加密 python 脚本的工具，也可以将加密后的脚本绑定到固件上，或设置已加密脚本的有效期。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dashingsoft/pyarmor) (👨‍💻 17 · 🔀 150 · 📥 18 · 📦 330 · 📋 630 - 1% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/dashingsoft/pyarmor
	```
- [PyPi](https://pypi.org/project/pyarmor) (📥 67K / month):
	```
	pip install pyarmor
	```
- [Conda](https://anaconda.org/conda-forge/pyarmor):
	```
	conda install -c conda-forge pyarmor
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉19 ·  ⭐ 1.3K) - 一个命令行工具，可用于构建完全独立的 zip 应用（PEP 441 所描述的那种），同时包含了所有的依赖项。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 34 · 🔀 72 · 📥 160 · 📋 93 - 24% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 7K / month):
	```
	pip install shiv
	```
- [Conda](https://anaconda.org/conda-forge/shiv):
	```
	conda install -c conda-forge shiv
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉15 ·  ⭐ 1.5K) - 构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 58 · 🔀 160 · 📋 190 - 12% open · ⏱️ 10.11.2021):

	```
	git clone https://github.com/spotify/dh-virtualenv
	```
- [PyPi](https://pypi.org/project/dh-virtualenv):
	```
	pip install dh-virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/dh-virtualenv):
	```
	conda install -c conda-forge dh-virtualenv
	```
</details>
<br>

## 文档

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用以生成项目文档的库。_

🔗&nbsp;<b><a href="https://github.com/yoloseem/awesome-sphinxdoc">awesome-sphinxdoc</a></b> ( ⭐ 780 · 💤)  - A curated list of awesome tools for Sphinx Python Documentation..

<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇26 ·  ⭐ 4.3K) - Python 文档生成器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (🔀 1.5K · 📦 170K · 📋 5.7K - 15% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/sphinx-doc/sphinx/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥉22 ·  ⭐ 1.1K) - 一个可以替换 Epydoc 的库，可以自动生成 Python 库的 API 文档。<code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 32 · 🔀 110 · 📦 470 · 📋 200 - 4% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 96K / month):
	```
	pip install pdoc
	```
- [Conda](https://anaconda.org/conda-forge/pdoc):
	```
	conda install -c conda-forge pdoc
	```
</details>
<details><summary><b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉20 ·  ⭐ 760 · 💀) - 文学编程（literate-programming）风格的文档生成器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pycco-docs/pycco) (👨‍💻 36 · 🔀 130 · 📦 240 · 📋 57 - 50% open · ⏱️ 20.12.2019):

	```
	git clone https://github.com/pycco-docs/pycco
	```
- [PyPi](https://pypi.org/project/pycco) (📥 1.5K / month):
	```
	pip install pycco
	```
- [Conda](https://anaconda.org/conda-forge/pycco):
	```
	conda install -c conda-forge pycco
	```
</details>
<br>

## 下载器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行下载的库._

🔗&nbsp;<b><a href="https://you-get.org/">you-get</a></b>  - 一个 YouTube/Youku/Niconico 视频下载器，使用 Python3 编写。

🔗&nbsp;<b><a href="https://rg3.github.io/youtube-dl/">youtube-dl</a></b>  - 一个小巧的命令行程序，用来下载 YouTube 视频。

<details><summary><b><a href="https://github.com/akfamily/akshare">akshare</a></b> (🥇27 ·  ⭐ 4.4K · 📈) - 为方便人使用而创建的金融数据接口库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akfamily/akshare) (👨‍💻 21 · 🔀 920 · 📦 120 · ⏱️ 23.12.2021):

	```
	git clone https://github.com/jindaxiang/akshare
	```
- [PyPi](https://pypi.org/project/akshare) (📥 35K / month):
	```
	pip install akshare
	```
- [Conda](https://anaconda.org/conda-forge/akshare):
	```
	conda install -c conda-forge akshare
	```
</details>
<details><summary><b><a href="https://github.com/s3tools/s3cmd">s3cmd</a></b> (🥉26 ·  ⭐ 3.8K) - 一个用来管理 Amazon S3 和 CloudFront 的命令行工具。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/s3tools/s3cmd) (👨‍💻 200 · 🔀 790 · 📥 3M · 📋 790 - 29% open · ⏱️ 08.11.2021):

	```
	git clone https://github.com/s3tools/s3cmd
	```
- [PyPi](https://pypi.org/project/s3cmd) (📥 1.7M / month):
	```
	pip install s3cmd
	```
- [Conda](https://anaconda.org/conda-forge/s3cmd) (📥 5.6K · ⏱️ 22.12.2018):
	```
	conda install -c conda-forge s3cmd
	```
</details>
<details><summary><b><a href="https://github.com/bloomreach/s4cmd">s4cmd</a></b> (🥉21 ·  ⭐ 1.2K) - 超级 S3 命令行工具，性能更加强劲。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bloomreach/s4cmd) (👨‍💻 34 · 🔀 190 · 📦 26 · 📋 130 - 59% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/bloomreach/s4cmd
	```
- [PyPi](https://pypi.org/project/s4cmd) (📥 14K / month):
	```
	pip install s4cmd
	```
- [Conda](https://anaconda.org/conda-forge/s4cmd):
	```
	conda install -c conda-forge s4cmd
	```
</details>
<br>

## 电子商务

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于电子商务以及支付的框架和库。_

🔗&nbsp;<b><a href="http://oscarcommerce.com/">django-oscar</a></b>  - 一个用于 Django 的开源的电子商务框架。

🔗&nbsp;<b><a href="http://getsaleor.com/">saleor</a></b>  - 一款兼容 Django 的电子商务平台。

🔗&nbsp;<b><a href="https://www.shuup.com/en/">shoop</a></b>  - 一个基于 Django 的开源电子商务平台。

<details><summary><b><a href="https://github.com/MicroPyramid/forex-python">forex-python</a></b> (🥇25 ·  ⭐ 450) - 外汇汇率，比特币价格指数和货币换算。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MicroPyramid/forex-python) (👨‍💻 24 · 🔀 140 · 📦 1K · 📋 57 - 24% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/MicroPyramid/forex-python
	```
- [PyPi](https://pypi.org/project/forex-python) (📥 130K / month):
	```
	pip install forex-python
	```
- [Conda](https://anaconda.org/conda-forge/forex-python):
	```
	conda install -c conda-forge forex-python
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥈24 ·  ⭐ 2.7K · 💤) - 一个基于 Django 的店铺系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 900 · 📦 200 · 📋 370 - 21% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 4.5K / month):
	```
	pip install django-shop
	```
- [Conda](https://anaconda.org/conda-forge/django-shop):
	```
	conda install -c conda-forge django-shop
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/cartridge">Cartridge</a></b> (🥈21 ·  ⭐ 640) - 一个基于 Mezzanine 构建的购物车应用。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/cartridge) (👨‍💻 74 · 🔀 280 · 📦 180 · 📋 150 - 15% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/stephenmcd/cartridge
	```
- [PyPi](https://pypi.org/project/cartridge) (📥 390 / month):
	```
	pip install cartridge
	```
- [Conda](https://anaconda.org/conda-forge/cartridge):
	```
	conda install -c conda-forge cartridge
	```
</details>
<details><summary><b><a href="https://github.com/carlospalol/money">money</a></b> (🥉20 ·  ⭐ 200 · 💀) - 一个货币类库。带有可选的 CLDR 后端本地化格式，提供可扩展的货币兑换解决方案。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carlospalol/money) (👨‍💻 4 · 🔀 25 · 📦 220 · 📋 23 - 30% open · ⏱️ 04.09.2016):

	```
	git clone https://github.com/carlospalol/money
	```
- [PyPi](https://pypi.org/project/money) (📥 44K / month):
	```
	pip install money
	```
- [Conda](https://anaconda.org/conda-forge/money):
	```
	conda install -c conda-forge money
	```
</details>
<details><summary><b><a href="https://github.com/agiliq/merchant">merchant</a></b> (🥉18 ·  ⭐ 980 · 💀) - 一个可以接收来自多种支付平台支付的 Django 应用。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/agiliq/merchant) (👨‍💻 49 · 🔀 170 · 📦 20 · 📋 63 - 36% open · ⏱️ 08.07.2015):

	```
	git clone https://github.com/agiliq/merchant
	```
- [PyPi](https://pypi.org/project/merchant):
	```
	pip install merchant
	```
- [Conda](https://anaconda.org/conda-forge/merchant):
	```
	conda install -c conda-forge merchant
	```
</details>
<details><summary><b><a href="https://github.com/lxneng/alipay">alipay</a></b> (🥉14 ·  ⭐ 320 · 💀) - 非官方的 Python 支付宝 API。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lxneng/alipay) (👨‍💻 13 · 🔀 93 · 📦 98 · 📋 14 - 14% open · ⏱️ 22.11.2017):

	```
	git clone https://github.com/lxneng/alipay
	```
- [PyPi](https://pypi.org/project/alipay) (📥 300 / month):
	```
	pip install alipay
	```
- [Conda](https://anaconda.org/conda-forge/alipay):
	```
	conda install -c conda-forge alipay
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/python-currencies">python-currencies</a></b> (🥉12 ·  ⭐ 57 · 💤) - 显示货币格式以及它的数值。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Alir3z4/python-currencies) (👨‍💻 5 · 🔀 12 · 📥 6 · 📦 25 · 📋 5 - 40% open · ⏱️ 22.12.2020):

	```
	git clone https://github.com/Alir3z4/python-currencies
	```
- [PyPi](https://pypi.org/project/python-currencies):
	```
	pip install python-currencies
	```
- [Conda](https://anaconda.org/conda-forge/python-currencies):
	```
	conda install -c conda-forge python-currencies
	```
</details>
<br>

##  Emacs [elpy](https://github.com/jorgenschaefer/elpy)：Emacs Python 开发环境。

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_ Emacs [elpy](https://github.com/jorgenschaefer/elpy)：Emacs Python 开发环境。_

🔗&nbsp;<b><a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Python</a></b>  - 对 Python 有丰富支持的官方 VSCode 扩展。

🔗&nbsp;<b><a href="https://www.jetbrains.com/pycharm/">PyCharm</a></b>  - JetBrains 提供的商业 Python IDE，也有免费的社区版。

<details><summary><b><a href="https://github.com/spyder-ide/spyder">spyder</a></b> (🥇34 ·  ⭐ 6.7K) -  开源 Python IDE。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/spyder-ide/spyder) (👨‍💻 230 · 🔀 1.3K · 📥 1.2M · 📦 21K · 📋 14K - 8% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/spyder-ide/spyder
	```
- [PyPi](https://pypi.org/project/spyder):
	```
	pip install spyder
	```
- [Conda](https://anaconda.org/conda-forge/spyder) (📥 1.2M · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge spyder
	```
</details>
<details><summary><b><a href="https://github.com/jorgenschaefer/elpy">elpy</a></b> (🥈22 ·  ⭐ 1.7K) - Emacs Python Development Environment. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/jorgenschaefer/elpy) (👨‍💻 84 · 🔀 230 · 📦 200 · 📋 1.5K - 22% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/jorgenschaefer/elpy
	```
- [PyPi](https://pypi.org/project/elpy) (📥 590 / month):
	```
	pip install elpy
	```
- [Conda](https://anaconda.org/conda-forge/elpy):
	```
	conda install -c conda-forge elpy
	```
</details>
<details><summary><b><a href="https://github.com/DamnWidget/anaconda">anaconda</a></b> (🥈21 ·  ⭐ 2.1K) - Anaconda 可将功能齐全的 Python 开发 IDE 转换为 Sublime Text 3。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/DamnWidget/anaconda) (👨‍💻 89 · 🔀 250 · 📋 770 - 21% open · ⏱️ 28.11.2021):

	```
	git clone https://github.com/DamnWidget/anaconda
	```
- [PyPi](https://pypi.org/project/anaconda) (📥 12K / month):
	```
	pip install anaconda
	```
- [Conda](https://anaconda.org/conda-forge/anaconda):
	```
	conda install -c conda-forge anaconda
	```
</details>
<details><summary><b><a href="https://github.com/ycm-core/YouCompleteMe">YouCompleteMe</a></b> (🥉19 ·  ⭐ 24K) - 包含 Jedi 补全的 Python 引擎。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ycm-core/YouCompleteMe) (👨‍💻 170 · 🔀 2.6K · 📋 3.1K - 0% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/Valloric/YouCompleteMe
	```
- [PyPi](https://pypi.org/project/YouCompleteMe):
	```
	pip install YouCompleteMe
	```
- [Conda](https://anaconda.org/conda-forge/YouCompleteMe):
	```
	conda install -c conda-forge YouCompleteMe
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/PTVS">PTVS</a></b> (🥉18 ·  ⭐ 2.4K) - Visual Studio Python 工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/PTVS) (👨‍💻 73 · 🔀 650 · 📥 32K · 📋 4.1K - 2% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/Microsoft/PTVS
	```
- [PyPi](https://pypi.org/project/PTVS):
	```
	pip install PTVS
	```
- [Conda](https://anaconda.org/conda-forge/PTVS):
	```
	conda install -c conda-forge PTVS
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/jedi-vim">jedi-vim</a></b> (🥉16 ·  ⭐ 4.9K) - 用于 Python 的 Jedi 自动补全库的 Vim 绑定。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi-vim) (👨‍💻 93 · 🔀 360 · 📋 750 - 2% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/davidhalter/jedi-vim
	```
- [PyPi](https://pypi.org/project/jedi-vim):
	```
	pip install jedi-vim
	```
- [Conda](https://anaconda.org/conda-forge/jedi-vim):
	```
	conda install -c conda-forge jedi-vim
	```
</details>
<details><summary><b><a href="https://github.com/python-mode/python-mode">python-mode</a></b> (🥉15 ·  ⭐ 5.3K) - 一个将Vim转换为Python IDE的多合一插件。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-mode/python-mode) (👨‍💻 130 · 🔀 770 · 📋 890 - 2% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/python-mode/python-mode
	```
- [PyPi](https://pypi.org/project/python-mode):
	```
	pip install python-mode
	```
- [Conda](https://anaconda.org/conda-forge/python-mode):
	```
	conda install -c conda-forge python-mode
	```
</details>
<details><summary><b><a href="https://github.com/srusskih/SublimeJEDI">SublimeJEDI</a></b> (🥉15 ·  ⭐ 920 · 💤) - 一个很棒的自动补全库 Jedi 的Sublime Text 插件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/srusskih/SublimeJEDI) (👨‍💻 46 · 🔀 110 · 📋 220 - 15% open · ⏱️ 23.02.2021):

	```
	git clone https://github.com/srusskih/SublimeJEDI
	```
- [PyPi](https://pypi.org/project/SublimeJEDI):
	```
	pip install SublimeJEDI
	```
- [Conda](https://anaconda.org/conda-forge/SublimeJEDI):
	```
	conda install -c conda-forge SublimeJEDI
	```
</details>
<br>

## 电子邮件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来发送和解析电子邮件的库。_

<details><summary><b><a href="https://github.com/kootenpv/yagmail">yagmail</a></b> (🥇27 ·  ⭐ 2.2K) - yagmail是一个GMAIL / SMTP客户端，旨在使其尽可能简单地发送电子邮件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kootenpv/yagmail) (👨‍💻 27 · 🔀 240 · 📦 1.9K · 📋 180 - 43% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/kootenpv/yagmail
	```
- [PyPi](https://pypi.org/project/yagmail) (📥 130K / month):
	```
	pip install yagmail
	```
- [Conda](https://anaconda.org/conda-forge/yagmail) (📥 9K · ⏱️ 30.08.2021):
	```
	conda install -c conda-forge yagmail
	```
</details>
<details><summary><b><a href="https://github.com/mailgun/flanker">flanker</a></b> (🥈26 ·  ⭐ 1.5K · 💤) - 一个 email 地址和 Mime 解析库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mailgun/flanker) (👨‍💻 54 · 🔀 170 · 📦 210 · 📋 88 - 59% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/mailgun/flanker
	```
- [PyPi](https://pypi.org/project/flanker) (📥 44K / month):
	```
	pip install flanker
	```
- [Conda](https://anaconda.org/conda-forge/flanker):
	```
	conda install -c conda-forge flanker
	```
</details>
<details><summary><b><a href="https://github.com/modoboa/modoboa">modoboa</a></b> (🥈25 ·  ⭐ 2K) - 一个邮件托管和管理平台，具有现代的、简约的 Web UI。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/modoboa/modoboa) (👨‍💻 100 · 🔀 280 · 📦 33 · 📋 1.6K - 4% open · ⏱️ 10.11.2021):

	```
	git clone https://github.com/modoboa/modoboa
	```
- [PyPi](https://pypi.org/project/modoboa) (📥 1.6K / month):
	```
	pip install modoboa
	```
- [Conda](https://anaconda.org/conda-forge/modoboa):
	```
	conda install -c conda-forge modoboa
	```
</details>
<details><summary><b><a href="https://github.com/martinrusev/imbox">imbox</a></b> (🥉24 ·  ⭐ 1K) - Python IMAP 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinrusev/imbox) (👨‍💻 49 · 🔀 160 · 📦 120 · 📋 110 - 43% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/martinrusev/imbox
	```
- [PyPi](https://pypi.org/project/imbox) (📥 24K / month):
	```
	pip install imbox
	```
- [Conda](https://anaconda.org/conda-forge/imbox):
	```
	conda install -c conda-forge imbox
	```
</details>
<details><summary><b><a href="https://github.com/marrow/mailer">mailer</a></b> (🥉18 ·  ⭐ 230 · 💤) - 一款高性能可扩展的邮件投递框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marrow/mailer) (👨‍💻 20 · 🔀 51 · 📥 120 · 📋 72 - 36% open · ⏱️ 20.04.2021):

	```
	git clone https://github.com/marrow/mailer
	```
- [PyPi](https://pypi.org/project/mailer) (📥 59K / month):
	```
	pip install mailer
	```
- [Conda](https://anaconda.org/conda-forge/mailer) (📥 44K · ⏱️ 01.07.2021):
	```
	conda install -c conda-forge mailer
	```
</details>
<details><summary><b><a href="https://github.com/moggers87/salmon">salmon</a></b> (🥉14 ·  ⭐ 520) - 一个 Python 邮件服务器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/moggers87/salmon) (👨‍💻 15 · 🔀 51 · 📥 50 · 📦 15 · 📋 90 - 18% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/moggers87/salmon
	```
- [PyPi](https://pypi.org/project/salmon) (📥 38 / month):
	```
	pip install salmon
	```
- [Conda](https://anaconda.org/conda-forge/salmon):
	```
	conda install -c conda-forge salmon
	```
</details>
<br>

## 企业级应用集成

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_企业级环境中用于集成的平台与工具。_

🔗&nbsp;<b><a href="https://zato.io">Zato</a></b>  - ESB, SOA, REST, APIs 以及云的 Python 整合。

<br>

## 环境管理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理 Python 版本和环境的工具_

<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥇26 ·  ⭐ 26K) - 简单的 Python 版本管理工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 350 · 🔀 2.2K · 📋 1.4K - 2% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 6.9K / month):
	```
	pip install pyenv
	```
- [Conda](https://anaconda.org/conda-forge/pyenv):
	```
	conda install -c conda-forge pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥉24 ·  ⭐ 4K) - 创建独立 Python 环境的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 62 · 🔀 860 · 📋 1.2K - 5% open · ⏱️ 04.12.2021):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 23M / month):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 1.4M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<br>

## 文件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_文件管理和 MIME（多用途的网际邮件扩充协议）类型检测。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/mimetypes.html">mimetypes</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/pathlib.html">pathlib</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

<details><summary><b><a href="https://github.com/gorakhargosh/watchdog">watchdog</a></b> (🥇29 ·  ⭐ 5.1K) - 管理文件系统事件的 API 和 shell 工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gorakhargosh/watchdog) (👨‍💻 120 · 🔀 590 · 📦 45K · 📋 550 - 27% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/gorakhargosh/watchdog
	```
- [PyPi](https://pypi.org/project/watchdog):
	```
	pip install watchdog
	```
- [Conda](https://anaconda.org/conda-forge/watchdog) (📥 890K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge watchdog
	```
</details>
<details><summary><b><a href="https://github.com/ahupp/python-magic">python-magic</a></b> (🥇29 ·  ⭐ 2K) - 文件类型检测的第三方库 libmagic 的 Python 接口。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ahupp/python-magic) (👨‍💻 53 · 🔀 220 · 📦 21K · 📋 160 - 14% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/ahupp/python-magic
	```
- [PyPi](https://pypi.org/project/python-magic) (📥 3.3M / month):
	```
	pip install python-magic
	```
- [Conda](https://anaconda.org/conda-forge/python-magic) (📥 110K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge python-magic
	```
</details>
<details><summary><b><a href="https://github.com/mikeorr/Unipath">Unipath</a></b> (🥉20 ·  ⭐ 500 · 💀) - 用面向对象的方式操作文件和目录。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mikeorr/Unipath) (👨‍💻 6 · 🔀 37 · 📦 6.4K · 📋 17 - 41% open · ⏱️ 14.02.2015):

	```
	git clone https://github.com/mikeorr/Unipath
	```
- [PyPi](https://pypi.org/project/Unipath) (📥 69K / month):
	```
	pip install Unipath
	```
- [Conda](https://anaconda.org/conda-forge/Unipath):
	```
	conda install -c conda-forge Unipath
	```
</details>
<details><summary><b><a href="https://github.com/PyFilesystem/pyfilesystem2">PyFilesystem2</a></b> (🥉19 ·  ⭐ 1.6K) - Python 的文件系统抽象层。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyFilesystem/pyfilesystem2) (👨‍💻 43 · 🔀 150 · 📋 310 - 18% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/pyfilesystem/pyfilesystem2
	```
- [PyPi](https://pypi.org/project/pyfilesystem2):
	```
	pip install pyfilesystem2
	```
- [Conda](https://anaconda.org/conda-forge/pyfilesystem2):
	```
	conda install -c conda-forge pyfilesystem2
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/path">path.py</a></b> (🥉19 ·  ⭐ 970) - A module wrapper for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/path) (👨‍💻 44 · 🔀 130 · 📋 130 - 2% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/jaraco/path.py
	```
- [PyPi](https://pypi.org/project/path.py) (📥 240K / month):
	```
	pip install path.py
	```
- [Conda](https://anaconda.org/conda-forge/path.py) (📥 480K · ⏱️ 28.07.2020):
	```
	conda install -c conda-forge path.py
	```
</details>
<br>

## 外来函数接口

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_使用外来函数接口的库。_

🔗&nbsp;<b><a href="https://pypi.org/project/cffi/">cffi</a></b>  - 用来调用 C 代码的外来函数接口。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/ctypes.html">ctypes</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://mathema.tician.de/software/pycuda/">PyCUDA</a></b>  - Nvidia CUDA API 的封装。

🔗&nbsp;<b><a href="http://www.swig.org/Doc1.3/Python.html">SWIG</a></b>  - 简化的封装和接口生成器。

<br>

## 表单

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_进行表单操作的库。_

<details><summary><b><a href="https://github.com/django-crispy-forms/django-crispy-forms">django-crispy-forms</a></b> (🥇32 ·  ⭐ 4.4K) - 一个 Django 应用，他可以让你以一种非常优雅且 DRY（Don't repeat yourself） 的方式来创建美观的表单。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-crispy-forms/django-crispy-forms) (👨‍💻 220 · 🔀 660 · 📦 79K · 📋 630 - 9% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/django-crispy-forms/django-crispy-forms
	```
- [PyPi](https://pypi.org/project/django-crispy-forms) (📥 590K / month):
	```
	pip install django-crispy-forms
	```
- [Conda](https://anaconda.org/conda-forge/django-crispy-forms) (📥 44K · ⏱️ 25.09.2021):
	```
	conda install -c conda-forge django-crispy-forms
	```
</details>
<details><summary><b><a href="https://github.com/wtforms/wtforms">WTForms</a></b> (🥈31 ·  ⭐ 1.3K) - 一个灵活的表单验证和呈现库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wtforms/wtforms) (👨‍💻 130 · 🔀 350 · 📦 110K · 📋 380 - 10% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/wtforms/wtforms
	```
- [PyPi](https://pypi.org/project/wtforms):
	```
	pip install wtforms
	```
- [Conda](https://anaconda.org/conda-forge/wtforms) (📥 85K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge wtforms
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈26 ·  ⭐ 2.3K) - 集成了 Bootstrap 3 的 Django。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 98 · 🔀 680 · 📦 16K · 📋 290 - 2% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/dyve/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 95K / month):
	```
	pip install django-bootstrap3
	```
- [Conda](https://anaconda.org/conda-forge/django-bootstrap3) (📥 20K · ⏱️ 04.08.2019):
	```
	conda install -c conda-forge django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥉24 ·  ⭐ 940) - 集成了 Bootstrap 4 的 Django。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 210 · 📦 54K · 📋 150 - 12% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4):
	```
	pip install django-bootstrap4
	```
- [Conda](https://anaconda.org/conda-forge/django-bootstrap4) (📥 16K · ⏱️ 20.10.2021):
	```
	conda install -c conda-forge django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/Pylons/deform">Deform</a></b> (🥉17 ·  ⭐ 370) - Python HTML 表单生成库，受到了 formish 表单生成库的启发。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Pylons/deform) (👨‍💻 100 · 🔀 150 · 📦 700 · 📋 180 - 24% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/Pylons/deform
	```
- [PyPi](https://pypi.org/project/deform):
	```
	pip install deform
	```
- [Conda](https://anaconda.org/conda-forge/deform):
	```
	conda install -c conda-forge deform
	```
</details>
<details><summary><b><a href="https://github.com/WiserTogether/django-remote-forms">django-remote-forms</a></b> (🥉14 ·  ⭐ 210 · 💀) - 一个平台独立的 Django 表单序列化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WiserTogether/django-remote-forms) (👨‍💻 9 · 🔀 83 · 📦 18 · 📋 16 - 75% open · ⏱️ 12.07.2017):

	```
	git clone https://github.com/WiserTogether/django-remote-forms
	```
- [PyPi](https://pypi.org/project/django-remote-forms) (📥 100 / month):
	```
	pip install django-remote-forms
	```
- [Conda](https://anaconda.org/conda-forge/django-remote-forms):
	```
	conda install -c conda-forge django-remote-forms
	```
</details>
<br>

## 函数式编程

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_使用 Python 进行函数式编程。_

<details><summary><b><a href="https://github.com/more-itertools/more-itertools">more-itertools</a></b> (🥇35 ·  ⭐ 2.2K) - 比 `itertools` 拥有更多的可迭代对象的操作方式。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/more-itertools/more-itertools) (👨‍💻 86 · 🔀 180 · 📥 2.4K · 📦 120K · 📋 190 - 3% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/erikrose/more-itertools
	```
- [PyPi](https://pypi.org/project/more-itertools) (📥 13M / month):
	```
	pip install more-itertools
	```
- [Conda](https://anaconda.org/conda-forge/more-itertools) (📥 8.6M · ⏱️ 24.11.2021):
	```
	conda install -c conda-forge more-itertools
	```
</details>
<details><summary><b><a href="https://github.com/pytoolz/toolz">Toolz</a></b> (🥈32 ·  ⭐ 3.8K) - 一组用于迭代器，函数和字典的函数式编程工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytoolz/toolz) (👨‍💻 70 · 🔀 210 · 📦 51K · 📋 210 - 34% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/pytoolz/toolz
	```
- [PyPi](https://pypi.org/project/toolz) (📥 9.1M / month):
	```
	pip install toolz
	```
- [Conda](https://anaconda.org/conda-forge/toolz) (📥 5.7M · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge toolz
	```
</details>
<details><summary><b><a href="https://github.com/Suor/funcy">funcy</a></b> (🥈28 ·  ⭐ 2.7K) - 炫酷又实用的函数式工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/funcy) (👨‍💻 29 · 🔀 120 · 📦 4K · 📋 66 - 6% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/Suor/funcy
	```
- [PyPi](https://pypi.org/project/funcy) (📥 780K / month):
	```
	pip install funcy
	```
- [Conda](https://anaconda.org/conda-forge/funcy) (📥 170K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge funcy
	```
</details>
<details><summary><b><a href="https://github.com/dry-python/returns">returns</a></b> (🥉23 ·  ⭐ 2K) - 一个类型安全的单元、转换器与合成工具集合。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/dry-python/returns) (👨‍💻 38 · 🔀 86 · 📦 120 · 📋 370 - 14% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/dry-python/returns
	```
- [PyPi](https://pypi.org/project/returns):
	```
	pip install returns
	```
- [Conda](https://anaconda.org/conda-forge/returns) (📥 580 · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge returns
	```
</details>
<details><summary><b><a href="https://github.com/evhub/coconut">Coconut</a></b> (🥉22 ·  ⭐ 3.4K) - 为了简单、优雅、更 Pythonic 的函数式编程而构建的 Python 变体。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evhub/coconut) (👨‍💻 29 · 🔀 99 · 📋 540 - 11% open · ⏱️ 07.11.2021):

	```
	git clone https://github.com/evhub/coconut
	```
- [PyPi](https://pypi.org/project/coconut):
	```
	pip install coconut
	```
- [Conda](https://anaconda.org/conda-forge/coconut) (📥 120K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge coconut
	```
</details>
<details><summary><b><a href="https://github.com/pytoolz/cytoolz">CyToolz</a></b> (🥉20 ·  ⭐ 810) - Toolz 的 Cython 实现：高性能函数式工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytoolz/cytoolz) (🔀 60 · 📦 34K · 📋 62 - 35% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/pytoolz/cytoolz/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/kachayev/fn.py">fn.py</a></b> (🥉16 ·  ⭐ 3.2K · 💀) - 在 Python 中进行函数式编程：实现了一些享受函数式编程缺失的功能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kachayev/fn.py) (👨‍💻 18 · 🔀 180 · 📦 380 · 📋 45 - 44% open · ⏱️ 13.10.2014):

	```
	git clone https://github.com/kachayev/fn.py
	```
- [PyPi](https://pypi.org/project/fn.py):
	```
	pip install fn.py
	```
- [Conda](https://anaconda.org/conda-forge/fn.py):
	```
	conda install -c conda-forge fn.py
	```
</details>
<br>

## 图形用户界面

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来创建图形用户界面程序的库。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/curses.html">curses</a></b>  - 内建的 <a href="http://www.gnu.org/software/ncurses/">ncurses</a> 封装，用来创建终端图形用户界面。

🔗&nbsp;<b><a href="https://kivy.org/">kivy</a></b>  - 一个用来创建自然用户交互（NUI）应用程序的库，可以运行在 Windows, Linux, Mac OS X, Android 以及 iOS 平台上。

🔗&nbsp;<b><a href="https://wiki.gnome.org/Projects/PyGObject">PyGObject</a></b>  - GLib/GObject/GIO/GTK+ (GTK+3) 的 Python 绑定。

🔗&nbsp;<b><a href="https://riverbankcomputing.com/software/pyqt/intro">PyQt</a></b>  - 跨平台用户界面框架 <a href="http://www.qt.io/">Qt</a> 的 Python 绑定 ，支持 Qt v4 和 Qt v5。

🔗&nbsp;<b><a href="https://wiki.python.org/moin/TkInter">Tkinter</a></b>  - Tkinter 是 Python GUI 的一个事实标准库。

🔗&nbsp;<b><a href="http://urwid.org/">urwid</a></b>  - 一个用来创建终端 GUI 应用的库，支持组件，事件和丰富的色彩等。

🔗&nbsp;<b><a href="https://wxpython.org/">wxPython</a></b>  - wxPython 是 wxWidgets C++ 类库和 Python 语言混合的产物。

<details><summary><b><a href="https://github.com/pyglet/pyglet">pyglet</a></b> (🥇28 ·  ⭐ 1K) - 一个 Python 的跨平台窗口及多媒体库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyglet/pyglet) (👨‍💻 130 · 🔀 200 · 📦 15K · 📋 300 - 20% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/pyglet/pyglet
	```
- [PyPi](https://pypi.org/project/pyglet):
	```
	pip install pyglet
	```
- [Conda](https://anaconda.org/conda-forge/pyglet) (📥 350K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge pyglet
	```
</details>
<details><summary><b><a href="https://github.com/PySimpleGUI/PySimpleGUI">PySimpleGUI</a></b> (🥈27 ·  ⭐ 9K) - tkinter，Qt，WxPython 和 Remi 的封装。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PySimpleGUI/PySimpleGUI) (👨‍💻 18 · 🔀 1.3K · 📦 4.1K · 📋 2.5K - 25% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/PySimpleGUI/PySimpleGUI
	```
- [PyPi](https://pypi.org/project/PySimpleGUI):
	```
	pip install PySimpleGUI
	```
- [Conda](https://anaconda.org/conda-forge/PySimpleGUI) (📥 44K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge PySimpleGUI
	```
</details>
<details><summary><b><a href="https://github.com/ChrisKnott/Eel">Eel</a></b> (🥈27 ·  ⭐ 4.7K) - 用于制作简单离线 HTML/JS GUI 应用的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ChrisKnott/Eel) (👨‍💻 38 · 🔀 470 · 📦 2.9K · 📋 430 - 28% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/ChrisKnott/Eel
	```
- [PyPi](https://pypi.org/project/Eel) (📥 42K / month):
	```
	pip install Eel
	```
- [Conda](https://anaconda.org/conda-forge/Eel):
	```
	conda install -c conda-forge Eel
	```
</details>
<details><summary><b><a href="https://github.com/chriskiehl/Gooey">Gooey</a></b> (🥈25 ·  ⭐ 15K) - 一条命令，将命令行程序变成一个 GUI 程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chriskiehl/Gooey) (👨‍💻 99 · 🔀 780 · 📥 160 · 📦 470 · 📋 500 - 17% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/chriskiehl/Gooey
	```
- [PyPi](https://pypi.org/project/Gooey) (📥 4.4K / month):
	```
	pip install Gooey
	```
- [Conda](https://anaconda.org/conda-forge/Gooey) (📥 42K · ⏱️ 13.06.2021):
	```
	conda install -c conda-forge Gooey
	```
</details>
<details><summary><b><a href="https://github.com/hoffstadt/DearPyGui">DearPyGui</a></b> (🥉23 ·  ⭐ 6.7K) - 一个简单的可使用 GPU 加速的 Python GUI 框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hoffstadt/DearPyGui) (🔀 310 · 📦 230 · 📋 840 - 13% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/RaylockLLC/DearPyGui/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/flexxui/flexx">Flexx</a></b> (🥉23 ·  ⭐ 2.8K) - Flexx 是一个纯 Python 语言编写的用来创建 GUI 程序的工具集，它使用 web 技术进行界面的展示。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/flexxui/flexx) (👨‍💻 37 · 🔀 250 · 📦 97 · 📋 430 - 19% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/zoofIO/flexx
	```
- [PyPi](https://pypi.org/project/flexx):
	```
	pip install flexx
	```
- [Conda](https://anaconda.org/conda-forge/flexx) (📥 84K · ⏱️ 16.09.2021):
	```
	conda install -c conda-forge flexx
	```
</details>
<details><summary><b><a href="https://github.com/r0x0r/pywebview">pywebview</a></b> (🥉22 ·  ⭐ 2.7K) - 围绕网页视图组件的轻量级跨平台的原生包装。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/r0x0r/pywebview) (🔀 350 · 📦 560 · 📋 580 - 4% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/r0x0r/pywebview/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/nucleic/enaml">enaml</a></b> (🥉21 ·  ⭐ 1.1K) - 使用类似 QML 的 Declaratic 语法来创建美观的用户界面。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nucleic/enaml) (👨‍💻 34 · 🔀 110 · 📥 75 · 📦 200 · 📋 210 - 19% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/nucleic/enaml
	```
- [PyPi](https://pypi.org/project/enaml) (📥 2.6K / month):
	```
	pip install enaml
	```
- [Conda](https://anaconda.org/conda-forge/enaml) (📥 97K · ⏱️ 21.11.2021):
	```
	conda install -c conda-forge enaml
	```
</details>
<details><summary><b><a href="https://github.com/beeware/toga">Toga</a></b> (🥉19 ·  ⭐ 2.9K) - 一个 Python 原生的, 操作系统原生的 GUI 工具包。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/beeware/toga) (👨‍💻 200 · 🔀 500 · 📋 510 - 25% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/pybee/toga
	```
- [PyPi](https://pypi.org/project/toga) (📥 2.2K / month):
	```
	pip install toga
	```
- [Conda](https://anaconda.org/conda-forge/toga):
	```
	conda install -c conda-forge toga
	```
</details>
<br>

## GraphQL

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_GraphQL 相关库。_

🔗&nbsp;<b><a href="https://tartiflette.io">tartiflette</a></b>  - 支持 Python 3.6+ 和 asyncio 的 SDL 优先的 GraphQL 引擎实现。

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇25 ·  ⭐ 7K) - Python GraphQL 框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (🔀 720 · 📦 11K · 📋 920 - 11% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/graphql-python/graphene/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/tartiflette/tartiflette-aiohttp">tartiflette-aiohttp</a></b> (🥉16 ·  ⭐ 55) - Tartiflette 的基于 aiohttp 的装饰器，用于通过 HTTP 公开 GraphQL API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tartiflette/tartiflette-aiohttp) (🔀 8 · 📦 34 · 📋 17 - 17% open · ⏱️ 15.11.2021):

	```
	git clone https://github.com/tartiflette/tartiflette-aiohttp/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/tartiflette/tartiflette-asgi">tartiflette-asgi</a></b> (🥉12 ·  ⭐ 97) - Tartiflette GraphQL 引擎的 ASGI 支持。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tartiflette/tartiflette-asgi) (🔀 14 · 📦 7 · 📋 48 - 10% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/tartiflette/tartiflette-asgi/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 游戏开发

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_超赞的游戏开发库。_

🔗&nbsp;<b><a href="https://arcade.academy/index.html">Arcade</a></b>  - 一个现代 Python 框架，用于制作具有引人入胜的图形与声音的游戏。

🔗&nbsp;<b><a href="http://cocos2d.org/">Cocos2d</a></b>  - cocos2d 是一个用来开发 2D 游戏， 示例和其他图形/交互应用的框架。基于 pyglet。

🔗&nbsp;<b><a href="http://www.harfang3d.com">Harfang3D</a></b>  - 支持3D，VR 与游戏开发的 Python 框架。

🔗&nbsp;<b><a href="https://www.panda3d.org/">Panda3D</a></b>  - 由迪士尼开发的 3D 游戏引擎，并由卡内基梅陇娱乐技术中心负责维护。使用 C++ 编写, 针对 Python 进行了完全的封装。

🔗&nbsp;<b><a href="http://www.pygame.org/news.html">Pygame</a></b>  - Pygame 是一组 Python 模块，用来编写游戏。

🔗&nbsp;<b><a href="http://www.ogre3d.org/tikiwiki/PyOgre">PyOgre</a></b>  - Ogre 3D 渲染引擎的 Python 绑定，可以用来开发游戏和仿真程序等任何 3D 应用。

🔗&nbsp;<b><a href="http://pyopengl.sourceforge.net/">PyOpenGL</a></b>  - OpenGL 的 Python 绑定及其相关 APIs。

🔗&nbsp;<b><a href="https://pysdl2.readthedocs.io">PySDL2</a></b>  - SDL2 库的封装，基于 ctypes。

🔗&nbsp;<b><a href="https://www.renpy.org/">RenPy</a></b>  - A Visual Novel engine.

<br>

## 地理位置

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_地理编码地址以及用来处理经纬度的库。_

🔗&nbsp;<b><a href="https://docs.djangoproject.com/en/dev/ref/contrib/gis/">GeoDjango</a></b>  - 世界级地理图形 web 框架。

<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥇33 ·  ⭐ 3.5K) - Python 地址编码工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 120 · 🔀 550 · 📦 31K · 📋 250 - 9% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 3.8M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 630K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥈20 ·  ⭐ 680) - GeoJSON 的 Python 绑定及工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 45 · 🔀 85 · 📦 8.2K · 📋 77 - 24% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/frewsxcv/python-geojson
	```
- [PyPi](https://pypi.org/project/python-geojson):
	```
	pip install python-geojson
	```
- [Conda](https://anaconda.org/conda-forge/python-geojson):
	```
	conda install -c conda-forge python-geojson
	```
</details>
<details><summary><b><a href="https://github.com/SmileyChris/django-countries">django-countries</a></b> (🥉19 ·  ⭐ 1.1K · 💤) - 一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SmileyChris/django-countries) (👨‍💻 45 · 🔀 220 · 📋 230 - 4% open · ⏱️ 11.05.2021):

	```
	git clone https://github.com/SmileyChris/django-countries
	```
- [PyPi](https://pypi.org/project/django-countries) (📥 380K / month):
	```
	pip install django-countries
	```
- [Conda](https://anaconda.org/conda-forge/django-countries):
	```
	conda install -c conda-forge django-countries
	```
</details>
<details><summary><b><a href="https://github.com/maxmind/geoip-api-python">GeoIP</a></b> (🥉16 ·  ⭐ 220 · 💤) - MaxMind GeoIP Legacy 数据库的 Python API。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/maxmind/geoip-api-python) (👨‍💻 13 · 🔀 53 · 📦 930 · ⏱️ 11.02.2021):

	```
	git clone https://github.com/maxmind/geoip-api-python
	```
- [PyPi](https://pypi.org/project/geoip-api-python):
	```
	pip install geoip-api-python
	```
- [Conda](https://anaconda.org/conda-forge/geoip-api-python):
	```
	conda install -c conda-forge geoip-api-python
	```
</details>
<br>

## HTML 处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_处理 HTML 和 XML 的库。_

🔗&nbsp;<b><a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">BeautifulSoup</a></b>  - 以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。

🔗&nbsp;<b><a href="https://pypi.org/project/cssutils/">cssutils</a></b>  - A CSS library for Python.

🔗&nbsp;<b><a href="http://lxml.de/">lxml</a></b>  - 一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。

🔗&nbsp;<b><a href="http://weasyprint.org">WeasyPrint</a></b>  - 用于HTML和CSS的可视化呈现引擎，并可以导出为PDF。

🔗&nbsp;<b><a href="https://xmldataset.readthedocs.io/en/latest/">xmldataset</a></b>  - Simple XML Parsing.

<details><summary><b><a href="https://github.com/martinblech/xmltodict">xmltodict</a></b> (🥇31 ·  ⭐ 4.6K · 💀) - 像处理 JSON 一样处理 XML。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinblech/xmltodict) (👨‍💻 41 · 🔀 420 · 📦 34K · 📋 200 - 32% open · ⏱️ 26.04.2020):

	```
	git clone https://github.com/martinblech/xmltodict
	```
- [PyPi](https://pypi.org/project/xmltodict) (📥 15M / month):
	```
	pip install xmltodict
	```
- [Conda](https://anaconda.org/conda-forge/xmltodict) (📥 1.3M · ⏱️ 11.02.2019):
	```
	conda install -c conda-forge xmltodict
	```
</details>
<details><summary><b><a href="https://github.com/pallets/markupsafe">MarkupSafe</a></b> (🥇31 ·  ⭐ 440) - 为 Python 实现 XML/HTML/XHTML 标记安全字符串。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/markupsafe) (👨‍💻 37 · 🔀 100 · 📦 730K · ⏱️ 05.11.2021):

	```
	git clone https://github.com/pallets/markupsafe
	```
- [PyPi](https://pypi.org/project/markupsafe) (📥 78M / month):
	```
	pip install markupsafe
	```
- [Conda](https://anaconda.org/conda-forge/markupsafe) (📥 14M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge markupsafe
	```
</details>
<details><summary><b><a href="https://github.com/gawel/pyquery">pyquery</a></b> (🥈27 ·  ⭐ 2.1K) - 一个解析 HTML 的库，类似 jQuery。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gawel/pyquery) (👨‍💻 50 · 🔀 170 · 📦 13K · 📋 170 - 25% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/gawel/pyquery
	```
- [PyPi](https://pypi.org/project/pyquery) (📥 930K / month):
	```
	pip install pyquery
	```
- [Conda](https://anaconda.org/conda-forge/pyquery) (📥 21K · ⏱️ 27.11.2020):
	```
	conda install -c conda-forge pyquery
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/bleach">bleach</a></b> (🥉26 ·  ⭐ 2.3K) - 一个基于白名单的 HTML 清理和文本链接库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mozilla/bleach) (👨‍💻 73 · 🔀 210 · 📦 150K · 📋 340 - 14% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/mozilla/bleach
	```
- [PyPi](https://pypi.org/project/bleach):
	```
	pip install bleach
	```
- [Conda](https://anaconda.org/conda-forge/bleach) (📥 5.6M · ⏱️ 25.08.2021):
	```
	conda install -c conda-forge bleach
	```
</details>
<details><summary><b><a href="https://github.com/stchris/untangle">untangle</a></b> (🥉18 ·  ⭐ 540 · 💀) - 将 XML 文档转换为 Python 对象，使其可以方便的访问。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stchris/untangle) (👨‍💻 13 · 🔀 79 · 📥 520 · 📦 750 · 📋 44 - 40% open · ⏱️ 07.08.2020):

	```
	git clone https://github.com/stchris/untangle
	```
- [PyPi](https://pypi.org/project/untangle):
	```
	pip install untangle
	```
- [Conda](https://anaconda.org/conda-forge/untangle) (📥 1.9K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge untangle
	```
</details>
<details><summary><b><a href="https://github.com/html5lib/html5lib-python">html5lib</a></b> (🥉15 ·  ⭐ 940 · 📉) - 一个兼容标准的 HTML 文档和片段解析及序列化库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/html5lib/html5lib-python) (👨‍💻 62 · 🔀 250 · 📋 240 - 34% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/html5lib/html5lib-python
	```
- [PyPi](https://pypi.org/project/html5lib-python):
	```
	pip install html5lib-python
	```
- [Conda](https://anaconda.org/conda-forge/html5lib-python):
	```
	conda install -c conda-forge html5lib-python
	```
</details>
<br>

## HTTP

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_使用 HTTP 的库。_

<details><summary><b><a href="https://github.com/psf/requests">requests</a></b> (🥇39 ·  ⭐ 47K) - 人性化的 HTTP 请求库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/psf/requests) (👨‍💻 700 · 🔀 8.3K · 📦 1.2M · 📋 3.5K - 4% open · ⏱️ 05.12.2021):

	```
	git clone https://github.com/psf/requests
	```
- [PyPi](https://pypi.org/project/requests) (📥 130M / month):
	```
	pip install requests
	```
- [Conda](https://anaconda.org/conda-forge/requests) (📥 15M · ⏱️ 24.11.2021):
	```
	conda install -c conda-forge requests
	```
</details>
<details><summary><b><a href="https://github.com/urllib3/urllib3">urllib3</a></b> (🥈36 ·  ⭐ 2.9K) - 一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/urllib3/urllib3) (👨‍💻 290 · 🔀 840 · 📥 1.1K · 📦 720K · 📋 970 - 12% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/shazow/urllib3
	```
- [PyPi](https://pypi.org/project/urllib3) (📥 190M / month):
	```
	pip install urllib3
	```
- [Conda](https://anaconda.org/conda-forge/urllib3) (📥 15M · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge urllib3
	```
</details>
<details><summary><b><a href="https://github.com/encode/httpx">httpx</a></b> (🥈28 ·  ⭐ 8.1K) - 下一代 Python HTTP 客户端。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/httpx) (👨‍💻 150 · 🔀 520 · 📦 14K · 📋 640 - 6% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/encode/httpx
	```
- [PyPi](https://pypi.org/project/httpx):
	```
	pip install httpx
	```
- [Conda](https://anaconda.org/conda-forge/httpx) (📥 94K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge httpx
	```
</details>
<details><summary><b><a href="https://github.com/spyoungtech/grequests">grequests</a></b> (🥈28 ·  ⭐ 3.9K) - requests + gevent for asynchronous HTTP requests. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/spyoungtech/grequests) (👨‍💻 28 · 🔀 300 · 📦 2.7K · 📋 100 - 8% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/spyoungtech/grequests
	```
- [PyPi](https://pypi.org/project/grequests) (📥 800K / month):
	```
	pip install grequests
	```
- [Conda](https://anaconda.org/conda-forge/grequests) (📥 44K · ⏱️ 22.04.2020):
	```
	conda install -c conda-forge grequests
	```
</details>
<details><summary><b><a href="https://github.com/httplib2/httplib2">httplib2</a></b> (🥉26 ·  ⭐ 430) - 全面的 HTTP 客户端库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/httplib2/httplib2) (👨‍💻 70 · 🔀 150 · 📦 92K · 📋 100 - 38% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/httplib2/httplib2
	```
- [PyPi](https://pypi.org/project/httplib2):
	```
	pip install httplib2
	```
- [Conda](https://anaconda.org/conda-forge/httplib2) (📥 1.2M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge httplib2
	```
</details>
<details><summary><b><a href="https://github.com/twisted/treq">treq</a></b> (🥉19 ·  ⭐ 540) - 类似 requests 的 Python API 构建于 Twisted HTTP 客户端之上。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/twisted/treq) (👨‍💻 45 · 🔀 130 · 📥 110 · 📦 890 · 📋 140 - 37% open · ⏱️ 11.07.2021):

	```
	git clone https://github.com/twisted/treq
	```
- [PyPi](https://pypi.org/project/treq):
	```
	pip install treq
	```
- [Conda](https://anaconda.org/conda-forge/treq) (📥 58K · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge treq
	```
</details>
<br>

## 硬件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来对硬件进行编程的库。_

🔗&nbsp;<b><a href="http://inotool.org/">ino</a></b>  - 操作 <a href="https://www.arduino.cc/">Arduino</a> 的命令行工具。

🔗&nbsp;<b><a href="http://www.pingo.io/">Pingo</a></b>  - Pingo 为类似 Raspberry Pi，pcDuino， Intel Galileo 等设备提供统一的 API 用以编程。

<details><summary><b><a href="https://github.com/secdev/scapy">scapy</a></b> (🥇28 ·  ⭐ 6.9K) - 一个非常棒的操作数据包的库。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/secdev/scapy) (👨‍💻 360 · 🔀 1.5K · 📦 6.8K · 📋 1.3K - 2% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/secdev/scapy
	```
- [PyPi](https://pypi.org/project/scapy):
	```
	pip install scapy
	```
- [Conda](https://anaconda.org/conda-forge/scapy) (📥 16K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge scapy
	```
</details>
<details><summary><b><a href="https://github.com/boppreh/keyboard">keyboard</a></b> (🥈26 ·  ⭐ 2.7K) - 在 Windows 和 Linux 上挂钩并模拟全局键盘事件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/boppreh/keyboard) (👨‍💻 34 · 🔀 320 · 📦 5.2K · 📋 460 - 63% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/boppreh/keyboard
	```
- [PyPi](https://pypi.org/project/keyboard):
	```
	pip install keyboard
	```
- [Conda](https://anaconda.org/conda-forge/keyboard) (📥 2.5K · ⏱️ 08.11.2021):
	```
	conda install -c conda-forge keyboard
	```
</details>
<details><summary><b><a href="https://github.com/boppreh/mouse">mouse</a></b> (🥉21 ·  ⭐ 550 · 💤) - 在 Windows 和 Linux 上挂钩并模拟全局键盘事件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/boppreh/mouse) (👨‍💻 8 · 🔀 83 · 📦 470 · 📋 92 - 71% open · ⏱️ 05.04.2021):

	```
	git clone https://github.com/boppreh/mouse
	```
- [PyPi](https://pypi.org/project/mouse) (📥 18K / month):
	```
	pip install mouse
	```
- [Conda](https://anaconda.org/conda-forge/mouse):
	```
	conda install -c conda-forge mouse
	```
</details>
<details><summary><b><a href="https://github.com/SavinaRoja/PyUserInput">PyUserInput</a></b> (🥉17 ·  ⭐ 990 · 💤) - 跨平台的，控制鼠标和键盘的模块。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/SavinaRoja/PyUserInput) (👨‍💻 21 · 🔀 170 · 📦 400 · 📋 96 - 68% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/SavinaRoja/PyUserInput
	```
- [PyPi](https://pypi.org/project/PyUserInput):
	```
	pip install PyUserInput
	```
- [Conda](https://anaconda.org/conda-forge/PyUserInput):
	```
	conda install -c conda-forge PyUserInput
	```
</details>
<details><summary><b><a href="https://github.com/rockymeza/wifi">wifi</a></b> (🥉15 ·  ⭐ 280 · 💀) - 一个 Python 库和命令行工具用来在 Linux 平台上操作 WiFi。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/rockymeza/wifi) (👨‍💻 13 · 🔀 140 · 📦 350 · 📋 64 - 51% open · ⏱️ 20.03.2017):

	```
	git clone https://github.com/rockymeza/wifi
	```
- [PyPi](https://pypi.org/project/wifi):
	```
	pip install wifi
	```
- [Conda](https://anaconda.org/conda-forge/wifi):
	```
	conda install -c conda-forge wifi
	```
</details>
<br>

## 图像处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来操作图像的库._

🔗&nbsp;<b><a href="https://sourceforge.net/projects/imgseek/">imgSeek</a></b>  - 一个使用视觉相似性搜索一组图片集合的项目。

🔗&nbsp;<b><a href="http://github.com/pymatting/pymatting">PyMatting</a></b>  - 支持 alpha matting 的库。

🔗&nbsp;<b><a href="http://scikit-image.org/">scikit-image</a></b>  - 一个用于（科学）图像处理的 Python 库。

<details><summary><b><a href="https://github.com/thumbor/thumbor">thumbor</a></b> (🥇29 ·  ⭐ 8.7K) - 一个小型图像服务，具有剪裁，尺寸重设和翻转功能。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thumbor/thumbor) (👨‍💻 160 · 🔀 710 · 📦 290 · 📋 860 - 14% open · ⏱️ 26.11.2021):

	```
	git clone https://github.com/thumbor/thumbor
	```
- [PyPi](https://pypi.org/project/thumbor) (📥 8.4K / month):
	```
	pip install thumbor
	```
- [Conda](https://anaconda.org/conda-forge/thumbor):
	```
	conda install -c conda-forge thumbor
	```
</details>
<details><summary><b><a href="https://github.com/python-pillow/Pillow">pillow</a></b> (🥇26 ·  ⭐ 9.3K · 📉) - Pillow is the friendly.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 380 · 🔀 1.6K · 📋 2.4K - 5% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 34M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/Pillow) (📥 12M · ⏱️ 10.11.2021):
	```
	conda install -c conda-forge Pillow
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">wand</a></b> (🥇26 ·  ⭐ 1.1K) - Python bindings for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 97 · 🔀 190 · 📥 5.3K · 📦 8K · 📋 360 - 3% open · ⏱️ 20.11.2021):

	```
	git clone https://github.com/dahlia/wand
	```
- [PyPi](https://pypi.org/project/wand):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 7.9K · ⏱️ 30.11.2020):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/WhyNotHugo/python-barcode">python-barcode</a></b> (🥈25 ·  ⭐ 300) - 不借助其他库在 Python 程序中生成条形码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WhyNotHugo/python-barcode) (👨‍💻 40 · 🔀 87 · 📥 180 · 📦 10K · 📋 81 - 37% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/WhyNotHugo/python-barcode
	```
- [PyPi](https://pypi.org/project/python-barcode) (📥 130K / month):
	```
	pip install python-barcode
	```
- [Conda](https://anaconda.org/conda-forge/python-barcode) (📥 4.6K · ⏱️ 22.08.2020):
	```
	conda install -c conda-forge python-barcode
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥈22 ·  ⭐ 380) - 低内存消耗且快速的图像处理库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 12 · 🔀 32 · 📦 250 · 📋 260 - 36% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 16K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 14K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/dylanaraps/pywal">pywal</a></b> (🥉21 ·  ⭐ 5.9K) - 由图像生成配色方案的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dylanaraps/pywal) (👨‍💻 60 · 🔀 240 · 📥 660 · 📦 160 · 📋 480 - 21% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/dylanaraps/pywal
	```
- [PyPi](https://pypi.org/project/pywal):
	```
	pip install pywal
	```
- [Conda](https://anaconda.org/conda-forge/pywal):
	```
	conda install -c conda-forge pywal
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉16 ·  ⭐ 830 · 💀) - 裸体检测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/nude.py) (👨‍💻 12 · 🔀 130 · 📦 1.4K · 📋 10 - 70% open · ⏱️ 23.11.2020):

	```
	git clone https://github.com/hhatto/nude.py
	```
- [PyPi](https://pypi.org/project/nude.py):
	```
	pip install nude.py
	```
- [Conda](https://anaconda.org/conda-forge/nude.py):
	```
	conda install -c conda-forge nude.py
	```
</details>
<details><summary><b><a href="https://github.com/daboth/pagan">pagan</a></b> (🥉15 ·  ⭐ 240) - 基于输入和哈希的复古风图标（头像）生成工具。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/daboth/pagan) (👨‍💻 9 · 🔀 34 · 📦 39 · 📋 7 - 57% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/daboth/pagan
	```
- [PyPi](https://pypi.org/project/pagan):
	```
	pip install pagan
	```
- [Conda](https://anaconda.org/conda-forge/pagan):
	```
	conda install -c conda-forge pagan
	```
</details>
<details><summary><b><a href="https://github.com/lincolnloop/python-qrcode">python-qrcode</a></b> (🥉14 ·  ⭐ 2.8K) - 一个纯 Python 实现的二维码生成器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lincolnloop/python-qrcode) (👨‍💻 48 · 🔀 460 · 📋 150 - 15% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/lincolnloop/python-qrcode
	```
- [PyPi](https://pypi.org/project/python-qrcode):
	```
	pip install python-qrcode
	```
- [Conda](https://anaconda.org/conda-forge/python-qrcode):
	```
	conda install -c conda-forge python-qrcode
	```
</details>
<details><summary><b><a href="https://github.com/fogleman/Quads">Quads</a></b> (🥉10 ·  ⭐ 1K · 💀) - 基于四叉树的计算机艺术。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fogleman/Quads) (🔀 120 · ⏱️ 20.05.2014):

	```
	git clone https://github.com/fogleman/Quads
	```
- [PyPi](https://pypi.org/project/Quads) (📥 130 / month):
	```
	pip install Quads
	```
- [Conda](https://anaconda.org/conda-forge/Quads):
	```
	conda install -c conda-forge Quads
	```
</details>
<details><summary><b><a href="https://github.com/rossgoodwin/hmap">hmap</a></b> (🥉10 ·  ⭐ 190 · 💀) - 图像直方图映射。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rossgoodwin/hmap) (👨‍💻 3 · 🔀 19 · ⏱️ 04.11.2019):

	```
	git clone https://github.com/rossgoodwin/hmap
	```
- [PyPi](https://pypi.org/project/hmap) (📥 160 / month):
	```
	pip install hmap
	```
- [Conda](https://anaconda.org/conda-forge/hmap):
	```
	conda install -c conda-forge hmap
	```
</details>
<details><summary><b><a href="https://github.com/ajknzhol/pygram">pygram</a></b> (🥉6 ·  ⭐ 100 · 💀) - 类似 Instagram 的图像滤镜。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ajknzhol/pygram) (🔀 12 · ⏱️ 22.02.2014):

	```
	git clone https://github.com/ajkumar25/pygram
	```
- [PyPi](https://pypi.org/project/pygram):
	```
	pip install pygram
	```
- [Conda](https://anaconda.org/conda-forge/pygram):
	```
	conda install -c conda-forge pygram
	```
</details>
<br>

## 高性能

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_让 Python 更快的库。_

🔗&nbsp;<b><a href="http://cython.org/">Cython</a></b>  - 优化的 Python 静态编译器。使用类型混合使 Python 编译成 C 或 C++ 模块来获得性能的极大提升。

🔗&nbsp;<b><a href="https://hg.python.org/jython">Jython</a></b>  - 为 JVM 用 Java 编写的 Python 编程语言的实现。

🔗&nbsp;<b><a href="http://numba.pydata.org/">Numba</a></b>  - Python JIT (just in time) 编译器，针对科学用的 Python ，由 Cython 和 NumPy 的开发者开发。

🔗&nbsp;<b><a href="https://foss.heptapod.net/pypy/pypy">PyPy</a></b>  - 使用 Python 实现的 Python。解释器使用黑魔法加快 Python 运行速度且不需要加入额外的类型信息。

<details><summary><b><a href="https://github.com/micropython/micropython">MicroPython</a></b> (🥇23 ·  ⭐ 13K) - 精简高效的 Python 编程语言实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/micropython/micropython) (👨‍💻 460 · 🔀 3.7K · 📥 30K · 📋 3.9K - 27% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/micropython/micropython
	```
- [PyPi](https://pypi.org/project/micropython):
	```
	pip install micropython
	```
- [Conda](https://anaconda.org/conda-forge/micropython) (📥 5.1K · ⏱️ 14.09.2021):
	```
	conda install -c conda-forge micropython
	```
</details>
<details><summary><b><a href="https://github.com/IronLanguages/ironpython3">IronPython</a></b> (🥈19 ·  ⭐ 1.6K) - 用 Common Lisp 编写的 Python 编程语言的实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IronLanguages/ironpython3) (👨‍💻 29 · 🔀 190 · 📥 15K · 📋 420 - 45% open · ⏱️ 20.11.2021):

	```
	git clone https://github.com/IronLanguages/ironpython3
	```
- [PyPi](https://pypi.org/project/ironpython3):
	```
	pip install ironpython3
	```
- [Conda](https://anaconda.org/conda-forge/ironpython3):
	```
	conda install -c conda-forge ironpython3
	```
</details>
<details><summary><b><a href="https://github.com/python/cpython">CPython</a></b> (🥈17 ·  ⭐ 42K) - **Default, most widely used implementation of the Python.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python/cpython) (👨‍💻 1.9K · 🔀 21K · ⏱️ 23.12.2021):

	```
	git clone https://github.com/python/cpython
	```
- [PyPi](https://pypi.org/project/cpython):
	```
	pip install cpython
	```
- [Conda](https://anaconda.org/conda-forge/cpython):
	```
	conda install -c conda-forge cpython
	```
</details>
<details><summary><b><a href="https://github.com/google/grumpy">Grumpy</a></b> (🥈16 ·  ⭐ 10K · 💀) - 编译器比解释器更强大的 cpython2.7 替代品（alpha）。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/grumpy) (👨‍💻 30 · 🔀 630 · 📋 140 - 44% open · ⏱️ 22.11.2017):

	```
	git clone https://github.com/google/grumpy
	```
- [PyPi](https://pypi.org/project/grumpy):
	```
	pip install grumpy
	```
- [Conda](https://anaconda.org/conda-forge/grumpy):
	```
	conda install -c conda-forge grumpy
	```
</details>
<details><summary><b><a href="https://github.com/Maratyszcza/PeachPy">PeachPy</a></b> (🥉14 ·  ⭐ 1.6K) - 嵌入 Python 的 x86-64 汇编器。可以被用作 Python 内联的汇编器或者是独立的汇编器，用于 Windows, Linux, OS X, Native Client 或者 Go 。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Maratyszcza/PeachPy) (👨‍💻 21 · 🔀 130 · 📦 9 · 📋 82 - 25% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/Maratyszcza/PeachPy
	```
- [PyPi](https://pypi.org/project/PeachPy):
	```
	pip install PeachPy
	```
- [Conda](https://anaconda.org/conda-forge/PeachPy):
	```
	conda install -c conda-forge PeachPy
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/Pyjion">Pyjion</a></b> (🥉13 ·  ⭐ 1.5K · 💀) - 基于 CoreCLR 的 Python JIT。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/Pyjion) (👨‍💻 17 · 🔀 67 · 📋 110 - 33% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Microsoft/Pyjion
	```
- [PyPi](https://pypi.org/project/Pyjion):
	```
	pip install Pyjion
	```
- [Conda](https://anaconda.org/conda-forge/Pyjion):
	```
	conda install -c conda-forge Pyjion
	```
</details>
<details><summary><b><a href="https://github.com/pyston/pyston_v1">Pyston</a></b> (🥉12 ·  ⭐ 5K · 💤) - 使用 LLVM 和现代 JIT 技术构建的 Python 实现，目标是为了获得很好的性能。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyston/pyston_v1) (🔀 300 · 📥 5.1K · 📋 280 - 3% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/dropbox/pyston
	```
- [PyPi](https://pypi.org/project/pyston):
	```
	pip install pyston
	```
- [Conda](https://anaconda.org/conda-forge/pyston):
	```
	conda install -c conda-forge pyston
	```
</details>
<details><summary><b><a href="https://github.com/stackless-dev/stackless">Stackless Python</a></b> (🥉11 ·  ⭐ 780) - 一个强化版的 Python。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stackless-dev/stackless) (👨‍💻 1K · 🔀 53 · 📋 270 - 4% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/stackless-dev/stackless
	```
- [PyPi](https://pypi.org/project/stackless) (📥 32 / month):
	```
	pip install stackless
	```
- [Conda](https://anaconda.org/conda-forge/stackless):
	```
	conda install -c conda-forge stackless
	```
</details>
<details><summary><b><a href="https://github.com/metawilm/cl-python">CLPython</a></b> (🥉11 ·  ⭐ 330 · 💀) - 用 Common Lisp 编写的 Python 编程语言的实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/metawilm/cl-python) (👨‍💻 12 · 🔀 31 · 📋 16 - 18% open · ⏱️ 15.04.2020):

	```
	git clone https://github.com/metawilm/cl-python
	```
- [PyPi](https://pypi.org/project/cl-python):
	```
	pip install cl-python
	```
- [Conda](https://anaconda.org/conda-forge/cl-python):
	```
	conda install -c conda-forge cl-python
	```
</details>
<br>

## 交互式解析器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_交互式 Python 解析器。_

🔗&nbsp;<b><a href="https://jupyter.org">Jupyter Notebook (IPython)</a></b>  - 一个能够让你最大限度地以交互式方式使用 Python 的丰富工具包。

🔗&nbsp;<b><a href="https://github.com/markusschanta/awesome-jupyter">awesome-jupyter</a></b> ( ⭐ 2.5K)  - A curated list of awesome Jupyter projects, libraries and resources.

<details><summary><b><a href="https://github.com/prompt-toolkit/ptpython">ptpython</a></b> (🥇27 ·  ⭐ 4.4K) - 高级交互式 Python 解析器， 构建于 <a href="https://github.com/jonathanslenders/python-prompt-toolkit">python-prompt-toolkit</a> 之上。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/prompt-toolkit/ptpython) (👨‍💻 50 · 🔀 250 · 📦 1.6K · 📋 330 - 55% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/jonathanslenders/ptpython
	```
- [PyPi](https://pypi.org/project/ptpython) (📥 260K / month):
	```
	pip install ptpython
	```
- [Conda](https://anaconda.org/conda-forge/ptpython) (📥 7.6K · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge ptpython
	```
</details>
<details><summary><b><a href="https://github.com/bpython/bpython">bpython</a></b> (🥉20 ·  ⭐ 2K) - 界面丰富的 Python 解析器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/bpython/bpython) (👨‍💻 120 · 🔀 200 · 📋 750 - 17% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/bpython/bpython
	```
- [PyPi](https://pypi.org/project/bpython) (📥 77K / month):
	```
	pip install bpython
	```
- [Conda](https://anaconda.org/conda-forge/bpython) (📥 31K · ⏱️ 26.01.2021):
	```
	conda install -c conda-forge bpython
	```
</details>
<br>

## 国际化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行国际化的库。_

🔗&nbsp;<b><a href="http://babel.pocoo.org/en/latest/">Babel</a></b>  - 一个 Python 的国际化库。

<details><summary><b><a href="https://github.com/ovalhub/pyicu">PyICU</a></b> (🥇21 ·  ⭐ 130 · 💤) - 一个封装了 <a href="http://site.icu-project.org/">ICU</a> C++ 库的 Python 扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ovalhub/pyicu) (👨‍💻 18 · 🔀 58 · 📦 2.1K · ⏱️ 08.04.2021):

	```
	git clone https://github.com/ovalhub/pyicu
	```
- [PyPi](https://pypi.org/project/pyicu) (📥 180K / month):
	```
	pip install pyicu
	```
- [Conda](https://anaconda.org/conda-forge/pyicu) (📥 74K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge pyicu
	```
</details>
<br>

## 任务调度

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_任务调度库。_

🔗&nbsp;<b><a href="https://airflow.apache.org/">Airflow</a></b>  - 是一个工作流分配管理系统，通过有向非循环图的方式管理任务流程，设置任务依赖关系和时间调度。

🔗&nbsp;<b><a href="http://apscheduler.readthedocs.io/en/latest/">APScheduler</a></b>  - 轻巧但强大的进程内任务调度，使你可以调度函数。

🔗&nbsp;<b><a href="http://pydoit.org/">doit</a></b>  - 一个任务执行和构建工具。

🔗&nbsp;<b><a href="https://joblib.readthedocs.io/">Joblib</a></b>  - 一组为 Python 提供轻量级作业流水线的工具。

🔗&nbsp;<b><a href="https://docs.openstack.org/developer/taskflow/">TaskFlow</a></b>  - 一个可以让你方便执行任务的 Python 库，一致并且可靠。

<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥇29 ·  ⭐ 8K) - 一个现代的工作流程编排框架，使构建、计划和监视健壮的数据管道变得容易。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 280 · 🔀 740 · 📦 530 · 📋 2K - 18% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 230K · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/dbader/schedule">schedule</a></b> (🥈26 ·  ⭐ 9.3K) - 人性化的 Python 任务调度库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dbader/schedule) (👨‍💻 45 · 🔀 760 · 📦 15K · 📋 350 - 30% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/dbader/schedule
	```
- [PyPi](https://pypi.org/project/schedule):
	```
	pip install schedule
	```
- [Conda](https://anaconda.org/conda-forge/schedule) (📥 10K · ⏱️ 10.04.2021):
	```
	conda install -c conda-forge schedule
	```
</details>
<details><summary><b><a href="https://github.com/sartography/SpiffWorkflow">Spiff</a></b> (🥈22 ·  ⭐ 1.1K) - 使用纯 Python 实现的强大的工作流引擎。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/sartography/SpiffWorkflow) (👨‍💻 43 · 🔀 240 · 📦 28 · 📋 73 - 2% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/knipknap/SpiffWorkflow
	```
- [PyPi](https://pypi.org/project/SpiffWorkflow) (📥 2.9K / month):
	```
	pip install SpiffWorkflow
	```
- [Conda](https://anaconda.org/conda-forge/SpiffWorkflow):
	```
	conda install -c conda-forge SpiffWorkflow
	```
</details>
<details><summary><b><a href="https://github.com/fengsp/plan">Plan</a></b> (🥉13 ·  ⭐ 1.1K · 💀) - 如有神助地编写 crontab 文件。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fengsp/plan) (👨‍💻 7 · 🔀 89 · 📦 66 · 📋 9 - 11% open · ⏱️ 14.05.2020):

	```
	git clone https://github.com/fengsp/plan
	```
- [PyPi](https://pypi.org/project/plan):
	```
	pip install plan
	```
- [Conda](https://anaconda.org/conda-forge/plan):
	```
	conda install -c conda-forge plan
	```
</details>
<details><summary><b><a href="https://github.com/gunnery/gunnery">gunnery</a></b> (🥉13 ·  ⭐ 730 · 💀) - 分布式系统使用的多用途任务执行工具 ，具有 web 交互界面。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gunnery/gunnery) (👨‍💻 7 · 🔀 75 · 📋 37 - 27% open · ⏱️ 29.10.2015):

	```
	git clone https://github.com/gunnery/gunnery
	```
- [PyPi](https://pypi.org/project/gunnery):
	```
	pip install gunnery
	```
- [Conda](https://anaconda.org/conda-forge/gunnery):
	```
	conda install -c conda-forge gunnery
	```
</details>
<details><summary><b><a href="https://github.com/thauber/django-schedule">django-schedule</a></b> (🥉11 ·  ⭐ 800 · 💀) - 一个 Django 排程应用。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/thauber/django-schedule) (👨‍💻 17 · 🔀 190 · 📋 58 - 34% open · ⏱️ 16.04.2016):

	```
	git clone https://github.com/thauber/django-schedule
	```
- [PyPi](https://pypi.org/project/django-schedule):
	```
	pip install django-schedule
	```
- [Conda](https://anaconda.org/conda-forge/django-schedule):
	```
	conda install -c conda-forge django-schedule
	```
</details>
<br>

## 日志

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来生成和操作日志的库。_

🔗&nbsp;<b><a href="http://logbook.readthedocs.io/en/stable/">logbook</a></b>  - Logging 库的替代品。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/logging.html">logging</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://www.structlog.org/en/stable/">structlog</a></b>  - 结构化日志，让日志变得简单。

<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇31 ·  ⭐ 11K) - 旨在带来愉悦体验的 Python 日志库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 30 · 🔀 460 · 📦 13K · 📋 500 - 17% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 2M / month):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 330K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-python</a></b> (🥉27 ·  ⭐ 1.1K) - Python 版 Sentry SDK。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 110 · 🔀 240 · 📥 4.5K · 📦 16K · 📋 580 - 26% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-python):
	```
	pip install sentry-python
	```
- [Conda](https://anaconda.org/conda-forge/sentry-python):
	```
	conda install -c conda-forge sentry-python
	```
</details>
<br>

## 机器学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_机器学习相关库，也可以参考 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python)。_

🔗&nbsp;<b><a href="http://scikit-learn.org/">scikit-learn</a></b>  - 基于 SciPy 构建的机器学习 Python 模块。

🔗&nbsp;<b><a href="http://spark.apache.org/docs/latest/ml-guide.html">Spark ML</a></b>  - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.

<details><summary><b><a href="https://github.com/dmlc/xgboost">xgboost</a></b> (🥇37 ·  ⭐ 22K) - 可扩展，便携式和分布式梯度提升库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 540 · 🔀 7.7K · 📥 3.5K · 📦 25K · 📋 4.2K - 6% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 8.6M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2.2M · ⏱️ 20.11.2021):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/openai/gym">gym</a></b> (🥈34 ·  ⭐ 26K) - 在 AWS Lambda 开发和部署 Python 代码的工具包。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 330 · 🔀 7K · 📦 25K · 📋 1.4K - 6% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 900K / month):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 84K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥈24 ·  ⭐ 6.3K · 💀) - 智能计算 Numenta 平台。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/numenta/nupic) (👨‍💻 120 · 🔀 1.6K · 📦 110 · 📋 1.8K - 25% open · ⏱️ 23.10.2019):

	```
	git clone https://github.com/numenta/nupic
	```
- [PyPi](https://pypi.org/project/nupic) (📥 3.7K / month):
	```
	pip install nupic
	```
- [Conda](https://anaconda.org/conda-forge/nupic):
	```
	conda install -c conda-forge nupic
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/h2o-3">H2O</a></b> (🥉20 ·  ⭐ 5.7K) - 开源快速可扩展的机器学习平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/h2oai/h2o-3) (👨‍💻 220 · 🔀 1.8K · ⏱️ 23.12.2021):

	```
	git clone https://github.com/h2oai/h2o-3
	```
- [PyPi](https://pypi.org/project/h2o-3):
	```
	pip install h2o-3
	```
- [Conda](https://anaconda.org/conda-forge/h2o-3):
	```
	conda install -c conda-forge h2o-3
	```
</details>
<details><summary><b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉19 ·  ⭐ 4.2K) - MindsDB是现有数据库的开源AI层，可让使用标准查询轻松地进行开发，训练和部署最新的机器学习模型。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/mindsdb/mindsdb) (👨‍💻 89 · 🔀 550 · 📋 780 - 9% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/mindsdb/mindsdb
	```
- [PyPi](https://pypi.org/project/mindsdb) (📥 1.1K / month):
	```
	pip install mindsdb
	```
- [Conda](https://anaconda.org/conda-forge/mindsdb):
	```
	conda install -c conda-forge mindsdb
	```
</details>
<details><summary><b><a href="https://github.com/benhamner/Metrics">Metrics</a></b> (🥉15 ·  ⭐ 1.5K · 💀) - 机器学习的评估指标。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/benhamner/Metrics) (👨‍💻 7 · 🔀 400 · 📋 17 - 58% open · ⏱️ 09.09.2015):

	```
	git clone https://github.com/benhamner/Metrics
	```
- [PyPi](https://pypi.org/project/Metrics) (📥 4K / month):
	```
	pip install Metrics
	```
- [Conda](https://anaconda.org/conda-forge/Metrics):
	```
	conda install -c conda-forge Metrics
	```
</details>
<details><summary><b><a href="https://github.com/josephreisinger/vowpal_porpoise">vowpal_porpoise</a></b> (🥉9 ·  ⭐ 160 · 💀) - 支持 <a href="https://lucene.apache.org/solr/">Apache Solr</a> 的轻量级 Python 装饰器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/josephreisinger/vowpal_porpoise) (👨‍💻 14 · 🔀 28 · 📋 9 - 66% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/josephreisinger/vowpal_porpoise
	```
- [PyPi](https://pypi.org/project/vowpal_porpoise) (📥 4 / month):
	```
	pip install vowpal_porpoise
	```
- [Conda](https://anaconda.org/conda-forge/vowpal_porpoise):
	```
	conda install -c conda-forge vowpal_porpoise
	```
</details>
<br>

## 微软的 Windows 平台

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_在 Windows 平台上进行 Python 编程。_

🔗&nbsp;<b><a href="http://python-xy.github.io/">Python(x,y)</a></b>  - 面向科学应用的 Python 发行版，基于 Qt 和 Spyder。

🔗&nbsp;<b><a href="http://www.lfd.uci.edu/~gohlke/pythonlibs/">pythonlibs</a></b>  - 非官方的 Windows 平台 Python 扩展二进制包。

🔗&nbsp;<b><a href="https://winpython.github.io/">WinPython</a></b>  - Windows 7/8 系统下便携式开发环境。

<details><summary><b><a href="https://github.com/mhammond/pywin32">PyWin32</a></b> (🥇27 ·  ⭐ 3.5K) - 针对 Windows 的 Python 扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mhammond/pywin32) (👨‍💻 70 · 🔀 640 · 📥 510K · 📦 63K · 📋 1.6K - 26% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/mhammond/pywin32
	```
- [PyPi](https://pypi.org/project/pywin32) (📥 2.8M / month):
	```
	pip install pywin32
	```
- [Conda](https://anaconda.org/conda-forge/pywin32) (📥 2M · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge pywin32
	```
</details>
<details><summary><b><a href="https://github.com/pythonnet/pythonnet">PythonNet</a></b> (🥇27 ·  ⭐ 2.9K) - Python 与 .NET 公共语言运行库 (CLR)的集成。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pythonnet/pythonnet) (👨‍💻 95 · 🔀 470 · 📦 58 · 📋 1.1K - 15% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/pythonnet/pythonnet
	```
- [PyPi](https://pypi.org/project/pythonnet) (📥 110K / month):
	```
	pip install pythonnet
	```
- [Conda](https://anaconda.org/conda-forge/pythonnet) (📥 32K · ⏱️ 21.08.2021):
	```
	conda install -c conda-forge pythonnet
	```
</details>
<br>

## 杂项

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_不属于上面任何一个类别，但是非常有用的库。_

🔗&nbsp;<b><a href="http://www.tryton.org/">tryton</a></b>  - 一个通用业务框架。

<details><summary><b><a href="https://github.com/pallets/itsdangerous">itsdangerous</a></b> (🥇29 ·  ⭐ 2.4K) - 将受信任的数据传递到不受信任的环境的帮助工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/itsdangerous) (👨‍💻 38 · 🔀 180 · 📦 530K · ⏱️ 05.11.2021):

	```
	git clone https://github.com/pallets/itsdangerous
	```
- [PyPi](https://pypi.org/project/itsdangerous):
	```
	pip install itsdangerous
	```
- [Conda](https://anaconda.org/conda-forge/itsdangerous) (📥 2.5M · ⏱️ 18.05.2021):
	```
	conda install -c conda-forge itsdangerous
	```
</details>
<details><summary><b><a href="https://github.com/jek/blinker">blinker</a></b> (🥇29 ·  ⭐ 1.3K · 💤) - 快速的 Python 运行时信号/事件分配系统。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jek/blinker) (👨‍💻 11 · 🔀 160 · 📦 89K · 📋 34 - 52% open · ⏱️ 29.01.2021):

	```
	git clone https://github.com/jek/blinker
	```
- [PyPi](https://pypi.org/project/blinker) (📥 4.7M / month):
	```
	pip install blinker
	```
- [Conda](https://anaconda.org/conda-forge/blinker) (📥 3.9M · ⏱️ 20.06.2018):
	```
	conda install -c conda-forge blinker
	```
</details>
<details><summary><b><a href="https://github.com/mahmoud/boltons">boltons</a></b> (🥉28 ·  ⭐ 5.7K) - 一组纯 Python 实用工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mahmoud/boltons) (👨‍💻 72 · 🔀 310 · 📥 23 · 📦 1.9K · 📋 130 - 29% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/mahmoud/boltons
	```
- [PyPi](https://pypi.org/project/boltons) (📥 1.4M / month):
	```
	pip install boltons
	```
- [Conda](https://anaconda.org/conda-forge/boltons) (📥 530K · ⏱️ 27.05.2021):
	```
	conda install -c conda-forge boltons
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">magenta</a></b> (🥉26 ·  ⭐ 17K) - 使用人工智能生成音乐与艺术的工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.5K · 📦 330 · 📋 860 - 33% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 7.5K / month):
	```
	pip install magenta
	```
- [Conda](https://anaconda.org/conda-forge/magenta):
	```
	conda install -c conda-forge magenta
	```
</details>
<details><summary><b><a href="https://github.com/mitsuhiko/pluginbase">pluginbase</a></b> (🥉21 ·  ⭐ 990 · 💤) - 一个简单但灵活的Python插件系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mitsuhiko/pluginbase) (👨‍💻 9 · 🔀 140 · 📦 1.1K · ⏱️ 16.05.2021):

	```
	git clone https://github.com/mitsuhiko/pluginbase
	```
- [PyPi](https://pypi.org/project/pluginbase) (📥 430K / month):
	```
	pip install pluginbase
	```
- [Conda](https://anaconda.org/conda-forge/pluginbase) (📥 210K · ⏱️ 04.02.2019):
	```
	conda install -c conda-forge pluginbase
	```
</details>
<br>

## 自然语言处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来处理人类语言的库。_

🔗&nbsp;<b><a href="http://www.nltk.org/">nltk</a></b>  - 一个先进的平台，用以构建处理人类语言数据的 Python 程序。

🔗&nbsp;<b><a href="https://spacy.io/">spacy</a></b>  - Python 和 Cython 中用于工业级自然语言处理的库。

<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇36 ·  ⭐ 13K) - 人性化的话题建模库。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 420 · 🔀 3.9K · 📥 3.5K · 📦 29K · 📋 1.7K - 20% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 10M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 760K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/fxsjy/jieba">jieba</a></b> (🥇28 ·  ⭐ 28K · 💀) - 中文分词工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fxsjy/jieba) (👨‍💻 48 · 🔀 6.2K · 📦 12K · 📋 790 - 73% open · ⏱️ 15.02.2020):

	```
	git clone https://github.com/fxsjy/jieba
	```
- [PyPi](https://pypi.org/project/jieba):
	```
	pip install jieba
	```
- [Conda](https://anaconda.org/conda-forge/jieba) (📥 100K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge jieba
	```
</details>
<details><summary><b><a href="https://github.com/clips/pattern">pattern</a></b> (🥇28 ·  ⭐ 8.1K · 💀) - Python 网络挖掘模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/clips/pattern) (👨‍💻 30 · 🔀 1.5K · 📦 1.2K · 📋 200 - 62% open · ⏱️ 25.04.2020):

	```
	git clone https://github.com/clips/pattern
	```
- [PyPi](https://pypi.org/project/pattern) (📥 98K / month):
	```
	pip install pattern
	```
- [Conda](https://anaconda.org/conda-forge/pattern) (📥 9.1K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge pattern
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">Stanza</a></b> (🥈24 ·  ⭐ 5.9K) - 斯坦福 NLP 集团的官方 Python 库，支持60多种语言。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 41 · 🔀 740 · 📦 790 · 📋 620 - 11% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 320K / month):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/conda-forge/stanza) (📥 2.1K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge stanza
	```
</details>
<details><summary><b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥈23 ·  ⭐ 1.9K · 💀) - 支持数百种语言的自然语言处理管道。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/aboSamoor/polyglot) (👨‍💻 26 · 🔀 300 · 📦 620 · 📋 200 - 68% open · ⏱️ 22.09.2020):

	```
	git clone https://github.com/aboSamoor/polyglot
	```
- [PyPi](https://pypi.org/project/polyglot) (📥 85K / month):
	```
	pip install polyglot
	```
- [Conda](https://anaconda.org/conda-forge/polyglot):
	```
	conda install -c conda-forge polyglot
	```
</details>
<details><summary><b><a href="https://github.com/lancopku/pkuseg-python">pkuseg-python</a></b> (🥉22 ·  ⭐ 5.7K · 💀) - 一个支持对不同领域进行中文分词的工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lancopku/pkuseg-python) (👨‍💻 6 · 🔀 900 · 📥 72K · 📦 160 · 📋 150 - 72% open · ⏱️ 21.06.2020):

	```
	git clone https://github.com/lancopku/pkuseg-python
	```
- [PyPi](https://pypi.org/project/pkuseg-python):
	```
	pip install pkuseg-python
	```
- [Conda](https://anaconda.org/conda-forge/pkuseg-python):
	```
	conda install -c conda-forge pkuseg-python
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">PyTorch-NLP</a></b> (🥉20 ·  ⭐ 2K) - 一个支持快速深度学习 NLP 原型研究的工具包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 240 · 📦 310 · 📋 66 - 25% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/PyTorch-NLP):
	```
	pip install PyTorch-NLP
	```
- [Conda](https://anaconda.org/conda-forge/PyTorch-NLP):
	```
	conda install -c conda-forge PyTorch-NLP
	```
</details>
<details><summary><b><a href="https://github.com/isnowfy/snownlp">snownlp</a></b> (🥉19 ·  ⭐ 5.7K · 💀) - 一个用来处理中文文本的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isnowfy/snownlp) (👨‍💻 8 · 🔀 1.3K · 📦 760 · 📋 100 - 37% open · ⏱️ 19.01.2020):

	```
	git clone https://github.com/isnowfy/snownlp
	```
- [PyPi](https://pypi.org/project/snownlp):
	```
	pip install snownlp
	```
- [Conda](https://anaconda.org/conda-forge/snownlp) (📥 260 · ⏱️ 07.09.2021):
	```
	conda install -c conda-forge snownlp
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">pytext</a></b> (🥉18 ·  ⭐ 6.3K) - 基于 PyTouch 的自然语言模型框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 220 · 🔀 790 · 📥 280 · 📦 100 · 📋 130 - 44% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/facebookresearch/pytext
	```
- [PyPi](https://pypi.org/project/pytext):
	```
	pip install pytext
	```
- [Conda](https://anaconda.org/conda-forge/pytext):
	```
	conda install -c conda-forge pytext
	```
</details>
<details><summary><b><a href="https://github.com/saffsd/langid.py">langid.py</a></b> (🥉17 ·  ⭐ 1.9K · 💀) - 独立的语言识别系统。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/saffsd/langid.py) (👨‍💻 9 · 🔀 280 · 📦 870 · 📋 71 - 36% open · ⏱️ 15.07.2017):

	```
	git clone https://github.com/saffsd/langid.py
	```
- [PyPi](https://pypi.org/project/langid.py):
	```
	pip install langid.py
	```
- [Conda](https://anaconda.org/conda-forge/langid.py):
	```
	conda install -c conda-forge langid.py
	```
</details>
<details><summary><b><a href="https://github.com/fighting41love/funNLP">funNLP</a></b> (🥉14 ·  ⭐ 36K) - 中文自然语言处理的工具和数据集。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fighting41love/funNLP) (👨‍💻 10 · 🔀 9.8K · 📋 44 - 36% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/fighting41love/funNLP
	```
- [PyPi](https://pypi.org/project/funNLP) (📥 10 / month):
	```
	pip install funNLP
	```
- [Conda](https://anaconda.org/conda-forge/funNLP):
	```
	conda install -c conda-forge funNLP
	```
</details>
<br>

## 网络可视化和 SDN

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行网络可视化和 SDN(软件定义网络)的工具和库。_

<details><summary><b><a href="https://github.com/mininet/mininet">mininet</a></b> (🥇24 ·  ⭐ 4.2K) - 一款流行的网络模拟器以及用 Python 编写的 API。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mininet/mininet) (👨‍💻 78 · 🔀 1.5K · 📥 410K · 📦 120 · 📋 650 - 40% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/mininet/mininet
	```
- [PyPi](https://pypi.org/project/mininet):
	```
	pip install mininet
	```
- [Conda](https://anaconda.org/conda-forge/mininet):
	```
	conda install -c conda-forge mininet
	```
</details>
<details><summary><b><a href="https://github.com/napalm-automation/napalm">napalm</a></b> (🥇24 ·  ⭐ 1.8K) - 可跨供应商 API 来操纵网络设备。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/napalm-automation/napalm) (👨‍💻 170 · 🔀 470 · 📦 740 · 📋 530 - 22% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/napalm-automation/napalm
	```
- [PyPi](https://pypi.org/project/napalm):
	```
	pip install napalm
	```
- [Conda](https://anaconda.org/conda-forge/napalm):
	```
	conda install -c conda-forge napalm
	```
</details>
<details><summary><b><a href="https://github.com/noxrepo/pox">pox</a></b> (🥉16 ·  ⭐ 550 · 💀) - 一个针对基于 Python 的软件定义网络应用（例如 OpenFlow SDN 控制器）的开源开发平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/noxrepo/pox) (👨‍💻 26 · 🔀 420 · 📋 180 - 24% open · ⏱️ 20.05.2020):

	```
	git clone https://github.com/noxrepo/pox
	```
- [PyPi](https://pypi.org/project/pox):
	```
	pip install pox
	```
- [Conda](https://anaconda.org/conda-forge/pox) (📥 170K · ⏱️ 15.06.2021):
	```
	conda install -c conda-forge pox
	```
</details>
<br>

## 动态消息

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来创建用户活动的库。_

<details><summary><b><a href="https://github.com/justquick/django-activity-stream">django-activity-stream</a></b> (🥇23 ·  ⭐ 2K) - 从你的站点行为中生成通用活动信息流。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/justquick/django-activity-stream) (👨‍💻 110 · 🔀 440 · 📦 740 · 📋 290 - 19% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/justquick/django-activity-stream
	```
- [PyPi](https://pypi.org/project/django-activity-stream):
	```
	pip install django-activity-stream
	```
- [Conda](https://anaconda.org/conda-forge/django-activity-stream):
	```
	conda install -c conda-forge django-activity-stream
	```
</details>
<details><summary><b><a href="https://github.com/tschellenbach/Stream-Framework">Stream Framework</a></b> (🥉15 ·  ⭐ 4.6K · 💀) - Building news feed and notification systems using.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/tschellenbach/Stream-Framework) (👨‍💻 26 · 🔀 530 · 📋 180 - 35% open · ⏱️ 15.07.2020):

	```
	git clone https://github.com/tschellenbach/Stream-Framework
	```
- [PyPi](https://pypi.org/project/Stream-Framework):
	```
	pip install Stream-Framework
	```
- [Conda](https://anaconda.org/conda-forge/Stream-Framework):
	```
	conda install -c conda-forge Stream-Framework
	```
</details>
<br>

## ORM

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_实现对象关系映射或数据映射技术的库。_

🔗&nbsp;<b><a href="https://docs.djangoproject.com/en/dev/topics/db/models/">Django Models</a></b>  - The Django ORM.

🔗&nbsp;<b><a href="https://www.sqlalchemy.org/">SQLAlchemy</a></b>  - Python SQL 工具以及对象关系映射工具。

🔗&nbsp;<b><a href="https://github.com/dahlia/awesome-sqlalchemy">awesome-sqlalchemy</a></b> ( ⭐ 2.3K · 💀)  - A curated list of awesome tools for SQLAlchemy.

<details><summary><b><a href="https://github.com/coleifer/peewee">peewee</a></b> (🥇34 ·  ⭐ 8.8K) - 一个小但是很有表现力的 ORM。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/peewee) (👨‍💻 150 · 🔀 1.3K · 📦 15K · 📋 2.1K - 0% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/coleifer/peewee
	```
- [PyPi](https://pypi.org/project/peewee) (📥 560K / month):
	```
	pip install peewee
	```
- [Conda](https://anaconda.org/conda-forge/peewee) (📥 370K · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge peewee
	```
</details>
<details><summary><b><a href="https://github.com/MongoEngine/mongoengine">mongoengine</a></b> (🥈33 ·  ⭐ 3.6K) - 一个 Python 对象文档映射工具，用于 MongoDB。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MongoEngine/mongoengine) (👨‍💻 370 · 🔀 1.1K · 📦 15K · 📋 1.6K - 21% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/MongoEngine/mongoengine
	```
- [PyPi](https://pypi.org/project/mongoengine) (📥 720K / month):
	```
	pip install mongoengine
	```
- [Conda](https://anaconda.org/conda-forge/mongoengine) (📥 140K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge mongoengine
	```
</details>
<details><summary><b><a href="https://github.com/pynamodb/PynamoDB">PynamoDB</a></b> (🥈29 ·  ⭐ 1.8K) - <a href="https://aws.amazon.com/dynamodb/">Amazon DynamoDB</a> 的一个 Python 风格接口。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pynamodb/PynamoDB) (👨‍💻 92 · 🔀 380 · 📦 870 · 📋 470 - 39% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/pynamodb/PynamoDB
	```
- [PyPi](https://pypi.org/project/PynamoDB) (📥 920K / month):
	```
	pip install PynamoDB
	```
- [Conda](https://anaconda.org/conda-forge/PynamoDB) (📥 140K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge PynamoDB
	```
</details>
<details><summary><b><a href="https://github.com/pudo/dataset">dataset</a></b> (🥈23 ·  ⭐ 4.1K) - 在数据库中存储字典，支持 SQLite，MySQL 和 PostgreSQL。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pudo/dataset) (👨‍💻 76 · 🔀 270 · 📦 2.2K · 📋 260 - 3% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/pudo/dataset
	```
- [PyPi](https://pypi.org/project/dataset):
	```
	pip install dataset
	```
- [Conda](https://anaconda.org/conda-forge/dataset) (📥 1.1K · ⏱️ 16.12.2021):
	```
	conda install -c conda-forge dataset
	```
</details>
<details><summary><b><a href="https://github.com/ponyorm/pony">pony</a></b> (🥉20 ·  ⭐ 2.8K) - 提供面向生成器的SQL接口的ORM。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ponyorm/pony) (🔀 200 · 📦 2.2K · 📋 560 - 43% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/ponyorm/pony/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/encode/orm">orm</a></b> (🥉19 ·  ⭐ 1.5K) - 一个异步的 ORM。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/orm) (👨‍💻 15 · 🔀 83 · 📋 69 - 15% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/encode/orm
	```
- [PyPi](https://pypi.org/project/orm) (📥 3.8K / month):
	```
	pip install orm
	```
- [Conda](https://anaconda.org/conda-forge/orm):
	```
	conda install -c conda-forge orm
	```
</details>
<details><summary><b><a href="https://github.com/web2py/pydal">pydal</a></b> (🥉19 ·  ⭐ 400) - 纯 Python 数据库抽象接口层。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/web2py/pydal) (🔀 120 · 📦 200 · 📋 300 - 48% open · ⏱️ 28.11.2021):

	```
	git clone https://github.com/web2py/pydal/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/sdispater/orator">orator</a></b> (🥉18 ·  ⭐ 1.3K · 💀) - Orator ORM，提供了一个简单而美观的 ActiveRecord 实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdispater/orator) (👨‍💻 31 · 🔀 150 · 📋 310 - 41% open · ⏱️ 06.01.2020):

	```
	git clone https://github.com/sdispater/orator
	```
- [PyPi](https://pypi.org/project/orator):
	```
	pip install orator
	```
- [Conda](https://anaconda.org/conda-forge/orator) (📥 1.4K · ⏱️ 18.03.2020):
	```
	conda install -c conda-forge orator
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/hot-redis">hot-redis</a></b> (🥉16 ·  ⭐ 280 · 💀) - 为 Redis 提供 Python 丰富的数据类型。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/hot-redis) (👨‍💻 6 · 🔀 28 · 📦 24 · 📋 10 - 50% open · ⏱️ 16.10.2018):

	```
	git clone https://github.com/stephenmcd/hot-redis
	```
- [PyPi](https://pypi.org/project/hot-redis) (📥 320 / month):
	```
	pip install hot-redis
	```
- [Conda](https://anaconda.org/conda-forge/hot-redis):
	```
	conda install -c conda-forge hot-redis
	```
</details>
<details><summary><b><a href="https://github.com/kiddouk/redisco">redisco</a></b> (🥉14 ·  ⭐ 430 · 💀) - 一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kiddouk/redisco) (👨‍💻 20 · 🔀 85 · 📋 51 - 70% open · ⏱️ 06.06.2016):

	```
	git clone https://github.com/kiddouk/redisco
	```
- [PyPi](https://pypi.org/project/redisco) (📥 320 / month):
	```
	pip install redisco
	```
- [Conda](https://anaconda.org/conda-forge/redisco):
	```
	conda install -c conda-forge redisco
	```
</details>
<br>

## 包管理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理包和依赖的工具。_

🔗&nbsp;<b><a href="https://pip.pypa.io/en/stable/">pip</a></b>  - Python 包和依赖关系管理工具。

🔗&nbsp;<b><a href="https://pypi.org/">PyPI</a></b>  

<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥇30 ·  ⭐ 18K) - 可完全取代 setup.py 的包管理工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 320 · 🔀 1.4K · 📥 9.9M · 📋 3.4K - 33% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/sdispater/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 4.4M / month):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 350K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥉28 ·  ⭐ 5.4K) - 保证 Python 包依赖关系更新的一组工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 160 · 🔀 410 · 📋 780 - 15% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 3.9M / month):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 21K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥉18 ·  ⭐ 4.4K) - 跨平台的 Python 二进制包管理工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/conda/conda) (🔀 1.1K · 📋 8.2K - 21% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/conda/conda/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 包仓库

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_本地 PyPI 仓库服务和代理。_

<details><summary><b><a href="https://github.com/devpi/devpi">devpi</a></b> (🥇19 ·  ⭐ 520) - PyPI 服务和打包/测试/分发工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/devpi/devpi) (👨‍💻 81 · 🔀 92 · 📦 160 · 📋 670 - 14% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/devpi/devpi
	```
- [PyPi](https://pypi.org/project/devpi) (📥 2.4K / month):
	```
	pip install devpi
	```
- [Conda](https://anaconda.org/conda-forge/devpi):
	```
	conda install -c conda-forge devpi
	```
</details>
<details><summary><b><a href="https://github.com/pypa/warehouse">warehouse</a></b> (🥈15 ·  ⭐ 2.9K) - 下一代 PyPI。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/warehouse) (👨‍💻 310 · 🔀 720 · 📋 2.4K - 13% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/pypa/warehouse
	```
- [PyPi](https://pypi.org/project/warehouse):
	```
	pip install warehouse
	```
- [Conda](https://anaconda.org/conda-forge/warehouse):
	```
	conda install -c conda-forge warehouse
	```
</details>
<details><summary><b><a href="https://github.com/mvantellingen/localshop">localshop</a></b> (🥈15 ·  ⭐ 380 · 💀) - 本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mvantellingen/localshop) (👨‍💻 46 · 🔀 110 · 📦 3 · 📋 110 - 30% open · ⏱️ 08.07.2020):

	```
	git clone https://github.com/jazzband/localshop
	```
- [PyPi](https://pypi.org/project/localshop) (📥 150 / month):
	```
	pip install localshop
	```
- [Conda](https://anaconda.org/conda-forge/localshop):
	```
	conda install -c conda-forge localshop
	```
</details>
<details><summary><b><a href="https://github.com/pypa/bandersnatch">bandersnatch</a></b> (🥉13 ·  ⭐ 270) - PyPA 提供的 PyPI 镜像工具。<code><a href="https://tldrlegal.com/search?q=AFL-3.0">❗️AFL-3.0</a></code></summary>

- [GitHub](https://github.com/pypa/bandersnatch) (🔀 88 · 📋 180 - 12% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/pypa/bandersnatch/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 渗透测试

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_渗透测试相关框架和工具。_

<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥇22 ·  ⭐ 22K) - 自动 SQL 注入和数据库接管工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 110 · 🔀 4.4K · 📋 4.5K - 1% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 7.6K / month):
	```
	pip install sqlmap
	```
- [Conda](https://anaconda.org/conda-forge/sqlmap):
	```
	conda install -c conda-forge sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/Manisso/fsociety">fsociety</a></b> (🥉17 ·  ⭐ 7.2K · 💀) - 一款渗透测试框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Manisso/fsociety) (👨‍💻 21 · 🔀 1.5K · 📋 110 - 14% open · ⏱️ 16.10.2020):

	```
	git clone https://github.com/Manisso/fsociety
	```
- [PyPi](https://pypi.org/project/fsociety):
	```
	pip install fsociety
	```
- [Conda](https://anaconda.org/conda-forge/fsociety):
	```
	conda install -c conda-forge fsociety
	```
</details>
<details><summary><b><a href="https://github.com/trustedsec/social-engineer-toolkit">setoolkit</a></b> (🥉17 ·  ⭐ 7.1K) - 社会工程工具包。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/trustedsec/social-engineer-toolkit) (👨‍💻 81 · 🔀 2K · 📋 770 - 22% open · ⏱️ 20.07.2021):

	```
	git clone https://github.com/trustedsec/social-engineer-toolkit
	```
- [PyPi](https://pypi.org/project/social-engineer-toolkit):
	```
	pip install social-engineer-toolkit
	```
- [Conda](https://anaconda.org/conda-forge/social-engineer-toolkit):
	```
	conda install -c conda-forge social-engineer-toolkit
	```
</details>
<br>

## 权限

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_允许或拒绝用户访问数据或功能的库。_

<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥇27 ·  ⭐ 3.1K) - Django 1.2+ ，实现了单个对象权限。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 510 · 📦 4.4K · 📋 430 - 25% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 240K / month):
	```
	pip install django-guardian
	```
- [Conda](https://anaconda.org/conda-forge/django-guardian) (📥 33K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/dfunckt/django-rules">django-rules</a></b> (🥉24 ·  ⭐ 1.4K) - 一个小巧但是强大的应用，提供对象级别的权限管理，且不需要使用数据库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dfunckt/django-rules) (👨‍💻 25 · 🔀 120 · 📦 720 · 📋 100 - 19% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/dfunckt/django-rules
	```
- [PyPi](https://pypi.org/project/django-rules) (📥 220 / month):
	```
	pip install django-rules
	```
- [Conda](https://anaconda.org/conda-forge/django-rules):
	```
	conda install -c conda-forge django-rules
	```
</details>
<br>

## 进程

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_操作系统进程启动及通信库。_

🔗&nbsp;<b><a href="https://sarge.readthedocs.io/en/latest/">sarge</a></b>  - 另一 种 subprocess 模块的封装。

<details><summary><b><a href="https://github.com/amoffat/sh">sh</a></b> (🥇27 ·  ⭐ 6K) - 一个完备的 subprocess 替代库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amoffat/sh) (👨‍💻 82 · 🔀 430 · 📦 8.2K · 📋 400 - 2% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/amoffat/sh
	```
- [PyPi](https://pypi.org/project/sh):
	```
	pip install sh
	```
- [Conda](https://anaconda.org/conda-forge/sh) (📥 110K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge sh
	```
</details>
<details><summary><b><a href="https://github.com/amitt001/delegator.py">delegator.py</a></b> (🥉17 ·  ⭐ 1.6K · 💀) - .. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amitt001/delegator.py) (👨‍💻 23 · 🔀 77 · 📋 45 - 17% open · ⏱️ 06.05.2019):

	```
	git clone https://github.com/amitt001/delegator.py
	```
- [PyPi](https://pypi.org/project/delegator.py) (📥 20K / month):
	```
	pip install delegator.py
	```
- [Conda](https://anaconda.org/conda-forge/delegator.py):
	```
	conda install -c conda-forge delegator.py
	```
</details>
<br>

## 推荐系统

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于构建推荐系统的相关库。_

<details><summary><b><a href="https://github.com/spotify/annoy">annoy</a></b> (🥇24 ·  ⭐ 9.3K) - 对 C++/Python 实现的近似近邻算法进行了内存优化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 75 · 🔀 950 · 📦 1.9K · 📋 340 - 11% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/annoy):
	```
	conda install -c conda-forge annoy
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥇24 ·  ⭐ 3.9K · 💤) - John Gruber’s Markdown 的 Python 版实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 610 · 📦 610 · 📋 430 - 20% open · ⏱️ 07.02.2021):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 110K · ⏱️ 07.02.2021):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥈22 ·  ⭐ 2.6K) - 对隐式数据集进行协作过滤的快速 Python 实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 30 · 🔀 510 · 📦 520 · 📋 370 - 22% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 320K · ⏱️ 29.08.2021):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉17 ·  ⭐ 960 · 💤) - Factorization Machine 相关库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ibayer/fastFM) (👨‍💻 20 · 🔀 190 · 📥 420 · 📦 92 · 📋 110 - 43% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/ibayer/fastFM
	```
- [PyPi](https://pypi.org/project/fastFM):
	```
	pip install fastFM
	```
- [Conda](https://anaconda.org/conda-forge/fastFM):
	```
	conda install -c conda-forge fastFM
	```
</details>
<details><summary><b><a href="https://github.com/maciejkula/spotlight">spotlight</a></b> (🥉16 ·  ⭐ 2.6K · 💀) - 使用 PyTorch 实现的深度推荐模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maciejkula/spotlight) (👨‍💻 11 · 🔀 390 · 📋 110 - 55% open · ⏱️ 09.02.2020):

	```
	git clone https://github.com/maciejkula/spotlight
	```
- [PyPi](https://pypi.org/project/spotlight):
	```
	pip install spotlight
	```
- [Conda](https://anaconda.org/conda-forge/spotlight):
	```
	conda install -c conda-forge spotlight
	```
</details>
<details><summary><b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉16 ·  ⭐ 1.2K · 💀) - TensorFlow 的推荐引擎框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jfkirk/tensorrec) (👨‍💻 9 · 🔀 220 · 📦 26 · 📋 120 - 28% open · ⏱️ 04.02.2020):

	```
	git clone https://github.com/jfkirk/tensorrec
	```
- [PyPi](https://pypi.org/project/tensorrec):
	```
	pip install tensorrec
	```
- [Conda](https://anaconda.org/conda-forge/tensorrec):
	```
	conda install -c conda-forge tensorrec
	```
</details>
<details><summary><b><a href="https://github.com/NicolasHug/Surprise">Surprise</a></b> (🥉15 ·  ⭐ 5.2K · 💀) - 用于构建和分析推荐系统的科学工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NicolasHug/Surprise) (👨‍💻 38 · 🔀 890 · 📋 330 - 12% open · ⏱️ 05.08.2020):

	```
	git clone https://github.com/NicolasHug/Surprise
	```
- [PyPi](https://pypi.org/project/Surprise):
	```
	pip install Surprise
	```
- [Conda](https://anaconda.org/conda-forge/Surprise):
	```
	conda install -c conda-forge Surprise
	```
</details>
<details><summary><b><a href="https://github.com/ycjuan/libffm">libffm</a></b> (🥉11 ·  ⭐ 1.5K · 💀) - Field-aware Factorization Machine (FFM) 相关库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ycjuan/libffm) (👨‍💻 5 · 🔀 420 · 📋 36 - 58% open · ⏱️ 22.02.2019):

	```
	git clone https://github.com/guestwalk/libffm
	```
- [PyPi](https://pypi.org/project/libffm):
	```
	pip install libffm
	```
- [Conda](https://anaconda.org/conda-forge/libffm):
	```
	conda install -c conda-forge libffm
	```
</details>
<br>

## 重构

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Python 重构相关库和工具。_

🔗&nbsp;<b><a href="http://bicyclerepair.sourceforge.net/">Bicycle Repair Man</a></b>  - Python 的重构工具。

🔗&nbsp;<b><a href="https://pybowler.io/">Bowler</a></b>  - 适用于现代Python的安全代码重构。

<details><summary><b><a href="https://github.com/python-rope/rope">Rope</a></b> (🥇29 ·  ⭐ 1.2K) - 一个 Python 的重构库。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 68 · 🔀 130 · 📦 34K · 📋 230 - 30% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 560K / month):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 610K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge rope
	```
</details>
<br>

## RESTful API

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来开发 RESTful APIs 的库_

🔗&nbsp;<b><a href="http://www.django-rest-framework.org/">django-rest-framework</a></b>  - 一个强大灵活的工具，用来构建 web API。

🔗&nbsp;<b><a href="http://tastypieapi.org/">django-tastypie</a></b>  - 为 Django 应用开发 API。

🔗&nbsp;<b><a href="https://vibora.io/">vibora</a></b>  - 快速高效且支持异步的 Web 框架，灵感来源于 Flask。

<details><summary><b><a href="https://github.com/falconry/falcon">falcon</a></b> (🥇33 ·  ⭐ 8.7K) - 一个用来建立云 API 和 web app 后端的高性能框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/falconry/falcon) (👨‍💻 180 · 🔀 840 · 📥 1.5K · 📦 6.1K · 📋 930 - 19% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/falconry/falcon
	```
- [PyPi](https://pypi.org/project/falcon) (📥 660K / month):
	```
	pip install falcon
	```
- [Conda](https://anaconda.org/conda-forge/falcon) (📥 230K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge falcon
	```
</details>
<details><summary><b><a href="https://github.com/sanic-org/sanic">sanic</a></b> (🥈32 ·  ⭐ 16K) - A Python 3.6+ web server and web framework that's written to go fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sanic-org/sanic) (👨‍💻 310 · 🔀 1.4K · 📦 6.2K · 📋 1.1K - 3% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/huge-success/sanic
	```
- [PyPi](https://pypi.org/project/sanic) (📥 1M / month):
	```
	pip install sanic
	```
- [Conda](https://anaconda.org/conda-forge/sanic) (📥 180K · ⏱️ 21.11.2021):
	```
	conda install -c conda-forge sanic
	```
</details>
<details><summary><b><a href="https://github.com/tiangolo/fastapi">fastapi</a></b> (🥈30 ·  ⭐ 40K) - 一个现代，快速，基于标准 Python 类型注解的的 web框架，可使用 Python3.6+ 版本构建 API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tiangolo/fastapi) (👨‍💻 280 · 🔀 2.9K · 📋 2.6K - 32% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/tiangolo/fastapi
	```
- [PyPi](https://pypi.org/project/fastapi) (📥 4.5M / month):
	```
	pip install fastapi
	```
- [Conda](https://anaconda.org/conda-forge/fastapi) (📥 500K · ⏱️ 12.12.2021):
	```
	conda install -c conda-forge fastapi
	```
</details>
<details><summary><b><a href="https://github.com/flask-restful/flask-restful">flask-restful</a></b> (🥈29 ·  ⭐ 6.2K) - 为 flask 快速创建 REST APIs 。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/flask-restful/flask-restful) (👨‍💻 160 · 🔀 940 · 📦 68K · 📋 530 - 15% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/flask-restful/flask-restful
	```
- [PyPi](https://pypi.org/project/flask-restful):
	```
	pip install flask-restful
	```
- [Conda](https://anaconda.org/conda-forge/flask-restful) (📥 100K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge flask-restful
	```
</details>
<details><summary><b><a href="https://github.com/hugapi/hug">hug</a></b> (🥉27 ·  ⭐ 6.6K · 💀) - 一个为纯净公开的 API 打造的 Python 3 框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hugapi/hug) (👨‍💻 120 · 🔀 370 · 📦 1.2K · 📋 450 - 34% open · ⏱️ 10.08.2020):

	```
	git clone https://github.com/hugapi/hug
	```
- [PyPi](https://pypi.org/project/hug) (📥 29K / month):
	```
	pip install hug
	```
- [Conda](https://anaconda.org/conda-forge/hug) (📥 140K · ⏱️ 19.02.2020):
	```
	conda install -c conda-forge hug
	```
</details>
<details><summary><b><a href="https://github.com/pyeve/eve">eve</a></b> (🥉25 ·  ⭐ 6.4K) - REST API 框架，由 Flask, MongoDB 等驱动。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyeve/eve) (👨‍💻 200 · 🔀 720 · 📦 990 · 📋 950 - 3% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/pyeve/eve
	```
- [PyPi](https://pypi.org/project/eve) (📥 22K / month):
	```
	pip install eve
	```
- [Conda](https://anaconda.org/conda-forge/eve):
	```
	conda install -c conda-forge eve
	```
</details>
<details><summary><b><a href="https://github.com/flask-api/flask-api">flask-api</a></b> (🥉25 ·  ⭐ 1.3K) - 为 flask 开发的，可浏览 Web APIs 。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/flask-api/flask-api) (👨‍💻 32 · 🔀 160 · 📦 4.8K · 📋 63 - 19% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/flask-api/flask-api
	```
- [PyPi](https://pypi.org/project/flask-api) (📥 95K / month):
	```
	pip install flask-api
	```
- [Conda](https://anaconda.org/conda-forge/flask-api):
	```
	conda install -c conda-forge flask-api
	```
</details>
<details><summary><b><a href="https://github.com/encode/apistar">apistar</a></b> (🥉23 ·  ⭐ 5.6K) - 专为Python 3设计的智能 Web API 框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/apistar) (👨‍💻 89 · 🔀 420 · 📦 660 · 📋 310 - 7% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/encode/apistar
	```
- [PyPi](https://pypi.org/project/apistar):
	```
	pip install apistar
	```
- [Conda](https://anaconda.org/conda-forge/apistar) (📥 90K · ⏱️ 03.04.2019):
	```
	conda install -c conda-forge apistar
	```
</details>
<details><summary><b><a href="https://github.com/jeffknupp/sandman2">sandman2</a></b> (🥉20 ·  ⭐ 1.8K · 💤) - 为数据库驱动的系统自动生成 REST API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jeffknupp/sandman2) (👨‍💻 23 · 🔀 180 · 📦 17 · 📋 79 - 34% open · ⏱️ 21.12.2020):

	```
	git clone https://github.com/jeffknupp/sandman2
	```
- [PyPi](https://pypi.org/project/sandman2) (📥 460 / month):
	```
	pip install sandman2
	```
- [Conda](https://anaconda.org/conda-forge/sandman2):
	```
	conda install -c conda-forge sandman2
	```
</details>
<details><summary><b><a href="https://github.com/Cornices/cornice">cornice</a></b> (🥉20 ·  ⭐ 370) - 一个 Pyramid 的 REST 框架 。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Cornices/cornice) (👨‍💻 120 · 🔀 140 · 📦 680 · 📋 230 - 18% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/Cornices/cornice
	```
- [PyPi](https://pypi.org/project/cornice):
	```
	pip install cornice
	```
- [Conda](https://anaconda.org/conda-forge/cornice):
	```
	conda install -c conda-forge cornice
	```
</details>
<br>

## 机器人

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_机器人相关库。_

🔗&nbsp;<b><a href="http://wiki.ros.org/rospy">rospy</a></b>  - ROS (Robot Operating System) 库。

<details><summary><b><a href="https://github.com/AtsushiSakai/PythonRobotics">PythonRobotics</a></b> (🥇19 ·  ⭐ 14K) - 各种具有可视化效果的机器人算法的汇总。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/AtsushiSakai/PythonRobotics) (👨‍💻 94 · 🔀 4.3K · 📋 260 - 4% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/AtsushiSakai/PythonRobotics
	```
- [PyPi](https://pypi.org/project/PythonRobotics):
	```
	pip install PythonRobotics
	```
- [Conda](https://anaconda.org/conda-forge/PythonRobotics):
	```
	conda install -c conda-forge PythonRobotics
	```
</details>
<br>

## RPC 服务器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_兼容 RPC 的服务器。_

<details><summary><b><a href="https://github.com/0rpc/zerorpc-python">zeroRPC</a></b> (🥇13 ·  ⭐ 2.9K · 💀) - zerorpc 是一个灵活的 RPC 实现，基于 <a href="http://zeromq.org/">ZeroMQ</a> 和 <a href="http://msgpack.org/">MessagePack</a>。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/0rpc/zerorpc-python) (👨‍💻 36 · 🔀 360 · 📋 160 - 31% open · ⏱️ 27.05.2020):

	```
	git clone https://github.com/0rpc/zerorpc-python
	```
- [PyPi](https://pypi.org/project/zerorpc-python):
	```
	pip install zerorpc-python
	```
- [Conda](https://anaconda.org/conda-forge/zerorpc-python):
	```
	conda install -c conda-forge zerorpc-python
	```
</details>
<br>

## 科学计算和数据分析

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行科学计算和数据分析的库。_

🔗&nbsp;<b><a href="http://www.astropy.org/">astropy</a></b>  - 一个天文学 Python 库。

🔗&nbsp;<b><a href="http://biopython.org/wiki/Main_Page">Biopython</a></b>  - Biopython 是一组可以免费使用的用来进行生物计算的工具。

🔗&nbsp;<b><a href="http://cclib.github.io/">cclib</a></b>  - 一个用来解析和解释计算化学软件包输出结果的库。

🔗&nbsp;<b><a href="http://colour-science.org/">Colour</a></b>  - 大量色彩理论转换和算法的实现。

🔗&nbsp;<b><a href="https://networkx.github.io/">NetworkX</a></b>  - 一个为复杂网络设计的高性能软件。

🔗&nbsp;<b><a href="http://nipy.org">NIPY</a></b>  - 神经影响学工具箱集合。

🔗&nbsp;<b><a href="http://www.numpy.org/">NumPy</a></b>  - 使用 Python 进行科学计算的基础包。

🔗&nbsp;<b><a href="http://openbabel.org/wiki/Main_Page">Open Babel</a></b>  - 一个化学工具箱，用来描述多种化学数据。

🔗&nbsp;<b><a href="http://www.pydy.org/">PyDy</a></b>  - PyDy 是 Python Dynamics 的缩写，用来为动力学运动建模工作流程提供帮助， 基于 NumPy, SciPy, IPython 和 matplotlib。

🔗&nbsp;<b><a href="http://qutip.org/">QuTiP</a></b>  - Python 版 Quantum 工具箱。

🔗&nbsp;<b><a href="http://www.rdkit.org/">RDKit</a></b>  - 化学信息学和机器学习软件。

🔗&nbsp;<b><a href="https://www.scipy.org/">SciPy</a></b>  - 由一些基于 Python ，用于数学，科学和工程的开源软件构成的生态系统。

🔗&nbsp;<b><a href="https://gitlab.com/team-simpy/simpy">SimPy</a></b>  - 一个基于过程的离散事件模拟框架。

<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇35 ·  ⭐ 8.7K) - 一个用于符号数学的 Python 库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.1K · 🔀 3.5K · 📥 440K · 📦 38K · 📋 11K - 32% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 2M / month):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 1.8M · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">statsmodels</a></b> (🥈33 ·  ⭐ 6.9K) - 统计建模和计量经济学。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 350 · 🔀 2.2K · 📥 26 · 📦 55K · 📋 4.6K - 46% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 7.4M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 5.4M · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/zipline">Zipline</a></b> (🥈29 ·  ⭐ 15K · 💀) - 一个 Python 算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/zipline) (👨‍💻 150 · 🔀 3.9K · 📦 800 · 📋 960 - 32% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/zipline
	```
- [PyPi](https://pypi.org/project/zipline) (📥 4.2K / month):
	```
	pip install zipline
	```
- [Conda](https://anaconda.org/conda-forge/zipline) (📥 5.3K · ⏱️ 05.10.2020):
	```
	conda install -c conda-forge zipline
	```
</details>
<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC</a></b> (🥉26 ·  ⭐ 6.2K) - 马尔科夫链蒙特卡洛采样工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pymc-devs/pymc) (👨‍💻 350 · 🔀 1.4K · 📥 1.3K · 📦 570 · 📋 2.5K - 7% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/pymc-devs/pymc3
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 270K / month):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 360K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥉23 ·  ⭐ 1.5K) - 用于图形结构化数据的无监督机器学习工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/karateclub) (👨‍💻 13 · 🔀 170 · 📦 65 · 📋 65 - 1% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/benedekrozemberczki/karateclub
	```
- [PyPi](https://pypi.org/project/karateclub) (📥 5K / month):
	```
	pip install karateclub
	```
- [Conda](https://anaconda.org/conda-forge/karateclub) (📥 7.4K · ⏱️ 05.08.2021):
	```
	conda install -c conda-forge karateclub
	```
</details>
<details><summary><b><a href="https://github.com/bcbio/bcbio-nextgen">bcbio-nextgen</a></b> (🥉21 ·  ⭐ 850) - 这个工具箱为全自动高通量测序分析提供符合最佳实践的处理流程。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bcbio/bcbio-nextgen) (👨‍💻 93 · 🔀 330 · 📋 2.9K - 2% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/chapmanb/bcbio-nextgen
	```
- [PyPi](https://pypi.org/project/bcbio-nextgen) (📥 140 / month):
	```
	pip install bcbio-nextgen
	```
- [Conda](https://anaconda.org/conda-forge/bcbio-nextgen):
	```
	conda install -c conda-forge bcbio-nextgen
	```
</details>
<details><summary><b><a href="https://github.com/chapmanb/bcbb">bccb</a></b> (🥉18 ·  ⭐ 530) - 生物分析相关代码集合。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/chapmanb/bcbb) (👨‍💻 32 · 🔀 210 · 📦 190 · 📋 73 - 19% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/chapmanb/bcbb
	```
- [PyPi](https://pypi.org/project/bcbb):
	```
	pip install bcbb
	```
- [Conda](https://anaconda.org/conda-forge/bcbb):
	```
	conda install -c conda-forge bcbb
	```
</details>
<details><summary><b><a href="https://github.com/obspy/obspy">ObsPy</a></b> (🥉17 ·  ⭐ 850) - 地震学 Python 工具箱。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/obspy/obspy) (🔀 460 · 📥 6.7K · 📋 1.5K - 19% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/obspy/obspy/wiki/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 搜索

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_对数据进行索引和执行搜索查询的库和软件。_

🔗&nbsp;<b><a href="https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html">elasticsearch-py</a></b>  - Elasticsearch 的官方底层 Python 客户端。

🔗&nbsp;<b><a href="http://whoosh.readthedocs.io/en/latest/">whoosh</a></b>  - 一个快速的纯 Python 搜索引擎库。

<details><summary><b><a href="https://github.com/django-haystack/django-haystack">django-haystack</a></b> (🥇27 ·  ⭐ 3.2K) - Django 模块化搜索。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-haystack/django-haystack) (👨‍💻 200 · 🔀 1.2K · 📦 7.5K · 📋 1.2K - 36% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/django-haystack/django-haystack
	```
- [PyPi](https://pypi.org/project/django-haystack):
	```
	pip install django-haystack
	```
- [Conda](https://anaconda.org/conda-forge/django-haystack) (📥 4.4K · ⏱️ 31.05.2018):
	```
	conda install -c conda-forge django-haystack
	```
</details>
<details><summary><b><a href="https://github.com/django-haystack/pysolr">pysolr</a></b> (🥇27 ·  ⭐ 610) - 支持 <a href="https://lucene.apache.org/solr/">Apache Solr</a> 的轻量级 Python 装饰器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-haystack/pysolr) (👨‍💻 65 · 🔀 300 · 📦 2.5K · 📋 140 - 13% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/django-haystack/pysolr
	```
- [PyPi](https://pypi.org/project/pysolr) (📥 130K / month):
	```
	pip install pysolr
	```
- [Conda](https://anaconda.org/conda-forge/pysolr) (📥 17K · ⏱️ 28.04.2020):
	```
	conda install -c conda-forge pysolr
	```
</details>
<details><summary><b><a href="https://github.com/elastic/elasticsearch-dsl-py">elasticsearch-dsl-py</a></b> (🥉25 ·  ⭐ 3.4K) - Elasticsearch 的官方高级 Python 客户端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elastic/elasticsearch-dsl-py) (👨‍💻 120 · 🔀 690 · 📥 100 · 📦 5.4K · 📋 1.2K - 7% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/elastic/elasticsearch-dsl-py
	```
- [PyPi](https://pypi.org/project/elasticsearch-dsl-py):
	```
	pip install elasticsearch-dsl-py
	```
- [Conda](https://anaconda.org/conda-forge/elasticsearch-dsl-py):
	```
	conda install -c conda-forge elasticsearch-dsl-py
	```
</details>
<br>

## 序列化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_复杂数据类型序列化相关库。_

<details><summary><b><a href="https://github.com/marshmallow-code/marshmallow">marshmallow</a></b> (🥇27 ·  ⭐ 5.9K) - 一个轻量级的库，用于将复杂对象与简单 Python 数据类型相互转换。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marshmallow-code/marshmallow) (👨‍💻 200 · 🔀 560 · 📦 38K · 📋 1.1K - 9% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/marshmallow-code/marshmallow
	```
- [PyPi](https://pypi.org/project/marshmallow):
	```
	pip install marshmallow
	```
- [Conda](https://anaconda.org/conda-forge/marshmallow) (📥 900K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge marshmallow
	```
</details>
<details><summary><b><a href="https://github.com/python-rapidjson/python-rapidjson">python-rapidjson</a></b> (🥈23 ·  ⭐ 430) - A Python wrapper around.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-rapidjson/python-rapidjson) (👨‍💻 18 · 🔀 35 · 📦 1.9K · 📋 98 - 10% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/python-rapidjson/python-rapidjson
	```
- [PyPi](https://pypi.org/project/python-rapidjson) (📥 570K / month):
	```
	pip install python-rapidjson
	```
- [Conda](https://anaconda.org/conda-forge/python-rapidjson) (📥 780K · ⏱️ 12.11.2021):
	```
	conda install -c conda-forge python-rapidjson
	```
</details>
<details><summary><b><a href="https://github.com/TkTech/pysimdjson">pysimdjson</a></b> (🥉21 ·  ⭐ 500) - A Python bindings for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TkTech/pysimdjson) (👨‍💻 12 · 🔀 40 · 📦 180 · 📋 70 - 11% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/TkTech/pysimdjson
	```
- [PyPi](https://pypi.org/project/pysimdjson) (📥 90K / month):
	```
	pip install pysimdjson
	```
- [Conda](https://anaconda.org/conda-forge/pysimdjson) (📥 17K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge pysimdjson
	```
</details>
<details><summary><b><a href="https://github.com/ultrajson/ultrajson">ultrajson</a></b> (🥉15 ·  ⭐ 3.5K) - 使用 Python 绑定的，用 C 编写的快速 JSON 解码器和编码器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ultrajson/ultrajson) (👨‍💻 76 · 🔀 310 · 📋 310 - 13% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/esnme/ultrajson
	```
- [PyPi](https://pypi.org/project/ultrajson):
	```
	pip install ultrajson
	```
- [Conda](https://anaconda.org/conda-forge/ultrajson):
	```
	conda install -c conda-forge ultrajson
	```
</details>
<br>

## Serverless 框架

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_使用 Python 开发 Serverless 模型相关的库。_

<details><summary><b><a href="https://github.com/Miserlou/Zappa">Zappa</a></b> (🥇22 ·  ⭐ 12K · 💤) - 在 AWS Lambda 和 API Gateway 部署 WSGI 应用的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Miserlou/Zappa) (👨‍💻 260 · 🔀 1.2K · 📥 260 · 📋 1.3K - 47% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/Miserlou/Zappa
	```
- [PyPi](https://pypi.org/project/Zappa):
	```
	pip install Zappa
	```
- [Conda](https://anaconda.org/conda-forge/Zappa):
	```
	conda install -c conda-forge Zappa
	```
</details>
<details><summary><b><a href="https://github.com/nficano/python-lambda">python-lambda</a></b> (🥉19 ·  ⭐ 1.3K) - 在 AWS Lambda 开发和部署 Python 代码的工具包。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/nficano/python-lambda) (👨‍💻 47 · 🔀 220 · 📦 140 · 📋 88 - 39% open · ⏱️ 14.07.2021):

	```
	git clone https://github.com/nficano/python-lambda
	```
- [PyPi](https://pypi.org/project/python-lambda):
	```
	pip install python-lambda
	```
- [Conda](https://anaconda.org/conda-forge/python-lambda):
	```
	conda install -c conda-forge python-lambda
	```
</details>
<br>

## 命令行工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于创建命令行程序的库。_

<details><summary><b><a href="https://github.com/xonsh/xonsh">xonsh</a></b> (🥇19 ·  ⭐ 5.3K) - 一种基于 python 的跨平台，面向 unix 的 shell 语言和命令提示符。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/xonsh/xonsh) (🔀 500 · 📥 5.9K · 📦 280 · 📋 2.2K - 13% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/xonsh/xonsh/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## 特殊文本格式处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_一些用来解析和操作特殊文本格式的库。_

🔗&nbsp;<b><a href="https://openpyxl.readthedocs.io/en/stable/">openpyxl</a></b>  - 一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。

🔗&nbsp;<b><a href="https://www.reportlab.com/opensource/">ReportLab</a></b>  - 快速创建富文本 PDF 文档。

🔗&nbsp;<b><a href="http://pyyaml.org/">PyYAML</a></b>  - Python 版本的 YAML 解析器。

<details><summary><b><a href="https://github.com/jazzband/tablib">tablib</a></b> (🥇32 ·  ⭐ 4.1K) - 一个用来处理中表格数据的模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/tablib) (👨‍💻 120 · 🔀 550 · 📦 13K · 📋 240 - 11% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/jazzband/tablib
	```
- [PyPi](https://pypi.org/project/tablib) (📥 1.1M / month):
	```
	pip install tablib
	```
- [Conda](https://anaconda.org/conda-forge/tablib) (📥 69K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge tablib
	```
</details>
<details><summary><b><a href="https://github.com/jmcnamara/XlsxWriter">XlsxWriter</a></b> (🥇32 ·  ⭐ 2.8K · 📈) - 一个用于创建 Excel .xlsx 文件的 Python 模块。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jmcnamara/XlsxWriter) (👨‍💻 46 · 🔀 550 · 📦 42K · 📋 740 - 1% open · ⏱️ 26.11.2021):

	```
	git clone https://github.com/jmcnamara/XlsxWriter
	```
- [PyPi](https://pypi.org/project/XlsxWriter) (📥 8.8M / month):
	```
	pip install XlsxWriter
	```
- [Conda](https://anaconda.org/conda-forge/XlsxWriter) (📥 1.5M · ⏱️ 01.11.2021):
	```
	conda install -c conda-forge XlsxWriter
	```
</details>
<details><summary><b><a href="https://github.com/xlwings/xlwings">xlwings</a></b> (🥈28 ·  ⭐ 2.2K) - 一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/xlwings/xlwings) (👨‍💻 56 · 🔀 380 · 📥 28K · 📦 20K · 📋 1.4K - 22% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/ZoomerAnalytics/xlwings
	```
- [PyPi](https://pypi.org/project/xlwings) (📥 660K / month):
	```
	pip install xlwings
	```
- [Conda](https://anaconda.org/conda-forge/xlwings) (📥 390K · ⏱️ 17.12.2021):
	```
	conda install -c conda-forge xlwings
	```
</details>
<details><summary><b><a href="https://github.com/euske/pdfminer">PDFMiner</a></b> (🥈26 ·  ⭐ 4.7K · 💀) - 一个用于从 PDF 文档中抽取信息的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/euske/pdfminer) (👨‍💻 28 · 🔀 960 · 📦 2.7K · 📋 230 - 82% open · ⏱️ 18.01.2020):

	```
	git clone https://github.com/euske/pdfminer
	```
- [PyPi](https://pypi.org/project/pdfminer) (📥 150K / month):
	```
	pip install pdfminer
	```
- [Conda](https://anaconda.org/conda-forge/pdfminer) (📥 20K · ⏱️ 15.02.2021):
	```
	conda install -c conda-forge pdfminer
	```
</details>
<details><summary><b><a href="https://github.com/mstamy2/PyPDF2">PyPDF2</a></b> (🥈26 ·  ⭐ 3.9K · 💀) - 一个可以分割，合并和转换 PDF 页面的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mstamy2/PyPDF2) (👨‍💻 83 · 🔀 880 · 📦 26K · 📋 420 - 74% open · ⏱️ 25.06.2018):

	```
	git clone https://github.com/mstamy2/PyPDF2
	```
- [PyPi](https://pypi.org/project/PyPDF2):
	```
	pip install PyPDF2
	```
- [Conda](https://anaconda.org/conda-forge/PyPDF2) (📥 190K · ⏱️ 20.11.2018):
	```
	conda install -c conda-forge PyPDF2
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/csvkit">csvkit</a></b> (🥈25 ·  ⭐ 4.8K) - 用于转换和操作 CSV 的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/csvkit) (👨‍💻 100 · 🔀 540 · 📦 970 · 📋 840 - 7% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/wireservice/csvkit
	```
- [PyPi](https://pypi.org/project/csvkit):
	```
	pip install csvkit
	```
- [Conda](https://anaconda.org/conda-forge/csvkit) (📥 58K · ⏱️ 13.07.2021):
	```
	conda install -c conda-forge csvkit
	```
</details>
<details><summary><b><a href="https://github.com/Python-Markdown/markdown">Python-Markdown</a></b> (🥉24 ·  ⭐ 2.7K) - John Gruber’s Markdown 的 Python 版实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Python-Markdown/markdown) (👨‍💻 150 · 🔀 680 · 📦 170K · 📋 740 - 3% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/waylan/Python-Markdown
	```
- [PyPi](https://pypi.org/project/Python-Markdown):
	```
	pip install Python-Markdown
	```
- [Conda](https://anaconda.org/conda-forge/Python-Markdown):
	```
	conda install -c conda-forge Python-Markdown
	```
</details>
<details><summary><b><a href="https://github.com/lepture/mistune">Mistune</a></b> (🥉24 ·  ⭐ 2K · 📉) - 快速并且功能齐全的纯 Python 实现的 Markdown 解析器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lepture/mistune) (👨‍💻 32 · 🔀 200 · 📋 220 - 9% open · ⏱️ 05.12.2021):

	```
	git clone https://github.com/lepture/mistune
	```
- [PyPi](https://pypi.org/project/mistune):
	```
	pip install mistune
	```
- [Conda](https://anaconda.org/conda-forge/mistune) (📥 5.7M · ⏱️ 08.12.2021):
	```
	conda install -c conda-forge mistune
	```
</details>
<details><summary><b><a href="https://github.com/unoconv/unoconv">unoconv</a></b> (🥉23 ·  ⭐ 2.2K) - 在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/unoconv/unoconv) (👨‍💻 52 · 🔀 360 · 📦 84 · 📋 470 - 15% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/unoconv/unoconv
	```
- [PyPi](https://pypi.org/project/unoconv) (📥 7.5K / month):
	```
	pip install unoconv
	```
- [Conda](https://anaconda.org/conda-forge/unoconv):
	```
	conda install -c conda-forge unoconv
	```
</details>
<details><summary><b><a href="https://github.com/pyexcel/pyexcel">pyexcel</a></b> (🥉23 ·  ⭐ 980) - 一个提供统一 API，用来读写，操作 Excel 文件的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyexcel/pyexcel) (👨‍💻 21 · 🔀 150 · 📥 160 · 📦 2.3K · 📋 190 - 5% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/pyexcel/pyexcel
	```
- [PyPi](https://pypi.org/project/pyexcel):
	```
	pip install pyexcel
	```
- [Conda](https://anaconda.org/conda-forge/pyexcel) (📥 40K · ⏱️ 12.09.2021):
	```
	conda install -c conda-forge pyexcel
	```
</details>
<details><summary><b><a href="https://github.com/python-openxml/python-docx">python-docx</a></b> (🥉22 ·  ⭐ 2.9K · 💤) - 读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-openxml/python-docx) (👨‍💻 14 · 🔀 740 · 📋 880 - 44% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/python-openxml/python-docx
	```
- [PyPi](https://pypi.org/project/python-docx) (📥 900K / month):
	```
	pip install python-docx
	```
- [Conda](https://anaconda.org/conda-forge/python-docx) (📥 95K · ⏱️ 27.05.2021):
	```
	conda install -c conda-forge python-docx
	```
</details>
<details><summary><b><a href="https://github.com/scanny/python-pptx">python-pptx</a></b> (🥉20 ·  ⭐ 1.4K) - 可用于创建和修改 ppt 文件的 Python 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/scanny/python-pptx) (👨‍💻 12 · 🔀 330 · 📋 670 - 41% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/scanny/python-pptx
	```
- [PyPi](https://pypi.org/project/python-pptx):
	```
	pip install python-pptx
	```
- [Conda](https://anaconda.org/conda-forge/python-pptx) (📥 140K · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge python-pptx
	```
</details>
<details><summary><b><a href="https://github.com/elapouya/python-docx-template">docxtpl</a></b> (🥉20 ·  ⭐ 1.2K) - 通过 jinja2 模版编辑 docx 文档。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/elapouya/python-docx-template) (👨‍💻 43 · 🔀 280 · 📦 960 · 📋 320 - 21% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/elapouya/python-docx-template
	```
- [PyPi](https://pypi.org/project/python-docx-template):
	```
	pip install python-docx-template
	```
- [Conda](https://anaconda.org/conda-forge/python-docx-template):
	```
	conda install -c conda-forge python-docx-template
	```
</details>
<details><summary><b><a href="https://github.com/mitsuhiko/unp">unp</a></b> (🥉9 ·  ⭐ 400 · 💀) - 一个用来方便解包归档文件的命令行工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mitsuhiko/unp) (👨‍💻 2 · 🔀 58 · 📦 9 · 📋 7 - 85% open · ⏱️ 26.08.2014):

	```
	git clone https://github.com/mitsuhiko/unp
	```
- [PyPi](https://pypi.org/project/unp) (📥 45 / month):
	```
	pip install unp
	```
- [Conda](https://anaconda.org/conda-forge/unp):
	```
	conda install -c conda-forge unp
	```
</details>
<br>

## 静态站点生成器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_静态站点生成器是一个软件，它把文本和模板作为输入，然后输出 HTML 文件。_

<details><summary><b><a href="https://github.com/getpelican/pelican">pelican</a></b> (🥇32 ·  ⭐ 11K) - 使用 Markdown 或 ReST 来处理内容， Jinja 2 来制作主题。支持 DVCS, Disqus.。AGPL 许可。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/getpelican/pelican) (👨‍💻 420 · 🔀 1.7K · 📥 460 · 📦 5.5K · 📋 1.5K - 2% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/getpelican/pelican
	```
- [PyPi](https://pypi.org/project/pelican) (📥 19K / month):
	```
	pip install pelican
	```
- [Conda](https://anaconda.org/conda-forge/pelican) (📥 120K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pelican
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥈27 ·  ⭐ 13K) - 对 Markdown 友好的文档生成器。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (🔀 1.8K · 📦 17K · 📋 1.6K - 6% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/mkdocs/mkdocs/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥈27 ·  ⭐ 2.2K) - 一个静态网站和博客生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 220 · 🔀 330 · 📦 400 · 📋 2.1K - 1% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola):
	```
	pip install nikola
	```
- [Conda](https://anaconda.org/conda-forge/nikola) (📥 2.9K · ⏱️ 14.02.2021):
	```
	conda install -c conda-forge nikola
	```
</details>
<details><summary><b><a href="https://github.com/lektor/lektor">lektor</a></b> (🥉21 ·  ⭐ 3.5K) - 一个简单易用的静态 CMS 和博客引擎。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lektor/lektor) (👨‍💻 89 · 🔀 270 · 📥 6.9K · 📋 560 - 38% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/lektor/lektor
	```
- [PyPi](https://pypi.org/project/lektor) (📥 2.6K / month):
	```
	pip install lektor
	```
- [Conda](https://anaconda.org/conda-forge/lektor) (📥 50K · ⏱️ 27.08.2020):
	```
	conda install -c conda-forge lektor
	```
</details>
<details><summary><b><a href="https://github.com/sunainapai/makesite">makesite</a></b> (🥉13 ·  ⭐ 1.6K · 💤) - 简单轻量的站点/博客生成器 (小于 130 行代码)。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sunainapai/makesite) (👨‍💻 8 · 🔀 250 · 📋 13 - 38% open · ⏱️ 03.01.2021):

	```
	git clone https://github.com/sunainapai/makesite
	```
- [PyPi](https://pypi.org/project/makesite):
	```
	pip install makesite
	```
- [Conda](https://anaconda.org/conda-forge/makesite):
	```
	conda install -c conda-forge makesite
	```
</details>
<br>

## 标记

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来进行标记的库。_

<details><summary><b><a href="https://github.com/jazzband/django-taggit">django-taggit</a></b> (🥇22 ·  ⭐ 2.8K) - 简单的 Django 标记工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-taggit) (👨‍💻 140 · 🔀 540 · 📋 370 - 17% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/jazzband/django-taggit
	```
- [PyPi](https://pypi.org/project/django-taggit) (📥 270K / month):
	```
	pip install django-taggit
	```
- [Conda](https://anaconda.org/conda-forge/django-taggit) (📥 88K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge django-taggit
	```
</details>
<br>

## 队列

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_处理事件以及任务队列的库。_

🔗&nbsp;<b><a href="https://docs.celeryproject.org/en/stable/">celery</a></b>  - 一个异步任务队列/作业队列，基于分布式消息传递

<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇28 ·  ⭐ 8.1K) - 简单的 Python 作业队列。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 250 · 🔀 1.2K · 📦 9.3K · 📋 930 - 16% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 66K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥈27 ·  ⭐ 3.8K) - 小型多线程任务队列。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 66 · 🔀 320 · 📦 840 · ⏱️ 03.12.2021):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 48K / month):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 23K · ⏱️ 16.10.2019):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/Bogdanp/dramatiq">dramatiq</a></b> (🥈27 ·  ⭐ 2.8K) - A fast and reliable background task processing library for Python.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Bogdanp/dramatiq) (👨‍💻 75 · 🔀 200 · 📥 32 · 📦 360 · 📋 270 - 8% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/Bogdanp/dramatiq
	```
- [PyPi](https://pypi.org/project/dramatiq) (📥 61K / month):
	```
	pip install dramatiq
	```
- [Conda](https://anaconda.org/conda-forge/dramatiq) (📥 26K · ⏱️ 19.12.2021):
	```
	conda install -c conda-forge dramatiq
	```
</details>
<details><summary><b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉20 ·  ⭐ 860 · 💤) - 一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pricingassistant/mrq) (👨‍💻 37 · 🔀 110 · 📦 27 · 📋 170 - 30% open · ⏱️ 13.12.2020):

	```
	git clone https://github.com/pricingassistant/mrq
	```
- [PyPi](https://pypi.org/project/mrq) (📥 190 / month):
	```
	pip install mrq
	```
- [Conda](https://anaconda.org/conda-forge/mrq):
	```
	conda install -c conda-forge mrq
	```
</details>
<br>

## 模板引擎

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_模板生成和词法解析的库和工具。_

🔗&nbsp;<b><a href="https://genshi.edgewall.org/">Genshi</a></b>  - Python 模板工具，用以生成 web 感知的结果。

🔗&nbsp;<b><a href="http://www.makotemplates.org/">Mako</a></b>  - Python 平台的超高速轻量级模板。

<details><summary><b><a href="https://github.com/pallets/jinja">Jinja2</a></b> (🥇22 ·  ⭐ 8.2K) - 一个现代的，对设计师友好的模板引擎。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/jinja) (👨‍💻 290 · 🔀 1.4K · 📥 52K · 📋 810 - 3% open · ⏱️ 10.11.2021):

	```
	git clone https://github.com/pallets/jinja
	```
- [PyPi](https://pypi.org/project/jinja):
	```
	pip install jinja
	```
- [Conda](https://anaconda.org/conda-forge/jinja):
	```
	conda install -c conda-forge jinja
	```
</details>
<br>

## 测试

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_进行代码库测试和生成测试数据的库。_

🔗&nbsp;<b><a href="https://docs.pytest.org/en/latest/">pytest</a></b>  - 一个成熟的全功能 Python 测试工具。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="http://nestorsalceda.github.io/mamba/">mamba</a></b>  - Python 的终极测试工具， 拥护 BDD。

🔗&nbsp;<b><a href="https://tox.readthedocs.io/en/latest/">tox</a></b>  - 自动化测试与发布的工具，支持多个 Python 版本。

🔗&nbsp;<b><a href="https://pypi.org/project/selenium/">Selenium</a></b>  - <a href="http://www.seleniumhq.org/">Selenium</a> WebDriver 的 Python 绑定。

🔗&nbsp;<b><a href="https://pypi.org/project/doublex/">doublex</a></b>  - Python 的一个功能强大的 doubles  测试框架。

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.mock.html">mock</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://pypi.org/project/coverage/">coverage</a></b>  - 代码覆盖率测量。

🔗&nbsp;<b><a href="https://pypi.org/project/radar/">radar</a></b>  - 生成随机的日期/时间。

<details><summary><b><a href="https://github.com/joke2k/faker">faker</a></b> (🥇37 ·  ⭐ 13K) - 一个 Python 库，用来生成伪数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/faker) (👨‍💻 430 · 🔀 1.5K · 📦 45K · 📋 530 - 24% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/joke2k/faker
	```
- [PyPi](https://pypi.org/project/faker) (📥 5.2M / month):
	```
	pip install faker
	```
- [Conda](https://anaconda.org/conda-forge/faker) (📥 530K · ⏱️ 07.12.2021):
	```
	conda install -c conda-forge faker
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/responses">responses</a></b> (🥇32 ·  ⭐ 3.4K) - 伪造 Python 中的 requests 库的一个通用库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/getsentry/responses) (👨‍💻 100 · 🔀 270 · 📥 23 · 📦 11K · 📋 200 - 16% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/getsentry/responses
	```
- [PyPi](https://pypi.org/project/responses) (📥 5.5M / month):
	```
	pip install responses
	```
- [Conda](https://anaconda.org/conda-forge/responses) (📥 920K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge responses
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇31 ·  ⭐ 5.6K) - Hypothesis 是一个基于先进的 Quickcheck 风格特性的测试库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 260 · 🔀 450 · 📦 11K · 📋 1.2K - 4% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 2.2M / month):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 5.1M · ⏱️ 23.12.2021):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/locustio/locust">locust</a></b> (🥈30 ·  ⭐ 18K) - 使用 Python 编写的，可扩展的用户加载测试工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/locustio/locust) (👨‍💻 220 · 🔀 2.2K · 📦 2.1K · 📋 1.2K - 1% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/locustio/locust
	```
- [PyPi](https://pypi.org/project/locust):
	```
	pip install locust
	```
- [Conda](https://anaconda.org/conda-forge/locust) (📥 43K · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge locust
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">Robot Framework</a></b> (🥈30 ·  ⭐ 6.5K) - 一个通用的自动化测试框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 150 · 🔀 1.8K · 📥 510 · 📦 4.7K · 📋 3.7K - 4% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 69K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/kevin1024/vcrpy">VCR.py</a></b> (🥈29 ·  ⭐ 2.1K) - 在你的测试中记录和重放 HTTP 交互。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kevin1024/vcrpy) (👨‍💻 110 · 🔀 280 · 📦 3.4K · 📋 320 - 22% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/kevin1024/vcrpy
	```
- [PyPi](https://pypi.org/project/vcrpy) (📥 1.3M / month):
	```
	pip install vcrpy
	```
- [Conda](https://anaconda.org/conda-forge/vcrpy) (📥 230K · ⏱️ 09.10.2020):
	```
	conda install -c conda-forge vcrpy
	```
</details>
<details><summary><b><a href="https://github.com/gabrielfalcao/HTTPretty">httpretty</a></b> (🥈28 ·  ⭐ 1.9K) - Python 的 HTTP 请求 mock 工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gabrielfalcao/HTTPretty) (👨‍💻 100 · 🔀 240 · 📦 5.4K · 📋 230 - 38% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/gabrielfalcao/HTTPretty
	```
- [PyPi](https://pypi.org/project/HTTPretty) (📥 430K / month):
	```
	pip install HTTPretty
	```
- [Conda](https://anaconda.org/conda-forge/HTTPretty) (📥 140K · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge HTTPretty
	```
</details>
<details><summary><b><a href="https://github.com/cobrateam/splinter">splinter</a></b> (🥈27 ·  ⭐ 2.5K) - 开源的 web 应用测试工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cobrateam/splinter) (👨‍💻 170 · 🔀 490 · 📦 5.2K · 📋 490 - 9% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/cobrateam/splinter
	```
- [PyPi](https://pypi.org/project/splinter):
	```
	pip install splinter
	```
- [Conda](https://anaconda.org/conda-forge/splinter):
	```
	conda install -c conda-forge splinter
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">PyAutoGUI</a></b> (🥈26 ·  ⭐ 6K) - PyAutoGUI 是一个人性化的跨平台 GUI 自动测试模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 51 · 🔀 790 · 📦 12K · 📋 520 - 62% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 140K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥉25 ·  ⭐ 3.4K) - 一个帮助你生成伪数据的 Python 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 270 · 📥 190 · 📋 300 - 0% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 88K / month):
	```
	pip install mimesis
	```
- [Conda](https://anaconda.org/conda-forge/mimesis) (📥 4.2K · ⏱️ 15.07.2020):
	```
	conda install -c conda-forge mimesis
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥉24 ·  ⭐ 3.1K) - 通过伪造日期模块来生成不同的时间。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 97 · 🔀 210 · 📋 240 - 29% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 3.5M / month):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 300K · ⏱️ 20.01.2021):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉24 ·  ⭐ 700) - The successor to `nose`, based on `unittest2`. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 71 · 🔀 120 · 📦 4.3K · 📋 250 - 20% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 420K / month):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 42K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉23 ·  ⭐ 2.7K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 320 · 📋 490 - 28% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 1.9M / month):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 88K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉22 ·  ⭐ 720) - 干净，多彩的测试工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 37 · 🔀 69 · 📦 630 · 📋 170 - 1% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 14K / month):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 91K · ⏱️ 12.11.2020):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/patrys/httmock">httmock</a></b> (🥉20 ·  ⭐ 430 · 💀) - 针对 Python 2.6+ 和 3.2+ 生成 伪造请求的库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/patrys/httmock) (👨‍💻 29 · 🔀 47 · 📦 1.5K · 📋 26 - 42% open · ⏱️ 28.10.2020):

	```
	git clone https://github.com/patrys/httmock
	```
- [PyPi](https://pypi.org/project/httmock) (📥 120K / month):
	```
	pip install httmock
	```
- [Conda](https://anaconda.org/conda-forge/httmock) (📥 5.7K · ⏱️ 23.10.2017):
	```
	conda install -c conda-forge httmock
	```
</details>
<details><summary><b><a href="https://github.com/mindflayer/python-mocket">mocket</a></b> (🥉20 ·  ⭐ 220) - gevent/asyncio/SSL 支持的 socket mock 框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mindflayer/python-mocket) (👨‍💻 22 · 🔀 36 · 📦 62 · 📋 54 - 3% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/mindflayer/python-mocket
	```
- [PyPi](https://pypi.org/project/python-mocket):
	```
	pip install python-mocket
	```
- [Conda](https://anaconda.org/conda-forge/python-mocket):
	```
	conda install -c conda-forge python-mocket
	```
</details>
<details><summary><b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - 伪数据库生成器。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/emirozer/fake2db) (👨‍💻 18 · 🔀 110 · 📦 17 · 📋 22 - 31% open · ⏱️ 25.11.2019):

	```
	git clone https://github.com/emirozer/fake2db
	```
- [PyPi](https://pypi.org/project/fake2db) (📥 350 / month):
	```
	pip install fake2db
	```
- [Conda](https://anaconda.org/conda-forge/fake2db):
	```
	conda install -c conda-forge fake2db
	```
</details>
<details><summary><b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉18 ·  ⭐ 1.7K · 💀) - 一个和语言无关的 A/B 测试框架。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/sixpack/sixpack) (👨‍💻 56 · 🔀 180 · 📦 9 · 📋 190 - 35% open · ⏱️ 26.08.2020):

	```
	git clone https://github.com/seatgeek/sixpack
	```
- [PyPi](https://pypi.org/project/sixpack):
	```
	pip install sixpack
	```
- [Conda](https://anaconda.org/conda-forge/sixpack):
	```
	conda install -c conda-forge sixpack
	```
</details>
<details><summary><b><a href="https://github.com/schemathesis/schemathesis">Schemathesis</a></b> (🥉18 ·  ⭐ 1.1K) - 基于属性的自动测试工具，用于测试使用 Open API / Swagger 规范构建的 Web 应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/schemathesis/schemathesis) (👨‍💻 36 · 🔀 76 · 📋 600 - 16% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/kiwicom/schemathesis
	```
- [PyPi](https://pypi.org/project/schemathesis):
	```
	pip install schemathesis
	```
- [Conda](https://anaconda.org/conda-forge/schemathesis):
	```
	conda install -c conda-forge schemathesis
	```
</details>
<details><summary><b><a href="https://github.com/berinhard/model_mommy">model_mommy</a></b> (🥉18 ·  ⭐ 920 · 💀) - Creating random fixtures for testing in Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/berinhard/model_mommy) (👨‍💻 100 · 🔀 150 · ⏱️ 21.10.2019):

	```
	git clone https://github.com/vandersonmota/model_mommy
	```
- [PyPi](https://pypi.org/project/model_mommy) (📥 150K / month):
	```
	pip install model_mommy
	```
- [Conda](https://anaconda.org/conda-forge/model_mommy):
	```
	conda install -c conda-forge model_mommy
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉17 ·  ⭐ 790) - 另外一个测试固件 (test fixtures) 替代库，支持 Django, Flask, SQLAlchemy, Peewee 等。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 41 · 🔀 86 · 📋 77 - 38% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 68K / month):
	```
	pip install mixer
	```
- [Conda](https://anaconda.org/conda-forge/mixer):
	```
	conda install -c conda-forge mixer
	```
</details>
<br>

## 文本处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于解析和操作文本的库。_

🔗&nbsp;<b><a href="https://docs.python.org/3/library/difflib.html">difflib</a></b>  - （Python 标准库）将文件名映射为 MIME 类型。

🔗&nbsp;<b><a href="https://pypi.org/project/Unidecode/">unidecode</a></b>  - Unicode 文本的 ASCII 转换形式 。

🔗&nbsp;<b><a href="http://pygments.org/">pygments</a></b>  - 通用语法高亮工具。

<details><summary><b><a href="https://github.com/pyparsing/pyparsing">pyparsing</a></b> (🥇32 ·  ⭐ 1.3K) - 生成通用解析器的框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyparsing/pyparsing) (👨‍💻 40 · 🔀 200 · 📥 6.2K · 📦 420K · 📋 210 - 8% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/pyparsing/pyparsing
	```
- [PyPi](https://pypi.org/project/pyparsing):
	```
	pip install pyparsing
	```
- [Conda](https://anaconda.org/conda-forge/pyparsing) (📥 17M · ⏱️ 12.11.2021):
	```
	conda install -c conda-forge pyparsing
	```
</details>
<details><summary><b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥇31 ·  ⭐ 8.6K) - 模糊字符串匹配。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/seatgeek/fuzzywuzzy) (👨‍💻 70 · 🔀 860 · 📦 11K · 📋 180 - 43% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/seatgeek/fuzzywuzzy
	```
- [PyPi](https://pypi.org/project/fuzzywuzzy) (📥 5.3M / month):
	```
	pip install fuzzywuzzy
	```
- [Conda](https://anaconda.org/conda-forge/fuzzywuzzy) (📥 340K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge fuzzywuzzy
	```
</details>
<details><summary><b><a href="https://github.com/un33k/python-slugify">python-slugify</a></b> (🥈29 ·  ⭐ 1.1K · 💤) - 一个 Python slug 化库，可以保持 Unicode。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/un33k/python-slugify) (👨‍💻 29 · 🔀 88 · 📦 23K · 📋 51 - 1% open · ⏱️ 12.05.2021):

	```
	git clone https://github.com/un33k/python-slugify
	```
- [PyPi](https://pypi.org/project/python-slugify) (📥 4M / month):
	```
	pip install python-slugify
	```
- [Conda](https://anaconda.org/conda-forge/python-slugify) (📥 640K · ⏱️ 06.05.2021):
	```
	conda install -c conda-forge python-slugify
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">textdistance</a></b> (🥈26 ·  ⭐ 2.6K) - 支持 30 多种算法来计算序列之间的距离。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 11 · 🔀 200 · 📥 420 · 📦 1.4K · ⏱️ 29.11.2021):

	```
	git clone https://github.com/orsinium/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 280K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 67K · ⏱️ 27.10.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/andialbrecht/sqlparse">sqlparse</a></b> (🥈25 ·  ⭐ 2.7K) - 一个无验证的 SQL 解析器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/andialbrecht/sqlparse) (👨‍💻 91 · 🔀 510 · 📋 460 - 41% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/andialbrecht/sqlparse
	```
- [PyPi](https://pypi.org/project/sqlparse) (📥 24M / month):
	```
	pip install sqlparse
	```
- [Conda](https://anaconda.org/conda-forge/sqlparse) (📥 530K · ⏱️ 10.09.2021):
	```
	conda install -c conda-forge sqlparse
	```
</details>
<details><summary><b><a href="https://github.com/chardet/chardet">chardet</a></b> (🥈25 ·  ⭐ 1.6K) - 字符编码检测器，兼容 Python2 和 Python3。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/chardet/chardet) (👨‍💻 44 · 🔀 220 · 📋 120 - 48% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/chardet/chardet
	```
- [PyPi](https://pypi.org/project/chardet) (📥 49M / month):
	```
	pip install chardet
	```
- [Conda](https://anaconda.org/conda-forge/chardet) (📥 15M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge chardet
	```
</details>
<details><summary><b><a href="https://github.com/pwaller/pyfiglet">pyfiglet</a></b> (🥈25 ·  ⭐ 930) - figlet 的 Python 实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pwaller/pyfiglet) (👨‍💻 20 · 🔀 89 · 📦 15K · 📋 41 - 21% open · ⏱️ 04.09.2021):

	```
	git clone https://github.com/pwaller/pyfiglet
	```
- [PyPi](https://pypi.org/project/pyfiglet) (📥 650K / month):
	```
	pip install pyfiglet
	```
- [Conda](https://anaconda.org/conda-forge/pyfiglet) (📥 80K · ⏱️ 18.05.2019):
	```
	conda install -c conda-forge pyfiglet
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈22 ·  ⭐ 3.1K · 💤) - 让 Unicode 文本更完整更连贯。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 100 · 📦 4.5K · 📋 120 - 9% open · ⏱️ 17.05.2021):

	```
	git clone https://github.com/LuminosoInsight/python-ftfy
	```
- [PyPi](https://pypi.org/project/python-ftfy):
	```
	pip install python-ftfy
	```
- [Conda](https://anaconda.org/conda-forge/python-ftfy):
	```
	conda install -c conda-forge python-ftfy
	```
</details>
<details><summary><b><a href="https://github.com/selwin/python-user-agents">python-user-agents</a></b> (🥉21 ·  ⭐ 1.2K) - 浏览器 user agent 解析器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/selwin/python-user-agents) (👨‍💻 31 · 🔀 180 · 📦 3.5K · 📋 65 - 52% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/selwin/python-user-agents
	```
- [PyPi](https://pypi.org/project/python-user-agents):
	```
	pip install python-user-agents
	```
- [Conda](https://anaconda.org/conda-forge/python-user-agents):
	```
	conda install -c conda-forge python-user-agents
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/unicode-slugify">unicode-slugify</a></b> (🥉20 ·  ⭐ 300) - 一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mozilla/unicode-slugify) (👨‍💻 14 · 🔀 48 · 📦 1.9K · 📋 18 - 55% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/mozilla/unicode-slugify
	```
- [PyPi](https://pypi.org/project/unicode-slugify) (📥 91K / month):
	```
	pip install unicode-slugify
	```
- [Conda](https://anaconda.org/conda-forge/unicode-slugify):
	```
	conda install -c conda-forge unicode-slugify
	```
</details>
<details><summary><b><a href="https://github.com/dabeaz/ply">ply</a></b> (🥉19 ·  ⭐ 2.1K · 💀) - lex 和 yacc 解析工具的 Python 实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dabeaz/ply) (👨‍💻 32 · 🔀 350 · 📋 170 - 16% open · ⏱️ 18.06.2020):

	```
	git clone https://github.com/dabeaz/ply
	```
- [PyPi](https://pypi.org/project/ply):
	```
	pip install ply
	```
- [Conda](https://anaconda.org/conda-forge/ply) (📥 890K · ⏱️ 07.07.2018):
	```
	conda install -c conda-forge ply
	```
</details>
<details><summary><b><a href="https://github.com/skorokithakis/shortuuid">shortuuid</a></b> (🥉19 ·  ⭐ 1.6K · 📉) - 一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/skorokithakis/shortuuid) (👨‍💻 23 · 🔀 93 · ⏱️ 11.11.2021):

	```
	git clone https://github.com/skorokithakis/shortuuid
	```
- [PyPi](https://pypi.org/project/shortuuid):
	```
	pip install shortuuid
	```
- [Conda](https://anaconda.org/conda-forge/shortuuid) (📥 130K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge shortuuid
	```
</details>
<details><summary><b><a href="https://github.com/voronind/awesome-slugify">awesome-slugify</a></b> (🥉19 ·  ⭐ 460 · 💀) - 一个 Python slug 化库，可以保持 Unicode。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/voronind/awesome-slugify) (👨‍💻 11 · 🔀 39 · 📦 2.9K · 📋 24 - 54% open · ⏱️ 20.01.2017):

	```
	git clone https://github.com/dimka665/awesome-slugify
	```
- [PyPi](https://pypi.org/project/awesome-slugify) (📥 63K / month):
	```
	pip install awesome-slugify
	```
- [Conda](https://anaconda.org/conda-forge/awesome-slugify) (📥 56K · ⏱️ 28.06.2019):
	```
	conda install -c conda-forge awesome-slugify
	```
</details>
<details><summary><b><a href="https://github.com/mozillazg/python-pinyin">pypinyin</a></b> (🥉18 ·  ⭐ 3.6K) - Convert Chinese hanzi () to pinyin (). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mozillazg/python-pinyin) (👨‍💻 20 · 🔀 520 · 📋 210 - 14% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/mozillazg/python-pinyin
	```
- [PyPi](https://pypi.org/project/python-pinyin):
	```
	pip install python-pinyin
	```
- [Conda](https://anaconda.org/conda-forge/python-pinyin):
	```
	conda install -c conda-forge python-pinyin
	```
</details>
<details><summary><b><a href="https://github.com/derek73/python-nameparser">python-nameparser</a></b> (🥉17 ·  ⭐ 510 · 💀) - 把一个人名分解为几个独立的部分。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/derek73/python-nameparser) (👨‍💻 15 · 🔀 84 · 📦 760 · 📋 94 - 25% open · ⏱️ 09.08.2020):

	```
	git clone https://github.com/derek73/python-nameparser
	```
- [PyPi](https://pypi.org/project/python-nameparser):
	```
	pip install python-nameparser
	```
- [Conda](https://anaconda.org/conda-forge/python-nameparser):
	```
	conda install -c conda-forge python-nameparser
	```
</details>
<details><summary><b><a href="https://github.com/ztane/python-Levenshtein">Levenshtein</a></b> (🥉16 ·  ⭐ 1.1K · 💤) - 快速计算编辑距离以及字符串的相似度。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/ztane/python-Levenshtein) (🔀 140 · 📦 10K · 📋 55 - 74% open · ⏱️ 01.02.2021):

	```
	git clone https://github.com/ztane/python-Levenshtein/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/daviddrysdale/python-phonenumbers">python-phonenumbers</a></b> (🥉14 ·  ⭐ 2.9K) - 解析，格式化，存储，校验国际电话号码。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/daviddrysdale/python-phonenumbers) (👨‍💻 25 · 🔀 350 · 📋 130 - 2% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/daviddrysdale/python-phonenumbers
	```
- [PyPi](https://pypi.org/project/python-phonenumbers):
	```
	pip install python-phonenumbers
	```
- [Conda](https://anaconda.org/conda-forge/python-phonenumbers):
	```
	conda install -c conda-forge python-phonenumbers
	```
</details>
<details><summary><b><a href="https://github.com/vinta/pangu.py">pangu.py</a></b> (🥉14 ·  ⭐ 180 · 💀) - 在中日韩语字符和数字字母之间添加空格。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vinta/pangu.py) (👨‍💻 7 · 🔀 22 · 📦 59 · 📋 8 - 37% open · ⏱️ 09.02.2019):

	```
	git clone https://github.com/vinta/pangu.py
	```
- [PyPi](https://pypi.org/project/pangu.py):
	```
	pip install pangu.py
	```
- [Conda](https://anaconda.org/conda-forge/pangu.py):
	```
	conda install -c conda-forge pangu.py
	```
</details>
<details><summary><b><a href="https://github.com/davidaurelio/hashids-python">hashids</a></b> (🥉12 ·  ⭐ 1.3K · 💀) - Implementation of [hashids](http://hashids.org) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidaurelio/hashids-python) (👨‍💻 10 · 🔀 88 · 📋 23 - 21% open · ⏱️ 07.09.2020):

	```
	git clone https://github.com/davidaurelio/hashids-python
	```
- [PyPi](https://pypi.org/project/hashids-python):
	```
	pip install hashids-python
	```
- [Conda](https://anaconda.org/conda-forge/hashids-python):
	```
	conda install -c conda-forge hashids-python
	```
</details>
<br>

## 第三方 API

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来访问第三方 API 的库。 参见： [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers)。_

🔗&nbsp;<b><a href="https://libcloud.apache.org/">apache-libcloud</a></b>  - 一个为各种云设计的 Python 库。

<details><summary><b><a href="https://github.com/boto/boto3">boto3</a></b> (🥇33 ·  ⭐ 6.9K) - Amazon Web Services 的 Python 接口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/boto/boto3) (👨‍💻 130 · 🔀 1.4K · 📦 150K · 📋 2.5K - 10% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/boto/boto3
	```
- [PyPi](https://pypi.org/project/boto3):
	```
	pip install boto3
	```
- [Conda](https://anaconda.org/conda-forge/boto3) (📥 7.9M · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge boto3
	```
</details>
<details><summary><b><a href="https://github.com/burnash/gspread">gspread</a></b> (🥈32 ·  ⭐ 5.7K) - Google 电子表格的 Python API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/burnash/gspread) (👨‍💻 140 · 🔀 820 · 📥 56 · 📦 13K · 📋 670 - 10% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/burnash/gspread
	```
- [PyPi](https://pypi.org/project/gspread) (📥 5.6M / month):
	```
	pip install gspread
	```
- [Conda](https://anaconda.org/conda-forge/gspread) (📥 210K · ⏱️ 09.08.2021):
	```
	conda install -c conda-forge gspread
	```
</details>
<details><summary><b><a href="https://github.com/googleapis/google-api-python-client">google-api-python-client</a></b> (🥈31 ·  ⭐ 5.3K) - Python 用的 Google APIs 客户端库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googleapis/google-api-python-client) (👨‍💻 180 · 🔀 2K · 📥 93 · 📦 83K · 📋 860 - 4% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/google/google-api-python-client
	```
- [PyPi](https://pypi.org/project/google-api-python-client):
	```
	pip install google-api-python-client
	```
- [Conda](https://anaconda.org/conda-forge/google-api-python-client) (📥 990K · ⏱️ 07.12.2021):
	```
	conda install -c conda-forge google-api-python-client
	```
</details>
<details><summary><b><a href="https://github.com/ryanmcgrath/twython">twython</a></b> (🥉29 ·  ⭐ 1.8K) - Twitter API 的封装。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryanmcgrath/twython) (👨‍💻 100 · 🔀 380 · 📦 4.8K · 📋 320 - 5% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/ryanmcgrath/twython
	```
- [PyPi](https://pypi.org/project/twython) (📥 120K / month):
	```
	pip install twython
	```
- [Conda](https://anaconda.org/conda-forge/twython) (📥 250K · ⏱️ 17.07.2021):
	```
	conda install -c conda-forge twython
	```
</details>
<details><summary><b><a href="https://github.com/mobolic/facebook-sdk">facebook-sdk</a></b> (🥉27 ·  ⭐ 2.6K · 💤) - Facebook 平台的 Python SDK。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mobolic/facebook-sdk) (👨‍💻 99 · 🔀 910 · 📦 3.3K · 📋 240 - 8% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/mobolic/facebook-sdk
	```
- [PyPi](https://pypi.org/project/facebook-sdk) (📥 130K / month):
	```
	pip install facebook-sdk
	```
- [Conda](https://anaconda.org/conda-forge/facebook-sdk):
	```
	conda install -c conda-forge facebook-sdk
	```
</details>
<details><summary><b><a href="https://github.com/jcarbaugh/django-wordpress">django-wordpress</a></b> (🥉12 ·  ⭐ 320 · 💀) - Django 的 WordPress 模型与视图。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jcarbaugh/django-wordpress) (👨‍💻 10 · 🔀 79 · 📦 5 · 📋 11 - 18% open · ⏱️ 24.01.2018):

	```
	git clone https://github.com/istrategylabs/django-wordpress
	```
- [PyPi](https://pypi.org/project/django-wordpress):
	```
	pip install django-wordpress
	```
- [Conda](https://anaconda.org/conda-forge/django-wordpress):
	```
	conda install -c conda-forge django-wordpress
	```
</details>
<br>

## URL 处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_解析 URLs 的库_

<details><summary><b><a href="https://github.com/marshmallow-code/webargs">webargs</a></b> (🥇22 ·  ⭐ 1.2K) - 一个解析 HTTP 请求参数的库，内置对流行 web 框架的支持，包括 Flask, Django, Bottle, Tornado 和 Pyramid。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marshmallow-code/webargs) (👨‍💻 58 · 🔀 140 · 📦 3.4K · 📋 260 - 2% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/marshmallow-code/webargs
	```
- [PyPi](https://pypi.org/project/webargs):
	```
	pip install webargs
	```
- [Conda](https://anaconda.org/conda-forge/webargs) (📥 150K · ⏱️ 12.08.2021):
	```
	conda install -c conda-forge webargs
	```
</details>
<details><summary><b><a href="https://github.com/ellisonleao/pyshorteners">pyshorteners</a></b> (🥈18 ·  ⭐ 320 · 💀) - 一个纯 Python URL 缩短库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ellisonleao/pyshorteners) (👨‍💻 24 · 🔀 55 · 📦 3.3K · 📋 74 - 4% open · ⏱️ 29.07.2020):

	```
	git clone https://github.com/ellisonleao/pyshorteners
	```
- [PyPi](https://pypi.org/project/pyshorteners):
	```
	pip install pyshorteners
	```
- [Conda](https://anaconda.org/conda-forge/pyshorteners):
	```
	conda install -c conda-forge pyshorteners
	```
</details>
<details><summary><b><a href="https://github.com/codeinthehole/purl">purl</a></b> (🥈18 ·  ⭐ 260 · 💤) - 一个简单的，不可变的 URL 类，具有简洁的 API 来进行询问和处理。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/codeinthehole/purl) (👨‍💻 18 · 🔀 34 · 📦 1.8K · 📋 20 - 25% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/codeinthehole/purl
	```
- [PyPi](https://pypi.org/project/purl):
	```
	pip install purl
	```
- [Conda](https://anaconda.org/conda-forge/purl):
	```
	conda install -c conda-forge purl
	```
</details>
<details><summary><b><a href="https://github.com/gruns/furl">furl</a></b> (🥉16 ·  ⭐ 2.2K) - 一个让处理 URL 更简单小型 Python 库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gruns/furl) (👨‍💻 14 · 🔀 120 · 📋 100 - 20% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/gruns/furl
	```
- [PyPi](https://pypi.org/project/furl):
	```
	pip install furl
	```
- [Conda](https://anaconda.org/conda-forge/furl) (📥 150K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge furl
	```
</details>
<br>

## Video

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用来操作视频和 GIF 的库。_

🔗&nbsp;<b><a href="https://zulko.github.io/moviepy/">moviepy</a></b>  - 一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。

<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥇20 ·  ⭐ 2.1K) -  强大的多线程视频处理框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 9 · 🔀 160 · 📥 500 · 📦 160 · 📋 190 - 1% open · ⏱️ 05.12.2021):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear):
	```
	pip install vidgear
	```
- [Conda](https://anaconda.org/conda-forge/vidgear):
	```
	conda install -c conda-forge vidgear
	```
</details>
<details><summary><b><a href="https://github.com/aizvorski/scikit-video">scikit-video</a></b> (🥉9 ·  ⭐ 110 · 💀) - SciPy 视频处理常用程序。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/aizvorski/scikit-video) (👨‍💻 2 · 🔀 23 · 📋 7 - 57% open · ⏱️ 28.05.2016):

	```
	git clone https://github.com/aizvorski/scikit-video
	```
- [PyPi](https://pypi.org/project/scikit-video):
	```
	pip install scikit-video
	```
- [Conda](https://anaconda.org/conda-forge/scikit-video) (📥 16K · ⏱️ 20.09.2018):
	```
	conda install -c conda-forge scikit-video
	```
</details>
<br>

## Web 资源管理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理、压缩、缩小网站资源的工具。_

🔗&nbsp;<b><a href="http://www.fanstatic.org/en/latest/">fanstatic</a></b>  - 打包、优化，并且把静态文件依赖作为 Python 的包来提供。

🔗&nbsp;<b><a href="http://wimleers.com/fileconveyor">fileconveyor</a></b>  - A daemon to detect and sync files to CDNs, S3 and FTP.

<details><summary><b><a href="https://github.com/jazzband/django-pipeline">django-pipeline</a></b> (🥇31 ·  ⭐ 1.4K) - Django 的资源包装库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-pipeline) (👨‍💻 170 · 🔀 350 · 📦 1.9K · 📋 430 - 27% open · ⏱️ 25.11.2021):

	```
	git clone https://github.com/jazzband/django-pipeline
	```
- [PyPi](https://pypi.org/project/django-pipeline) (📥 110K / month):
	```
	pip install django-pipeline
	```
- [Conda](https://anaconda.org/conda-forge/django-pipeline):
	```
	conda install -c conda-forge django-pipeline
	```
</details>
<details><summary><b><a href="https://github.com/miracle2k/webassets">webassets</a></b> (🥈23 ·  ⭐ 900 · 💤) - 为你的静态资源打包、优化和管理生成独一无二的缓存 URL。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/miracle2k/webassets) (👨‍💻 160 · 🔀 250 · 📦 5.3K · 📋 290 - 19% open · ⏱️ 01.05.2021):

	```
	git clone https://github.com/miracle2k/webassets
	```
- [PyPi](https://pypi.org/project/webassets):
	```
	pip install webassets
	```
- [Conda](https://anaconda.org/conda-forge/webassets) (📥 39K · ⏱️ 24.12.2019):
	```
	conda install -c conda-forge webassets
	```
</details>
<details><summary><b><a href="https://github.com/miracle2k/flask-assets">flask-assets</a></b> (🥉22 ·  ⭐ 420 · 💀) - 帮你将 web 资源整合到你的 Flask app 中。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/miracle2k/flask-assets) (👨‍💻 38 · 🔀 83 · 📦 6K · 📋 94 - 21% open · ⏱️ 29.02.2020):

	```
	git clone https://github.com/miracle2k/flask-assets
	```
- [PyPi](https://pypi.org/project/flask-assets):
	```
	pip install flask-assets
	```
- [Conda](https://anaconda.org/conda-forge/flask-assets) (📥 27K · ⏱️ 24.12.2019):
	```
	conda install -c conda-forge flask-assets
	```
</details>
<details><summary><b><a href="https://github.com/django-compressor/django-compressor">django-compressor</a></b> (🥉21 ·  ⭐ 2.5K) - 将链接和内联的 JavaScript 或 CSS 压缩到一个单独的缓存文件中。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-compressor/django-compressor) (👨‍💻 200 · 🔀 540 · 📋 610 - 16% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/django-compressor/django-compressor
	```
- [PyPi](https://pypi.org/project/django-compressor) (📥 300K / month):
	```
	pip install django-compressor
	```
- [Conda](https://anaconda.org/conda-forge/django-compressor):
	```
	conda install -c conda-forge django-compressor
	```
</details>
<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥉20 ·  ⭐ 2.1K) - 一个针对 Django 的自定义存储后端的工具集合。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 220 · 🔀 700 · 📋 550 - 25% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages):
	```
	pip install django-storages
	```
- [Conda](https://anaconda.org/conda-forge/django-storages) (📥 31K · ⏱️ 30.10.2021):
	```
	conda install -c conda-forge django-storages
	```
</details>
<br>

## 网络

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_用于网络编程的库。_

<details><summary><b><a href="https://github.com/psf/requests-html">requests-html</a></b> (🥇25 ·  ⭐ 12K · 💀) - 人性化的，Pythonic 的 HTML 解析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/requests-html) (👨‍💻 62 · 🔀 820 · 📦 6.5K · 📋 340 - 42% open · ⏱️ 10.05.2020):

	```
	git clone https://github.com/psf/requests-html
	```
- [PyPi](https://pypi.org/project/requests-html):
	```
	pip install requests-html
	```
- [Conda](https://anaconda.org/conda-forge/requests-html) (📥 540 · ⏱️ 26.06.2021):
	```
	conda install -c conda-forge requests-html
	```
</details>
<details><summary><b><a href="https://github.com/deanmalmgren/textract">textract</a></b> (🥈24 ·  ⭐ 3.2K) - 从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deanmalmgren/textract) (👨‍💻 39 · 🔀 440 · 📋 200 - 37% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/deanmalmgren/textract
	```
- [PyPi](https://pypi.org/project/textract) (📥 73K / month):
	```
	pip install textract
	```
- [Conda](https://anaconda.org/conda-forge/textract) (📥 13K · ⏱️ 22.08.2021):
	```
	conda install -c conda-forge textract
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">sumy</a></b> (🥈23 ·  ⭐ 2.7K) - 一个为文本文件和 HTML 页面进行自动摘要的模块。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 21 · 🔀 450 · 📦 1K · 📋 93 - 13% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 570 · ⏱️ 22.10.2021):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/html2text">html2text</a></b> (🥈23 ·  ⭐ 1.2K) - 将 HTML 转换为 Markdown 格式文本。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Alir3z4/html2text) (👨‍💻 76 · 🔀 200 · 📋 190 - 35% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/Alir3z4/html2text
	```
- [PyPi](https://pypi.org/project/html2text) (📥 1.2M / month):
	```
	pip install html2text
	```
- [Conda](https://anaconda.org/conda-forge/html2text) (📥 7.8K · ⏱️ 09.02.2020):
	```
	conda install -c conda-forge html2text
	```
</details>
<details><summary><b><a href="https://github.com/codelucas/newspaper">newspaper</a></b> (🥉22 ·  ⭐ 12K · 💀) - 使用 Python 进行新闻提取，文章提取以及内容策展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/codelucas/newspaper) (👨‍💻 100 · 🔀 1.8K · 📋 630 - 59% open · ⏱️ 02.09.2020):

	```
	git clone https://github.com/codelucas/newspaper
	```
- [PyPi](https://pypi.org/project/newspaper) (📥 27K / month):
	```
	pip install newspaper
	```
- [Conda](https://anaconda.org/conda-forge/newspaper):
	```
	conda install -c conda-forge newspaper
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/micawber">micawber</a></b> (🥉22 ·  ⭐ 560) - 一个小型网页内容提取库，用来从 URLs 提取富内容。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/micawber) (👨‍💻 27 · 🔀 82 · 📦 640 · ⏱️ 12.07.2021):

	```
	git clone https://github.com/coleifer/micawber
	```
- [PyPi](https://pypi.org/project/micawber) (📥 15K / month):
	```
	pip install micawber
	```
- [Conda](https://anaconda.org/conda-forge/micawber) (📥 1.6K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge micawber
	```
</details>
<details><summary><b><a href="https://github.com/buriy/python-readability">python-readability</a></b> (🥉18 ·  ⭐ 2.1K) - arc90 公司 readability 工具的 Python 高速端口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/buriy/python-readability) (👨‍💻 37 · 🔀 330 · 📋 92 - 31% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/buriy/python-readability
	```
- [PyPi](https://pypi.org/project/python-readability):
	```
	pip install python-readability
	```
- [Conda](https://anaconda.org/conda-forge/python-readability):
	```
	conda install -c conda-forge python-readability
	```
</details>
<details><summary><b><a href="https://github.com/gaojiuli/toapi">toapi</a></b> (🥉16 ·  ⭐ 3.2K) - 一个轻巧，简单，快速的 Flask 库，致力于为所有网站提供 API 服务。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gaojiuli/toapi) (👨‍💻 12 · 🔀 220 · 📋 53 - 9% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/gaojiuli/toapi
	```
- [PyPi](https://pypi.org/project/toapi) (📥 210 / month):
	```
	pip install toapi
	```
- [Conda](https://anaconda.org/conda-forge/toapi):
	```
	conda install -c conda-forge toapi
	```
</details>
<details><summary><b><a href="https://github.com/michaelhelmick/lassie">lassie</a></b> (🥉15 ·  ⭐ 540) - 人性化的网页内容检索库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/michaelhelmick/lassie) (👨‍💻 15 · 🔀 42 · 📦 27 · 📋 38 - 23% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/michaelhelmick/lassie
	```
- [PyPi](https://pypi.org/project/lassie):
	```
	pip install lassie
	```
- [Conda](https://anaconda.org/conda-forge/lassie):
	```
	conda install -c conda-forge lassie
	```
</details>
<br>

## HTML 处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_处理 HTML 和 XML 的库。_

🔗&nbsp;<b><a href="https://pythonhosted.org/feedparser/">feedparser</a></b>  - Universal feed parser.

🔗&nbsp;<b><a href="https://scrapy.org/">scrapy</a></b>  - 一个快速高级的屏幕爬取及网页采集框架。

<details><summary><b><a href="https://github.com/lorien/grab">grab</a></b> (🥇25 ·  ⭐ 2.1K · 💤) - 站点爬取框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lorien/grab) (👨‍💻 65 · 🔀 250 · 📦 330 · 📋 220 - 12% open · ⏱️ 08.12.2020):

	```
	git clone https://github.com/lorien/grab
	```
- [PyPi](https://pypi.org/project/grab) (📥 3.3K / month):
	```
	pip install grab
	```
- [Conda](https://anaconda.org/conda-forge/grab):
	```
	conda install -c conda-forge grab
	```
</details>
<details><summary><b><a href="https://github.com/binux/pyspider">pyspider</a></b> (🥈24 ·  ⭐ 15K · 💀) - 一个强大的爬虫系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/binux/pyspider) (👨‍💻 62 · 🔀 3.5K · 📦 300 · 📋 810 - 33% open · ⏱️ 02.08.2020):

	```
	git clone https://github.com/binux/pyspider
	```
- [PyPi](https://pypi.org/project/pyspider):
	```
	pip install pyspider
	```
- [Conda](https://anaconda.org/conda-forge/pyspider):
	```
	conda install -c conda-forge pyspider
	```
</details>
<details><summary><b><a href="https://github.com/MechanicalSoup/MechanicalSoup">MechanicalSoup</a></b> (🥈21 ·  ⭐ 3.9K) - 用于自动和网络站点交互的 Python 库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MechanicalSoup/MechanicalSoup) (👨‍💻 46 · 🔀 330 · 📥 42 · 📋 160 - 15% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/MechanicalSoup/MechanicalSoup
	```
- [PyPi](https://pypi.org/project/MechanicalSoup):
	```
	pip install MechanicalSoup
	```
- [Conda](https://anaconda.org/conda-forge/MechanicalSoup) (📥 120K · ⏱️ 31.05.2021):
	```
	conda install -c conda-forge MechanicalSoup
	```
</details>
<details><summary><b><a href="https://github.com/jmcarp/robobrowser">robobrowser</a></b> (🥉20 ·  ⭐ 3.6K · 💀) - 一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jmcarp/robobrowser) (👨‍💻 10 · 🔀 330 · 📦 800 · 📋 74 - 59% open · ⏱️ 07.06.2015):

	```
	git clone https://github.com/jmcarp/robobrowser
	```
- [PyPi](https://pypi.org/project/robobrowser) (📥 6.1K / month):
	```
	pip install robobrowser
	```
- [Conda](https://anaconda.org/conda-forge/robobrowser) (📥 4K · ⏱️ 23.03.2018):
	```
	conda install -c conda-forge robobrowser
	```
</details>
<details><summary><b><a href="https://github.com/scrapinghub/portia">portia</a></b> (🥉17 ·  ⭐ 8.3K · 💀) - Scrapy 可视化爬取。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/scrapinghub/portia) (👨‍💻 49 · 🔀 1.3K · 📥 140 · 📦 41 · 📋 450 - 25% open · ⏱️ 10.07.2019):

	```
	git clone https://github.com/scrapinghub/portia
	```
- [PyPi](https://pypi.org/project/portia):
	```
	pip install portia
	```
- [Conda](https://anaconda.org/conda-forge/portia):
	```
	conda install -c conda-forge portia
	```
</details>
<details><summary><b><a href="https://github.com/qinxuye/cola">cola</a></b> (🥉14 ·  ⭐ 1.4K · 💀) - 一个分布式爬虫框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/qinxuye/cola) (👨‍💻 3 · 🔀 530 · 📦 4 · 📋 65 - 20% open · ⏱️ 01.03.2020):

	```
	git clone https://github.com/chineking/cola
	```
- [PyPi](https://pypi.org/project/cola) (📥 82 / month):
	```
	pip install cola
	```
- [Conda](https://anaconda.org/conda-forge/cola):
	```
	conda install -c conda-forge cola
	```
</details>
<br>

## Web 框架

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_全栈 Web 框架。_

🔗&nbsp;<b><a href="https://www.djangoproject.com/">Django</a></b>  - Python 界最流行的 web 框架。

🔗&nbsp;<b><a href="https://github.com/shahraizali/awesome-django">awesome-django</a></b> ( ⭐ 700 · 💀)  - The Best Django Resource, Awesome Django for mature packages.

🔗&nbsp;<b><a href="http://flask.pocoo.org/">Flask</a></b>  - 一个 Python 微型框架。

🔗&nbsp;<b><a href="https://github.com/humiaozuzu/awesome-flask">awesome-flask</a></b> ( ⭐ 10K · 💀)  - A curated list of awesome Flask resources and plugins.

🔗&nbsp;<b><a href="https://pylonsproject.org/">Pyramid</a></b>  - 一个小巧，快速，接地气的开源 Python web 框架。

🔗&nbsp;<b><a href="https://github.com/uralbash/awesome-pyramid">awesome-pyramid</a></b> ( ⭐ 520)  - A curated list of awesome Pyramid apps, projects and resources.

🔗&nbsp;<b><a href="http://www.tornadoweb.org/en/latest/">Tornado</a></b>  - 一个 web 框架和异步网络库。

<details><summary><b><a href="https://github.com/MasoniteFramework/masonite">Masonite</a></b> (🥇19 ·  ⭐ 1.7K) - 以开发者为中心的现代 Python Web 框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MasoniteFramework/masonite) (👨‍💻 74 · 🔀 98 · 📥 8 · 📋 260 - 1% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/MasoniteFramework/masonite
	```
- [PyPi](https://pypi.org/project/masonite):
	```
	pip install masonite
	```
- [Conda](https://anaconda.org/conda-forge/masonite):
	```
	conda install -c conda-forge masonite
	```
</details>
<br>

## WebSocket

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Web socket 相关库。_

<details><summary><b><a href="https://github.com/aaugustin/websockets">websockets</a></b> (🥇29 ·  ⭐ 3.7K) - 一个用于构建 WebSocket 服务器和客户端的库，着重于正确性和简单性。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aaugustin/websockets) (👨‍💻 53 · 🔀 390 · 📦 45K · 📋 820 - 2% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/aaugustin/websockets
	```
- [PyPi](https://pypi.org/project/websockets) (📥 8.1M / month):
	```
	pip install websockets
	```
- [Conda](https://anaconda.org/conda-forge/websockets) (📥 1.1M · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge websockets
	```
</details>
<details><summary><b><a href="https://github.com/django/channels">channels</a></b> (🥉27 ·  ⭐ 5.1K) - 开发者友好的 Django 异步工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django/channels) (👨‍💻 230 · 🔀 680 · 📦 15K · 📋 1.1K - 9% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/django/channels
	```
- [PyPi](https://pypi.org/project/channels) (📥 400K / month):
	```
	pip install channels
	```
- [Conda](https://anaconda.org/conda-forge/channels) (📥 71K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge channels
	```
</details>
<details><summary><b><a href="https://github.com/crossbario/autobahn-python">autobahn-python</a></b> (🥉23 ·  ⭐ 2.3K) - 适用于 Twisted 和 asyncio 的 Python WebSocket 和 WAMP。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/crossbario/autobahn-python) (👨‍💻 120 · 🔀 720 · 📦 16K · 📋 830 - 21% open · ⏱️ 21.11.2021):

	```
	git clone https://github.com/crossbario/autobahn-python
	```
- [PyPi](https://pypi.org/project/autobahn-python):
	```
	pip install autobahn-python
	```
- [Conda](https://anaconda.org/conda-forge/autobahn-python):
	```
	conda install -c conda-forge autobahn-python
	```
</details>
<br>

## WSGI 服务器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_兼容 WSGI 的 web 服务器_

🔗&nbsp;<b><a href="https://uwsgi-docs.readthedocs.io/en/latest/">uWSGI</a></b>  - uwsgi 项目的目的是开发一组全栈工具，用来建立托管服务， 由 C 语言编写。

<details><summary><b><a href="https://github.com/pallets/werkzeug">werkzeug</a></b> (🥇36 ·  ⭐ 5.9K) - 一个 WSGI 工具库，驱动着 Flask ，而且可以很方便大嵌入到你的项目中去。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/werkzeug) (👨‍💻 440 · 🔀 1.6K · 📥 250 · 📦 640K · 📋 910 - 2% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/pallets/werkzeug
	```
- [PyPi](https://pypi.org/project/werkzeug) (📥 46M / month):
	```
	pip install werkzeug
	```
- [Conda](https://anaconda.org/conda-forge/werkzeug) (📥 3.8M · ⏱️ 20.05.2021):
	```
	conda install -c conda-forge werkzeug
	```
</details>
<details><summary><b><a href="https://github.com/benoitc/gunicorn">gunicorn</a></b> (🥈32 ·  ⭐ 8K) - Pre-forked, 部分是由 C 语言编写的。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/benoitc/gunicorn) (👨‍💻 360 · 🔀 1.5K · 📥 99 · 📦 570K · 📋 1.7K - 17% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/benoitc/gunicorn
	```
- [PyPi](https://pypi.org/project/gunicorn):
	```
	pip install gunicorn
	```
- [Conda](https://anaconda.org/conda-forge/gunicorn) (📥 820K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge gunicorn
	```
</details>
<details><summary><b><a href="https://github.com/jonashaag/bjoern">bjoern</a></b> (🥉23 ·  ⭐ 2.7K) - 异步，非常快速，由 C 语言编写。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jonashaag/bjoern) (👨‍💻 41 · 🔀 180 · 📦 380 · 📋 140 - 17% open · ⏱️ 13.08.2021):

	```
	git clone https://github.com/jonashaag/bjoern
	```
- [PyPi](https://pypi.org/project/bjoern) (📥 16K / month):
	```
	pip install bjoern
	```
- [Conda](https://anaconda.org/conda-forge/bjoern) (📥 58K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge bjoern
	```
</details>
<details><summary><b><a href="https://github.com/Pylons/waitress">waitress</a></b> (🥉19 ·  ⭐ 1K) - 多线程, 是它驱动着 Pyramid 框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Pylons/waitress) (👨‍💻 44 · 🔀 130 · 📋 190 - 9% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/Pylons/waitress
	```
- [PyPi](https://pypi.org/project/waitress) (📥 2.2M / month):
	```
	pip install waitress
	```
- [Conda](https://anaconda.org/conda-forge/waitress) (📥 44K · ⏱️ 08.03.2021):
	```
	conda install -c conda-forge waitress
	```
</details>

---

## 相关资源

- [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources): 周更新的各种应用方向与主题的资源汇集列表
- [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources): 周更新的各种python机器学习资源汇集列表
- [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources): 周更新的各种Jupyter及相关工具资源汇集列表
- [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources): 周更新的各种NLP板块涉及的项目和工具资源汇集列表
- [**CV项目和资源大全**](https://github.com/HanXinzi-AI/awesome-computer-vision-resources): 周更新的各种CV板块涉及的项目和工具资源汇集列表
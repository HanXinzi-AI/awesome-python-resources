<!-- markdownlint-disable -->
<h1 align="center">
    Python资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>Python开源工具库资源大全，按应用方向划分并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-680-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-python-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-python-resources?color=green&label=updated"></a>
</p>

本资源清单包含680个python相关的开源工具资源，这些热门工具总共分成91个不同的应用领域，目前在github上已经收到2.8M个点赞。所有的工具(github项目)每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-python](https://github.com/vinta/awesome-python)，欢迎大家提PR丰富本清单。
## Contents

- [Admin Panels](#admin-panels) _9 projects_
- [Algorithms and Design Patterns](#algorithms-and-design-patterns) _7 projects_
- [ASGI Servers](#asgi-servers) _2 projects_
- [Asynchronous Programming](#asynchronous-programming) _4 projects_
- [Audio](#audio) _13 projects_
- [Authentication](#authentication) _9 projects_
- [Build Tools](#build-tools) _5 projects_
- [Built-in Classes Enhancement](#built-in-classes-enhancement) _5 projects_
- [CMS](#cms) _8 projects_
- [Caching](#caching) _7 projects_
- [ChatOps Tools](#chatops-tools) _1 projects_
- [Code Analysis](#code-analysis) _20 projects_
- [Command-line Interface Development](#command-line-interface-development) _12 projects_
- [Command-line Tools](#command-line-tools) _16 projects_
- [Compatibility](#compatibility) _3 projects_
- [Computer Vision](#computer-vision) _7 projects_
- [Concurrency and Parallelism](#concurrency-and-parallelism) _5 projects_
- [Configuration](#configuration) _5 projects_
- [Cryptography](#cryptography) _4 projects_
- [Data Analysis](#data-analysis) _6 projects_
- [Data Validation](#data-validation) _7 projects_
- [Data Visualization](#data-visualization) _14 projects_
- [Database](#database) _3 projects_
- [Database Drivers](#database-drivers) _17 projects_
- [Date and Time](#date-and-time) _10 projects_
- [Debugging Tools](#debugging-tools) _18 projects_
- [Deep Learning](#deep-learning) _6 projects_
- [DevOps Tools](#devops-tools) _13 projects_
- [Distributed Computing](#distributed-computing) _7 projects_
- [Distribution](#distribution) _8 projects_
- [Documentation](#documentation) _4 projects_
- [Downloader](#downloader) _5 projects_
- [E-commerce](#e-commerce) _10 projects_
- [Editor Plugins and IDEs](#editor-plugins-and-ides) _10 projects_
- [Email](#email) _6 projects_
- [Enterprise Application Integrations](#enterprise-application-integrations) _1 projects_
- [Environment Management](#environment-management) _2 projects_
- [Files](#files) _7 projects_
- [Foreign Function Interface](#foreign-function-interface) _4 projects_
- [Forms](#forms) _6 projects_
- [Functional Programming](#functional-programming) _7 projects_
- [GUI Development](#gui-development) _16 projects_
- [GraphQL](#graphql) _4 projects_
- [Game Development](#game-development) _9 projects_
- [Geolocation](#geolocation) _5 projects_
- [HTML Manipulation](#html-manipulation) _11 projects_
- [HTTP Clients](#http-clients) _6 projects_
- [Hardware](#hardware) _7 projects_
- [Image Processing](#image-processing) _14 projects_
- [Implementations](#implementations) _13 projects_
- [Interactive Interpreter](#interactive-interpreter) _4 projects_
- [Internationalization](#internationalization) _2 projects_
- [Job Scheduler](#job-scheduler) _11 projects_
- [Logging](#logging) _5 projects_
- [Machine Learning](#machine-learning) _9 projects_
- [Microsoft Windows](#microsoft-windows) _5 projects_
- [Miscellaneous](#miscellaneous) _6 projects_
- [Natural Language Processing](#natural-language-processing) _13 projects_
- [Network Virtualization](#network-virtualization) _3 projects_
- [News Feed](#news-feed) _2 projects_
- [ORM](#orm) _13 projects_
- [Package Management](#package-management) _5 projects_
- [Package Repositories](#package-repositories) _4 projects_
- [Penetration Testing](#penetration-testing) _3 projects_
- [Permissions](#permissions) _2 projects_
- [Processes](#processes) _3 projects_
- [Recommender Systems](#recommender-systems) _8 projects_
- [Refactoring](#refactoring) _3 projects_
- [RESTful API](#restful-api) _13 projects_
- [Robotics](#robotics) _2 projects_
- [RPC Servers](#rpc-servers) _1 projects_
- [Science](#science) _21 projects_
- [Search](#search) _5 projects_
- [Serialization](#serialization) _4 projects_
- [Serverless Frameworks](#serverless-frameworks) _2 projects_
- [Shell](#shell) _1 projects_
- [Specific Formats Processing](#specific-formats-processing) _17 projects_
- [Static Site Generator](#static-site-generator) _5 projects_
- [Tagging](#tagging) _1 projects_
- [Task Queues](#task-queues) _5 projects_
- [Template Engine](#template-engine) _3 projects_
- [Testing](#testing) _30 projects_
- [Text Processing](#text-processing) _22 projects_
- [Third-party APIs](#third-party-apis) _7 projects_
- [URL Manipulation](#url-manipulation) _4 projects_
- [Video](#video) _3 projects_
- [Web Asset Management](#web-asset-management) _7 projects_
- [Web Content Extracting](#web-content-extracting) _9 projects_
- [Web Crawling](#web-crawling) _8 projects_
- [Web Frameworks](#web-frameworks) _8 projects_
- [WebSocket](#websocket) _3 projects_
- [WSGI Servers](#wsgi-servers) _5 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Admin Panels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for administrative interfaces._

🔗&nbsp;<b><a href="https://grappelliproject.com/">django-grappelli</a></b>  - A jazzy skin for the Django Admin-Interface.

🔗&nbsp;<b><a href="https://djangosuit.com/">django-suit</a></b>  - Alternative Django Admin-Interface (free only for Non-commercial use).

<details><summary><b><a href="https://github.com/flask-admin/flask-admin">flask-admin</a></b> (🥇33 ·  ⭐ 5.1K) - Simple and extensible administrative interface framework for Flask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/flask-admin/flask-admin) (👨‍💻 340 · 🔀 1.4K · 📦 16K · 📋 1.3K - 27% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/flask-admin/flask-admin
	```
- [PyPi](https://pypi.org/project/flask-admin) (📥 1.6M / month):
	```
	pip install flask-admin
	```
- [Conda](https://anaconda.org/conda-forge/flask-admin) (📥 130K · ⏱️ 30.01.2022):
	```
	conda install -c conda-forge flask-admin
	```
</details>
<details><summary><b><a href="https://github.com/mher/flower">flower</a></b> (🥈29 ·  ⭐ 5.4K) - Real-time monitor and web admin for Celery. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mher/flower) (👨‍💻 200 · 🔀 910 · 📦 9.2K · 📋 840 - 11% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/mher/flower
	```
- [PyPi](https://pypi.org/project/flower) (📥 2M / month):
	```
	pip install flower
	```
- [Conda](https://anaconda.org/conda-forge/flower) (📥 120K · ⏱️ 07.08.2022):
	```
	conda install -c conda-forge flower
	```
</details>
<details><summary><b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥈26 ·  ⭐ 3.3K · 💀) - Modern responsive template for the Django admin interface.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/geex-arts/django-jet) (👨‍💻 29 · 🔀 660 · 📦 2.7K · 📋 340 - 64% open · ⏱️ 21.05.2019):

	```
	git clone https://github.com/geex-arts/django-jet
	```
- [PyPi](https://pypi.org/project/django-jet) (📥 28K / month):
	```
	pip install django-jet
	```
- [Conda](https://anaconda.org/conda-forge/django-jet):
	```
	conda install -c conda-forge django-jet
	```
</details>
<details><summary><b><a href="https://github.com/ajenti/ajenti">ajenti</a></b> (🥉24 ·  ⭐ 6.9K) - The admin panel your servers deserve. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ajenti/ajenti) (👨‍💻 23 · 🔀 780 · 📦 25 · 📋 1.1K - 0% open · ⏱️ 24.07.2022):

	```
	git clone https://github.com/ajenti/ajenti
	```
- [PyPi](https://pypi.org/project/ajenti) (📥 270 / month):
	```
	pip install ajenti
	```
- [Conda](https://anaconda.org/conda-forge/ajenti):
	```
	conda install -c conda-forge ajenti
	```
</details>
<details><summary><b><a href="https://github.com/sshwsfc/xadmin">django-xadmin</a></b> (🥉24 ·  ⭐ 4.7K · 💀) - Drop-in replacement of Django admin comes with lots of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/sshwsfc/xadmin) (👨‍💻 51 · 🔀 1.4K · 📦 770 · 📋 570 - 65% open · ⏱️ 03.04.2019):

	```
	git clone https://github.com/sshwsfc/xadmin
	```
- [PyPi](https://pypi.org/project/xadmin) (📥 250 / month):
	```
	pip install xadmin
	```
- [Conda](https://anaconda.org/conda-forge/xadmin):
	```
	conda install -c conda-forge xadmin
	```
</details>
<details><summary><b><a href="https://github.com/wooey/Wooey">wooey</a></b> (🥉22 ·  ⭐ 1.8K) - A Django app which creates automatic web UIs for Python scripts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wooey/Wooey) (👨‍💻 23 · 🔀 170 · 📦 38 · 📋 210 - 24% open · ⏱️ 12.08.2022):

	```
	git clone https://github.com/wooey/wooey
	```
- [PyPi](https://pypi.org/project/wooey) (📥 180 / month):
	```
	pip install wooey
	```
- [Conda](https://anaconda.org/conda-forge/wooey):
	```
	conda install -c conda-forge wooey
	```
</details>
<details><summary><b><a href="https://github.com/jet-admin/jet-bridge">jet-bridge</a></b> (🥉16 ·  ⭐ 1.3K) - Admin panel framework for any application with nice UI (ex Jet Django). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jet-admin/jet-bridge) (👨‍💻 4 · 🔀 110 · 📋 14 - 71% open · ⏱️ 31.08.2022):

	```
	git clone https://github.com/jet-admin/jet-bridge
	```
- [PyPi](https://pypi.org/project/jet-bridge) (📥 530 / month):
	```
	pip install jet-bridge
	```
- [Conda](https://anaconda.org/conda-forge/jet-bridge):
	```
	conda install -c conda-forge jet-bridge
	```
</details>
<br>

## Algorithms and Design Patterns

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Python implementation of data structures, algorithms and design patterns._

<details><summary><b><a href="https://github.com/TheAlgorithms/Python">TheAlgorithms</a></b> (🥇29 ·  ⭐ 140K) - All Algorithms implemented in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/TheAlgorithms/Python) (👨‍💻 860 · 🔀 36K · 📋 1.1K - 2% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/TheAlgorithms/Python
	```
- [PyPi](https://pypi.org/project/Python):
	```
	pip install Python
	```
- [Conda](https://anaconda.org/conda-forge/Python) (📥 64M · ⏱️ 22.08.2022):
	```
	conda install -c conda-forge Python
	```
</details>
<details><summary><b><a href="https://github.com/pytransitions/transitions">transitions</a></b> (🥇29 ·  ⭐ 4.6K) - A lightweight, object-oriented finite state machine implementation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytransitions/transitions) (👨‍💻 74 · 🔀 490 · 📦 2.5K · 📋 410 - 0% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/pytransitions/transitions
	```
- [PyPi](https://pypi.org/project/transitions) (📥 310K / month):
	```
	pip install transitions
	```
- [Conda](https://anaconda.org/conda-forge/transitions) (📥 240K · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge transitions
	```
</details>
<details><summary><b><a href="https://github.com/keon/algorithms">algorithms</a></b> (🥈25 ·  ⭐ 22K) - Minimal examples of data structures and algorithms. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keon/algorithms) (👨‍💻 190 · 🔀 4.1K · 📦 67 · 📋 160 - 37% open · ⏱️ 29.07.2022):

	```
	git clone https://github.com/keon/algorithms
	```
- [PyPi](https://pypi.org/project/algorithms) (📥 6K / month):
	```
	pip install algorithms
	```
- [Conda](https://anaconda.org/conda-forge/algorithms) (📥 950 · ⏱️ 23.04.2021):
	```
	conda install -c conda-forge algorithms
	```
</details>
<details><summary><b><a href="https://github.com/tylerlaberge/PyPattyrn">PyPattyrn</a></b> (🥉19 ·  ⭐ 1.6K · 💀) - A simple yet effective library for implementing common design.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tylerlaberge/PyPattyrn) (👨‍💻 4 · 🔀 120 · 📦 27 · ⏱️ 09.02.2020):

	```
	git clone https://github.com/tylerlaberge/PyPattyrn
	```
- [PyPi](https://pypi.org/project/PyPattyrn) (📥 4.4K / month):
	```
	pip install PyPattyrn
	```
- [Conda](https://anaconda.org/conda-forge/PyPattyrn):
	```
	conda install -c conda-forge PyPattyrn
	```
</details>
<details><summary><b><a href="https://github.com/faif/python-patterns">python-patterns</a></b> (🥉16 ·  ⭐ 35K) - A collection of design patterns in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/faif/python-patterns) (👨‍💻 120 · 🔀 6.2K · 📋 80 - 13% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/faif/python-patterns
	```
- [PyPi](https://pypi.org/project/python-patterns) (📥 20 / month):
	```
	pip install python-patterns
	```
- [Conda](https://anaconda.org/conda-forge/python-patterns):
	```
	conda install -c conda-forge python-patterns
	```
</details>
<details><summary><b><a href="https://github.com/prabhupant/python-ds">python-ds</a></b> (🥉16 ·  ⭐ 1.9K) - A collection of data structure and algorithms for coding interviews. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/prabhupant/python-ds) (👨‍💻 110 · 🔀 490 · 📋 86 - 20% open · ⏱️ 07.04.2022):

	```
	git clone https://github.com/prabhupant/python-ds
	```
- [PyPi](https://pypi.org/project/python-ds) (📥 17 / month):
	```
	pip install python-ds
	```
- [Conda](https://anaconda.org/conda-forge/python-ds):
	```
	conda install -c conda-forge python-ds
	```
</details>
<details><summary><b><a href="https://github.com/grantjenks/python-sortedcontainers">sortedcontainers</a></b> (🥉15 ·  ⭐ 2.7K) - Fast and pure-Python implementation of sorted.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/grantjenks/python-sortedcontainers) (👨‍💻 22 · 🔀 180 · 📋 160 - 8% open · ⏱️ 20.08.2022):

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

## ASGI Servers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_compatible web servers._

<details><summary><b><a href="https://github.com/encode/uvicorn">uvicorn</a></b> (🥇34 ·  ⭐ 5.7K · 📈) - A lightning-fast ASGI server implementation, using uvloop and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/uvicorn) (👨‍💻 140 · 🔀 470 · 📦 93K · 📋 600 - 7% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/encode/uvicorn
	```
- [PyPi](https://pypi.org/project/uvicorn) (📥 9.1M / month):
	```
	pip install uvicorn
	```
- [Conda](https://anaconda.org/conda-forge/uvicorn) (📥 1.2M · ⏱️ 24.08.2022):
	```
	conda install -c conda-forge uvicorn
	```
</details>
<details><summary><b><a href="https://github.com/django/daphne">daphne</a></b> (🥉27 ·  ⭐ 1.8K) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django/daphne) (👨‍💻 62 · 🔀 210 · 📦 16K · 📋 290 - 12% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/django/daphne
	```
- [PyPi](https://pypi.org/project/daphne) (📥 520K / month):
	```
	pip install daphne
	```
- [Conda](https://anaconda.org/conda-forge/daphne) (📥 100K · ⏱️ 07.04.2021):
	```
	conda install -c conda-forge daphne
	```
</details>
<br>

## Asynchronous Programming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Asynchronous I/O, event loop, coroutines and tasks._

🔗&nbsp;<b><a href="https://github.com/timofurrer/awesome-asyncio">awesome-asyncio</a></b> ( ⭐ 3.6K)  - A curated list of awesome Python asyncio frameworks, libraries, software..

🔗&nbsp;<b><a href="https://twistedmatrix.com/trac/">Twisted</a></b>  - An event-driven networking engine.

<details><summary><b><a href="https://github.com/MagicStack/uvloop">uvloop</a></b> (🥇34 ·  ⭐ 8.9K) - Ultra fast asyncio event loop. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/MagicStack/uvloop) (👨‍💻 55 · 🔀 440 · 📥 350 · 📦 51K · 📋 290 - 14% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/MagicStack/uvloop
	```
- [PyPi](https://pypi.org/project/uvloop) (📥 9.2M / month):
	```
	pip install uvloop
	```
- [Conda](https://anaconda.org/conda-forge/uvloop) (📥 480K · ⏱️ 14.09.2022):
	```
	conda install -c conda-forge uvloop
	```
</details>
<details><summary><b><a href="https://github.com/python-trio/trio">trio</a></b> (🥉29 ·  ⭐ 4.9K) - A friendly library for async concurrency and I/O. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-trio/trio) (👨‍💻 130 · 🔀 270 · 📦 15K · 📋 670 - 39% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/python-trio/trio
	```
- [PyPi](https://pypi.org/project/trio) (📥 6.5M / month):
	```
	pip install trio
	```
- [Conda](https://anaconda.org/conda-forge/trio) (📥 800K · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge trio
	```
</details>
<br>

## Audio

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for manipulating audio and its metadata._

🔗&nbsp;<b><a href="http://bspaans.github.io/python-mingus/">mingus</a></b>  - An advanced music theory and notation package with MIDI file and playback support.

<details><summary><b><a href="https://github.com/beetbox/beets">beets</a></b> (🥇30 ·  ⭐ 11K) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/beets) (👨‍💻 510 · 🔀 1.7K · 📥 7.7K · 📦 260 · 📋 2.5K - 18% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/beetbox/beets
	```
- [PyPi](https://pypi.org/project/beets) (📥 2K / month):
	```
	pip install beets
	```
- [Conda](https://anaconda.org/conda-forge/beets):
	```
	conda install -c conda-forge beets
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">pydub</a></b> (🥇30 ·  ⭐ 6.4K) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 92 · 🔀 840 · 📦 14K · 📋 490 - 47% open · ⏱️ 14.05.2022):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 1.9M / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 29K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/quodlibet/mutagen">mutagen</a></b> (🥈27 ·  ⭐ 1.1K) - A Python module to handle audio metadata. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/quodlibet/mutagen) (👨‍💻 37 · 🔀 120 · 📥 56K · 📦 8.2K · 📋 480 - 20% open · ⏱️ 16.07.2022):

	```
	git clone https://github.com/quodlibet/mutagen
	```
- [PyPi](https://pypi.org/project/mutagen) (📥 1.7M / month):
	```
	pip install mutagen
	```
- [Conda](https://anaconda.org/conda-forge/mutagen) (📥 130K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge mutagen
	```
</details>
<details><summary><b><a href="https://github.com/nicfit/eyeD3">eyeD3</a></b> (🥈25 ·  ⭐ 400) - A tool for working with audio files, specifically MP3 files containing.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicfit/eyeD3) (👨‍💻 24 · 🔀 54 · 📥 2.3K · 📦 1.9K · 📋 180 - 24% open · ⏱️ 29.07.2022):

	```
	git clone https://github.com/nicfit/eyeD3
	```
- [PyPi](https://pypi.org/project/eyeD3) (📥 38K / month):
	```
	pip install eyeD3
	```
- [Conda](https://anaconda.org/conda-forge/eyeD3):
	```
	conda install -c conda-forge eyeD3
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥈24 ·  ⭐ 5K) - Audio feature extraction, classification, segmentation and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 26 · 🔀 1.1K · 📦 300 · 📋 290 - 59% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 15K / month):
	```
	pip install pyAudioAnalysis
	```
- [Conda](https://anaconda.org/conda-forge/pyAudioAnalysis):
	```
	conda install -c conda-forge pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥉23 ·  ⭐ 5.4K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 110 · 🔀 820 · 📋 1K - 4% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 1.1M / month):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 510K · ⏱️ 27.06.2022):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉23 ·  ⭐ 560) - A library for reading music meta data of MP3, OGG, FLAC and Wave files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 22 · 🔀 89 · 📦 590 · 📋 95 - 14% open · ⏱️ 13.08.2022):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 74K / month):
	```
	pip install tinytag
	```
- [Conda](https://anaconda.org/conda-forge/tinytag):
	```
	conda install -c conda-forge tinytag
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉22 ·  ⭐ 850) - Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 140 · 📥 22 · 📦 1.8K · 📋 94 - 12% open · ⏱️ 04.07.2022):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 3K / month):
	```
	pip install kapre
	```
- [Conda](https://anaconda.org/conda-forge/kapre):
	```
	conda install -c conda-forge kapre
	```
</details>
<details><summary><b><a href="https://github.com/worldveil/dejavu">dejavu</a></b> (🥉19 ·  ⭐ 5.8K · 💀) - Audio fingerprinting and recognition. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/worldveil/dejavu) (👨‍💻 22 · 🔀 1.3K · 📦 23 · 📋 210 - 39% open · ⏱️ 03.06.2020):

	```
	git clone https://github.com/worldveil/dejavu
	```
- [PyPi](https://pypi.org/project/dejavu) (📥 100 / month):
	```
	pip install dejavu
	```
- [Conda](https://anaconda.org/conda-forge/dejavu):
	```
	conda install -c conda-forge dejavu
	```
</details>
<details><summary><b><a href="https://github.com/sergree/matchering">matchering</a></b> (🥉19 ·  ⭐ 670) - A library for automated reference audio mastering. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sergree/matchering) (👨‍💻 3 · 🔀 91 · 📦 10 · 📋 36 - 27% open · ⏱️ 30.08.2022):

	```
	git clone https://github.com/sergree/matchering
	```
- [PyPi](https://pypi.org/project/matchering) (📥 510 / month):
	```
	pip install matchering
	```
- [Conda](https://anaconda.org/conda-forge/matchering):
	```
	conda install -c conda-forge matchering
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥉19 ·  ⭐ 410) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 22 · 🔀 95 · 📋 80 - 38% open · ⏱️ 12.08.2022):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 1.1M / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 490K · ⏱️ 14.08.2022):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/Parisson/TimeSide">TimeSide</a></b> (🥉18 ·  ⭐ 330) - Open web audio processing framework. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Parisson/TimeSide) (👨‍💻 22 · 🔀 55 · 📦 16 · 📋 210 - 27% open · ⏱️ 22.07.2022):

	```
	git clone https://github.com/Parisson/TimeSide
	```
- [PyPi](https://pypi.org/project/TimeSide) (📥 88 / month):
	```
	pip install TimeSide
	```
- [Conda](https://anaconda.org/conda-forge/TimeSide):
	```
	conda install -c conda-forge TimeSide
	```
</details>
<br>

## Authentication

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for implementing authentications schemes._

<details><summary><b><a href="https://github.com/oauthlib/oauthlib">oauthlib</a></b> (🥇37 ·  ⭐ 2.4K · 📈) - A generic and thorough implementation of the OAuth request-signing.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oauthlib/oauthlib) (👨‍💻 190 · 🔀 430 · 📦 260K · 📋 360 - 20% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/idan/oauthlib
	```
- [PyPi](https://pypi.org/project/oauthlib) (📥 97M / month):
	```
	pip install oauthlib
	```
- [Conda](https://anaconda.org/conda-forge/oauthlib) (📥 6M · ⏱️ 09.09.2022):
	```
	conda install -c conda-forge oauthlib
	```
</details>
<details><summary><b><a href="https://github.com/jpadilla/pyjwt">pyjwt</a></b> (🥈35 ·  ⭐ 4.3K) - JSON Web Token implementation in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jpadilla/pyjwt) (👨‍💻 120 · 🔀 570 · 📦 240K · 📋 360 - 4% open · ⏱️ 14.08.2022):

	```
	git clone https://github.com/jpadilla/pyjwt
	```
- [PyPi](https://pypi.org/project/pyjwt) (📥 100M / month):
	```
	pip install pyjwt
	```
- [Conda](https://anaconda.org/conda-forge/pyjwt) (📥 7.6M · ⏱️ 12.05.2022):
	```
	conda install -c conda-forge pyjwt
	```
</details>
<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥈34 ·  ⭐ 7.4K) - Authentication app for Django that just works. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 600 · 🔀 2.5K · 📦 100K · 📋 1.9K - 16% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 570K / month):
	```
	pip install django-allauth
	```
- [Conda](https://anaconda.org/conda-forge/django-allauth) (📥 78K · ⏱️ 07.06.2022):
	```
	conda install -c conda-forge django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/lepture/authlib">authlib</a></b> (🥈34 ·  ⭐ 3.3K) - JavaScript Object Signing and Encryption draft implementation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lepture/authlib) (👨‍💻 86 · 🔀 320 · 📦 23K · 📋 340 - 13% open · ⏱️ 27.08.2022):

	```
	git clone https://github.com/lepture/authlib
	```
- [PyPi](https://pypi.org/project/authlib) (📥 5.4M / month):
	```
	pip install authlib
	```
- [Conda](https://anaconda.org/conda-forge/authlib) (📥 83K · ⏱️ 13.09.2022):
	```
	conda install -c conda-forge authlib
	```
</details>
<details><summary><b><a href="https://github.com/omab/python-social-auth">python-social-auth</a></b> (🥉28 ·  ⭐ 2.8K · 💀) - An easy-to-setup social authentication mechanism. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/omab/python-social-auth) (👨‍💻 280 · 🔀 1.1K · 📦 5.4K · 📋 660 - 2% open · ⏱️ 04.02.2017):

	```
	git clone https://github.com/omab/python-social-auth
	```
- [PyPi](https://pypi.org/project/python-social-auth) (📥 30K / month):
	```
	pip install python-social-auth
	```
- [Conda](https://anaconda.org/conda-forge/python-social-auth):
	```
	conda install -c conda-forge python-social-auth
	```
</details>
<details><summary><b><a href="https://github.com/joestump/python-oauth2">python-oauth2</a></b> (🥉26 ·  ⭐ 3K · 💀) - A fully tested, abstract interface to creating OAuth clients.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joestump/python-oauth2) (👨‍💻 42 · 🔀 810 · 📦 9.6K · 📋 130 - 38% open · ⏱️ 12.02.2018):

	```
	git clone https://github.com/joestump/python-oauth2
	```
- [PyPi](https://pypi.org/project/python-oauth2) (📥 36K / month):
	```
	pip install python-oauth2
	```
- [Conda](https://anaconda.org/conda-forge/python-oauth2) (📥 86K · ⏱️ 28.06.2019):
	```
	conda install -c conda-forge python-oauth2
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥉24 ·  ⭐ 2.6K) - OAuth 2 goodies for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-oauth-toolkit) (👨‍💻 210 · 🔀 660 · 📋 720 - 20% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/evonove/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 340K / month):
	```
	pip install django-oauth-toolkit
	```
- [Conda](https://anaconda.org/conda-forge/django-oauth-toolkit):
	```
	conda install -c conda-forge django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/davedoesdev/python-jwt">python-jwt</a></b> (🥉18 ·  ⭐ 200) - A module for generating and verifying JSON Web Tokens. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davedoesdev/python-jwt) (👨‍💻 5 · 🔀 23 · ⏱️ 31.08.2022):

	```
	git clone https://github.com/davedoesdev/python-jwt
	```
- [PyPi](https://pypi.org/project/python-jwt) (📥 220K / month):
	```
	pip install python-jwt
	```
- [Conda](https://anaconda.org/conda-forge/python-jwt):
	```
	conda install -c conda-forge python-jwt
	```
</details>
<details><summary><b><a href="https://github.com/mpdavis/python-jose">python-jose</a></b> (🥉17 ·  ⭐ 1.2K · 💤) - A JOSE implementation in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mpdavis/python-jose) (🔀 200 · 📋 130 - 42% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/mpdavis/python-jose/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Compile software from source code._

🔗&nbsp;<b><a href="http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html">BitBake</a></b>  - A make-like build tool for embedded Linux.

🔗&nbsp;<b><a href="http://www.buildout.org/en/latest/">buildout</a></b>  - A build system for creating, assembling and deploying applications from multiple parts.

🔗&nbsp;<b><a href="http://www.scons.org/">SCons</a></b>  - A software construction tool.

<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥇24 ·  ⭐ 1.4K) - A continuous build tool written in pure Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 38 · 🔀 230 · 📋 500 - 16% open · ⏱️ 20.08.2022):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📥 25K / month):
	```
	pip install pybuilder
	```
- [Conda](https://anaconda.org/conda-forge/pybuilder) (📥 20K · ⏱️ 11.08.2022):
	```
	conda install -c conda-forge pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/platformio/platformio-core">PlatformIO</a></b> (🥉20 ·  ⭐ 6.1K) - A console tool to build code with different development platforms. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/platformio/platformio-core) (👨‍💻 69 · 🔀 650 · 📋 3.8K - 3% open · ⏱️ 03.09.2022):

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

## Built-in Classes Enhancement

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for enhancing Python built-in classes._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/dataclasses.html">dataclasses</a></b>  - (Python standard library) Data classes.

<details><summary><b><a href="https://github.com/python-attrs/attrs">attrs</a></b> (🥇34 ·  ⭐ 4.4K) - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-attrs/attrs) (👨‍💻 130 · 🔀 300 · 📦 470K · 📋 580 - 17% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/python-attrs/attrs
	```
- [PyPi](https://pypi.org/project/attrs) (📥 140M / month):
	```
	pip install attrs
	```
- [Conda](https://anaconda.org/conda-forge/attrs) (📥 20M · ⏱️ 31.07.2022):
	```
	conda install -c conda-forge attrs
	```
</details>
<details><summary><b><a href="https://github.com/jab/bidict">bidict</a></b> (🥈26 ·  ⭐ 1.2K) - Efficient, Pythonic bidirectional map data structures and related.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/jab/bidict) (👨‍💻 12 · 🔀 48 · 📦 8.8K · 📋 52 - 7% open · ⏱️ 07.09.2022):

	```
	git clone https://github.com/jab/bidict
	```
- [PyPi](https://pypi.org/project/bidict) (📥 910K / month):
	```
	pip install bidict
	```
- [Conda](https://anaconda.org/conda-forge/bidict) (📥 150K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge bidict
	```
</details>
<details><summary><b><a href="https://github.com/cdgriffith/Box">Box</a></b> (🥉16 ·  ⭐ 2.1K) - Python dictionaries with advanced dot notation access. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cdgriffith/Box) (🔀 83 · 📥 30 · 📋 140 - 14% open · ⏱️ 02.04.2022):

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
<details><summary><b><a href="https://github.com/carlosescri/DottedDict">DottedDict</a></b> (🥉16 ·  ⭐ 150 · 💀) - A library that provides a method of accessing lists and dicts with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carlosescri/DottedDict) (👨‍💻 3 · 🔀 17 · 📥 62 · 📦 63 · 📋 9 - 77% open · ⏱️ 30.10.2015):

	```
	git clone https://github.com/carlosescri/DottedDict
	```
- [PyPi](https://pypi.org/project/DottedDict) (📥 28 / month):
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

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems._

🔗&nbsp;<b><a href="https://www.django-cms.org/en/">django-cms</a></b>  - An Open source enterprise CMS based on the Django.

🔗&nbsp;<b><a href="https://plone.org/">plone</a></b>  - A CMS built on top of the open source application server Zope.

🔗&nbsp;<b><a href="https://wagtail.io/">wagtail</a></b>  - A Django content management system.

<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥇25 ·  ⭐ 4.5K) - A powerful, consistent, and flexible content management platform. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 320 · 🔀 1.5K · 📋 1K - 3% open · ⏱️ 03.07.2022):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 3.9K / month):
	```
	pip install mezzanine
	```
- [Conda](https://anaconda.org/conda-forge/mezzanine):
	```
	conda install -c conda-forge mezzanine
	```
</details>
<details><summary><b><a href="https://github.com/indico/indico">indico</a></b> (🥈23 ·  ⭐ 1.4K) - A feature-rich event management system, made @.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/indico/indico) (👨‍💻 130 · 🔀 340 · 📥 2.9K · 📋 3.3K - 18% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/indico/indico
	```
- [PyPi](https://pypi.org/project/indico) (📥 1.2K / month):
	```
	pip install indico
	```
- [Conda](https://anaconda.org/conda-forge/indico):
	```
	conda install -c conda-forge indico
	```
</details>
<details><summary><b><a href="https://github.com/Kotti/Kotti">Kotti</a></b> (🥉19 ·  ⭐ 390) - A high-level, Pythonic web application framework built on Pyramid. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Kotti/Kotti) (👨‍💻 66 · 🔀 110 · 📦 220 · 📋 210 - 20% open · ⏱️ 03.07.2022):

	```
	git clone https://github.com/Kotti/Kotti
	```
- [PyPi](https://pypi.org/project/Kotti) (📥 580 / month):
	```
	pip install Kotti
	```
- [Conda](https://anaconda.org/conda-forge/Kotti):
	```
	conda install -c conda-forge Kotti
	```
</details>
<details><summary><b><a href="https://github.com/feincms/feincms">feincms</a></b> (🥉16 ·  ⭐ 840) - One of the most advanced Content Management Systems built on Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/feincms/feincms) (👨‍💻 140 · 🔀 210 · 📋 440 - 5% open · ⏱️ 04.07.2022):

	```
	git clone https://github.com/feincms/feincms
	```
- [PyPi](https://pypi.org/project/feincms) (📥 4K / month):
	```
	pip install feincms
	```
- [Conda](https://anaconda.org/conda-forge/feincms):
	```
	conda install -c conda-forge feincms
	```
</details>
<details><summary><b><a href="https://github.com/quokkaproject/quokka">quokka</a></b> (🥉14 ·  ⭐ 2.2K · 💀) - Flexible, extensible, small CMS powered by Flask and MongoDB. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/quokkaproject/quokka) (👨‍💻 9 · 🔀 440 · 📋 420 - 15% open · ⏱️ 06.03.2019):

	```
	git clone https://github.com/rochacbruno/quokka
	```
- [PyPi](https://pypi.org/project/quokka) (📥 120 / month):
	```
	pip install quokka
	```
- [Conda](https://anaconda.org/conda-forge/quokka):
	```
	conda install -c conda-forge quokka
	```
</details>
<br>

## Caching

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for caching data._

🔗&nbsp;<b><a href="http://dogpilecache.readthedocs.io/en/latest/">dogpile.cache</a></b>  - dogpile.cache is next generation replacement for Beaker made by same authors.

🔗&nbsp;<b><a href="https://pypi.org/project/HermesCache/">HermesCache</a></b>  - Python caching library with tag-based invalidation and dogpile effect prevention.

🔗&nbsp;<b><a href="http://www.grantjenks.com/docs/diskcache/">python-diskcache</a></b>  - SQLite and file backed cache backend with faster lookups than memcached and redis.

<details><summary><b><a href="https://github.com/lericson/pylibmc">pylibmc</a></b> (🥇28 ·  ⭐ 460) - A Python wrapper around the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lericson/pylibmc) (👨‍💻 52 · 🔀 120 · 📥 40 · 📦 4.1K · 📋 190 - 10% open · ⏱️ 26.08.2022):

	```
	git clone https://github.com/lericson/pylibmc
	```
- [PyPi](https://pypi.org/project/pylibmc) (📥 170K / month):
	```
	pip install pylibmc
	```
- [Conda](https://anaconda.org/conda-forge/pylibmc) (📥 180K · ⏱️ 30.08.2022):
	```
	conda install -c conda-forge pylibmc
	```
</details>
<details><summary><b><a href="https://github.com/Suor/django-cacheops">django-cacheops</a></b> (🥈26 ·  ⭐ 1.7K) - A slick ORM cache with automatic granular event-driven.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/django-cacheops) (👨‍💻 64 · 🔀 190 · 📦 750 · 📋 300 - 7% open · ⏱️ 11.07.2022):

	```
	git clone https://github.com/Suor/django-cacheops
	```
- [PyPi](https://pypi.org/project/django-cacheops) (📥 130K / month):
	```
	pip install django-cacheops
	```
- [Conda](https://anaconda.org/conda-forge/django-cacheops):
	```
	conda install -c conda-forge django-cacheops
	```
</details>
<details><summary><b><a href="https://github.com/bbangert/beaker">beaker</a></b> (🥉24 ·  ⭐ 490 · 💤) - A WSGI middleware for sessions and caching. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/bbangert/beaker) (👨‍💻 86 · 🔀 130 · 📦 3.7K · 📋 120 - 53% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/bbangert/beaker
	```
- [PyPi](https://pypi.org/project/beaker) (📥 300K / month):
	```
	pip install beaker
	```
- [Conda](https://anaconda.org/conda-forge/beaker) (📥 63K · ⏱️ 27.08.2019):
	```
	conda install -c conda-forge beaker
	```
</details>
<details><summary><b><a href="https://github.com/django-cache-machine/django-cache-machine">django-cache-machine</a></b> (🥉22 ·  ⭐ 840) - Automatic caching and invalidation for Django models. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-cache-machine/django-cache-machine) (👨‍💻 27 · 🔀 150 · 📦 230 · 📋 71 - 21% open · ⏱️ 06.07.2022):

	```
	git clone https://github.com/django-cache-machine/django-cache-machine
	```
- [PyPi](https://pypi.org/project/django-cache-machine) (📥 7.7K / month):
	```
	pip install django-cache-machine
	```
- [Conda](https://anaconda.org/conda-forge/django-cache-machine):
	```
	conda install -c conda-forge django-cache-machine
	```
</details>
<br>

## ChatOps Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for chatbot development._

<details><summary><b><a href="https://github.com/errbotio/errbot">errbot</a></b> (🥇21 ·  ⭐ 2.8K) - The easiest and most popular chatbot to implement ChatOps. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/errbotio/errbot) (🔀 570 · 📦 260 · 📋 750 - 8% open · ⏱️ 21.07.2022):

	```
	git clone https://github.com/errbotio/errbot/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Code Analysis

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools of static analysis, linters and code quality checkers._

🔗&nbsp;<b><a href="https://pypi.org/project/flake8/">flake8</a></b>  - A wrapper around `pycodestyle`, `pyflakes` and McCabe.

🔗&nbsp;<b><a href="https://github.com/DmytroLitvinov/awesome-flake8-extensions">awesome-flake8-extensions</a></b> ( ⭐ 900)  - A curated awesome list of flake8 extensions. Feel free to..

🔗&nbsp;<b><a href="https://www.pylint.org/">pylint</a></b>  - A fully customizable source code analyzer.

🔗&nbsp;<b><a href="https://github.com/typeddjango/awesome-python-typing">awesome-python-typing</a></b> ( ⭐ 1.1K)  - Collection of awesome Python types, stubs, plugins, and tools to..

🔗&nbsp;<b><a href="http://mypy-lang.org/">mypy</a></b>  - Check variable types during compile time.

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇35 ·  ⭐ 29K) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 340 · 🔀 1.8K · 📥 24K · 📦 180K · 📋 2K - 15% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/python/black
	```
- [PyPi](https://pypi.org/project/black) (📥 15M / month):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 4.9M · ⏱️ 06.08.2022):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥇32 ·  ⭐ 5.2K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 260 · 🔀 470 · 📦 270K · 📋 1.1K - 8% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/timothycrosley/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 22M / month):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 3.6M · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈31 ·  ⭐ 2K) - The strictest and most opinionated python linter ever. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 170 · 🔀 340 · 📦 5.6K · 📋 1K - 9% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 280K / month):
	```
	pip install wemake-python-styleguide
	```
- [Conda](https://anaconda.org/conda-forge/wemake-python-styleguide):
	```
	conda install -c conda-forge wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥈29 ·  ⭐ 13K) - Yet another Python code formatter from Google. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 140 · 🔀 840 · 📦 37K · 📋 750 - 47% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 2.3M / month):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 1.1M · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/klen/pylama">pylama</a></b> (🥈26 ·  ⭐ 930) - A code audit tool for Python and JavaScript. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/klen/pylama) (👨‍💻 46 · 🔀 89 · 📦 4.2K · 📋 130 - 30% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/klen/pylama
	```
- [PyPi](https://pypi.org/project/pylama) (📥 150K / month):
	```
	pip install pylama
	```
- [Conda](https://anaconda.org/conda-forge/pylama) (📥 85K · ⏱️ 18.05.2019):
	```
	conda install -c conda-forge pylama
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈25 ·  ⭐ 2.2K) - A tool for finding and analysing dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 33 · 🔀 110 · 📦 1.9K · 📋 160 - 10% open · ⏱️ 27.07.2022):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 360K / month):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 58K · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥉23 ·  ⭐ 6K) - Performant type checking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 210 · 🔀 370 · 📋 320 - 28% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 120K / month):
	```
	pip install pyre-check
	```
- [Conda](https://anaconda.org/conda-forge/pyre-check):
	```
	conda install -c conda-forge pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥉22 ·  ⭐ 1.7K) - A tool to analyse Python code. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 79 · 🔀 150 · 📋 320 - 12% open · ⏱️ 14.08.2022):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 420K / month):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 38K · ⏱️ 10.03.2022):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/gak/pycallgraph">pycallgraph</a></b> (🥉22 ·  ⭐ 1.7K · 💀) - A library that visualises the flow (call graph) of your.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/gak/pycallgraph) (👨‍💻 23 · 🔀 270 · 📦 370 · 📋 160 - 30% open · ⏱️ 28.02.2018):

	```
	git clone https://github.com/gak/pycallgraph
	```
- [PyPi](https://pypi.org/project/pycallgraph) (📥 27K / month):
	```
	pip install pycallgraph
	```
- [Conda](https://anaconda.org/conda-forge/pycallgraph):
	```
	conda install -c conda-forge pycallgraph
	```
</details>
<details><summary><b><a href="https://github.com/scottrogowski/code2flow">code2flow</a></b> (🥉20 ·  ⭐ 2.6K) - Turn your Python and JavaScript code into DOT flowcharts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/scottrogowski/code2flow) (👨‍💻 9 · 🔀 210 · 📦 10 · 📋 44 - 9% open · ⏱️ 25.07.2022):

	```
	git clone https://github.com/scottrogowski/code2flow
	```
- [PyPi](https://pypi.org/project/code2flow) (📥 1.7K / month):
	```
	pip install code2flow
	```
- [Conda](https://anaconda.org/conda-forge/code2flow) (📥 1.3K · ⏱️ 25.03.2022):
	```
	conda install -c conda-forge code2flow
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥉19 ·  ⭐ 3.4K · 💀) - Language independent and easily extendable code analysis.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (🔀 1.3K · 📥 150 · 📦 10 · 📋 3K - 21% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/coala/coala/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉19 ·  ⭐ 1.3K · 💤) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 17 · 🔀 56 · 📦 78 · 📋 59 - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate) (📥 4.7K / month):
	```
	pip install pyannotate
	```
- [Conda](https://anaconda.org/conda-forge/pyannotate):
	```
	conda install -c conda-forge pyannotate
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥉18 ·  ⭐ 3.9K) - Pytype checks and infers types for Python code - without.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 81 · 🔀 240 · 📋 550 - 18% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 300K / month):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 100K · ⏱️ 09.09.2022):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/python/typeshed">typeshed</a></b> (🥉18 ·  ⭐ 3.1K) - Collection of library stubs for Python, with static types. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python/typeshed) (👨‍💻 1.2K · 🔀 1.3K · 📋 1.9K - 7% open · ⏱️ 15.09.2022):

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
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥉16 ·  ⭐ 4K) - A system for Python that generates static type annotations by.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 42 · 🔀 140 · 📋 160 - 23% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/MonkeyType) (📥 54K / month):
	```
	pip install MonkeyType
	```
- [Conda](https://anaconda.org/conda-forge/MonkeyType) (📥 43K · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge MonkeyType
	```
</details>
<br>

## Command-line Interface Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building command-line applications._

🔗&nbsp;<b><a href="http://builtoncement.com/">cement</a></b>  - CLI Application Framework for Python.

🔗&nbsp;<b><a href="http://click.pocoo.org/dev/">click</a></b>  - A package for creating beautiful command line interfaces in a composable way.

🔗&nbsp;<b><a href="https://docs.openstack.org/developer/cliff/">cliff</a></b>  - A framework for creating command-line programs with multi-level commands.

🔗&nbsp;<b><a href="http://docopt.org/">docopt</a></b>  - Pythonic command line arguments parser.

🔗&nbsp;<b><a href="https://pypi.org/project/colorama/">colorama</a></b>  - Cross-platform colored terminal text.

<details><summary><b><a href="https://github.com/Textualize/rich">rich</a></b> (🥇37 ·  ⭐ 40K) - Python library for rich text and beautiful formatting in the terminal. Also.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Textualize/rich) (👨‍💻 190 · 🔀 1.3K · 📦 30K · 📋 900 - 7% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/willmcgugan/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 12M / month):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 1.7M · ⏱️ 11.07.2022):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥈36 ·  ⭐ 23K) - Fast, extensible progress bar for loops and CLI. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 110 · 🔀 1.1K · 📥 9.9K · 📦 320K · 📋 850 - 34% open · ⏱️ 03.09.2022):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 44M / month):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 14M · ⏱️ 03.09.2022):
	```
	conda install -c conda-forge tqdm
	```
</details>
<details><summary><b><a href="https://github.com/peterbrittain/asciimatics">asciimatics</a></b> (🥈27 ·  ⭐ 3.1K) - A package to create full-screen text UIs (from interactive.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/peterbrittain/asciimatics) (👨‍💻 40 · 🔀 230 · 📦 690 · 📋 280 - 8% open · ⏱️ 03.07.2022):

	```
	git clone https://github.com/peterbrittain/asciimatics
	```
- [PyPi](https://pypi.org/project/asciimatics) (📥 43K / month):
	```
	pip install asciimatics
	```
- [Conda](https://anaconda.org/conda-forge/asciimatics) (📥 110K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge asciimatics
	```
</details>
<details><summary><b><a href="https://github.com/google/python-fire">python-fire</a></b> (🥉25 ·  ⭐ 23K) - A library for creating command line interfaces from.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/python-fire) (👨‍💻 49 · 🔀 1.3K · 📦 14K · 📋 260 - 37% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/google/python-fire
	```
- [PyPi](https://pypi.org/project/python-fire) (📥 120 / month):
	```
	pip install python-fire
	```
- [Conda](https://anaconda.org/conda-forge/python-fire):
	```
	conda install -c conda-forge python-fire
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉24 ·  ⭐ 3.8K) - A new kind of Progress Bar, with real-time throughput, eta and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 7 · 🔀 150 · 📦 1.1K · 📋 150 - 12% open · ⏱️ 16.07.2022):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 88K / month):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 18K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/glamp/bashplotlib">bashplotlib</a></b> (🥉19 ·  ⭐ 1.7K · 💀) - Making basic plots in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/glamp/bashplotlib) (👨‍💻 20 · 🔀 82 · 📦 150 · 📋 29 - 62% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/glamp/bashplotlib
	```
- [PyPi](https://pypi.org/project/bashplotlib) (📥 5K / month):
	```
	pip install bashplotlib
	```
- [Conda](https://anaconda.org/conda-forge/bashplotlib) (📥 3.6K · ⏱️ 08.09.2018):
	```
	conda install -c conda-forge bashplotlib
	```
</details>
<details><summary><b><a href="https://github.com/prompt-toolkit/python-prompt-toolkit">python-prompt-toolkit</a></b> (🥉18 ·  ⭐ 7.9K) - A library for building powerful interactive command.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/prompt-toolkit/python-prompt-toolkit) (👨‍💻 210 · 🔀 620 · 📋 1K - 47% open · ⏱️ 02.09.2022):

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
<br>

## Command-line Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Useful CLI-based tools for productivity._

<details><summary><b><a href="https://github.com/httpie/httpie">httpie</a></b> (🥇34 ·  ⭐ 24K) - A command line HTTP client, a user-friendly cURL replacement. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/httpie/httpie) (👨‍💻 150 · 🔀 3.5K · 📥 1.2K · 📦 11K · 📋 780 - 14% open · ⏱️ 10.08.2022):

	```
	git clone https://github.com/jakubroztocil/httpie
	```
- [PyPi](https://pypi.org/project/httpie) (📥 200K / month):
	```
	pip install httpie
	```
- [Conda](https://anaconda.org/conda-forge/httpie) (📥 83K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge httpie
	```
</details>
<details><summary><b><a href="https://github.com/cookiecutter/cookiecutter">cookiecutter</a></b> (🥇32 ·  ⭐ 18K · 📉) - A command-line utility that creates projects from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cookiecutter/cookiecutter) (👨‍💻 280 · 🔀 1.7K · 📦 14K · 📋 740 - 24% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/audreyr/cookiecutter
	```
- [PyPi](https://pypi.org/project/cookiecutter) (📥 2M / month):
	```
	pip install cookiecutter
	```
- [Conda](https://anaconda.org/conda-forge/cookiecutter) (📥 410K · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge cookiecutter
	```
</details>
<details><summary><b><a href="https://github.com/nvbn/thefuck">thefuck</a></b> (🥈29 ·  ⭐ 73K) - Correcting your previous console command. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nvbn/thefuck) (👨‍💻 190 · 🔀 3.1K · 📦 370 · 📋 650 - 30% open · ⏱️ 07.09.2022):

	```
	git clone https://github.com/nvbn/thefuck
	```
- [PyPi](https://pypi.org/project/thefuck) (📥 7.3K / month):
	```
	pip install thefuck
	```
- [Conda](https://anaconda.org/conda-forge/thefuck):
	```
	conda install -c conda-forge thefuck
	```
</details>
<details><summary><b><a href="https://github.com/tmux-python/tmuxp">tmuxp</a></b> (🥈27 ·  ⭐ 3.5K) - A [tmux](https://github.com/tmux/tmux) session manager. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tmux-python/tmuxp) (👨‍💻 68 · 🔀 210 · 📦 200 · 📋 320 - 22% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/tony/tmuxp
	```
- [PyPi](https://pypi.org/project/tmuxp) (📥 5.8K / month):
	```
	pip install tmuxp
	```
- [Conda](https://anaconda.org/conda-forge/tmuxp):
	```
	conda install -c conda-forge tmuxp
	```
</details>
<details><summary><b><a href="https://github.com/dbcli/pgcli">pgcli</a></b> (🥈25 ·  ⭐ 11K) - PostgreSQL CLI with autocompletion and syntax highlighting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dbcli/pgcli) (👨‍💻 160 · 🔀 470 · 📦 580 · 📋 650 - 21% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/dbcli/pgcli
	```
- [PyPi](https://pypi.org/project/pgcli) (📥 35K / month):
	```
	pip install pgcli
	```
- [Conda](https://anaconda.org/conda-forge/pgcli) (📥 120K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge pgcli
	```
</details>
<details><summary><b><a href="https://github.com/dbcli/mycli">mycli</a></b> (🥈25 ·  ⭐ 11K) - MySQL CLI with autocompletion and syntax highlighting. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dbcli/mycli) (👨‍💻 100 · 🔀 620 · 📦 240 · 📋 600 - 28% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/dbcli/mycli
	```
- [PyPi](https://pypi.org/project/mycli) (📥 32K / month):
	```
	pip install mycli
	```
- [Conda](https://anaconda.org/conda-forge/mycli) (📥 38K · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge mycli
	```
</details>
<details><summary><b><a href="https://github.com/gleitz/howdoi">howdoi</a></b> (🥈24 ·  ⭐ 9.7K) - Instant coding answers via the command line. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gleitz/howdoi) (👨‍💻 80 · 🔀 820 · 📦 430 · 📋 250 - 8% open · ⏱️ 04.07.2022):

	```
	git clone https://github.com/gleitz/howdoi
	```
- [PyPi](https://pypi.org/project/howdoi) (📥 4.9K / month):
	```
	pip install howdoi
	```
- [Conda](https://anaconda.org/conda-forge/howdoi):
	```
	conda install -c conda-forge howdoi
	```
</details>
<details><summary><b><a href="https://github.com/copier-org/copier">copier</a></b> (🥈24 ·  ⭐ 700) - A library and command-line utility for rendering projects templates. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/copier-org/copier) (👨‍💻 42 · 🔀 85 · 📦 110 · 📋 270 - 12% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/pykong/copier
	```
- [PyPi](https://pypi.org/project/copier) (📥 15K / month):
	```
	pip install copier
	```
- [Conda](https://anaconda.org/conda-forge/copier) (📥 430 · ⏱️ 06.07.2022):
	```
	conda install -c conda-forge copier
	```
</details>
<details><summary><b><a href="https://github.com/laixintao/iredis">iredis</a></b> (🥉22 ·  ⭐ 2.1K) - Redis CLI with autocompletion and syntax highlighting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/laixintao/iredis) (👨‍💻 30 · 🔀 88 · 📥 10K · 📋 200 - 24% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/laixintao/iredis
	```
- [PyPi](https://pypi.org/project/iredis) (📥 1.6K / month):
	```
	pip install iredis
	```
- [Conda](https://anaconda.org/conda-forge/iredis) (📥 210 · ⏱️ 10.08.2022):
	```
	conda install -c conda-forge iredis
	```
</details>
<details><summary><b><a href="https://github.com/facebook/PathPicker">PathPicker</a></b> (🥉20 ·  ⭐ 4.8K) - Select files out of bash output. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/PathPicker) (👨‍💻 78 · 🔀 280 · 📥 44K · 📋 170 - 8% open · ⏱️ 03.07.2022):

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
<details><summary><b><a href="https://github.com/dbcli/litecli">litecli</a></b> (🥉20 ·  ⭐ 1.7K) - SQLite CLI with autocompletion and syntax highlighting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dbcli/litecli) (👨‍💻 24 · 🔀 60 · 📦 170 · 📋 85 - 30% open · ⏱️ 11.07.2022):

	```
	git clone https://github.com/dbcli/litecli
	```
- [PyPi](https://pypi.org/project/litecli) (📥 24K / month):
	```
	pip install litecli
	```
- [Conda](https://anaconda.org/conda-forge/litecli):
	```
	conda install -c conda-forge litecli
	```
</details>
<details><summary><b><a href="https://github.com/donnemartin/saws">saws</a></b> (🥉18 ·  ⭐ 5K · 💤) - A Supercharged [aws-cli](https://github.com/aws/aws-cli). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/donnemartin/saws) (👨‍💻 8 · 🔀 270 · 📦 38 · 📋 92 - 32% open · ⏱️ 15.01.2022):

	```
	git clone https://github.com/donnemartin/saws
	```
- [PyPi](https://pypi.org/project/saws) (📥 420 / month):
	```
	pip install saws
	```
- [Conda](https://anaconda.org/conda-forge/saws) (📥 21K · ⏱️ 16.03.2020):
	```
	conda install -c conda-forge saws
	```
</details>
<details><summary><b><a href="https://github.com/mooz/percol">percol</a></b> (🥉18 ·  ⭐ 3.1K · 💀) - Adds flavor of interactive selection to the traditional pipe.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mooz/percol) (👨‍💻 36 · 🔀 140 · 📦 32 · 📋 65 - 55% open · ⏱️ 23.07.2019):

	```
	git clone https://github.com/mooz/percol
	```
- [PyPi](https://pypi.org/project/percol) (📥 2.9K / month):
	```
	pip install percol
	```
- [Conda](https://anaconda.org/conda-forge/percol):
	```
	conda install -c conda-forge percol
	```
</details>
<details><summary><b><a href="https://github.com/cloudnativelabs/kube-shell">kube-shell</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - An integrated shell for working with the Kubernetes CLI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cloudnativelabs/kube-shell) (👨‍💻 6 · 🔀 160 · 📥 610 · 📦 13 · 📋 69 - 82% open · ⏱️ 19.09.2018):

	```
	git clone https://github.com/cloudnativelabs/kube-shell
	```
- [PyPi](https://pypi.org/project/kube-shell) (📥 300 / month):
	```
	pip install kube-shell
	```
- [Conda](https://anaconda.org/conda-forge/kube-shell):
	```
	conda install -c conda-forge kube-shell
	```
</details>
<details><summary><b><a href="https://github.com/sloria/doitlive">doitlive</a></b> (🥉16 ·  ⭐ 3.2K) - A tool for live presentations in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/doitlive) (👨‍💻 18 · 🔀 94 · 📦 17 · 📋 48 - 25% open · ⏱️ 14.08.2022):

	```
	git clone https://github.com/sloria/doitlive
	```
- [PyPi](https://pypi.org/project/doitlive) (📥 190 / month):
	```
	pip install doitlive
	```
- [Conda](https://anaconda.org/conda-forge/doitlive):
	```
	conda install -c conda-forge doitlive
	```
</details>
<details><summary><b><a href="https://github.com/timofurrer/try">try</a></b> (🥉12 ·  ⭐ 650) - A dead simple CLI to try out python packages - it's never been easier. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timofurrer/try) (👨‍💻 4 · 🔀 34 · 📦 5 · 📋 12 - 25% open · ⏱️ 15.05.2022):

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

## Compatibility

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for migrating from Python 2 to 3._

🔗&nbsp;<b><a href="http://python-future.org/index.html">python-future</a></b>  - The missing compatibility layer between Python 2 and Python 3.

🔗&nbsp;<b><a href="https://pypi.org/project/six/">six</a></b>  - Python 2 and 3 compatibility utilities.

<details><summary><b><a href="https://github.com/PyCQA/modernize">modernize</a></b> (🥇17 ·  ⭐ 290 · 💀) - Modernizes Python code for eventual Python 3 migration. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/PyCQA/modernize) (👨‍💻 32 · 🔀 46 · 📋 130 - 34% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/PyCQA/modernize
	```
- [PyPi](https://pypi.org/project/modernize) (📥 45K / month):
	```
	pip install modernize
	```
- [Conda](https://anaconda.org/conda-forge/modernize) (📥 26K · ⏱️ 04.10.2020):
	```
	conda install -c conda-forge modernize
	```
</details>
<br>

## Computer Vision

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Computer Vision._

🔗&nbsp;<b><a href="https://opencv.org/">OpenCV</a></b>  - Open Source Computer Vision Library.

<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇31 ·  ⭐ 16K) - Ready-to-use OCR with 40+ languages supported. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 110 · 🔀 2.2K · 📥 2.2M · 📦 1.5K · 📋 650 - 16% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/EasyOCR) (📥 98K / month):
	```
	pip install EasyOCR
	```
- [Conda](https://anaconda.org/conda-forge/EasyOCR):
	```
	conda install -c conda-forge EasyOCR
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈26 ·  ⭐ 1.7K) - Another simple, Pillow-friendly, wrapper around the `tesseract-ocr`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 27 · 🔀 220 · 📦 700 · 📋 250 - 31% open · ⏱️ 26.08.2022):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 48K / month):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 83K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈25 ·  ⭐ 46K) - Simple facial recognition library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 54 · 🔀 12K · 📥 470 · 📋 1.2K - 53% open · ⏱️ 10.06.2022):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 41K / month):
	```
	pip install face_recognition
	```
- [Conda](https://anaconda.org/conda-forge/face_recognition) (📥 9.2K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥉24 ·  ⭐ 7.1K) - Open Source Differentiable Computer Vision Library for PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kornia/kornia) (🔀 700 · 📥 440 · 📦 1.7K · 📋 620 - 27% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/kornia/kornia/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">pytesseract</a></b> (🥉24 ·  ⭐ 4.4K) - A wrapper for [Google Tesseract.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 41 · 🔀 610 · 📋 310 - 4% open · ⏱️ 16.08.2022):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 650K / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 520K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/sightmachine/SimpleCV">SimpleCV</a></b> (🥉24 ·  ⭐ 2.6K · 💀) - An open source framework for building computer vision applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/sightmachine/SimpleCV) (👨‍💻 100 · 🔀 760 · 📦 370 · 📋 330 - 22% open · ⏱️ 07.04.2015):

	```
	git clone https://github.com/sightmachine/SimpleCV
	```
- [PyPi](https://pypi.org/project/SimpleCV) (📥 1.8K / month):
	```
	pip install SimpleCV
	```
- [Conda](https://anaconda.org/conda-forge/SimpleCV):
	```
	conda install -c conda-forge SimpleCV
	```
</details>
<br>

## Concurrency and Parallelism

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for concurrent and parallel execution._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/concurrent.futures.html">concurrent.futures</a></b>  - (Python standard library) A high-level interface for asynchronously executing..

🔗&nbsp;<b><a href="http://eventlet.net/">eventlet</a></b>  - Asynchronous framework with WSGI support.

🔗&nbsp;<b><a href="http://www.gevent.org/">gevent</a></b>  - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-..

🔗&nbsp;<b><a href="https://docs.python.org/3/library/multiprocessing.html">multiprocessing</a></b>  - (Python standard library) Process-based parallelism.

<details><summary><b><a href="https://github.com/soravux/scoop">scoop</a></b> (🥇20 ·  ⭐ 560) - Scalable Concurrent Operations in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/soravux/scoop) (👨‍💻 24 · 🔀 84 · 📦 270 · 📋 73 - 43% open · ⏱️ 14.08.2022):

	```
	git clone https://github.com/soravux/scoop
	```
- [PyPi](https://pypi.org/project/scoop) (📥 1.2K / month):
	```
	pip install scoop
	```
- [Conda](https://anaconda.org/conda-forge/scoop):
	```
	conda install -c conda-forge scoop
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for storing and parsing configuration options._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/configparser.html">configparser</a></b>  - (Python standard library) INI file parser.

🔗&nbsp;<b><a href="https://profig.readthedocs.io/en/latest/">profig</a></b>  - Config from multiple formats with value conversion.

<details><summary><b><a href="https://github.com/henriquebastos/python-decouple">python-decouple</a></b> (🥇30 ·  ⭐ 2.2K) - Strict separation of settings from code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/henriquebastos/python-decouple) (👨‍💻 32 · 🔀 160 · 📥 10 · 📦 76K · 📋 80 - 11% open · ⏱️ 11.05.2022):

	```
	git clone https://github.com/henriquebastos/python-decouple
	```
- [PyPi](https://pypi.org/project/python-decouple) (📥 1M / month):
	```
	pip install python-decouple
	```
- [Conda](https://anaconda.org/conda-forge/python-decouple) (📥 48K · ⏱️ 02.02.2022):
	```
	conda install -c conda-forge python-decouple
	```
</details>
<details><summary><b><a href="https://github.com/DiffSK/configobj">configobj</a></b> (🥉27 ·  ⭐ 280 · 💀) - INI file parser with validation. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/DiffSK/configobj) (👨‍💻 22 · 🔀 65 · 📦 21K · 📋 140 - 48% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/DiffSK/configobj
	```
- [PyPi](https://pypi.org/project/configobj) (📥 2M / month):
	```
	pip install configobj
	```
- [Conda](https://anaconda.org/conda-forge/configobj) (📥 450K · ⏱️ 29.07.2018):
	```
	conda install -c conda-forge configobj
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hydra">hydra</a></b> (🥉23 ·  ⭐ 6.3K) - Hydra is a framework for elegantly configuring complex applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hydra) (👨‍💻 100 · 🔀 460 · 📦 10 · 📋 1.1K - 13% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/facebookresearch/hydra
	```
- [PyPi](https://pypi.org/project/hydra) (📥 12K / month):
	```
	pip install hydra
	```
- [Conda](https://anaconda.org/conda-forge/hydra) (📥 12K · ⏱️ 18.01.2021):
	```
	conda install -c conda-forge hydra
	```
</details>
<br>

## Cryptography

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Cryptography._

🔗&nbsp;<b><a href="https://cryptography.io/en/latest/">cryptography</a></b>  - A package designed to expose cryptographic primitives and recipes to Python developers.

🔗&nbsp;<b><a href="https://passlib.readthedocs.io/en/stable/">passlib</a></b>  - Secure password storage/hashing library, very high level.

<details><summary><b><a href="https://github.com/paramiko/paramiko">paramiko</a></b> (🥇31 ·  ⭐ 7.9K) - The leading native Python SSHv2 protocol library. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/paramiko/paramiko) (👨‍💻 180 · 🔀 1.8K · 📦 62K · 📋 1.4K - 51% open · ⏱️ 10.06.2022):

	```
	git clone https://github.com/paramiko/paramiko
	```
- [PyPi](https://pypi.org/project/paramiko) (📥 30M / month):
	```
	pip install paramiko
	```
- [Conda](https://anaconda.org/conda-forge/paramiko) (📥 2.1M · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge paramiko
	```
</details>
<details><summary><b><a href="https://github.com/pyca/pynacl">pynacl</a></b> (🥉22 ·  ⭐ 910) - Python binding to the Networking and Cryptography (NaCl) library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pyca/pynacl) (👨‍💻 64 · 🔀 200 · 📋 290 - 13% open · ⏱️ 07.09.2022):

	```
	git clone https://github.com/pyca/pynacl
	```
- [PyPi](https://pypi.org/project/pynacl) (📥 38M / month):
	```
	pip install pynacl
	```
- [Conda](https://anaconda.org/conda-forge/pynacl) (📥 3M · ⏱️ 09.04.2022):
	```
	conda install -c conda-forge pynacl
	```
</details>
<br>

## Data Analysis

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data analyzing._

🔗&nbsp;<b><a href="https://orange.biolab.si/">Orange</a></b>  - Data mining, data visualization, analysis and machine learning through visual programming or..

🔗&nbsp;<b><a href="http://pandas.pydata.org/">Pandas</a></b>  - A library providing high-performance, easy-to-use data structures and data analysis tools.

<details><summary><b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥇28 ·  ⭐ 3.1K · 💀) - NumPy and Pandas interface to Big Data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/blaze/blaze) (👨‍💻 65 · 🔀 360 · 📦 8.4K · 📋 750 - 33% open · ⏱️ 15.08.2019):

	```
	git clone https://github.com/blaze/blaze
	```
- [PyPi](https://pypi.org/project/blaze) (📥 7.6K / month):
	```
	pip install blaze
	```
- [Conda](https://anaconda.org/conda-forge/blaze) (📥 200K · ⏱️ 15.07.2018):
	```
	conda install -c conda-forge blaze
	```
</details>
<details><summary><b><a href="https://github.com/aws/aws-sdk-pandas">AWS Data Wrangler</a></b> (🥈20 ·  ⭐ 3.1K) - Pandas on AWS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aws/aws-sdk-pandas) (👨‍💻 120 · 🔀 510 · 📥 150K · 📋 740 - 3% open · ⏱️ 15.09.2022):

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
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉19 ·  ⭐ 1.3K) - Agile Data Science Workflows made easy with PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 23 · 🔀 210 · 📋 230 - 14% open · ⏱️ 21.06.2022):

	```
	git clone https://github.com/ironmussa/Optimus
	```
- [PyPi](https://pypi.org/project/Optimus) (📥 11K / month):
	```
	pip install Optimus
	```
- [Conda](https://anaconda.org/conda-forge/Optimus):
	```
	conda install -c conda-forge Optimus
	```
</details>
<details><summary><b><a href="https://github.com/mining/mining">Open Mining</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - Business Intelligence (BI) in Pandas interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mining/mining) (👨‍💻 14 · 🔀 230 · 📦 13 · 📋 180 - 36% open · ⏱️ 02.12.2016):

	```
	git clone https://github.com/mining/mining
	```
- [PyPi](https://pypi.org/project/mining) (📥 18 / month):
	```
	pip install mining
	```
- [Conda](https://anaconda.org/conda-forge/mining):
	```
	conda install -c conda-forge mining
	```
</details>
<br>

## Data Validation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for validating data. Used for forms in many cases._

🔗&nbsp;<b><a href="https://docs.pylonsproject.org/projects/colander/en/latest/">colander</a></b>  - Validating and deserializing data obtained via XML, JSON, an HTML form post.

<details><summary><b><a href="https://github.com/python-jsonschema/jsonschema">jsonschema</a></b> (🥇33 ·  ⭐ 3.8K) - An implementation of [JSON Schema](http://json-schema.org/) for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-jsonschema/jsonschema) (👨‍💻 100 · 🔀 510 · 📦 240K · 📋 680 - 6% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/Julian/jsonschema
	```
- [PyPi](https://pypi.org/project/jsonschema) (📥 44M / month):
	```
	pip install jsonschema
	```
- [Conda](https://anaconda.org/conda-forge/jsonschema) (📥 13M · ⏱️ 09.09.2022):
	```
	conda install -c conda-forge jsonschema
	```
</details>
<details><summary><b><a href="https://github.com/alecthomas/voluptuous">voluptuous</a></b> (🥈31 ·  ⭐ 1.7K) - A Python data validation library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alecthomas/voluptuous) (👨‍💻 88 · 🔀 200 · 📦 5.5K · 📋 240 - 16% open · ⏱️ 13.07.2022):

	```
	git clone https://github.com/alecthomas/voluptuous
	```
- [PyPi](https://pypi.org/project/voluptuous) (📥 1.4M / month):
	```
	pip install voluptuous
	```
- [Conda](https://anaconda.org/conda-forge/voluptuous) (📥 200K · ⏱️ 07.04.2022):
	```
	conda install -c conda-forge voluptuous
	```
</details>
<details><summary><b><a href="https://github.com/pyeve/cerberus">Cerberus</a></b> (🥈30 ·  ⭐ 2.8K · 💀) - A lightweight and extensible data validation library. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/pyeve/cerberus) (👨‍💻 62 · 🔀 220 · 📦 12K · 📋 330 - 11% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/pyeve/cerberus
	```
- [PyPi](https://pypi.org/project/cerberus) (📥 3.4M / month):
	```
	pip install cerberus
	```
- [Conda](https://anaconda.org/conda-forge/cerberus) (📥 240K · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge cerberus
	```
</details>
<details><summary><b><a href="https://github.com/keleshev/schema">schema</a></b> (🥉29 ·  ⭐ 2.6K · 💤) - A library for validating Python data structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/keleshev/schema) (👨‍💻 62 · 🔀 180 · 📦 4.4K · 📋 140 - 51% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/keleshev/schema
	```
- [PyPi](https://pypi.org/project/schema) (📥 2.7M / month):
	```
	pip install schema
	```
- [Conda](https://anaconda.org/conda-forge/schema) (📥 61K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge schema
	```
</details>
<details><summary><b><a href="https://github.com/schematics/schematics">Schematics</a></b> (🥉25 ·  ⭐ 2.5K · 💀) - Data Structure Validation. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/schematics/schematics) (👨‍💻 120 · 🔀 270 · 📦 1.3K · 📋 330 - 27% open · ⏱️ 17.08.2021):

	```
	git clone https://github.com/schematics/schematics
	```
- [PyPi](https://pypi.org/project/schematics) (📥 160K / month):
	```
	pip install schematics
	```
- [Conda](https://anaconda.org/conda-forge/schematics) (📥 24K · ⏱️ 17.07.2019):
	```
	conda install -c conda-forge schematics
	```
</details>
<details><summary><b><a href="https://github.com/podio/valideer">valideer</a></b> (🥉18 ·  ⭐ 260 · 💀) - Lightweight extensible data validation and adaptation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/podio/valideer) (👨‍💻 7 · 🔀 23 · 📦 61 · 📋 15 - 26% open · ⏱️ 07.03.2018):

	```
	git clone https://github.com/podio/valideer
	```
- [PyPi](https://pypi.org/project/valideer) (📥 12K / month):
	```
	pip install valideer
	```
- [Conda](https://anaconda.org/conda-forge/valideer) (📥 19K · ⏱️ 06.07.2018):
	```
	conda install -c conda-forge valideer
	```
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for visualizing data._

🔗&nbsp;<b><a href="https://plot.ly/products/dash/">Dash</a></b>  - Built on top of Flask, React and Plotly aimed at analytical web applications.

🔗&nbsp;<b><a href="https://github.com/ucg8j/awesome-dash">awesome-dash</a></b> ( ⭐ 1.6K)  - A curated list of awesome Dash (plotly) resources.

🔗&nbsp;<b><a href="http://matplotlib.org/">Matplotlib</a></b>  - A Python 2D plotting library.

🔗&nbsp;<b><a href="http://www.pygal.org/en/latest/">Pygal</a></b>  - A Python SVG Charts Creator.

🔗&nbsp;<b><a href="https://pypi.org/project/pygraphviz/">PyGraphviz</a></b>  - Python interface to [Graphviz](http://www.graphviz.org/).

🔗&nbsp;<b><a href="http://www.pyqtgraph.org/">PyQtGraph</a></b>  - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.

<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇33 ·  ⭐ 7.7K) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 140 · 🔀 660 · 📦 33K · 📋 1.6K - 13% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 7.9M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 1.4M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥈30 ·  ⭐ 9.8K) - Statistical data visualization using Matplotlib. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 170 · 🔀 1.6K · 📥 230 · 📋 2.1K - 4% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 8.8M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 4.7M · ⏱️ 06.09.2022):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥈28 ·  ⭐ 17K) - Interactive Web Plotting for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 610 · 🔀 3.9K · 📦 150 · 📋 7K - 9% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 4.1M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 8.5M · ⏱️ 15.08.2022):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥉27 ·  ⭐ 3.3K) - Interactive Plotting Library for the Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 59 · 🔀 440 · 📦 35 · 📋 570 - 36% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/bloomberg/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 89K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1M · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge bqplot
	```
</details>
<details><summary><b><a href="https://github.com/mingrammer/diagrams">diagrams</a></b> (🥉26 ·  ⭐ 26K) - Diagram as Code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mingrammer/diagrams) (👨‍💻 110 · 🔀 1.5K · 📋 390 - 60% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/mingrammer/diagrams
	```
- [PyPi](https://pypi.org/project/diagrams) (📥 85K / month):
	```
	pip install diagrams
	```
- [Conda](https://anaconda.org/conda-forge/diagrams) (📥 130K · ⏱️ 23.01.2022):
	```
	conda install -c conda-forge diagrams
	```
</details>
<details><summary><b><a href="https://github.com/SciTools/cartopy">Cartopy</a></b> (🥉26 ·  ⭐ 1.1K) - A cartographic python library with matplotlib support. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/SciTools/cartopy) (👨‍💻 120 · 🔀 330 · 📦 2.6K · 📋 1.1K - 25% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/SciTools/cartopy
	```
- [PyPi](https://pypi.org/project/cartopy) (📥 130K / month):
	```
	pip install cartopy
	```
- [Conda](https://anaconda.org/conda-forge/cartopy) (📥 2.3M · ⏱️ 10.09.2022):
	```
	conda install -c conda-forge cartopy
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥉25 ·  ⭐ 2.9K) - High-performance scientific visualization based on OpenGL. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 180 · 🔀 580 · 📦 850 · 📋 1.3K - 20% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy) (📥 73K / month):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 280K · ⏱️ 05.07.2022):
	```
	conda install -c conda-forge vispy
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥉21 ·  ⭐ 3.2K) - A grammar of graphics for Python based on ggplot2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 96 · 🔀 170 · 📋 510 - 12% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 320K / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 200K · ⏱️ 02.07.2022):
	```
	conda install -c conda-forge plotnine
	```
</details>
<br>

## Database

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Databases implemented in Python._

<details><summary><b><a href="https://github.com/msiemens/tinydb">tinydb</a></b> (🥇24 ·  ⭐ 5.3K) - A tiny, document-oriented database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/msiemens/tinydb) (👨‍💻 78 · 🔀 460 · 📋 280 - 3% open · ⏱️ 23.07.2022):

	```
	git clone https://github.com/msiemens/tinydb
	```
- [PyPi](https://pypi.org/project/tinydb) (📥 450K / month):
	```
	pip install tinydb
	```
- [Conda](https://anaconda.org/conda-forge/tinydb) (📥 200K · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge tinydb
	```
</details>
<details><summary><b><a href="https://github.com/zopefoundation/ZODB">ZODB</a></b> (🥇24 ·  ⭐ 550) - A native object database for Python. A key-value and object graph.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/zopefoundation/ZODB) (👨‍💻 120 · 🔀 74 · 📦 880 · 📋 150 - 37% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/zopefoundation/ZODB
	```
- [PyPi](https://pypi.org/project/ZODB) (📥 68K / month):
	```
	pip install ZODB
	```
- [Conda](https://anaconda.org/conda-forge/ZODB) (📥 50K · ⏱️ 17.03.2022):
	```
	conda install -c conda-forge ZODB
	```
</details>
<details><summary><b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉20 ·  ⭐ 700 · 💀) - A simple and lightweight key-value store for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/patx/pickledb) (👨‍💻 12 · 🔀 110 · 📦 960 · 📋 57 - 28% open · ⏱️ 15.11.2019):

	```
	git clone https://github.com/patx/pickledb
	```
- [PyPi](https://pypi.org/project/pickledb) (📥 45K / month):
	```
	pip install pickledb
	```
- [Conda](https://anaconda.org/conda-forge/pickledb) (📥 3K · ⏱️ 17.04.2019):
	```
	conda install -c conda-forge pickledb
	```
</details>
<br>

## Database Drivers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting and operating databases._

🔗&nbsp;<b><a href="https://github.com/dhamaniasad/awesome-postgres">awesome-postgres</a></b> ( ⭐ 8K)  - A curated list of awesome PostgreSQL software, libraries, tools and..

🔗&nbsp;<b><a href="http://initd.org/psycopg/">psycopg2</a></b>  - The most popular PostgreSQL adapter for Python.

🔗&nbsp;<b><a href="https://github.com/planetopendata/awesome-sqlite">awesome-sqlite</a></b> ( ⭐ 190)  - A collection of awesome sqlite tools, scripts, books, etc.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/sqlite3.html">sqlite3</a></b>  - (Python standard library) SQlite interface compliant with DB-API 2.0.

🔗&nbsp;<b><a href="https://pymssql.readthedocs.io/en/latest/">pymssql</a></b>  - A simple database interface to Microsoft SQL Server.

🔗&nbsp;<b><a href="https://py2neo.org/">py2neo</a></b>  - A client library and toolkit for working with Neo4j.

<details><summary><b><a href="https://github.com/redis/redis-py">redis-py</a></b> (🥇35 ·  ⭐ 11K) - The Python client for Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/redis/redis-py) (👨‍💻 350 · 🔀 2.1K · 📦 160K · 📋 1.3K - 9% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/andymccurdy/redis-py
	```
- [PyPi](https://pypi.org/project/redis-py):
	```
	pip install redis-py
	```
- [Conda](https://anaconda.org/conda-forge/redis-py) (📥 780K · ⏱️ 27.06.2022):
	```
	conda install -c conda-forge redis-py
	```
</details>
<details><summary><b><a href="https://github.com/dpkp/kafka-python">kafka-python</a></b> (🥇34 ·  ⭐ 5K) - The Python client for Apache Kafka. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dpkp/kafka-python) (👨‍💻 210 · 🔀 1.2K · 📥 1.8K · 📦 12K · 📋 1.4K - 15% open · ⏱️ 27.03.2022):

	```
	git clone https://github.com/dpkp/kafka-python
	```
- [PyPi](https://pypi.org/project/kafka-python) (📥 8M / month):
	```
	pip install kafka-python
	```
- [Conda](https://anaconda.org/conda-forge/kafka-python) (📥 330K · ⏱️ 30.09.2020):
	```
	conda install -c conda-forge kafka-python
	```
</details>
<details><summary><b><a href="https://github.com/mongodb/motor">motor</a></b> (🥇34 ·  ⭐ 2K) - The async Python driver for MongoDB. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mongodb/motor) (👨‍💻 41 · 🔀 180 · 📦 36K · ⏱️ 13.09.2022):

	```
	git clone https://github.com/mongodb/motor
	```
- [PyPi](https://pypi.org/project/motor) (📥 4.7M / month):
	```
	pip install motor
	```
- [Conda](https://anaconda.org/conda-forge/motor) (📥 48K · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge motor
	```
</details>
<details><summary><b><a href="https://github.com/PyMySQL/PyMySQL">PyMySQL</a></b> (🥈32 ·  ⭐ 7K) - A pure Python MySQL driver compatible to mysql-python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyMySQL/PyMySQL) (👨‍💻 120 · 🔀 1.3K · 📦 130K · 📋 610 - 4% open · ⏱️ 24.08.2022):

	```
	git clone https://github.com/PyMySQL/PyMySQL
	```
- [PyPi](https://pypi.org/project/PyMySQL) (📥 32M / month):
	```
	pip install PyMySQL
	```
- [Conda](https://anaconda.org/conda-forge/PyMySQL) (📥 780K · ⏱️ 09.01.2021):
	```
	conda install -c conda-forge PyMySQL
	```
</details>
<details><summary><b><a href="https://github.com/datastax/python-driver">cassandra-driver</a></b> (🥈24 ·  ⭐ 1.3K) - The Python Driver for Apache Cassandra. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/datastax/python-driver) (👨‍💻 180 · 🔀 440 · 📦 4.2K · ⏱️ 03.09.2022):

	```
	git clone https://github.com/datastax/python-driver
	```
- [PyPi](https://pypi.org/project/python-driver) (📥 15 / month):
	```
	pip install python-driver
	```
- [Conda](https://anaconda.org/conda-forge/python-driver):
	```
	conda install -c conda-forge python-driver
	```
</details>
<details><summary><b><a href="https://github.com/mymarilyn/clickhouse-driver">clickhouse-driver</a></b> (🥈24 ·  ⭐ 910) - Python driver with native interface for ClickHouse. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mymarilyn/clickhouse-driver) (👨‍💻 45 · 🔀 170 · 📦 730 · 📋 250 - 13% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/mymarilyn/clickhouse-driver
	```
- [PyPi](https://pypi.org/project/clickhouse-driver) (📥 1.4M / month):
	```
	pip install clickhouse-driver
	```
- [Conda](https://anaconda.org/conda-forge/clickhouse-driver) (📥 330K · ⏱️ 13.06.2022):
	```
	conda install -c conda-forge clickhouse-driver
	```
</details>
<details><summary><b><a href="https://github.com/python-happybase/happybase">happybase</a></b> (🥉22 ·  ⭐ 590) - A developer-friendly library for Apache HBase. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-happybase/happybase) (👨‍💻 19 · 🔀 150 · 📦 660 · 📋 200 - 10% open · ⏱️ 12.07.2022):

	```
	git clone https://github.com/wbolster/happybase
	```
- [PyPi](https://pypi.org/project/happybase) (📥 110K / month):
	```
	pip install happybase
	```
- [Conda](https://anaconda.org/conda-forge/happybase) (📥 100K · ⏱️ 01.07.2019):
	```
	conda install -c conda-forge happybase
	```
</details>
<details><summary><b><a href="https://github.com/mongodb/mongo-python-driver">pymongo</a></b> (🥉21 ·  ⭐ 3.7K) - The official Python client for MongoDB. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mongodb/mongo-python-driver) (👨‍💻 190 · 🔀 970 · ⏱️ 13.09.2022):

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
<details><summary><b><a href="https://github.com/gmr/queries">queries</a></b> (🥉19 ·  ⭐ 250 · 💤) - A wrapper of the psycopg2 library for interacting with PostgreSQL. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gmr/queries) (👨‍💻 11 · 🔀 30 · 📦 110 · 📋 18 - 22% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/gmr/queries
	```
- [PyPi](https://pypi.org/project/queries) (📥 3.2K / month):
	```
	pip install queries
	```
- [Conda](https://anaconda.org/conda-forge/queries):
	```
	conda install -c conda-forge queries
	```
</details>
<details><summary><b><a href="https://github.com/PyMySQL/mysqlclient">mysqlclient</a></b> (🥉17 ·  ⭐ 2.1K) - MySQL connector with Python 3 support ([mysql-.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyMySQL/mysqlclient) (👨‍💻 70 · 🔀 340 · 📥 5.2K · 📋 290 - 5% open · ⏱️ 05.08.2022):

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
<details><summary><b><a href="https://github.com/plasticityai/supersqlite">SuperSQLite</a></b> (🥉17 ·  ⭐ 700 · 💀) - A supercharged SQLite library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plasticityai/supersqlite) (👨‍💻 2 · 🔀 24 · 📦 10 · 📋 7 - 85% open · ⏱️ 27.08.2019):

	```
	git clone https://github.com/plasticityai/supersqlite
	```
- [PyPi](https://pypi.org/project/supersqlite) (📥 480 / month):
	```
	pip install supersqlite
	```
- [Conda](https://anaconda.org/conda-forge/supersqlite):
	```
	conda install -c conda-forge supersqlite
	```
</details>
<br>

## Date and Time

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with dates and times._

🔗&nbsp;<b><a href="https://arrow.readthedocs.io/en/latest/">Arrow</a></b>  - A Python library that offers a sensible and human-friendly approach to creating, manipulating,..

🔗&nbsp;<b><a href="https://launchpad.net/pytz">pytz</a></b>  - World timezone definitions, modern and historical. Brings the [tz..

<details><summary><b><a href="https://github.com/dateutil/dateutil">dateutil</a></b> (🥇28 ·  ⭐ 1.9K) - Extensions to the standard Python.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dateutil/dateutil) (👨‍💻 130 · 🔀 410 · 📥 35K · 📦 790K · 📋 630 - 39% open · ⏱️ 18.04.2022):

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
<details><summary><b><a href="https://github.com/timofurrer/maya">maya</a></b> (🥈27 ·  ⭐ 3.4K) - Datetimes for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timofurrer/maya) (👨‍💻 47 · 🔀 190 · 📦 970 · 📋 90 - 17% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/timofurrer/maya
	```
- [PyPi](https://pypi.org/project/maya) (📥 39K / month):
	```
	pip install maya
	```
- [Conda](https://anaconda.org/conda-forge/maya) (📥 49K · ⏱️ 14.09.2022):
	```
	conda install -c conda-forge maya
	```
</details>
<details><summary><b><a href="https://github.com/sdispater/pendulum">Pendulum</a></b> (🥈25 ·  ⭐ 5K) - Python datetimes made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdispater/pendulum) (👨‍💻 87 · 🔀 290 · 📋 440 - 41% open · ⏱️ 24.08.2022):

	```
	git clone https://github.com/sdispater/pendulum
	```
- [PyPi](https://pypi.org/project/pendulum) (📥 9.6M / month):
	```
	pip install pendulum
	```
- [Conda](https://anaconda.org/conda-forge/pendulum) (📥 560K · ⏱️ 06.04.2022):
	```
	conda install -c conda-forge pendulum
	```
</details>
<details><summary><b><a href="https://github.com/myusuf3/delorean">delorean</a></b> (🥉20 ·  ⭐ 1.8K) - A library for clearing up the inconvenient truths that arise dealing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myusuf3/delorean) (🔀 130 · 📦 810 · 📋 63 - 41% open · ⏱️ 28.06.2022):

	```
	git clone https://github.com/myusuf3/delorean/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/zachwill/moment">moment</a></b> (🥉20 ·  ⭐ 710 · 💀) - A Python library for dealing with dates/times. Inspired by.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/zachwill/moment) (👨‍💻 4 · 🔀 40 · 📦 710 · 📋 40 - 15% open · ⏱️ 27.11.2020):

	```
	git clone https://github.com/zachwill/moment
	```
- [PyPi](https://pypi.org/project/moment) (📥 61K / month):
	```
	pip install moment
	```
- [Conda](https://anaconda.org/conda-forge/moment) (📥 9.5K · ⏱️ 31.01.2019):
	```
	conda install -c conda-forge moment
	```
</details>
<details><summary><b><a href="https://github.com/KoffeinFlummi/Chronyk">Chronyk</a></b> (🥉16 ·  ⭐ 340 · 💀) - A Python 3 library for parsing human-written times and dates. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KoffeinFlummi/Chronyk) (👨‍💻 3 · 🔀 16 · 📦 21 · 📋 10 - 50% open · ⏱️ 02.08.2015):

	```
	git clone https://github.com/KoffeinFlummi/Chronyk
	```
- [PyPi](https://pypi.org/project/Chronyk) (📥 680 / month):
	```
	pip install Chronyk
	```
- [Conda](https://anaconda.org/conda-forge/Chronyk):
	```
	conda install -c conda-forge Chronyk
	```
</details>
<details><summary><b><a href="https://github.com/shinux/PyTime">PyTime</a></b> (🥉15 ·  ⭐ 150 · 💀) - An easy-to-use Python module which aims to operate date/time/datetime.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shinux/PyTime) (👨‍💻 5 · 🔀 17 · 📦 28 · ⏱️ 31.08.2021):

	```
	git clone https://github.com/shinux/PyTime
	```
- [PyPi](https://pypi.org/project/PyTime) (📥 15K / month):
	```
	pip install PyTime
	```
- [Conda](https://anaconda.org/conda-forge/PyTime):
	```
	conda install -c conda-forge PyTime
	```
</details>
<details><summary><b><a href="https://github.com/dirn/When.py">when.py</a></b> (🥉12 ·  ⭐ 190 · 💀) - Providing user-friendly functions to help perform common date and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dirn/When.py) (👨‍💻 5 · 🔀 18 · 📦 24 · ⏱️ 14.10.2017):

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

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for debugging code._

<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥇30 ·  ⭐ 9K) - A sampling profiler for Python programs. Written in Rust. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 30 · 🔀 310 · 📥 10K · 📦 300 · 📋 260 - 31% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 870K / month):
	```
	pip install py-spy
	```
- [Conda](https://anaconda.org/conda-forge/py-spy) (📥 330K · ⏱️ 09.09.2022):
	```
	conda install -c conda-forge py-spy
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-debug-toolbar">django-debug-toolbar</a></b> (🥇30 ·  ⭐ 7.2K) - Display various debug information for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-debug-toolbar) (👨‍💻 260 · 🔀 850 · 📥 180 · 📦 55K · 📋 800 - 9% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 1.6M / month):
	```
	pip install django-debug-toolbar
	```
- [Conda](https://anaconda.org/conda-forge/django-debug-toolbar) (📥 140K · ⏱️ 18.08.2022):
	```
	conda install -c conda-forge django-debug-toolbar
	```
</details>
<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥈29 ·  ⭐ 1.6K · 💤) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 49 · 🔀 130 · 📦 34K · 📋 180 - 34% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb) (📥 2.5M / month):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 290K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/flask-debugtoolbar/flask-debugtoolbar">flask-debugtoolbar</a></b> (🥈28 ·  ⭐ 840) - A port of the django-debug-toolbar to flask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/flask-debugtoolbar/flask-debugtoolbar) (👨‍💻 42 · 🔀 120 · 📦 19K · 📋 100 - 33% open · ⏱️ 18.08.2022):

	```
	git clone https://github.com/mgood/flask-debugtoolbar
	```
- [PyPi](https://pypi.org/project/flask-debugtoolbar) (📥 140K / month):
	```
	pip install flask-debugtoolbar
	```
- [Conda](https://anaconda.org/conda-forge/flask-debugtoolbar) (📥 55K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge flask-debugtoolbar
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥈27 ·  ⭐ 1.5K) - Parsing and analyzing ELF files and DWARF debugging.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 84 · 🔀 430 · 📦 3.9K · 📋 200 - 30% open · ⏱️ 22.08.2022):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📥 1.6M / month):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 100K · ⏱️ 12.08.2022):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥈25 ·  ⭐ 2.5K) - A full-screen, console-based Python debugger. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 89 · 🔀 200 · 📦 3.4K · 📋 300 - 45% open · ⏱️ 05.09.2022):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb) (📥 400K / month):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 150K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥈22 ·  ⭐ 6.2K) - Inspect variables, expressions, and program execution with a single,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 19 · 🔀 120 · 📋 93 - 26% open · ⏱️ 01.09.2022):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 170K / month):
	```
	pip install icecream
	```
- [Conda](https://anaconda.org/conda-forge/icecream) (📥 7.3K · ⏱️ 21.07.2022):
	```
	conda install -c conda-forge icecream
	```
</details>
<details><summary><b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥈22 ·  ⭐ 3.9K) - Visual Python profiler. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nvdv/vprof) (👨‍💻 17 · 🔀 150 · 📦 97 · 📋 82 - 31% open · ⏱️ 15.07.2022):

	```
	git clone https://github.com/nvdv/vprof
	```
- [PyPi](https://pypi.org/project/vprof) (📥 5.2K / month):
	```
	pip install vprof
	```
- [Conda](https://anaconda.org/conda-forge/vprof):
	```
	conda install -c conda-forge vprof
	```
</details>
<details><summary><b><a href="https://github.com/dcramer/django-devserver">django-devserver</a></b> (🥉21 ·  ⭐ 1.3K · 💀) - A drop-in replacement for Django's runserver. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dcramer/django-devserver) (👨‍💻 39 · 🔀 140 · 📦 360 · 📋 67 - 58% open · ⏱️ 05.03.2016):

	```
	git clone https://github.com/dcramer/django-devserver
	```
- [PyPi](https://pypi.org/project/django-devserver) (📥 3.5K / month):
	```
	pip install django-devserver
	```
- [Conda](https://anaconda.org/conda-forge/django-devserver):
	```
	conda install -c conda-forge django-devserver
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdb++</a></b> (🥉21 ·  ⭐ 980) - Another drop-in replacement for pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 41 · 🔀 52 · 📦 3.1K · 📋 190 - 37% open · ⏱️ 14.07.2022):

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
<details><summary><b><a href="https://github.com/Kozea/wdb">wdb</a></b> (🥉19 ·  ⭐ 1.6K · 💀) - An improbable web debugger through WebSockets. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Kozea/wdb) (👨‍💻 22 · 🔀 110 · 📦 120 · 📋 110 - 26% open · ⏱️ 16.09.2019):

	```
	git clone https://github.com/Kozea/wdb
	```
- [PyPi](https://pypi.org/project/wdb) (📥 7.8K / month):
	```
	pip install wdb
	```
- [Conda](https://anaconda.org/conda-forge/wdb):
	```
	conda install -c conda-forge wdb
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉19 ·  ⭐ 690 · 📈) - A flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 9 · 🔀 39 · 📦 99 · 📋 87 - 42% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/python-hunter) (📥 13 / month):
	```
	pip install python-hunter
	```
- [Conda](https://anaconda.org/conda-forge/python-hunter):
	```
	conda install -c conda-forge python-hunter
	```
</details>
<details><summary><b><a href="https://github.com/rkern/line_profiler">line_profiler</a></b> (🥉17 ·  ⭐ 3.6K · 💀) - Line-by-line profiling. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rkern/line_profiler) (👨‍💻 14 · 🔀 250 · 📋 140 - 36% open · ⏱️ 23.04.2019):

	```
	git clone https://github.com/rkern/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 200K / month):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 270K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/uber-archive/pyflame">pyflame</a></b> (🥉17 ·  ⭐ 2.9K · 💀) - A ptracing profiler For Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber-archive/pyflame) (👨‍💻 22 · 🔀 220 · 📋 77 - 31% open · ⏱️ 03.12.2019):

	```
	git clone https://github.com/uber/pyflame
	```
- [PyPi](https://pypi.org/project/pyflame) (📥 140 / month):
	```
	pip install pyflame
	```
- [Conda](https://anaconda.org/conda-forge/pyflame) (📥 18K · ⏱️ 25.06.2021):
	```
	conda install -c conda-forge pyflame
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">manhole</a></b> (🥉16 ·  ⭐ 330 · 💤) - Debugging UNIX socket connections and present the stacktraces for.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 11 · 🔀 19 · 📦 110 · 📋 21 - 28% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/python-manhole) (📥 3 / month):
	```
	pip install python-manhole
	```
- [Conda](https://anaconda.org/conda-forge/python-manhole):
	```
	conda install -c conda-forge python-manhole
	```
</details>
<details><summary><b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉16 ·  ⭐ 78 · 💀) - Monitor Memory usage of Python code. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fabianp/memory_profiler) (👨‍💻 61 · 🔀 13 · ⏱️ 28.06.2018):

	```
	git clone https://github.com/fabianp/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 580K / month):
	```
	pip install memory_profiler
	```
- [Conda](https://anaconda.org/conda-forge/memory_profiler) (📥 210K · ⏱️ 19.12.2021):
	```
	conda install -c conda-forge memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/google/pyringe">pyringe</a></b> (🥉12 ·  ⭐ 1.6K · 💀) - Debugger capable of attaching to and injecting code into.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/google/pyringe) (🔀 74 · 📦 4 · 📋 24 - 62% open · ⏱️ 10.05.2014):

	```
	git clone https://github.com/google/pyringe
	```
- [PyPi](https://pypi.org/project/pyringe) (📥 52 / month):
	```
	pip install pyringe
	```
- [Conda](https://anaconda.org/conda-forge/pyringe):
	```
	conda install -c conda-forge pyringe
	```
</details>
<details><summary><b><a href="https://github.com/khamidou/lptrace">lptrace</a></b> (🥉12 ·  ⭐ 680 · 💀) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/khamidou/lptrace) (🔀 37 · 📦 3 · 📋 12 - 41% open · ⏱️ 24.02.2017):

	```
	git clone https://github.com/khamidou/lptrace
	```
- [PyPi](https://pypi.org/project/lptrace) (📥 1K / month):
	```
	pip install lptrace
	```
- [Conda](https://anaconda.org/conda-forge/lptrace):
	```
	conda install -c conda-forge lptrace
	```
</details>
<br>

## Deep Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Frameworks for Neural Networks and Deep Learning._

<details><summary><b><a href="https://github.com/keras-team/keras">keras</a></b> (🥇32 ·  ⭐ 56K) - A high-level neural networks library and capable of running on top of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1.1K · 🔀 18K · 📋 11K - 2% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 8.9M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 2.5M · ⏱️ 04.09.2022):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈30 ·  ⭐ 9.6K · 💤) - A library for fast numerical computation. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.4K · 📦 13K · 📋 2.7K - 21% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/Theano) (📥 310K / month):
	```
	pip install Theano
	```
- [Conda](https://anaconda.org/conda-forge/Theano) (📥 2.1M · ⏱️ 16.03.2022):
	```
	conda install -c conda-forge Theano
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">pytorch</a></b> (🥈29 ·  ⭐ 59K) - Tensors and Dynamic neural networks in Python with strong GPU.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 3.5K · 🔀 16K · 📥 6.4K · 📋 28K - 32% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/pytorch) (📥 48K / month):
	```
	pip install pytorch
	```
- [Conda](https://anaconda.org/conda-forge/pytorch) (📥 730K · ⏱️ 10.08.2022):
	```
	conda install -c conda-forge pytorch
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">mxnet</a></b> (🥈29 ·  ⭐ 20K) - A deep learning framework designed for both efficiency and flexibility. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 980 · 🔀 6.5K · 📥 25K · 📋 9.5K - 18% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/dmlc/mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 420K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/conda-forge/mxnet):
	```
	conda install -c conda-forge mxnet
	```
</details>
<details><summary><b><a href="https://github.com/BVLC/caffe">caffe</a></b> (🥉22 ·  ⭐ 33K · 💀) - A fast open framework for deep learning.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/BVLC/caffe) (👨‍💻 310 · 🔀 14K · 📋 4.8K - 18% open · ⏱️ 13.02.2020):

	```
	git clone https://github.com/BVLC/caffe
	```
- [PyPi](https://pypi.org/project/caffe):
	```
	pip install caffe
	```
- [Conda](https://anaconda.org/conda-forge/caffe) (📥 97K · ⏱️ 27.06.2020):
	```
	conda install -c conda-forge caffe
	```
</details>
<details><summary><b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉14 ·  ⭐ 6.3K · 💀) - Game agent framework. Use any video game as a deep learning sandbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SerpentAI/SerpentAI) (👨‍💻 7 · 🔀 730 · 📥 210 · ⏱️ 22.05.2020):

	```
	git clone https://github.com/SerpentAI/SerpentAI
	```
- [PyPi](https://pypi.org/project/SerpentAI) (📥 69 / month):
	```
	pip install SerpentAI
	```
- [Conda](https://anaconda.org/conda-forge/SerpentAI):
	```
	conda install -c conda-forge SerpentAI
	```
</details>
<br>

## DevOps Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Software and libraries for DevOps._

🔗&nbsp;<b><a href="https://cloudinit.readthedocs.io/en/latest/">cloudinit</a></b>  - A multi-distribution package that handles early initialization of a cloud instance.

🔗&nbsp;<b><a href="https://www.openstack.org/">OpenStack</a></b>  - Open source software for building private and public clouds.

🔗&nbsp;<b><a href="https://www.borgbackup.org/">BorgBackup</a></b>  - A deduplicating archiver with compression and encryption.

🔗&nbsp;<b><a href="https://docs.docker.com/compose/">docker-compose</a></b>  - Fast, isolated development environments using [Docker](https://www.docker.com/).

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇37 ·  ⭐ 8.7K) - A cross-platform process and system utilities module. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 180 · 🔀 1.2K · 📦 200K · 📋 1.6K - 13% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 60M / month):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 15M · ⏱️ 05.09.2022):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible">ansible</a></b> (🥈33 ·  ⭐ 54K) - A radically simple IT automation platform. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ansible/ansible) (👨‍💻 6.6K · 🔀 21K · 📦 23K · 📋 31K - 2% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/ansible/ansible
	```
- [PyPi](https://pypi.org/project/ansible) (📥 4.9M / month):
	```
	pip install ansible
	```
- [Conda](https://anaconda.org/conda-forge/ansible) (📥 710K · ⏱️ 15.09.2022):
	```
	conda install -c conda-forge ansible
	```
</details>
<details><summary><b><a href="https://github.com/saltstack/salt">saltstack</a></b> (🥈30 ·  ⭐ 13K) - Infrastructure automation and management system. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/saltstack/salt) (👨‍💻 3.8K · 🔀 5.1K · 📥 16K · 📋 25K - 9% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/saltstack/salt
	```
- [PyPi](https://pypi.org/project/salt) (📥 71K / month):
	```
	pip install salt
	```
- [Conda](https://anaconda.org/conda-forge/salt) (📥 26K · ⏱️ 26.02.2019):
	```
	conda install -c conda-forge salt
	```
</details>
<details><summary><b><a href="https://github.com/Supervisor/supervisor">supervisor</a></b> (🥈30 ·  ⭐ 7.5K) - Supervisor process control system for UNIX. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Supervisor/supervisor) (👨‍💻 170 · 🔀 1.1K · 📦 7.6K · 📋 1.1K - 10% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/Supervisor/supervisor
	```
- [PyPi](https://pypi.org/project/supervisor) (📥 1.5M / month):
	```
	pip install supervisor
	```
- [Conda](https://anaconda.org/conda-forge/supervisor) (📥 210K · ⏱️ 12.04.2022):
	```
	conda install -c conda-forge supervisor
	```
</details>
<details><summary><b><a href="https://github.com/nickstenning/honcho">honcho</a></b> (🥉25 ·  ⭐ 1.5K) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nickstenning/honcho) (👨‍💻 46 · 🔀 130 · 📦 3.7K · 📋 100 - 11% open · ⏱️ 03.08.2022):

	```
	git clone https://github.com/nickstenning/honcho
	```
- [PyPi](https://pypi.org/project/honcho) (📥 140K / month):
	```
	pip install honcho
	```
- [Conda](https://anaconda.org/conda-forge/honcho):
	```
	conda install -c conda-forge honcho
	```
</details>
<details><summary><b><a href="https://github.com/Fizzadar/pyinfra">pyinfra</a></b> (🥉23 ·  ⭐ 1.6K) - A versatile CLI tools and python libraries to automate infrastructure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Fizzadar/pyinfra) (👨‍💻 73 · 🔀 280 · 📦 51 · 📋 620 - 18% open · ⏱️ 28.08.2022):

	```
	git clone https://github.com/Fizzadar/pyinfra
	```
- [PyPi](https://pypi.org/project/pyinfra) (📥 28K / month):
	```
	pip install pyinfra
	```
- [Conda](https://anaconda.org/conda-forge/pyinfra):
	```
	conda install -c conda-forge pyinfra
	```
</details>
<details><summary><b><a href="https://github.com/fabric/fabric">fabric</a></b> (🥉22 ·  ⭐ 14K) - A simple, Pythonic tool for remote execution and deployment. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fabric/fabric) (👨‍💻 19 · 🔀 1.7K · 📋 1.7K - 23% open · ⏱️ 14.07.2022):

	```
	git clone https://github.com/fabric/fabric
	```
- [PyPi](https://pypi.org/project/fabric) (📥 2.6M / month):
	```
	pip install fabric
	```
- [Conda](https://anaconda.org/conda-forge/fabric) (📥 53K · ⏱️ 09.09.2022):
	```
	conda install -c conda-forge fabric
	```
</details>
<details><summary><b><a href="https://github.com/fabtools/fabtools">fabtools</a></b> (🥉22 ·  ⭐ 1.3K · 💀) - Tools for writing awesome Fabric files. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fabtools/fabtools) (👨‍💻 88 · 🔀 190 · 📦 280 · 📋 140 - 54% open · ⏱️ 16.09.2019):

	```
	git clone https://github.com/fabtools/fabtools
	```
- [PyPi](https://pypi.org/project/fabtools) (📥 2K / month):
	```
	pip install fabtools
	```
- [Conda](https://anaconda.org/conda-forge/fabtools):
	```
	conda install -c conda-forge fabtools
	```
</details>
<details><summary><b><a href="https://github.com/sebastien/cuisine">cuisine</a></b> (🥉18 ·  ⭐ 1.2K · 💀) - Chef-like functionality for Fabric. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sebastien/cuisine) (👨‍💻 57 · 🔀 160 · 📦 160 · 📋 110 - 24% open · ⏱️ 27.02.2018):

	```
	git clone https://github.com/sebastien/cuisine
	```
- [PyPi](https://pypi.org/project/cuisine) (📥 810 / month):
	```
	pip install cuisine
	```
- [Conda](https://anaconda.org/conda-forge/cuisine):
	```
	conda install -c conda-forge cuisine
	```
</details>
<br>

## Distributed Computing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Frameworks and libraries for Distributed Computing._

🔗&nbsp;<b><a href="https://pypi.org/project/pyspark/">PySpark</a></b>  - [Apache Spark](https://spark.apache.org/) Python API.

<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇34 ·  ⭐ 16K) - A module that helps you build complex pipelines of batch jobs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 590 · 🔀 2.3K · 📦 1.8K · 📋 940 - 7% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 590K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/conda-forge/luigi) (📥 560K · ⏱️ 18.08.2022):
	```
	conda install -c conda-forge luigi
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥈32 ·  ⭐ 10K) - A flexible parallel computing library for analytic computing. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 560 · 🔀 1.5K · 📦 40K · 📋 4.5K - 15% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 7.1M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 6.5M · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥈27 ·  ⭐ 22K) - A system for parallel and distributed Python that unifies the machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (🔀 3.8K · 📦 5.8K · 📋 11K - 22% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/ray-project/ray/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈27 ·  ⭐ 2.6K · 💀) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Yelp/mrjob) (👨‍💻 140 · 🔀 580 · 📦 1.1K · 📋 1.3K - 15% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Yelp/mrjob
	```
- [PyPi](https://pypi.org/project/mrjob) (📥 68K / month):
	```
	pip install mrjob
	```
- [Conda](https://anaconda.org/conda-forge/mrjob) (📥 490K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge mrjob
	```
</details>
<details><summary><b><a href="https://github.com/robinhood/faust">faust</a></b> (🥉25 ·  ⭐ 6.3K · 💀) - A stream processing library, porting the ideas from [Kafka.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/robinhood/faust) (👨‍💻 94 · 🔀 530 · 📦 1.1K · 📋 460 - 48% open · ⏱️ 09.10.2020):

	```
	git clone https://github.com/robinhood/faust
	```
- [PyPi](https://pypi.org/project/faust) (📥 37K / month):
	```
	pip install faust
	```
- [Conda](https://anaconda.org/conda-forge/faust):
	```
	conda install -c conda-forge faust
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉24 ·  ⭐ 1.5K) - Run Python code against real-time streams of data via [Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 43 · 🔀 210 · 📦 55 · 📋 330 - 19% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 3K / month):
	```
	pip install streamparse
	```
- [Conda](https://anaconda.org/conda-forge/streamparse):
	```
	conda install -c conda-forge streamparse
	```
</details>
<br>

## Distribution

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to create packaged executables for release distribution._

🔗&nbsp;<b><a href="http://nuitka.net/">Nuitka</a></b>  - Compile scripts, modules, packages to an executable or extension module.

🔗&nbsp;<b><a href="http://pythonhosted.org/py2app/">py2app</a></b>  - Freezes Python scripts (Mac OS X).

🔗&nbsp;<b><a href="http://www.py2exe.org/">py2exe</a></b>  - Freezes Python scripts (Windows).

🔗&nbsp;<b><a href="http://pynsist.readthedocs.io/en/latest/">pynsist</a></b>  - A tool to build Windows installers, installers bundle Python itself.

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">PyInstaller</a></b> (🥇34 ·  ⭐ 9.5K) - Converts Python programs into stand-alone executables.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 440 · 🔀 1.7K · 📥 730K · 📦 30K · 📋 4.6K - 5% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 870K / month):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 350K · ⏱️ 21.05.2022):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥈28 ·  ⭐ 1.7K) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dashingsoft/pyarmor) (👨‍💻 25 · 🔀 190 · 📦 500 · 📋 800 - 2% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/dashingsoft/pyarmor
	```
- [PyPi](https://pypi.org/project/pyarmor) (📥 580K / month):
	```
	pip install pyarmor
	```
- [Conda](https://anaconda.org/conda-forge/pyarmor):
	```
	conda install -c conda-forge pyarmor
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉20 ·  ⭐ 1.5K) - A command line utility for building fully self-contained zipapps (PEP 441),.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 38 · 🔀 81 · 📥 330 · 📋 110 - 32% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 17K / month):
	```
	pip install shiv
	```
- [Conda](https://anaconda.org/conda-forge/shiv) (📥 210 · ⏱️ 14.09.2022):
	```
	conda install -c conda-forge shiv
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉15 ·  ⭐ 1.5K) - Build and distribute a virtualenv as a Debian package. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 59 · 🔀 170 · 📋 200 - 13% open · ⏱️ 15.07.2022):

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

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for generating project documentation._

🔗&nbsp;<b><a href="https://github.com/yoloseem/awesome-sphinxdoc">awesome-sphinxdoc</a></b> ( ⭐ 820 · 💀)  - A curated list of awesome tools for Sphinx Python Documentation..

<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥇23 ·  ⭐ 1.3K) - Epydoc replacement to auto generate API documentation for Python.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 39 · 🔀 140 · 📦 800 · 📋 280 - 2% open · ⏱️ 11.09.2022):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 93K / month):
	```
	pip install pdoc
	```
- [Conda](https://anaconda.org/conda-forge/pdoc) (📥 5.4K · ⏱️ 12.08.2022):
	```
	conda install -c conda-forge pdoc
	```
</details>
<details><summary><b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉20 ·  ⭐ 800 · 💀) - The literate-programming-style documentation generator. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pycco-docs/pycco) (👨‍💻 36 · 🔀 140 · 📦 260 · 📋 57 - 50% open · ⏱️ 20.12.2019):

	```
	git clone https://github.com/pycco-docs/pycco
	```
- [PyPi](https://pypi.org/project/pycco) (📥 1.6K / month):
	```
	pip install pycco
	```
- [Conda](https://anaconda.org/conda-forge/pycco):
	```
	conda install -c conda-forge pycco
	```
</details>
<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥉19 ·  ⭐ 4.9K · 📉) - Python Documentation generator. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (🔀 1.6K · 📋 6.2K - 16% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/sphinx-doc/sphinx/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Downloader

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for downloading._

🔗&nbsp;<b><a href="https://you-get.org/">you-get</a></b>  - A YouTube/Youku/Niconico video downloader written in Python 3.

🔗&nbsp;<b><a href="https://rg3.github.io/youtube-dl/">youtube-dl</a></b>  - A small command-line program to download videos from YouTube.

<details><summary><b><a href="https://github.com/akfamily/akshare">akshare</a></b> (🥇28 ·  ⭐ 5.4K) - A financial data interface library, built for human beings!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akfamily/akshare) (👨‍💻 41 · 🔀 1.2K · 📦 200 · ⏱️ 15.09.2022):

	```
	git clone https://github.com/jindaxiang/akshare
	```
- [PyPi](https://pypi.org/project/akshare) (📥 28K / month):
	```
	pip install akshare
	```
- [Conda](https://anaconda.org/conda-forge/akshare):
	```
	conda install -c conda-forge akshare
	```
</details>
<details><summary><b><a href="https://github.com/s3tools/s3cmd">s3cmd</a></b> (🥉25 ·  ⭐ 4K) - A command line tool for managing Amazon S3 and CloudFront. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/s3tools/s3cmd) (👨‍💻 210 · 🔀 810 · 📥 3.1M · 📋 830 - 29% open · ⏱️ 28.08.2022):

	```
	git clone https://github.com/s3tools/s3cmd
	```
- [PyPi](https://pypi.org/project/s3cmd) (📥 1.7M / month):
	```
	pip install s3cmd
	```
- [Conda](https://anaconda.org/conda-forge/s3cmd) (📥 7.1K · ⏱️ 22.12.2018):
	```
	conda install -c conda-forge s3cmd
	```
</details>
<details><summary><b><a href="https://github.com/bloomreach/s4cmd">s4cmd</a></b> (🥉21 ·  ⭐ 1.2K) - Super S3 command line tool, good for higher performance. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bloomreach/s4cmd) (👨‍💻 35 · 🔀 190 · 📦 31 · 📋 130 - 60% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/bloomreach/s4cmd
	```
- [PyPi](https://pypi.org/project/s4cmd) (📥 33K / month):
	```
	pip install s4cmd
	```
- [Conda](https://anaconda.org/conda-forge/s4cmd):
	```
	conda install -c conda-forge s4cmd
	```
</details>
<br>

## E-commerce

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Frameworks and libraries for e-commerce and payments._

🔗&nbsp;<b><a href="http://oscarcommerce.com/">django-oscar</a></b>  - An open-source e-commerce framework for Django.

🔗&nbsp;<b><a href="http://getsaleor.com/">saleor</a></b>  - An e-commerce storefront for Django.

🔗&nbsp;<b><a href="https://www.shuup.com/en/">shoop</a></b>  - An open source E-Commerce platform based on Django.

<details><summary><b><a href="https://github.com/MicroPyramid/forex-python">forex-python</a></b> (🥇25 ·  ⭐ 510) - Foreign exchange rates, Bitcoin price index and currency conversion. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MicroPyramid/forex-python) (👨‍💻 25 · 🔀 150 · 📦 1.4K · 📋 66 - 21% open · ⏱️ 05.08.2022):

	```
	git clone https://github.com/MicroPyramid/forex-python
	```
- [PyPi](https://pypi.org/project/forex-python) (📥 120K / month):
	```
	pip install forex-python
	```
- [Conda](https://anaconda.org/conda-forge/forex-python):
	```
	conda install -c conda-forge forex-python
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥈23 ·  ⭐ 2.9K · 💀) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 95 · 🔀 940 · 📦 200 · 📋 380 - 22% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 5.5K / month):
	```
	pip install django-shop
	```
- [Conda](https://anaconda.org/conda-forge/django-shop):
	```
	conda install -c conda-forge django-shop
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/cartridge">Cartridge</a></b> (🥈21 ·  ⭐ 670) - A shopping cart app built using the Mezzanine. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/cartridge) (👨‍💻 75 · 🔀 280 · 📋 150 - 15% open · ⏱️ 14.07.2022):

	```
	git clone https://github.com/stephenmcd/cartridge
	```
- [PyPi](https://pypi.org/project/cartridge) (📥 440 / month):
	```
	pip install cartridge
	```
- [Conda](https://anaconda.org/conda-forge/cartridge):
	```
	conda install -c conda-forge cartridge
	```
</details>
<details><summary><b><a href="https://github.com/carlospalol/money">money</a></b> (🥉20 ·  ⭐ 210 · 💀) - `Money` class with optional CLDR-backed locale-aware formatting and an.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carlospalol/money) (👨‍💻 4 · 🔀 27 · 📦 260 · 📋 23 - 30% open · ⏱️ 04.09.2016):

	```
	git clone https://github.com/carlospalol/money
	```
- [PyPi](https://pypi.org/project/money) (📥 43K / month):
	```
	pip install money
	```
- [Conda](https://anaconda.org/conda-forge/money):
	```
	conda install -c conda-forge money
	```
</details>
<details><summary><b><a href="https://github.com/agiliq/merchant">merchant</a></b> (🥉18 ·  ⭐ 990 · 💀) - A Django app to accept payments from various payment processors. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/agiliq/merchant) (👨‍💻 49 · 🔀 170 · 📦 25 · 📋 63 - 36% open · ⏱️ 08.07.2015):

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
<details><summary><b><a href="https://github.com/lxneng/alipay">alipay</a></b> (🥉14 ·  ⭐ 320 · 💀) - Unofficial Alipay API for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lxneng/alipay) (👨‍💻 13 · 🔀 91 · 📦 110 · 📋 15 - 20% open · ⏱️ 22.11.2017):

	```
	git clone https://github.com/lxneng/alipay
	```
- [PyPi](https://pypi.org/project/alipay) (📥 200 / month):
	```
	pip install alipay
	```
- [Conda](https://anaconda.org/conda-forge/alipay):
	```
	conda install -c conda-forge alipay
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/python-currencies">python-currencies</a></b> (🥉12 ·  ⭐ 62 · 💀) - Display money format and its filthy currencies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Alir3z4/python-currencies) (👨‍💻 5 · 🔀 13 · 📥 6 · 📦 39 · 📋 5 - 40% open · ⏱️ 22.12.2020):

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

## Editor Plugins and IDEs

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Editor Plugins and IDEs_

🔗&nbsp;<b><a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Python</a></b>  - The official VSCode extension with rich support for Python.

🔗&nbsp;<b><a href="https://www.jetbrains.com/pycharm/">PyCharm</a></b>  - Commercial Python IDE by JetBrains. Has free community edition available.

<details><summary><b><a href="https://github.com/spyder-ide/spyder">spyder</a></b> (🥇35 ·  ⭐ 7.2K) - Open Source Python IDE. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/spyder-ide/spyder) (👨‍💻 240 · 🔀 1.4K · 📥 2M · 📦 23K · 📋 16K - 7% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/spyder-ide/spyder
	```
- [PyPi](https://pypi.org/project/spyder) (📥 65K / month):
	```
	pip install spyder
	```
- [Conda](https://anaconda.org/conda-forge/spyder) (📥 1.4M · ⏱️ 30.08.2022):
	```
	conda install -c conda-forge spyder
	```
</details>
<details><summary><b><a href="https://github.com/jorgenschaefer/elpy">elpy</a></b> (🥈22 ·  ⭐ 1.8K) - Emacs Python Development Environment. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/jorgenschaefer/elpy) (👨‍💻 91 · 🔀 240 · 📦 210 · 📋 1.6K - 22% open · ⏱️ 27.06.2022):

	```
	git clone https://github.com/jorgenschaefer/elpy
	```
- [PyPi](https://pypi.org/project/elpy) (📥 680 / month):
	```
	pip install elpy
	```
- [Conda](https://anaconda.org/conda-forge/elpy):
	```
	conda install -c conda-forge elpy
	```
</details>
<details><summary><b><a href="https://github.com/DamnWidget/anaconda">anaconda</a></b> (🥈21 ·  ⭐ 2.2K · 💤) - Anaconda turns your Sublime Text 3 in a full featured Python.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/DamnWidget/anaconda) (👨‍💻 89 · 🔀 260 · 📋 780 - 21% open · ⏱️ 28.02.2022):

	```
	git clone https://github.com/DamnWidget/anaconda
	```
- [PyPi](https://pypi.org/project/anaconda) (📥 13K / month):
	```
	pip install anaconda
	```
- [Conda](https://anaconda.org/conda-forge/anaconda):
	```
	conda install -c conda-forge anaconda
	```
</details>
<details><summary><b><a href="https://github.com/ycm-core/YouCompleteMe">YouCompleteMe</a></b> (🥉19 ·  ⭐ 24K) - Includes [Jedi](https://github.com/davidhalter/jedi)-based.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ycm-core/YouCompleteMe) (👨‍💻 180 · 🔀 2.7K · 📋 3.1K - 0% open · ⏱️ 29.08.2022):

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
<details><summary><b><a href="https://github.com/microsoft/PTVS">PTVS</a></b> (🥉18 ·  ⭐ 2.4K) - Python Tools for Visual Studio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/PTVS) (👨‍💻 79 · 🔀 660 · 📥 33K · 📋 4.3K - 2% open · ⏱️ 09.09.2022):

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
<details><summary><b><a href="https://github.com/srusskih/SublimeJEDI">SublimeJEDI</a></b> (🥉17 ·  ⭐ 930) - A Sublime Text plugin to the awesome auto-complete library Jedi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/srusskih/SublimeJEDI) (👨‍💻 50 · 🔀 110 · 📋 220 - 15% open · ⏱️ 30.08.2022):

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
<details><summary><b><a href="https://github.com/davidhalter/jedi-vim">jedi-vim</a></b> (🥉15 ·  ⭐ 5.1K) - Vim bindings for the Jedi auto-completion library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi-vim) (👨‍💻 94 · 🔀 370 · 📋 760 - 3% open · ⏱️ 08.04.2022):

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
<details><summary><b><a href="https://github.com/python-mode/python-mode">python-mode</a></b> (🥉14 ·  ⭐ 5.4K · 💤) - An all in one plugin for turning Vim into a Python IDE. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-mode/python-mode) (👨‍💻 130 · 🔀 760 · 📋 900 - 2% open · ⏱️ 28.01.2022):

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
<br>

## Email

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for sending and parsing email._

<details><summary><b><a href="https://github.com/kootenpv/yagmail">yagmail</a></b> (🥇27 ·  ⭐ 2.4K) - Yet another Gmail/SMTP client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kootenpv/yagmail) (👨‍💻 31 · 🔀 260 · 📦 2.5K · 📋 210 - 43% open · ⏱️ 11.09.2022):

	```
	git clone https://github.com/kootenpv/yagmail
	```
- [PyPi](https://pypi.org/project/yagmail) (📥 200K / month):
	```
	pip install yagmail
	```
- [Conda](https://anaconda.org/conda-forge/yagmail) (📥 16K · ⏱️ 11.09.2022):
	```
	conda install -c conda-forge yagmail
	```
</details>
<details><summary><b><a href="https://github.com/mailgun/flanker">flanker</a></b> (🥈26 ·  ⭐ 1.5K · 💀) - An email address and Mime parsing library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mailgun/flanker) (👨‍💻 55 · 🔀 180 · 📦 260 · 📋 88 - 59% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/mailgun/flanker
	```
- [PyPi](https://pypi.org/project/flanker) (📥 53K / month):
	```
	pip install flanker
	```
- [Conda](https://anaconda.org/conda-forge/flanker):
	```
	conda install -c conda-forge flanker
	```
</details>
<details><summary><b><a href="https://github.com/modoboa/modoboa">modoboa</a></b> (🥈25 ·  ⭐ 2.2K) - A mail hosting and management platform including a modern Web UI. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/modoboa/modoboa) (👨‍💻 110 · 🔀 300 · 📦 35 · 📋 1.6K - 4% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/modoboa/modoboa
	```
- [PyPi](https://pypi.org/project/modoboa) (📥 2K / month):
	```
	pip install modoboa
	```
- [Conda](https://anaconda.org/conda-forge/modoboa):
	```
	conda install -c conda-forge modoboa
	```
</details>
<details><summary><b><a href="https://github.com/martinrusev/imbox">imbox</a></b> (🥈25 ·  ⭐ 1.1K) - Python IMAP for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinrusev/imbox) (👨‍💻 50 · 🔀 160 · 📦 150 · 📋 120 - 46% open · ⏱️ 01.07.2022):

	```
	git clone https://github.com/martinrusev/imbox
	```
- [PyPi](https://pypi.org/project/imbox) (📥 94K / month):
	```
	pip install imbox
	```
- [Conda](https://anaconda.org/conda-forge/imbox):
	```
	conda install -c conda-forge imbox
	```
</details>
<details><summary><b><a href="https://github.com/marrow/mailer">mailer</a></b> (🥉19 ·  ⭐ 250) - High-performance extensible mail delivery framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marrow/mailer) (👨‍💻 20 · 🔀 55 · 📥 130 · 📋 72 - 33% open · ⏱️ 15.07.2022):

	```
	git clone https://github.com/marrow/mailer
	```
- [PyPi](https://pypi.org/project/mailer) (📥 43K / month):
	```
	pip install mailer
	```
- [Conda](https://anaconda.org/conda-forge/mailer) (📥 50K · ⏱️ 01.07.2021):
	```
	conda install -c conda-forge mailer
	```
</details>
<details><summary><b><a href="https://github.com/moggers87/salmon">salmon</a></b> (🥉14 ·  ⭐ 560) - A Python Mail Server. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/moggers87/salmon) (👨‍💻 15 · 🔀 54 · 📥 74 · 📦 17 · 📋 90 - 18% open · ⏱️ 06.06.2022):

	```
	git clone https://github.com/moggers87/salmon
	```
- [PyPi](https://pypi.org/project/salmon) (📥 52 / month):
	```
	pip install salmon
	```
- [Conda](https://anaconda.org/conda-forge/salmon):
	```
	conda install -c conda-forge salmon
	```
</details>
<br>

## Enterprise Application Integrations

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Platforms and tools for systems integrations in enterprise environments_

🔗&nbsp;<b><a href="https://zato.io">Zato</a></b>  - ESB, SOA, REST, APIs and Cloud Integrations in Python.

<br>

## Environment Management

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Python version and virtual environment management._

<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥇26 ·  ⭐ 29K) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 380 · 🔀 2.5K · 📋 1.5K - 2% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 7.7K / month):
	```
	pip install pyenv
	```
- [Conda](https://anaconda.org/conda-forge/pyenv):
	```
	conda install -c conda-forge pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥉25 ·  ⭐ 4.3K) - A tool to create isolated Python environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 81 · 🔀 890 · 📋 1.2K - 6% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 34M / month):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 2.6M · ⏱️ 08.09.2022):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<br>

## Files

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for file manipulation and MIME type detection._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/mimetypes.html">mimetypes</a></b>  - (Python standard library) Map filenames to MIME types.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/pathlib.html">pathlib</a></b>  - (Python standard library) An cross-platform, object-oriented path library.

<details><summary><b><a href="https://github.com/gorakhargosh/watchdog">watchdog</a></b> (🥇34 ·  ⭐ 5.5K) - API and shell utilities to monitor file system events. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gorakhargosh/watchdog) (👨‍💻 130 · 🔀 630 · 📦 62K · 📋 570 - 28% open · ⏱️ 13.08.2022):

	```
	git clone https://github.com/gorakhargosh/watchdog
	```
- [PyPi](https://pypi.org/project/watchdog) (📥 7.3M / month):
	```
	pip install watchdog
	```
- [Conda](https://anaconda.org/conda-forge/watchdog) (📥 1.4M · ⏱️ 10.06.2022):
	```
	conda install -c conda-forge watchdog
	```
</details>
<details><summary><b><a href="https://github.com/ahupp/python-magic">python-magic</a></b> (🥈29 ·  ⭐ 2.2K) - A Python interface to the libmagic file type.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ahupp/python-magic) (👨‍💻 55 · 🔀 240 · 📦 31K · 📋 180 - 15% open · ⏱️ 20.06.2022):

	```
	git clone https://github.com/ahupp/python-magic
	```
- [PyPi](https://pypi.org/project/python-magic) (📥 6M / month):
	```
	pip install python-magic
	```
- [Conda](https://anaconda.org/conda-forge/python-magic) (📥 160K · ⏱️ 10.06.2022):
	```
	conda install -c conda-forge python-magic
	```
</details>
<details><summary><b><a href="https://github.com/mikeorr/Unipath">Unipath</a></b> (🥉20 ·  ⭐ 500 · 💀) - An object-oriented approach to file/directory operations. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mikeorr/Unipath) (👨‍💻 6 · 🔀 38 · 📦 7.9K · 📋 17 - 41% open · ⏱️ 14.02.2015):

	```
	git clone https://github.com/mikeorr/Unipath
	```
- [PyPi](https://pypi.org/project/Unipath) (📥 63K / month):
	```
	pip install Unipath
	```
- [Conda](https://anaconda.org/conda-forge/Unipath):
	```
	conda install -c conda-forge Unipath
	```
</details>
<details><summary><b><a href="https://github.com/PyFilesystem/pyfilesystem2">PyFilesystem2</a></b> (🥉19 ·  ⭐ 1.7K) - Python's filesystem abstraction layer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyFilesystem/pyfilesystem2) (👨‍💻 46 · 🔀 160 · 📋 340 - 21% open · ⏱️ 19.08.2022):

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
<details><summary><b><a href="https://github.com/jaraco/path">path.py</a></b> (🥉19 ·  ⭐ 1K) - A module wrapper for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/path) (👨‍💻 47 · 🔀 130 · 📋 130 - 0% open · ⏱️ 26.08.2022):

	```
	git clone https://github.com/jaraco/path.py
	```
- [PyPi](https://pypi.org/project/path.py) (📥 230K / month):
	```
	pip install path.py
	```
- [Conda](https://anaconda.org/conda-forge/path.py) (📥 530K · ⏱️ 28.07.2020):
	```
	conda install -c conda-forge path.py
	```
</details>
<br>

## Foreign Function Interface

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for providing foreign function interface._

🔗&nbsp;<b><a href="https://pypi.org/project/cffi/">cffi</a></b>  - Foreign Function Interface for Python calling C code.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/ctypes.html">ctypes</a></b>  - (Python standard library) Foreign Function Interface for Python calling C code.

🔗&nbsp;<b><a href="https://mathema.tician.de/software/pycuda/">PyCUDA</a></b>  - A Python wrapper for Nvidia's CUDA API.

🔗&nbsp;<b><a href="http://www.swig.org/Doc1.3/Python.html">SWIG</a></b>  - Simplified Wrapper and Interface Generator.

<br>

## Forms

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with forms._

<details><summary><b><a href="https://github.com/wtforms/wtforms">WTForms</a></b> (🥇33 ·  ⭐ 1.3K) - A flexible forms validation and rendering library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wtforms/wtforms) (👨‍💻 140 · 🔀 370 · 📦 140K · 📋 400 - 12% open · ⏱️ 17.07.2022):

	```
	git clone https://github.com/wtforms/wtforms
	```
- [PyPi](https://pypi.org/project/wtforms) (📥 3.1M / month):
	```
	pip install wtforms
	```
- [Conda](https://anaconda.org/conda-forge/wtforms) (📥 110K · ⏱️ 24.12.2021):
	```
	conda install -c conda-forge wtforms
	```
</details>
<details><summary><b><a href="https://github.com/django-crispy-forms/django-crispy-forms">django-crispy-forms</a></b> (🥈31 ·  ⭐ 4.5K) - A Django app which lets you create beautiful forms in a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-crispy-forms/django-crispy-forms) (👨‍💻 220 · 🔀 670 · 📦 98K · 📋 650 - 8% open · ⏱️ 15.07.2022):

	```
	git clone https://github.com/django-crispy-forms/django-crispy-forms
	```
- [PyPi](https://pypi.org/project/django-crispy-forms) (📥 680K / month):
	```
	pip install django-crispy-forms
	```
- [Conda](https://anaconda.org/conda-forge/django-crispy-forms) (📥 56K · ⏱️ 25.01.2022):
	```
	conda install -c conda-forge django-crispy-forms
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈27 ·  ⭐ 2.3K) - Bootstrap 3 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 98 · 🔀 680 · 📦 17K · 📋 290 - 2% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/dyve/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 88K / month):
	```
	pip install django-bootstrap3
	```
- [Conda](https://anaconda.org/conda-forge/django-bootstrap3) (📥 23K · ⏱️ 04.08.2019):
	```
	conda install -c conda-forge django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥈27 ·  ⭐ 960) - Bootstrap 4 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 210 · 📦 69K · 📋 160 - 13% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4) (📥 150K / month):
	```
	pip install django-bootstrap4
	```
- [Conda](https://anaconda.org/conda-forge/django-bootstrap4) (📥 20K · ⏱️ 20.10.2021):
	```
	conda install -c conda-forge django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/Pylons/deform">Deform</a></b> (🥉20 ·  ⭐ 380) - Python HTML form generation library influenced by the formish form.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Pylons/deform) (👨‍💻 100 · 🔀 160 · 📦 730 · 📋 180 - 25% open · ⏱️ 15.07.2022):

	```
	git clone https://github.com/Pylons/deform
	```
- [PyPi](https://pypi.org/project/deform) (📥 6.8K / month):
	```
	pip install deform
	```
- [Conda](https://anaconda.org/conda-forge/deform):
	```
	conda install -c conda-forge deform
	```
</details>
<details><summary><b><a href="https://github.com/WiserTogether/django-remote-forms">django-remote-forms</a></b> (🥉14 ·  ⭐ 220 · 💀) - A platform independent Django form serializer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WiserTogether/django-remote-forms) (👨‍💻 9 · 🔀 85 · 📦 19 · 📋 16 - 75% open · ⏱️ 12.07.2017):

	```
	git clone https://github.com/WiserTogether/django-remote-forms
	```
- [PyPi](https://pypi.org/project/django-remote-forms) (📥 140 / month):
	```
	pip install django-remote-forms
	```
- [Conda](https://anaconda.org/conda-forge/django-remote-forms):
	```
	conda install -c conda-forge django-remote-forms
	```
</details>
<br>

## Functional Programming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Functional Programming with Python._

<details><summary><b><a href="https://github.com/pytoolz/toolz">Toolz</a></b> (🥇32 ·  ⭐ 4K) - A collection of functional utilities for iterators, functions, and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytoolz/toolz) (👨‍💻 72 · 🔀 230 · 📦 68K · 📋 210 - 35% open · ⏱️ 18.08.2022):

	```
	git clone https://github.com/pytoolz/toolz
	```
- [PyPi](https://pypi.org/project/toolz) (📥 17M / month):
	```
	pip install toolz
	```
- [Conda](https://anaconda.org/conda-forge/toolz) (📥 8.9M · ⏱️ 10.07.2022):
	```
	conda install -c conda-forge toolz
	```
</details>
<details><summary><b><a href="https://github.com/Suor/funcy">funcy</a></b> (🥈28 ·  ⭐ 2.9K) - A fancy and practical functional tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/funcy) (👨‍💻 31 · 🔀 130 · 📦 5.7K · 📋 70 - 7% open · ⏱️ 25.08.2022):

	```
	git clone https://github.com/Suor/funcy
	```
- [PyPi](https://pypi.org/project/funcy) (📥 1.2M / month):
	```
	pip install funcy
	```
- [Conda](https://anaconda.org/conda-forge/funcy) (📥 230K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge funcy
	```
</details>
<details><summary><b><a href="https://github.com/more-itertools/more-itertools">more-itertools</a></b> (🥈27 ·  ⭐ 2.7K) - More routines for operating on iterables, beyond `itertools`. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/more-itertools/more-itertools) (👨‍💻 89 · 🔀 200 · 📥 2.5K · 📋 220 - 5% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/erikrose/more-itertools
	```
- [PyPi](https://pypi.org/project/more-itertools) (📥 22M / month):
	```
	pip install more-itertools
	```
- [Conda](https://anaconda.org/conda-forge/more-itertools) (📥 9.6M · ⏱️ 09.08.2022):
	```
	conda install -c conda-forge more-itertools
	```
</details>
<details><summary><b><a href="https://github.com/dry-python/returns">returns</a></b> (🥉26 ·  ⭐ 2.4K) - A set of type-safe monads, transformers, and composition utilities. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/dry-python/returns) (👨‍💻 41 · 🔀 88 · 📦 200 · 📋 390 - 14% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/dry-python/returns
	```
- [PyPi](https://pypi.org/project/returns) (📥 58K / month):
	```
	pip install returns
	```
- [Conda](https://anaconda.org/conda-forge/returns) (📥 3K · ⏱️ 13.03.2022):
	```
	conda install -c conda-forge returns
	```
</details>
<details><summary><b><a href="https://github.com/evhub/coconut">Coconut</a></b> (🥉21 ·  ⭐ 3.5K · 💤) - A variant of Python built for simple, elegant, Pythonic.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evhub/coconut) (👨‍💻 30 · 🔀 100 · 📋 570 - 12% open · ⏱️ 07.11.2021):

	```
	git clone https://github.com/evhub/coconut
	```
- [PyPi](https://pypi.org/project/coconut) (📥 860 / month):
	```
	pip install coconut
	```
- [Conda](https://anaconda.org/conda-forge/coconut) (📥 140K · ⏱️ 26.04.2022):
	```
	conda install -c conda-forge coconut
	```
</details>
<details><summary><b><a href="https://github.com/pytoolz/cytoolz">CyToolz</a></b> (🥉21 ·  ⭐ 880) - Cython implementation of `Toolz`: High performance functional.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytoolz/cytoolz) (🔀 67 · 📦 42K · 📋 73 - 32% open · ⏱️ 01.08.2022):

	```
	git clone https://github.com/pytoolz/cytoolz/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/kachayev/fn.py">fn.py</a></b> (🥉19 ·  ⭐ 3.2K · 💀) - Functional programming in Python: implementation of missing.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kachayev/fn.py) (👨‍💻 18 · 🔀 180 · 📦 430 · 📋 48 - 47% open · ⏱️ 13.10.2014):

	```
	git clone https://github.com/kachayev/fn.py
	```
- [PyPi](https://pypi.org/project/fn.py) (📥 380 / month):
	```
	pip install fn.py
	```
- [Conda](https://anaconda.org/conda-forge/fn.py):
	```
	conda install -c conda-forge fn.py
	```
</details>
<br>

## GUI Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with graphical user interface applications._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/curses.html">curses</a></b>  - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal..

🔗&nbsp;<b><a href="https://kivy.org/">kivy</a></b>  - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.

🔗&nbsp;<b><a href="https://wiki.gnome.org/Projects/PyGObject">PyGObject</a></b>  - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).

🔗&nbsp;<b><a href="https://riverbankcomputing.com/software/pyqt/intro">PyQt</a></b>  - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.

🔗&nbsp;<b><a href="https://wiki.python.org/moin/TkInter">Tkinter</a></b>  - Tkinter is Python's de-facto standard GUI package.

🔗&nbsp;<b><a href="http://urwid.org/">urwid</a></b>  - A library for creating terminal GUI applications with strong support for widgets, events, rich..

🔗&nbsp;<b><a href="https://wxpython.org/">wxPython</a></b>  - A blending of the wxWidgets C++ class library with the Python.

<details><summary><b><a href="https://github.com/pyglet/pyglet">pyglet</a></b> (🥇32 ·  ⭐ 1.2K) - A cross-platform windowing and multimedia library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyglet/pyglet) (👨‍💻 140 · 🔀 240 · 📦 18K · 📋 380 - 18% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/pyglet/pyglet
	```
- [PyPi](https://pypi.org/project/pyglet) (📥 190K / month):
	```
	pip install pyglet
	```
- [Conda](https://anaconda.org/conda-forge/pyglet) (📥 420K · ⏱️ 22.08.2022):
	```
	conda install -c conda-forge pyglet
	```
</details>
<details><summary><b><a href="https://github.com/PySimpleGUI/PySimpleGUI">PySimpleGUI</a></b> (🥈31 ·  ⭐ 11K) - Wrapper for tkinter, Qt, WxPython and Remi. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PySimpleGUI/PySimpleGUI) (👨‍💻 18 · 🔀 1.6K · 📦 5.9K · 📋 3K - 22% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/PySimpleGUI/PySimpleGUI
	```
- [PyPi](https://pypi.org/project/PySimpleGUI) (📥 130K / month):
	```
	pip install PySimpleGUI
	```
- [Conda](https://anaconda.org/conda-forge/PySimpleGUI) (📥 72K · ⏱️ 28.07.2022):
	```
	conda install -c conda-forge PySimpleGUI
	```
</details>
<details><summary><b><a href="https://github.com/ChrisKnott/Eel">Eel</a></b> (🥈28 ·  ⭐ 5.2K · 💤) - A library for making simple Electron-like offline HTML/JS GUI apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ChrisKnott/Eel) (👨‍💻 38 · 🔀 510 · 📦 4K · 📋 460 - 31% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/ChrisKnott/Eel
	```
- [PyPi](https://pypi.org/project/Eel) (📥 50K / month):
	```
	pip install Eel
	```
- [Conda](https://anaconda.org/conda-forge/Eel):
	```
	conda install -c conda-forge Eel
	```
</details>
<details><summary><b><a href="https://github.com/chriskiehl/Gooey">Gooey</a></b> (🥈25 ·  ⭐ 17K) - Turn command line programs into a full GUI application with one line. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chriskiehl/Gooey) (👨‍💻 100 · 🔀 870 · 📥 300 · 📦 600 · 📋 560 - 19% open · ⏱️ 08.05.2022):

	```
	git clone https://github.com/chriskiehl/Gooey
	```
- [PyPi](https://pypi.org/project/Gooey) (📥 3.8K / month):
	```
	pip install Gooey
	```
- [Conda](https://anaconda.org/conda-forge/Gooey) (📥 52K · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge Gooey
	```
</details>
<details><summary><b><a href="https://github.com/flexxui/flexx">Flexx</a></b> (🥉24 ·  ⭐ 3K) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/flexxui/flexx) (👨‍💻 37 · 🔀 260 · 📦 110 · 📋 440 - 19% open · ⏱️ 22.07.2022):

	```
	git clone https://github.com/zoofIO/flexx
	```
- [PyPi](https://pypi.org/project/flexx) (📥 840 / month):
	```
	pip install flexx
	```
- [Conda](https://anaconda.org/conda-forge/flexx) (📥 91K · ⏱️ 12.04.2022):
	```
	conda install -c conda-forge flexx
	```
</details>
<details><summary><b><a href="https://github.com/hoffstadt/DearPyGui">DearPyGui</a></b> (🥉23 ·  ⭐ 8.7K) - A Simple GPU accelerated Python GUI framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hoffstadt/DearPyGui) (🔀 440 · 📦 500 · 📋 1K - 21% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/RaylockLLC/DearPyGui/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/r0x0r/pywebview">pywebview</a></b> (🥉23 ·  ⭐ 3.1K) - A lightweight cross-platform native wrapper around a webview.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/r0x0r/pywebview) (🔀 400 · 📦 750 · 📋 650 - 2% open · ⏱️ 24.08.2022):

	```
	git clone https://github.com/r0x0r/pywebview/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/beeware/toga">Toga</a></b> (🥉18 ·  ⭐ 3.2K) - A Python native, OS native GUI toolkit. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/toga) (👨‍💻 210 · 🔀 540 · 📋 560 - 16% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/pybee/toga
	```
- [PyPi](https://pypi.org/project/toga) (📥 2.1K / month):
	```
	pip install toga
	```
- [Conda](https://anaconda.org/conda-forge/toga):
	```
	conda install -c conda-forge toga
	```
</details>
<details><summary><b><a href="https://github.com/nucleic/enaml">enaml</a></b> (🥉17 ·  ⭐ 1.4K) - Creating beautiful user-interfaces with Declarative Syntax like QML. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nucleic/enaml) (👨‍💻 36 · 🔀 120 · 📥 180 · 📋 220 - 16% open · ⏱️ 19.08.2022):

	```
	git clone https://github.com/nucleic/enaml
	```
- [PyPi](https://pypi.org/project/enaml) (📥 2.7K / month):
	```
	pip install enaml
	```
- [Conda](https://anaconda.org/conda-forge/enaml) (📥 120K · ⏱️ 20.08.2022):
	```
	conda install -c conda-forge enaml
	```
</details>
<br>

## GraphQL

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with GraphQL._

🔗&nbsp;<b><a href="https://tartiflette.io">tartiflette</a></b>  - SDL-first GraphQL engine implementation for Python 3.6+ and asyncio.

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇25 ·  ⭐ 7.4K) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (🔀 760 · 📦 14K · 📋 960 - 11% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/graphql-python/graphene/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/tartiflette/tartiflette-aiohttp">tartiflette-aiohttp</a></b> (🥉16 ·  ⭐ 59) - An `aiohttp`-based wrapper for Tartiflette to expose.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tartiflette/tartiflette-aiohttp) (🔀 7 · 📦 44 · 📋 18 - 16% open · ⏱️ 07.09.2022):

	```
	git clone https://github.com/tartiflette/tartiflette-aiohttp/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/tartiflette/tartiflette-asgi">tartiflette-asgi</a></b> (🥉15 ·  ⭐ 100) - ASGI support for the Tartiflette GraphQL engine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tartiflette/tartiflette-asgi) (🔀 15 · 📦 10 · 📋 49 - 12% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/tartiflette/tartiflette-asgi/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Game Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Awesome game development libraries._

🔗&nbsp;<b><a href="https://arcade.academy/index.html">Arcade</a></b>  - Arcade is a modern Python framework for crafting games with compelling graphics and sound.

🔗&nbsp;<b><a href="http://cocos2d.org/">Cocos2d</a></b>  - cocos2d is a framework for building 2D games, demos, and other graphical/interactive..

🔗&nbsp;<b><a href="http://www.harfang3d.com">Harfang3D</a></b>  - Python framework for 3D, VR and game development.

🔗&nbsp;<b><a href="https://www.panda3d.org/">Panda3D</a></b>  - 3D game engine developed by Disney.

🔗&nbsp;<b><a href="http://www.pygame.org/news.html">Pygame</a></b>  - Pygame is a set of Python modules designed for writing games.

🔗&nbsp;<b><a href="http://www.ogre3d.org/tikiwiki/PyOgre">PyOgre</a></b>  - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.

🔗&nbsp;<b><a href="http://pyopengl.sourceforge.net/">PyOpenGL</a></b>  - Python ctypes bindings for OpenGL and it's related APIs.

🔗&nbsp;<b><a href="https://pysdl2.readthedocs.io">PySDL2</a></b>  - A ctypes based wrapper for the SDL2 library.

🔗&nbsp;<b><a href="https://www.renpy.org/">RenPy</a></b>  - A Visual Novel engine.

<br>

## Geolocation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for geocoding addresses and working with latitudes and longitudes._

🔗&nbsp;<b><a href="https://docs.djangoproject.com/en/dev/ref/contrib/gis/">GeoDjango</a></b>  - A world-class geographic web framework.

<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥇32 ·  ⭐ 3.7K) - Python Geocoding Toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 130 · 🔀 580 · 📦 42K · 📋 260 - 7% open · ⏱️ 07.08.2022):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 4.6M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 800K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/SmileyChris/django-countries">django-countries</a></b> (🥈23 ·  ⭐ 1.2K) - A Django app that provides a country field for models and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SmileyChris/django-countries) (👨‍💻 48 · 🔀 240 · 📋 250 - 4% open · ⏱️ 12.08.2022):

	```
	git clone https://github.com/SmileyChris/django-countries
	```
- [PyPi](https://pypi.org/project/django-countries) (📥 440K / month):
	```
	pip install django-countries
	```
- [Conda](https://anaconda.org/conda-forge/django-countries) (📥 1.9K · ⏱️ 28.02.2022):
	```
	conda install -c conda-forge django-countries
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉20 ·  ⭐ 740) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 48 · 🔀 93 · 📦 10K · 📋 85 - 25% open · ⏱️ 07.05.2022):

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
<details><summary><b><a href="https://github.com/maxmind/geoip-api-python">GeoIP</a></b> (🥉16 ·  ⭐ 230 · 💀) - Python API for MaxMind GeoIP Legacy Database. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/maxmind/geoip-api-python) (👨‍💻 12 · 🔀 52 · 📦 1.2K · ⏱️ 11.02.2021):

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

## HTML Manipulation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with HTML and XML._

🔗&nbsp;<b><a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">BeautifulSoup</a></b>  - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

🔗&nbsp;<b><a href="https://pypi.org/project/cssutils/">cssutils</a></b>  - A CSS library for Python.

🔗&nbsp;<b><a href="http://lxml.de/">lxml</a></b>  - A very fast, easy-to-use and versatile library for handling HTML and XML.

🔗&nbsp;<b><a href="http://weasyprint.org">WeasyPrint</a></b>  - A visual rendering engine for HTML and CSS that can export to PDF.

🔗&nbsp;<b><a href="https://xmldataset.readthedocs.io/en/latest/">xmldataset</a></b>  - Simple XML Parsing.

<details><summary><b><a href="https://github.com/martinblech/xmltodict">xmltodict</a></b> (🥇31 ·  ⭐ 4.9K) - Working with XML feel like you are working with JSON. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/martinblech/xmltodict) (👨‍💻 49 · 🔀 440 · 📦 43K · 📋 220 - 27% open · ⏱️ 08.05.2022):

	```
	git clone https://github.com/martinblech/xmltodict
	```
- [PyPi](https://pypi.org/project/xmltodict) (📥 19M / month):
	```
	pip install xmltodict
	```
- [Conda](https://anaconda.org/conda-forge/xmltodict) (📥 1.9M · ⏱️ 08.05.2022):
	```
	conda install -c conda-forge xmltodict
	```
</details>
<details><summary><b><a href="https://github.com/pallets/markupsafe">MarkupSafe</a></b> (🥇31 ·  ⭐ 490) - Implements a XML/HTML/XHTML Markup safe string for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/markupsafe) (👨‍💻 39 · 🔀 110 · 📦 950K · ⏱️ 01.09.2022):

	```
	git clone https://github.com/pallets/markupsafe
	```
- [PyPi](https://pypi.org/project/markupsafe) (📥 120M / month):
	```
	pip install markupsafe
	```
- [Conda](https://anaconda.org/conda-forge/markupsafe) (📥 22M · ⏱️ 08.06.2022):
	```
	conda install -c conda-forge markupsafe
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/bleach">bleach</a></b> (🥈27 ·  ⭐ 2.4K) - A whitelist-based HTML sanitization and text linkification library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mozilla/bleach) (👨‍💻 78 · 🔀 220 · 📦 190K · 📋 360 - 9% open · ⏱️ 27.06.2022):

	```
	git clone https://github.com/mozilla/bleach
	```
- [PyPi](https://pypi.org/project/bleach) (📥 12M / month):
	```
	pip install bleach
	```
- [Conda](https://anaconda.org/conda-forge/bleach) (📥 8.5M · ⏱️ 27.06.2022):
	```
	conda install -c conda-forge bleach
	```
</details>
<details><summary><b><a href="https://github.com/gawel/pyquery">pyquery</a></b> (🥈27 ·  ⭐ 2.1K) - A jQuery-like library for parsing HTML. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gawel/pyquery) (👨‍💻 50 · 🔀 170 · 📦 15K · 📋 170 - 26% open · ⏱️ 17.07.2022):

	```
	git clone https://github.com/gawel/pyquery
	```
- [PyPi](https://pypi.org/project/pyquery) (📥 1.1M / month):
	```
	pip install pyquery
	```
- [Conda](https://anaconda.org/conda-forge/pyquery) (📥 29K · ⏱️ 27.11.2020):
	```
	conda install -c conda-forge pyquery
	```
</details>
<details><summary><b><a href="https://github.com/stchris/untangle">untangle</a></b> (🥉24 ·  ⭐ 550) - Converts XML documents to Python objects for easy access. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stchris/untangle) (👨‍💻 17 · 🔀 79 · 📥 530 · 📦 890 · 📋 54 - 27% open · ⏱️ 02.07.2022):

	```
	git clone https://github.com/stchris/untangle
	```
- [PyPi](https://pypi.org/project/untangle) (📥 160K / month):
	```
	pip install untangle
	```
- [Conda](https://anaconda.org/conda-forge/untangle) (📥 2.8K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge untangle
	```
</details>
<details><summary><b><a href="https://github.com/html5lib/html5lib-python">html5lib</a></b> (🥉16 ·  ⭐ 980 · 💤) - A standards-compliant library for parsing and serializing HTML.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/html5lib/html5lib-python) (👨‍💻 62 · 🔀 260 · 📋 240 - 34% open · ⏱️ 17.09.2021):

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

## HTTP Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with HTTP._

<details><summary><b><a href="https://github.com/psf/requests">requests</a></b> (🥇40 ·  ⭐ 48K) - HTTP Requests for Humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/psf/requests) (👨‍💻 720 · 🔀 8.5K · 📥 3.4K · 📦 1.6M · 📋 3.6K - 5% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/psf/requests
	```
- [PyPi](https://pypi.org/project/requests) (📥 240M / month):
	```
	pip install requests
	```
- [Conda](https://anaconda.org/conda-forge/requests) (📥 23M · ⏱️ 30.08.2022):
	```
	conda install -c conda-forge requests
	```
</details>
<details><summary><b><a href="https://github.com/encode/httpx">httpx</a></b> (🥈36 ·  ⭐ 9.4K · 📈) - A next generation HTTP client for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/httpx) (👨‍💻 170 · 🔀 600 · 📦 32K · 📋 710 - 5% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/encode/httpx
	```
- [PyPi](https://pypi.org/project/httpx) (📥 11M / month):
	```
	pip install httpx
	```
- [Conda](https://anaconda.org/conda-forge/httpx) (📥 300K · ⏱️ 09.08.2022):
	```
	conda install -c conda-forge httpx
	```
</details>
<details><summary><b><a href="https://github.com/urllib3/urllib3">urllib3</a></b> (🥈36 ·  ⭐ 3.1K) - A HTTP library with thread-safe connection pooling, file post support,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/urllib3/urllib3) (👨‍💻 310 · 🔀 940 · 📥 3.2K · 📦 960K · 📋 1K - 9% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/shazow/urllib3
	```
- [PyPi](https://pypi.org/project/urllib3) (📥 270M / month):
	```
	pip install urllib3
	```
- [Conda](https://anaconda.org/conda-forge/urllib3) (📥 23M · ⏱️ 25.07.2022):
	```
	conda install -c conda-forge urllib3
	```
</details>
<details><summary><b><a href="https://github.com/httplib2/httplib2">httplib2</a></b> (🥉30 ·  ⭐ 450) - Comprehensive HTTP client library. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/httplib2/httplib2) (👨‍💻 72 · 🔀 170 · 📦 110K · 📋 110 - 39% open · ⏱️ 16.07.2022):

	```
	git clone https://github.com/httplib2/httplib2
	```
- [PyPi](https://pypi.org/project/httplib2) (📥 33M / month):
	```
	pip install httplib2
	```
- [Conda](https://anaconda.org/conda-forge/httplib2) (📥 1.8M · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge httplib2
	```
</details>
<details><summary><b><a href="https://github.com/spyoungtech/grequests">grequests</a></b> (🥉27 ·  ⭐ 4.1K · 💤) - requests + gevent for asynchronous HTTP requests. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/spyoungtech/grequests) (👨‍💻 28 · 🔀 300 · 📦 3.2K · 📋 110 - 6% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/spyoungtech/grequests
	```
- [PyPi](https://pypi.org/project/grequests) (📥 380K / month):
	```
	pip install grequests
	```
- [Conda](https://anaconda.org/conda-forge/grequests) (📥 59K · ⏱️ 22.04.2020):
	```
	conda install -c conda-forge grequests
	```
</details>
<details><summary><b><a href="https://github.com/twisted/treq">treq</a></b> (🥉21 ·  ⭐ 550) - Python requests like API built on top of Twisted's HTTP client. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/twisted/treq) (👨‍💻 50 · 🔀 130 · 📥 120 · 📦 1K · 📋 160 - 37% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/twisted/treq
	```
- [PyPi](https://pypi.org/project/treq) (📥 72K / month):
	```
	pip install treq
	```
- [Conda](https://anaconda.org/conda-forge/treq) (📥 64K · ⏱️ 30.01.2022):
	```
	conda install -c conda-forge treq
	```
</details>
<br>

## Hardware

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for programming with hardware._

🔗&nbsp;<b><a href="http://inotool.org/">ino</a></b>  - Command line toolkit for working with Arduino.

🔗&nbsp;<b><a href="http://www.pingo.io/">Pingo</a></b>  - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo,..

<details><summary><b><a href="https://github.com/secdev/scapy">scapy</a></b> (🥇32 ·  ⭐ 7.9K) - A brilliant packet manipulation library. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/secdev/scapy) (👨‍💻 400 · 🔀 1.6K · 📦 8.6K · 📋 1.4K - 2% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/secdev/scapy
	```
- [PyPi](https://pypi.org/project/scapy) (📥 1.7M / month):
	```
	pip install scapy
	```
- [Conda](https://anaconda.org/conda-forge/scapy) (📥 49K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge scapy
	```
</details>
<details><summary><b><a href="https://github.com/boppreh/keyboard">keyboard</a></b> (🥈30 ·  ⭐ 3.1K) - Hook and simulate global keyboard events on Windows and Linux. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/boppreh/keyboard) (👨‍💻 40 · 🔀 360 · 📦 7.6K · 📋 500 - 63% open · ⏱️ 20.07.2022):

	```
	git clone https://github.com/boppreh/keyboard
	```
- [PyPi](https://pypi.org/project/keyboard) (📥 500K / month):
	```
	pip install keyboard
	```
- [Conda](https://anaconda.org/conda-forge/keyboard) (📥 7.9K · ⏱️ 08.11.2021):
	```
	conda install -c conda-forge keyboard
	```
</details>
<details><summary><b><a href="https://github.com/boppreh/mouse">mouse</a></b> (🥉22 ·  ⭐ 670) - Hook and simulate global mouse events on Windows and Linux. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/boppreh/mouse) (👨‍💻 8 · 🔀 99 · 📦 730 · 📋 110 - 73% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/boppreh/mouse
	```
- [PyPi](https://pypi.org/project/mouse) (📥 25K / month):
	```
	pip install mouse
	```
- [Conda](https://anaconda.org/conda-forge/mouse):
	```
	conda install -c conda-forge mouse
	```
</details>
<details><summary><b><a href="https://github.com/SavinaRoja/PyUserInput">PyUserInput</a></b> (🥉20 ·  ⭐ 1K · 💀) - A module for cross-platform control of the mouse and keyboard. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/SavinaRoja/PyUserInput) (👨‍💻 21 · 🔀 170 · 📦 440 · 📋 100 - 70% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/SavinaRoja/PyUserInput
	```
- [PyPi](https://pypi.org/project/PyUserInput) (📥 6.5K / month):
	```
	pip install PyUserInput
	```
- [Conda](https://anaconda.org/conda-forge/PyUserInput):
	```
	conda install -c conda-forge PyUserInput
	```
</details>
<details><summary><b><a href="https://github.com/rockymeza/wifi">wifi</a></b> (🥉19 ·  ⭐ 290 · 💀) - A Python library and command line tool for working with WiFi on Linux. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/rockymeza/wifi) (👨‍💻 13 · 🔀 140 · 📦 420 · 📋 64 - 51% open · ⏱️ 20.03.2017):

	```
	git clone https://github.com/rockymeza/wifi
	```
- [PyPi](https://pypi.org/project/wifi) (📥 9.2K / month):
	```
	pip install wifi
	```
- [Conda](https://anaconda.org/conda-forge/wifi):
	```
	conda install -c conda-forge wifi
	```
</details>
<br>

## Image Processing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for manipulating images._

🔗&nbsp;<b><a href="https://sourceforge.net/projects/imgseek/">imgSeek</a></b>  - A project for searching a collection of images using visual similarity.

🔗&nbsp;<b><a href="http://github.com/pymatting/pymatting">PyMatting</a></b>  - A library for alpha matting.

🔗&nbsp;<b><a href="http://scikit-image.org/">scikit-image</a></b>  - A Python library for (scientific) image processing.

<details><summary><b><a href="https://github.com/python-pillow/Pillow">pillow</a></b> (🥇35 ·  ⭐ 10K) - Pillow is the friendly.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 410 · 🔀 1.7K · 📦 840K · 📋 2.6K - 4% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 47M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/Pillow) (📥 19M · ⏱️ 13.08.2022):
	```
	conda install -c conda-forge Pillow
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">wand</a></b> (🥇30 ·  ⭐ 1.2K) - Python bindings for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 100 · 🔀 190 · 📥 8.5K · 📦 12K · 📋 380 - 4% open · ⏱️ 22.08.2022):

	```
	git clone https://github.com/dahlia/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 470K / month):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 16K · ⏱️ 22.08.2022):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/thumbor/thumbor">thumbor</a></b> (🥈29 ·  ⭐ 9.1K) - A smart imaging service. It enables on-demand crop, re-sizing and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thumbor/thumbor) (👨‍💻 180 · 🔀 750 · 📦 320 · 📋 900 - 1% open · ⏱️ 22.08.2022):

	```
	git clone https://github.com/thumbor/thumbor
	```
- [PyPi](https://pypi.org/project/thumbor) (📥 3.8K / month):
	```
	pip install thumbor
	```
- [Conda](https://anaconda.org/conda-forge/thumbor):
	```
	conda install -c conda-forge thumbor
	```
</details>
<details><summary><b><a href="https://github.com/WhyNotHugo/python-barcode">python-barcode</a></b> (🥈26 ·  ⭐ 390) - Create barcodes in Python with no extra dependencies. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WhyNotHugo/python-barcode) (👨‍💻 41 · 🔀 96 · 📥 240 · 📦 14K · 📋 93 - 38% open · ⏱️ 05.09.2022):

	```
	git clone https://github.com/WhyNotHugo/python-barcode
	```
- [PyPi](https://pypi.org/project/python-barcode) (📥 170K / month):
	```
	pip install python-barcode
	```
- [Conda](https://anaconda.org/conda-forge/python-barcode) (📥 7.3K · ⏱️ 22.08.2020):
	```
	conda install -c conda-forge python-barcode
	```
</details>
<details><summary><b><a href="https://github.com/dylanaraps/pywal">pywal</a></b> (🥈24 ·  ⭐ 6.7K · 💤) - A tool that generates color schemes from images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dylanaraps/pywal) (👨‍💻 60 · 🔀 260 · 📥 840 · 📦 190 · 📋 510 - 23% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/dylanaraps/pywal
	```
- [PyPi](https://pypi.org/project/pywal) (📥 3.4K / month):
	```
	pip install pywal
	```
- [Conda](https://anaconda.org/conda-forge/pywal):
	```
	conda install -c conda-forge pywal
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉22 ·  ⭐ 440) - A fast image processing library with low memory needs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 14 · 🔀 40 · 📦 360 · 📋 300 - 36% open · ⏱️ 13.08.2022):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 19K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 31K · ⏱️ 24.07.2022):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/daboth/pagan">pagan</a></b> (🥉18 ·  ⭐ 270 · 💤) - Retro identicon (Avatar) generation based on input string and hash. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/daboth/pagan) (👨‍💻 9 · 🔀 41 · 📦 55 · 📋 8 - 62% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/daboth/pagan
	```
- [PyPi](https://pypi.org/project/pagan) (📥 530 / month):
	```
	pip install pagan
	```
- [Conda](https://anaconda.org/conda-forge/pagan):
	```
	conda install -c conda-forge pagan
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉16 ·  ⭐ 870 · 💀) - Nudity detection. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/nude.py) (👨‍💻 12 · 🔀 130 · 📦 2.7K · 📋 10 - 70% open · ⏱️ 23.11.2020):

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
<details><summary><b><a href="https://github.com/lincolnloop/python-qrcode">python-qrcode</a></b> (🥉14 ·  ⭐ 3.3K) - A pure Python QR Code generator. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lincolnloop/python-qrcode) (👨‍💻 50 · 🔀 510 · 📋 180 - 20% open · ⏱️ 14.03.2022):

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
<details><summary><b><a href="https://github.com/fogleman/Quads">Quads</a></b> (🥉11 ·  ⭐ 1.1K · 💀) - Computer art based on quadtrees. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fogleman/Quads) (🔀 140 · ⏱️ 20.05.2014):

	```
	git clone https://github.com/fogleman/Quads
	```
- [PyPi](https://pypi.org/project/Quads) (📥 210 / month):
	```
	pip install Quads
	```
- [Conda](https://anaconda.org/conda-forge/Quads):
	```
	conda install -c conda-forge Quads
	```
</details>
<details><summary><b><a href="https://github.com/rossgoodwin/hmap">hmap</a></b> (🥉11 ·  ⭐ 200 · 💀) - Image histogram remapping. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rossgoodwin/hmap) (👨‍💻 3 · 🔀 21 · ⏱️ 04.11.2019):

	```
	git clone https://github.com/rossgoodwin/hmap
	```
- [PyPi](https://pypi.org/project/hmap) (📥 770 / month):
	```
	pip install hmap
	```
- [Conda](https://anaconda.org/conda-forge/hmap):
	```
	conda install -c conda-forge hmap
	```
</details>
<br>

## Implementations

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Implementations of Python._

🔗&nbsp;<b><a href="http://cython.org/">Cython</a></b>  - Optimizing Static Compiler for Python.

🔗&nbsp;<b><a href="https://hg.python.org/jython">Jython</a></b>  - Implementation of Python programming language written in Java for the JVM.

🔗&nbsp;<b><a href="http://numba.pydata.org/">Numba</a></b>  - Python JIT compiler to LLVM aimed at scientific Python.

🔗&nbsp;<b><a href="https://foss.heptapod.net/pypy/pypy">PyPy</a></b>  - A very fast and compliant implementation of the Python language.

<details><summary><b><a href="https://github.com/micropython/micropython">MicroPython</a></b> (🥇23 ·  ⭐ 15K) - A lean and efficient Python programming language.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/micropython/micropython) (👨‍💻 520 · 🔀 4.2K · 📥 48K · 📋 4.4K - 25% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/micropython/micropython
	```
- [PyPi](https://pypi.org/project/micropython):
	```
	pip install micropython
	```
- [Conda](https://anaconda.org/conda-forge/micropython) (📥 8.5K · ⏱️ 17.06.2022):
	```
	conda install -c conda-forge micropython
	```
</details>
<details><summary><b><a href="https://github.com/python/cpython">CPython</a></b> (🥈21 ·  ⭐ 48K) - **Default, most widely used implementation of the Python.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python/cpython) (👨‍💻 2.2K · 🔀 23K · 📋 61K - 11% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/python/cpython
	```
- [PyPi](https://pypi.org/project/cpython) (📥 28K / month):
	```
	pip install cpython
	```
- [Conda](https://anaconda.org/conda-forge/cpython):
	```
	conda install -c conda-forge cpython
	```
</details>
<details><summary><b><a href="https://github.com/IronLanguages/ironpython3">IronPython</a></b> (🥈21 ·  ⭐ 1.9K) - Implementation of the Python programming language written in C#. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IronLanguages/ironpython3) (👨‍💻 31 · 🔀 220 · 📥 34K · 📋 520 - 46% open · ⏱️ 15.09.2022):

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
<details><summary><b><a href="https://github.com/google/grumpy">Grumpy</a></b> (🥈16 ·  ⭐ 11K · 💀) - More compiler than interpreter as more powerful CPython2.7.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/grumpy) (👨‍💻 30 · 🔀 630 · 📋 140 - 42% open · ⏱️ 22.11.2017):

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
<details><summary><b><a href="https://github.com/Maratyszcza/PeachPy">PeachPy</a></b> (🥈16 ·  ⭐ 1.7K) - x86-64 assembler embedded in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Maratyszcza/PeachPy) (👨‍💻 23 · 🔀 140 · 📦 11 · 📋 87 - 26% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/Maratyszcza/PeachPy
	```
- [PyPi](https://pypi.org/project/PeachPy) (📥 33 / month):
	```
	pip install PeachPy
	```
- [Conda](https://anaconda.org/conda-forge/PeachPy):
	```
	conda install -c conda-forge PeachPy
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/Pyjion">Pyjion</a></b> (🥉15 ·  ⭐ 1.6K · 💀) - A JIT for Python based upon CoreCLR. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/Pyjion) (👨‍💻 17 · 🔀 70 · 📋 110 - 33% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/Microsoft/Pyjion
	```
- [PyPi](https://pypi.org/project/Pyjion) (📥 940 / month):
	```
	pip install Pyjion
	```
- [Conda](https://anaconda.org/conda-forge/Pyjion) (📥 290 · ⏱️ 13.02.2022):
	```
	conda install -c conda-forge Pyjion
	```
</details>
<details><summary><b><a href="https://github.com/pyston/pyston_v1">Pyston</a></b> (🥉12 ·  ⭐ 4.9K · 💀) - A Python implementation using JIT techniques. <code>❗Unlicensed</code></summary>

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
<details><summary><b><a href="https://github.com/stackless-dev/stackless">Stackless Python</a></b> (🥉12 ·  ⭐ 850 · 💀) - An enhanced version of the Python programming language. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stackless-dev/stackless) (👨‍💻 1K · 🔀 58 · 📋 270 - 4% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/stackless-dev/stackless
	```
- [PyPi](https://pypi.org/project/stackless) (📥 140 / month):
	```
	pip install stackless
	```
- [Conda](https://anaconda.org/conda-forge/stackless):
	```
	conda install -c conda-forge stackless
	```
</details>
<details><summary><b><a href="https://github.com/metawilm/cl-python">CLPython</a></b> (🥉11 ·  ⭐ 340) - Implementation of the Python programming language written in.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/metawilm/cl-python) (👨‍💻 12 · 🔀 32 · 📋 17 - 11% open · ⏱️ 10.03.2022):

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

## Interactive Interpreter

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Interactive Python interpreters (REPL)._

🔗&nbsp;<b><a href="https://jupyter.org">Jupyter Notebook (IPython)</a></b>  - A rich toolkit to help you make the most out of using Python..

🔗&nbsp;<b><a href="https://github.com/markusschanta/awesome-jupyter">awesome-jupyter</a></b> ( ⭐ 2.9K)  - A curated list of awesome Jupyter projects, libraries and resources.

<details><summary><b><a href="https://github.com/prompt-toolkit/ptpython">ptpython</a></b> (🥇28 ·  ⭐ 4.6K) - Advanced Python REPL built on top of the [python-prompt-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/prompt-toolkit/ptpython) (👨‍💻 52 · 🔀 260 · 📦 1.9K · 📋 350 - 57% open · ⏱️ 20.06.2022):

	```
	git clone https://github.com/jonathanslenders/ptpython
	```
- [PyPi](https://pypi.org/project/ptpython) (📥 500K / month):
	```
	pip install ptpython
	```
- [Conda](https://anaconda.org/conda-forge/ptpython) (📥 19K · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge ptpython
	```
</details>
<details><summary><b><a href="https://github.com/bpython/bpython">bpython</a></b> (🥉19 ·  ⭐ 2.2K) - A fancy interface to the Python interpreter. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/bpython/bpython) (👨‍💻 130 · 🔀 210 · 📋 770 - 16% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/bpython/bpython
	```
- [PyPi](https://pypi.org/project/bpython) (📥 77K / month):
	```
	pip install bpython
	```
- [Conda](https://anaconda.org/conda-forge/bpython) (📥 46K · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge bpython
	```
</details>
<br>

## Internationalization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with i18n._

🔗&nbsp;<b><a href="http://babel.pocoo.org/en/latest/">Babel</a></b>  - An internationalization library for Python.

<details><summary><b><a href="https://github.com/ovalhub/pyicu">PyICU</a></b> (🥇20 ·  ⭐ 130 · 💀) - A wrapper of International Components for Unicode C++ library.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ovalhub/pyicu) (👨‍💻 18 · 🔀 52 · 📦 2.7K · ⏱️ 08.04.2021):

	```
	git clone https://github.com/ovalhub/pyicu
	```
- [PyPi](https://pypi.org/project/pyicu) (📥 180K / month):
	```
	pip install pyicu
	```
- [Conda](https://anaconda.org/conda-forge/pyicu) (📥 100K · ⏱️ 26.04.2022):
	```
	conda install -c conda-forge pyicu
	```
</details>
<br>

## Job Scheduler

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for scheduling jobs._

🔗&nbsp;<b><a href="https://airflow.apache.org/">Airflow</a></b>  - Airflow is a platform to programmatically author, schedule and monitor workflows.

🔗&nbsp;<b><a href="http://apscheduler.readthedocs.io/en/latest/">APScheduler</a></b>  - A light but powerful in-process task scheduler that lets you schedule functions.

🔗&nbsp;<b><a href="http://pydoit.org/">doit</a></b>  - A task runner and build tool.

🔗&nbsp;<b><a href="https://joblib.readthedocs.io/">Joblib</a></b>  - A set of tools to provide lightweight pipelining in Python.

🔗&nbsp;<b><a href="https://docs.openstack.org/developer/taskflow/">TaskFlow</a></b>  - A Python library that helps to make task execution easy, consistent and reliable.

<details><summary><b><a href="https://github.com/dbader/schedule">schedule</a></b> (🥇31 ·  ⭐ 9.9K) - Python job scheduling for humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dbader/schedule) (👨‍💻 51 · 🔀 790 · 📦 20K · 📋 380 - 31% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/dbader/schedule
	```
- [PyPi](https://pypi.org/project/schedule) (📥 2.1M / month):
	```
	pip install schedule
	```
- [Conda](https://anaconda.org/conda-forge/schedule) (📥 20K · ⏱️ 10.04.2021):
	```
	conda install -c conda-forge schedule
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥈28 ·  ⭐ 10K) - A modern workflow orchestration framework that makes it easy to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 68 · 🔀 970 · 📦 1.2K · 📋 2.7K - 21% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 420K / month):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 320K · ⏱️ 14.09.2022):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/sartography/SpiffWorkflow">Spiff</a></b> (🥈21 ·  ⭐ 1.3K) - A powerful workflow engine implemented in pure Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/sartography/SpiffWorkflow) (👨‍💻 49 · 🔀 260 · 📦 41 · 📋 96 - 5% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/knipknap/SpiffWorkflow
	```
- [PyPi](https://pypi.org/project/SpiffWorkflow) (📥 4.1K / month):
	```
	pip install SpiffWorkflow
	```
- [Conda](https://anaconda.org/conda-forge/SpiffWorkflow):
	```
	conda install -c conda-forge SpiffWorkflow
	```
</details>
<details><summary><b><a href="https://github.com/fengsp/plan">Plan</a></b> (🥉17 ·  ⭐ 1.2K · 💀) - Writing crontab file in Python like a charm. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fengsp/plan) (👨‍💻 7 · 🔀 89 · 📦 71 · 📋 9 - 11% open · ⏱️ 14.05.2020):

	```
	git clone https://github.com/fengsp/plan
	```
- [PyPi](https://pypi.org/project/plan) (📥 1.5K / month):
	```
	pip install plan
	```
- [Conda](https://anaconda.org/conda-forge/plan):
	```
	conda install -c conda-forge plan
	```
</details>
<details><summary><b><a href="https://github.com/gunnery/gunnery">gunnery</a></b> (🥉13 ·  ⭐ 750 · 💀) - Multipurpose task execution tool for distributed systems with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gunnery/gunnery) (👨‍💻 7 · 🔀 73 · 📋 37 - 27% open · ⏱️ 29.10.2015):

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
<details><summary><b><a href="https://github.com/thauber/django-schedule">django-schedule</a></b> (🥉11 ·  ⭐ 800 · 💀) - A calendaring app for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/thauber/django-schedule) (👨‍💻 17 · 🔀 190 · 📋 59 - 33% open · ⏱️ 16.04.2016):

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

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for generating and working with logs._

🔗&nbsp;<b><a href="http://logbook.readthedocs.io/en/stable/">logbook</a></b>  - Logging replacement for Python.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/logging.html">logging</a></b>  - (Python standard library) Logging facility for Python.

🔗&nbsp;<b><a href="https://www.structlog.org/en/stable/">structlog</a></b>  - Structured logging made easy.

<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇33 ·  ⭐ 13K) - Library which aims to bring enjoyable logging in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 38 · 🔀 540 · 📦 26K · 📋 630 - 10% open · ⏱️ 21.08.2022):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 3.7M / month):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 660K · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-python</a></b> (🥉28 ·  ⭐ 1.3K) - Sentry SDK for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 140 · 🔀 300 · 📥 4.1K · 📦 24K · 📋 710 - 20% open · ⏱️ 14.09.2022):

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

## Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Machine Learning._

🔗&nbsp;<b><a href="http://scikit-learn.org/">scikit-learn</a></b>  - The most popular Python library for Machine Learning.

🔗&nbsp;<b><a href="http://spark.apache.org/docs/latest/ml-guide.html">Spark ML</a></b>  - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.

<details><summary><b><a href="https://github.com/dmlc/xgboost">xgboost</a></b> (🥇37 ·  ⭐ 23K) - A scalable, portable, and distributed gradient boosting library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 580 · 🔀 7.9K · 📥 5.1K · 📦 36K · 📋 4.5K - 5% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 8.3M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 3M · ⏱️ 01.09.2022):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/openai/gym">gym</a></b> (🥈34 ·  ⭐ 29K) - A toolkit for developing and comparing reinforcement learning.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 380 · 🔀 7.5K · 📦 32K · 📋 1.7K - 0% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 880K / month):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 140K · ⏱️ 10.07.2022):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥈24 ·  ⭐ 6.3K · 💀) - Numenta Platform for Intelligent Computing. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/numenta/nupic) (👨‍💻 120 · 🔀 1.5K · 📦 110 · 📋 1.8K - 25% open · ⏱️ 23.10.2019):

	```
	git clone https://github.com/numenta/nupic
	```
- [PyPi](https://pypi.org/project/nupic) (📥 1.2K / month):
	```
	pip install nupic
	```
- [Conda](https://anaconda.org/conda-forge/nupic):
	```
	conda install -c conda-forge nupic
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/h2o-3">H2O</a></b> (🥉20 ·  ⭐ 6K) - Open Source Fast Scalable Machine Learning Platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/h2oai/h2o-3) (👨‍💻 230 · 🔀 1.9K · ⏱️ 15.09.2022):

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
<details><summary><b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉19 ·  ⭐ 10K) - MindsDB is an open source AI layer for existing databases that.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/mindsdb/mindsdb) (👨‍💻 130 · 🔀 1.1K · 📋 1.3K - 13% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/mindsdb/mindsdb
	```
- [PyPi](https://pypi.org/project/mindsdb) (📥 3.2K / month):
	```
	pip install mindsdb
	```
- [Conda](https://anaconda.org/conda-forge/mindsdb):
	```
	conda install -c conda-forge mindsdb
	```
</details>
<details><summary><b><a href="https://github.com/benhamner/Metrics">Metrics</a></b> (🥉16 ·  ⭐ 1.5K · 💀) - Machine learning evaluation metrics. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/benhamner/Metrics) (👨‍💻 7 · 🔀 410 · 📋 19 - 63% open · ⏱️ 09.09.2015):

	```
	git clone https://github.com/benhamner/Metrics
	```
- [PyPi](https://pypi.org/project/Metrics) (📥 2.6K / month):
	```
	pip install Metrics
	```
- [Conda](https://anaconda.org/conda-forge/Metrics):
	```
	conda install -c conda-forge Metrics
	```
</details>
<details><summary><b><a href="https://github.com/josephreisinger/vowpal_porpoise">vowpal_porpoise</a></b> (🥉9 ·  ⭐ 160 · 💀) - A lightweight Python wrapper for [Vowpal.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/josephreisinger/vowpal_porpoise) (👨‍💻 14 · 🔀 28 · 📋 9 - 66% open · ⏱️ 07.01.2020):

	```
	git clone https://github.com/josephreisinger/vowpal_porpoise
	```
- [PyPi](https://pypi.org/project/vowpal_porpoise) (📥 14 / month):
	```
	pip install vowpal_porpoise
	```
- [Conda](https://anaconda.org/conda-forge/vowpal_porpoise):
	```
	conda install -c conda-forge vowpal_porpoise
	```
</details>
<br>

## Microsoft Windows

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Python programming on Microsoft Windows._

🔗&nbsp;<b><a href="http://python-xy.github.io/">Python(x,y)</a></b>  - Scientific-applications-oriented Python Distribution based on Qt and Spyder.

🔗&nbsp;<b><a href="http://www.lfd.uci.edu/~gohlke/pythonlibs/">pythonlibs</a></b>  - Unofficial Windows binaries for Python extension packages.

🔗&nbsp;<b><a href="https://winpython.github.io/">WinPython</a></b>  - Portable development environment for Windows 7/8.

<details><summary><b><a href="https://github.com/mhammond/pywin32">PyWin32</a></b> (🥇29 ·  ⭐ 3.9K) - Python Extensions for Windows. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mhammond/pywin32) (👨‍💻 80 · 🔀 690 · 📥 570K · 📦 91K · 📋 1.7K - 25% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/mhammond/pywin32
	```
- [PyPi](https://pypi.org/project/pywin32) (📥 3.9M / month):
	```
	pip install pywin32
	```
- [Conda](https://anaconda.org/conda-forge/pywin32) (📥 2.6M · ⏱️ 27.12.2021):
	```
	conda install -c conda-forge pywin32
	```
</details>
<details><summary><b><a href="https://github.com/pythonnet/pythonnet">PythonNet</a></b> (🥉27 ·  ⭐ 3.2K) - Python Integration with the .NET Common Language Runtime (CLR). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pythonnet/pythonnet) (👨‍💻 97 · 🔀 520 · 📥 190 · 📦 100 · 📋 1.2K - 9% open · ⏱️ 17.07.2022):

	```
	git clone https://github.com/pythonnet/pythonnet
	```
- [PyPi](https://pypi.org/project/pythonnet) (📥 110K / month):
	```
	pip install pythonnet
	```
- [Conda](https://anaconda.org/conda-forge/pythonnet) (📥 48K · ⏱️ 16.07.2022):
	```
	conda install -c conda-forge pythonnet
	```
</details>
<br>

## Miscellaneous

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Useful libraries or tools that don't fit in the categories above._

🔗&nbsp;<b><a href="http://www.tryton.org/">tryton</a></b>  - A general purpose business framework.

<details><summary><b><a href="https://github.com/pallets/itsdangerous">itsdangerous</a></b> (🥇33 ·  ⭐ 2.5K) - Various helpers to pass trusted data to untrusted environments. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/itsdangerous) (👨‍💻 41 · 🔀 200 · 📦 670K · ⏱️ 01.09.2022):

	```
	git clone https://github.com/pallets/itsdangerous
	```
- [PyPi](https://pypi.org/project/itsdangerous) (📥 75M / month):
	```
	pip install itsdangerous
	```
- [Conda](https://anaconda.org/conda-forge/itsdangerous) (📥 3.7M · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge itsdangerous
	```
</details>
<details><summary><b><a href="https://github.com/pallets-eco/blinker">blinker</a></b> (🥈29 ·  ⭐ 1.4K) - A fast Python in-process signal/event dispatching system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pallets-eco/blinker) (👨‍💻 14 · 🔀 160 · 📦 120K · 📋 35 - 8% open · ⏱️ 17.07.2022):

	```
	git clone https://github.com/jek/blinker
	```
- [PyPi](https://pypi.org/project/blinker) (📥 8.8M / month):
	```
	pip install blinker
	```
- [Conda](https://anaconda.org/conda-forge/blinker) (📥 6M · ⏱️ 20.06.2018):
	```
	conda install -c conda-forge blinker
	```
</details>
<details><summary><b><a href="https://github.com/mahmoud/boltons">boltons</a></b> (🥉28 ·  ⭐ 5.9K) - A set of pure-Python utilities. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mahmoud/boltons) (👨‍💻 75 · 🔀 320 · 📥 23 · 📦 2.5K · 📋 140 - 31% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/mahmoud/boltons
	```
- [PyPi](https://pypi.org/project/boltons) (📥 2M / month):
	```
	pip install boltons
	```
- [Conda](https://anaconda.org/conda-forge/boltons) (📥 680K · ⏱️ 27.05.2021):
	```
	conda install -c conda-forge boltons
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">magenta</a></b> (🥉27 ·  ⭐ 18K) - A tool to generate music and art using artificial intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.5K · 📦 380 · 📋 890 - 34% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 3.8K / month):
	```
	pip install magenta
	```
- [Conda](https://anaconda.org/conda-forge/magenta):
	```
	conda install -c conda-forge magenta
	```
</details>
<details><summary><b><a href="https://github.com/mitsuhiko/pluginbase">pluginbase</a></b> (🥉22 ·  ⭐ 1K · 💀) - A simple but flexible plugin system for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mitsuhiko/pluginbase) (👨‍💻 9 · 🔀 140 · 📦 1.4K · ⏱️ 16.05.2021):

	```
	git clone https://github.com/mitsuhiko/pluginbase
	```
- [PyPi](https://pypi.org/project/pluginbase) (📥 520K / month):
	```
	pip install pluginbase
	```
- [Conda](https://anaconda.org/conda-forge/pluginbase) (📥 240K · ⏱️ 04.02.2019):
	```
	conda install -c conda-forge pluginbase
	```
</details>
<br>

## Natural Language Processing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with human languages._

🔗&nbsp;<b><a href="http://www.nltk.org/">nltk</a></b>  - A leading platform for building Python programs to work with human language data.

🔗&nbsp;<b><a href="https://spacy.io/">spacy</a></b>  - A library for industrial-strength natural language processing in Python and Cython.

<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇36 ·  ⭐ 14K) - Topic Modeling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 430 · 🔀 4K · 📥 3.8K · 📦 36K · 📋 1.8K - 20% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 4.8M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 880K · ⏱️ 29.07.2022):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/fxsjy/jieba">jieba</a></b> (🥇32 ·  ⭐ 29K · 💀) - The most popular Chinese text segmentation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fxsjy/jieba) (👨‍💻 48 · 🔀 6.3K · 📦 15K · 📋 810 - 73% open · ⏱️ 15.02.2020):

	```
	git clone https://github.com/fxsjy/jieba
	```
- [PyPi](https://pypi.org/project/jieba) (📥 490K / month):
	```
	pip install jieba
	```
- [Conda](https://anaconda.org/conda-forge/jieba) (📥 120K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge jieba
	```
</details>
<details><summary><b><a href="https://github.com/clips/pattern">pattern</a></b> (🥈30 ·  ⭐ 8.3K · 💀) - A web mining module. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/clips/pattern) (👨‍💻 30 · 🔀 1.5K · 📥 11 · 📦 1.4K · 📋 200 - 62% open · ⏱️ 25.04.2020):

	```
	git clone https://github.com/clips/pattern
	```
- [PyPi](https://pypi.org/project/pattern) (📥 2M / month):
	```
	pip install pattern
	```
- [Conda](https://anaconda.org/conda-forge/pattern) (📥 12K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge pattern
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">Stanza</a></b> (🥈25 ·  ⭐ 6.3K) - The Stanford NLP Group's official Python library, supporting 60+.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 54 · 🔀 790 · 📦 1.2K · 📋 720 - 9% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 280K / month):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/conda-forge/stanza) (📥 5.1K · ⏱️ 14.09.2022):
	```
	conda install -c conda-forge stanza
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">PyTorch-NLP</a></b> (🥈24 ·  ⭐ 2.1K · 💀) - A toolkit enabling rapid deep learning NLP prototyping for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 250 · 📦 420 · 📋 67 - 26% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/PyTorch-NLP) (📥 5.1K / month):
	```
	pip install PyTorch-NLP
	```
- [Conda](https://anaconda.org/conda-forge/PyTorch-NLP):
	```
	conda install -c conda-forge PyTorch-NLP
	```
</details>
<details><summary><b><a href="https://github.com/lancopku/pkuseg-python">pkuseg-python</a></b> (🥉23 ·  ⭐ 6K) - A toolkit for Chinese word segmentation in various domains. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lancopku/pkuseg-python) (👨‍💻 6 · 🔀 930 · 📥 86K · 📦 210 · 📋 150 - 73% open · ⏱️ 08.06.2022):

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
<details><summary><b><a href="https://github.com/isnowfy/snownlp">snownlp</a></b> (🥉22 ·  ⭐ 5.9K · 💀) - A library for processing Chinese text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isnowfy/snownlp) (👨‍💻 8 · 🔀 1.3K · 📦 940 · 📋 100 - 38% open · ⏱️ 19.01.2020):

	```
	git clone https://github.com/isnowfy/snownlp
	```
- [PyPi](https://pypi.org/project/snownlp) (📥 3.7K / month):
	```
	pip install snownlp
	```
- [Conda](https://anaconda.org/conda-forge/snownlp) (📥 960 · ⏱️ 07.09.2021):
	```
	conda install -c conda-forge snownlp
	```
</details>
<details><summary><b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉21 ·  ⭐ 2K · 💀) - Natural language pipeline supporting hundreds of languages. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/aboSamoor/polyglot) (👨‍💻 26 · 🔀 310 · 📦 760 · 📋 210 - 68% open · ⏱️ 22.09.2020):

	```
	git clone https://github.com/aboSamoor/polyglot
	```
- [PyPi](https://pypi.org/project/polyglot) (📥 54K / month):
	```
	pip install polyglot
	```
- [Conda](https://anaconda.org/conda-forge/polyglot):
	```
	conda install -c conda-forge polyglot
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">pytext</a></b> (🥉18 ·  ⭐ 6.3K) - A natural language modeling framework based on PyTorch. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 230 · 🔀 790 · 📥 300 · 📦 110 · 📋 140 - 45% open · ⏱️ 07.09.2022):

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
<details><summary><b><a href="https://github.com/saffsd/langid.py">langid.py</a></b> (🥉17 ·  ⭐ 2K · 💀) - Stand-alone language identification system. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/saffsd/langid.py) (👨‍💻 9 · 🔀 280 · 📦 1.1K · 📋 71 - 35% open · ⏱️ 15.07.2017):

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
<details><summary><b><a href="https://github.com/fighting41love/funNLP">funNLP</a></b> (🥉15 ·  ⭐ 43K) - A collection of tools and datasets for Chinese NLP. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fighting41love/funNLP) (👨‍💻 10 · 🔀 11K · 📋 51 - 19% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/fighting41love/funNLP
	```
- [PyPi](https://pypi.org/project/funNLP) (📥 11 / month):
	```
	pip install funNLP
	```
- [Conda](https://anaconda.org/conda-forge/funNLP):
	```
	conda install -c conda-forge funNLP
	```
</details>
<br>

## Network Virtualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools and libraries for Virtual Networking and SDN (Software Defined Networking)._

<details><summary><b><a href="https://github.com/napalm-automation/napalm">napalm</a></b> (🥇30 ·  ⭐ 1.9K) - Cross-vendor API to manipulate network devices. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/napalm-automation/napalm) (👨‍💻 190 · 🔀 500 · 📦 910 · 📋 570 - 20% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/napalm-automation/napalm
	```
- [PyPi](https://pypi.org/project/napalm) (📥 33K / month):
	```
	pip install napalm
	```
- [Conda](https://anaconda.org/conda-forge/napalm):
	```
	conda install -c conda-forge napalm
	```
</details>
<details><summary><b><a href="https://github.com/mininet/mininet">mininet</a></b> (🥉26 ·  ⭐ 4.5K) - A popular network emulator and API written in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mininet/mininet) (👨‍💻 80 · 🔀 1.6K · 📥 460K · 📦 160 · 📋 670 - 39% open · ⏱️ 11.07.2022):

	```
	git clone https://github.com/mininet/mininet
	```
- [PyPi](https://pypi.org/project/mininet) (📥 1.1K / month):
	```
	pip install mininet
	```
- [Conda](https://anaconda.org/conda-forge/mininet):
	```
	conda install -c conda-forge mininet
	```
</details>
<details><summary><b><a href="https://github.com/noxrepo/pox">pox</a></b> (🥉21 ·  ⭐ 580 · 💀) - A Python-based SDN control applications, such as OpenFlow SDN.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/noxrepo/pox) (👨‍💻 26 · 🔀 430 · 📋 180 - 20% open · ⏱️ 20.05.2020):

	```
	git clone https://github.com/noxrepo/pox
	```
- [PyPi](https://pypi.org/project/pox) (📥 3.8M / month):
	```
	pip install pox
	```
- [Conda](https://anaconda.org/conda-forge/pox) (📥 220K · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge pox
	```
</details>
<br>

## News Feed

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building user's activities._

<details><summary><b><a href="https://github.com/justquick/django-activity-stream">django-activity-stream</a></b> (🥇25 ·  ⭐ 2.1K) - Generating generic activity streams from the actions.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/justquick/django-activity-stream) (👨‍💻 110 · 🔀 450 · 📦 870 · 📋 300 - 4% open · ⏱️ 18.08.2022):

	```
	git clone https://github.com/justquick/django-activity-stream
	```
- [PyPi](https://pypi.org/project/django-activity-stream) (📥 43K / month):
	```
	pip install django-activity-stream
	```
- [Conda](https://anaconda.org/conda-forge/django-activity-stream):
	```
	conda install -c conda-forge django-activity-stream
	```
</details>
<details><summary><b><a href="https://github.com/tschellenbach/Stream-Framework">Stream Framework</a></b> (🥉18 ·  ⭐ 4.6K · 💀) - Building news feed and notification systems using.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/tschellenbach/Stream-Framework) (👨‍💻 26 · 🔀 530 · 📋 180 - 35% open · ⏱️ 15.07.2020):

	```
	git clone https://github.com/tschellenbach/Stream-Framework
	```
- [PyPi](https://pypi.org/project/Stream-Framework) (📥 1.7K / month):
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

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that implement Object-Relational Mapping or data mapping techniques._

🔗&nbsp;<b><a href="https://docs.djangoproject.com/en/dev/topics/db/models/">Django Models</a></b>  - The Django ORM.

🔗&nbsp;<b><a href="https://www.sqlalchemy.org/">SQLAlchemy</a></b>  - The Python SQL Toolkit and Object Relational Mapper.

🔗&nbsp;<b><a href="https://github.com/dahlia/awesome-sqlalchemy">awesome-sqlalchemy</a></b> ( ⭐ 2.5K · 💀)  - A curated list of awesome tools for SQLAlchemy.

<details><summary><b><a href="https://github.com/coleifer/peewee">peewee</a></b> (🥇35 ·  ⭐ 9.4K · 📈) - A small, expressive ORM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/peewee) (👨‍💻 150 · 🔀 1.3K · 📦 17K · ⏱️ 14.09.2022):

	```
	git clone https://github.com/coleifer/peewee
	```
- [PyPi](https://pypi.org/project/peewee) (📥 1.3M / month):
	```
	pip install peewee
	```
- [Conda](https://anaconda.org/conda-forge/peewee) (📥 420K · ⏱️ 12.07.2022):
	```
	conda install -c conda-forge peewee
	```
</details>
<details><summary><b><a href="https://github.com/MongoEngine/mongoengine">mongoengine</a></b> (🥇35 ·  ⭐ 3.8K) - A Python Object-Document-Mapper for working with MongoDB. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MongoEngine/mongoengine) (👨‍💻 380 · 🔀 1.1K · 📦 18K · 📋 1.6K - 21% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/MongoEngine/mongoengine
	```
- [PyPi](https://pypi.org/project/mongoengine) (📥 790K / month):
	```
	pip install mongoengine
	```
- [Conda](https://anaconda.org/conda-forge/mongoengine) (📥 170K · ⏱️ 18.07.2022):
	```
	conda install -c conda-forge mongoengine
	```
</details>
<details><summary><b><a href="https://github.com/pynamodb/PynamoDB">PynamoDB</a></b> (🥈29 ·  ⭐ 2K) - A Pythonic interface for [Amazon.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pynamodb/PynamoDB) (👨‍💻 97 · 🔀 390 · 📦 1.1K · 📋 510 - 39% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/pynamodb/PynamoDB
	```
- [PyPi](https://pypi.org/project/PynamoDB) (📥 1.4M / month):
	```
	pip install PynamoDB
	```
- [Conda](https://anaconda.org/conda-forge/PynamoDB) (📥 200K · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge PynamoDB
	```
</details>
<details><summary><b><a href="https://github.com/pudo/dataset">dataset</a></b> (🥈26 ·  ⭐ 4.2K) - Store Python dicts in a database - works with SQLite, MySQL, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pudo/dataset) (👨‍💻 76 · 🔀 280 · 📦 2.5K · 📋 270 - 4% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/pudo/dataset
	```
- [PyPi](https://pypi.org/project/dataset) (📥 54K / month):
	```
	pip install dataset
	```
- [Conda](https://anaconda.org/conda-forge/dataset) (📥 2.9K · ⏱️ 16.12.2021):
	```
	conda install -c conda-forge dataset
	```
</details>
<details><summary><b><a href="https://github.com/sdispater/orator">orator</a></b> (🥉22 ·  ⭐ 1.4K) - The Orator ORM provides a simple yet beautiful ActiveRecord implementation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sdispater/orator) (👨‍💻 32 · 🔀 160 · 📋 310 - 42% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/sdispater/orator
	```
- [PyPi](https://pypi.org/project/orator) (📥 14K / month):
	```
	pip install orator
	```
- [Conda](https://anaconda.org/conda-forge/orator) (📥 2K · ⏱️ 18.03.2020):
	```
	conda install -c conda-forge orator
	```
</details>
<details><summary><b><a href="https://github.com/ponyorm/pony">pony</a></b> (🥉20 ·  ⭐ 3K) - ORM that provides a generator-oriented interface to SQL. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ponyorm/pony) (🔀 210 · 📥 32 · 📦 2.6K · 📋 590 - 45% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/ponyorm/pony/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/web2py/pydal">pydal</a></b> (🥉19 ·  ⭐ 430) - A pure Python Database Abstraction Layer. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/web2py/pydal) (🔀 130 · 📦 230 · 📋 310 - 44% open · ⏱️ 20.08.2022):

	```
	git clone https://github.com/web2py/pydal/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/encode/orm">orm</a></b> (🥉18 ·  ⭐ 1.6K) - An async ORM. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/orm) (👨‍💻 18 · 🔀 92 · 📋 78 - 19% open · ⏱️ 30.08.2022):

	```
	git clone https://github.com/encode/orm
	```
- [PyPi](https://pypi.org/project/orm) (📥 5.5K / month):
	```
	pip install orm
	```
- [Conda](https://anaconda.org/conda-forge/orm):
	```
	conda install -c conda-forge orm
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/hot-redis">hot-redis</a></b> (🥉16 ·  ⭐ 280 · 💀) - Rich Python data types for Redis. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/hot-redis) (👨‍💻 6 · 🔀 29 · 📦 26 · 📋 11 - 54% open · ⏱️ 16.10.2018):

	```
	git clone https://github.com/stephenmcd/hot-redis
	```
- [PyPi](https://pypi.org/project/hot-redis) (📥 300 / month):
	```
	pip install hot-redis
	```
- [Conda](https://anaconda.org/conda-forge/hot-redis):
	```
	conda install -c conda-forge hot-redis
	```
</details>
<details><summary><b><a href="https://github.com/kiddouk/redisco">redisco</a></b> (🥉14 ·  ⭐ 440 · 💀) - A Python Library for Simple Models and Containers Persisted in Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kiddouk/redisco) (👨‍💻 20 · 🔀 83 · 📋 51 - 70% open · ⏱️ 06.06.2016):

	```
	git clone https://github.com/kiddouk/redisco
	```
- [PyPi](https://pypi.org/project/redisco) (📥 470 / month):
	```
	pip install redisco
	```
- [Conda](https://anaconda.org/conda-forge/redisco):
	```
	conda install -c conda-forge redisco
	```
</details>
<br>

## Package Management

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for package and dependency management._

🔗&nbsp;<b><a href="https://pip.pypa.io/en/stable/">pip</a></b>  - The package installer for Python.

🔗&nbsp;<b><a href="https://pypi.org/">PyPI</a></b>  

<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥇30 ·  ⭐ 22K) - Python dependency management and packaging made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 390 · 🔀 1.7K · 📥 14M · 📋 4.2K - 20% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/sdispater/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 8.5M / month):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 610K · ⏱️ 31.08.2022):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥉28 ·  ⭐ 6.2K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 170 · 🔀 460 · 📋 850 - 13% open · ⏱️ 22.08.2022):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 6.9M / month):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 52K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥉15 ·  ⭐ 4.9K) - Cross-platform, Python-agnostic binary package manager. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/conda/conda) (🔀 1.2K · 📋 8.6K - 10% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/conda/conda/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Package Repositories

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Local PyPI repository server and proxies._

<details><summary><b><a href="https://github.com/devpi/devpi">devpi</a></b> (🥇19 ·  ⭐ 600) - PyPI server and packaging/testing/release tool. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/devpi/devpi) (👨‍💻 87 · 🔀 110 · 📦 190 · 📋 700 - 10% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/devpi/devpi
	```
- [PyPi](https://pypi.org/project/devpi) (📥 2.3K / month):
	```
	pip install devpi
	```
- [Conda](https://anaconda.org/conda-forge/devpi):
	```
	conda install -c conda-forge devpi
	```
</details>
<details><summary><b><a href="https://github.com/mvantellingen/localshop">localshop</a></b> (🥈16 ·  ⭐ 380) - Local PyPI server (custom packages and auto-mirroring of pypi). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mvantellingen/localshop) (👨‍💻 46 · 🔀 110 · 📦 4 · 📋 110 - 30% open · ⏱️ 17.07.2022):

	```
	git clone https://github.com/jazzband/localshop
	```
- [PyPi](https://pypi.org/project/localshop) (📥 86 / month):
	```
	pip install localshop
	```
- [Conda](https://anaconda.org/conda-forge/localshop):
	```
	conda install -c conda-forge localshop
	```
</details>
<details><summary><b><a href="https://github.com/pypi/warehouse">warehouse</a></b> (🥉15 ·  ⭐ 3K) - Next generation Python Package Repository (PyPI). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypi/warehouse) (👨‍💻 320 · 🔀 770 · 📋 2.7K - 14% open · ⏱️ 14.09.2022):

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
<details><summary><b><a href="https://github.com/pypa/bandersnatch">bandersnatch</a></b> (🥉13 ·  ⭐ 320) - PyPI mirroring tool provided by Python Packaging Authority.. <code><a href="https://tldrlegal.com/search?q=AFL-3.0">❗️AFL-3.0</a></code></summary>

- [GitHub](https://github.com/pypa/bandersnatch) (🔀 97 · 📋 210 - 16% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/pypa/bandersnatch/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Penetration Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Frameworks and tools for penetration testing._

<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥇22 ·  ⭐ 25K) - Automatic SQL injection and database takeover tool. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 120 · 🔀 4.8K · 📋 4.8K - 1% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 6.3K / month):
	```
	pip install sqlmap
	```
- [Conda](https://anaconda.org/conda-forge/sqlmap):
	```
	conda install -c conda-forge sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/Manisso/fsociety">fsociety</a></b> (🥉19 ·  ⭐ 7.9K) - A Penetration testing framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Manisso/fsociety) (👨‍💻 22 · 🔀 1.6K · 📋 120 - 21% open · ⏱️ 06.09.2022):

	```
	git clone https://github.com/Manisso/fsociety
	```
- [PyPi](https://pypi.org/project/fsociety) (📥 730 / month):
	```
	pip install fsociety
	```
- [Conda](https://anaconda.org/conda-forge/fsociety):
	```
	conda install -c conda-forge fsociety
	```
</details>
<details><summary><b><a href="https://github.com/trustedsec/social-engineer-toolkit">setoolkit</a></b> (🥉17 ·  ⭐ 8K · 💤) - A toolkit for social engineering. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/trustedsec/social-engineer-toolkit) (👨‍💻 85 · 🔀 2.2K · 📋 820 - 25% open · ⏱️ 26.01.2022):

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

## Permissions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that allow or deny users access to data or functionality._

<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥇27 ·  ⭐ 3.3K) - Implementation of per object permissions for Django.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 520 · 📦 5K · 📋 440 - 27% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 210K / month):
	```
	pip install django-guardian
	```
- [Conda](https://anaconda.org/conda-forge/django-guardian) (📥 39K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/dfunckt/django-rules">django-rules</a></b> (🥉22 ·  ⭐ 1.5K) - A tiny but powerful app providing object-level permissions to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dfunckt/django-rules) (👨‍💻 25 · 🔀 120 · 📦 930 · 📋 100 - 22% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/dfunckt/django-rules
	```
- [PyPi](https://pypi.org/project/django-rules) (📥 140 / month):
	```
	pip install django-rules
	```
- [Conda](https://anaconda.org/conda-forge/django-rules):
	```
	conda install -c conda-forge django-rules
	```
</details>
<br>

## Processes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for starting and communicating with OS processes._

🔗&nbsp;<b><a href="https://sarge.readthedocs.io/en/latest/">sarge</a></b>  - Yet another wrapper for subprocess.

<details><summary><b><a href="https://github.com/amoffat/sh">sh</a></b> (🥇31 ·  ⭐ 6.4K) - A full-fledged subprocess replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amoffat/sh) (👨‍💻 85 · 🔀 450 · 📦 10K · 📋 420 - 2% open · ⏱️ 18.08.2022):

	```
	git clone https://github.com/amoffat/sh
	```
- [PyPi](https://pypi.org/project/sh) (📥 3.4M / month):
	```
	pip install sh
	```
- [Conda](https://anaconda.org/conda-forge/sh) (📥 140K · ⏱️ 20.06.2022):
	```
	conda install -c conda-forge sh
	```
</details>
<details><summary><b><a href="https://github.com/amitt001/delegator.py">delegator.py</a></b> (🥉17 ·  ⭐ 1.6K · 💀) - .. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amitt001/delegator.py) (👨‍💻 23 · 🔀 83 · 📋 45 - 17% open · ⏱️ 06.05.2019):

	```
	git clone https://github.com/amitt001/delegator.py
	```
- [PyPi](https://pypi.org/project/delegator.py) (📥 38K / month):
	```
	pip install delegator.py
	```
- [Conda](https://anaconda.org/conda-forge/delegator.py):
	```
	conda install -c conda-forge delegator.py
	```
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building recommender systems._

<details><summary><b><a href="https://github.com/spotify/annoy">annoy</a></b> (🥇31 ·  ⭐ 10K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 82 · 🔀 1K · 📦 2.3K · 📋 350 - 10% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 1.3M / month):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/annoy):
	```
	conda install -c conda-forge annoy
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥈26 ·  ⭐ 4.1K) - A Python implementation of a number of popular recommendation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 630 · 📦 800 · 📋 460 - 24% open · ⏱️ 19.07.2022):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 330K / month):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 130K · ⏱️ 09.03.2022):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥈26 ·  ⭐ 2.9K) - A fast Python implementation of collaborative filtering for implicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 32 · 🔀 540 · 📥 120 · 📦 660 · 📋 430 - 16% open · ⏱️ 31.08.2022):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 160K / month):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 400K · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/NicolasHug/Surprise">Surprise</a></b> (🥉20 ·  ⭐ 5.5K) - A scikit for building and analyzing recommender systems. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NicolasHug/Surprise) (👨‍💻 43 · 🔀 920 · 📋 350 - 16% open · ⏱️ 29.08.2022):

	```
	git clone https://github.com/NicolasHug/Surprise
	```
- [PyPi](https://pypi.org/project/Surprise) (📥 18K / month):
	```
	pip install Surprise
	```
- [Conda](https://anaconda.org/conda-forge/Surprise):
	```
	conda install -c conda-forge Surprise
	```
</details>
<details><summary><b><a href="https://github.com/maciejkula/spotlight">spotlight</a></b> (🥉19 ·  ⭐ 2.8K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maciejkula/spotlight) (👨‍💻 11 · 🔀 400 · 📋 110 - 56% open · ⏱️ 09.02.2020):

	```
	git clone https://github.com/maciejkula/spotlight
	```
- [PyPi](https://pypi.org/project/spotlight) (📥 430 / month):
	```
	pip install spotlight
	```
- [Conda](https://anaconda.org/conda-forge/spotlight):
	```
	conda install -c conda-forge spotlight
	```
</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉19 ·  ⭐ 1K · 💀) - A library for Factorization Machines. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ibayer/fastFM) (👨‍💻 20 · 🔀 200 · 📥 450 · 📦 98 · 📋 110 - 43% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/ibayer/fastFM
	```
- [PyPi](https://pypi.org/project/fastFM) (📥 360 / month):
	```
	pip install fastFM
	```
- [Conda](https://anaconda.org/conda-forge/fastFM):
	```
	conda install -c conda-forge fastFM
	```
</details>
<details><summary><b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉18 ·  ⭐ 1.2K · 💀) - A Recommendation Engine Framework in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jfkirk/tensorrec) (👨‍💻 9 · 🔀 220 · 📦 27 · 📋 130 - 28% open · ⏱️ 04.02.2020):

	```
	git clone https://github.com/jfkirk/tensorrec
	```
- [PyPi](https://pypi.org/project/tensorrec) (📥 610 / month):
	```
	pip install tensorrec
	```
- [Conda](https://anaconda.org/conda-forge/tensorrec):
	```
	conda install -c conda-forge tensorrec
	```
</details>
<details><summary><b><a href="https://github.com/ycjuan/libffm">libffm</a></b> (🥉12 ·  ⭐ 1.6K · 💀) - A library for Field-aware Factorization Machine (FFM). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ycjuan/libffm) (👨‍💻 5 · 🔀 420 · 📋 36 - 55% open · ⏱️ 22.02.2019):

	```
	git clone https://github.com/guestwalk/libffm
	```
- [PyPi](https://pypi.org/project/libffm) (📥 1 / month):
	```
	pip install libffm
	```
- [Conda](https://anaconda.org/conda-forge/libffm):
	```
	conda install -c conda-forge libffm
	```
</details>
<br>

## Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Refactoring tools and libraries for Python_

🔗&nbsp;<b><a href="http://bicyclerepair.sourceforge.net/">Bicycle Repair Man</a></b>  - Bicycle Repair Man, a refactoring tool for Python.

🔗&nbsp;<b><a href="https://pybowler.io/">Bowler</a></b>  - Safe code refactoring for modern Python.

<details><summary><b><a href="https://github.com/python-rope/rope">Rope</a></b> (🥇22 ·  ⭐ 1.4K) - Rope is a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 70 · 🔀 140 · 📋 240 - 29% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 720K / month):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 830K · ⏱️ 29.07.2022):
	```
	conda install -c conda-forge rope
	```
</details>
<br>

## RESTful API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building RESTful APIs._

🔗&nbsp;<b><a href="http://www.django-rest-framework.org/">django-rest-framework</a></b>  - A powerful and flexible toolkit to build web APIs.

🔗&nbsp;<b><a href="http://tastypieapi.org/">django-tastypie</a></b>  - Creating delicious APIs for Django apps.

🔗&nbsp;<b><a href="https://vibora.io/">vibora</a></b>  - Fast, efficient and asynchronous Web framework inspired by Flask.

<details><summary><b><a href="https://github.com/falconry/falcon">falcon</a></b> (🥇33 ·  ⭐ 8.9K · 📉) - A high-performance framework for building cloud APIs and web app.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/falconry/falcon) (👨‍💻 190 · 🔀 860 · 📥 3.9K · 📦 7K · 📋 970 - 17% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/falconry/falcon
	```
- [PyPi](https://pypi.org/project/falcon) (📥 620K / month):
	```
	pip install falcon
	```
- [Conda](https://anaconda.org/conda-forge/falcon) (📥 270K · ⏱️ 09.04.2022):
	```
	conda install -c conda-forge falcon
	```
</details>
<details><summary><b><a href="https://github.com/flask-restful/flask-restful">flask-restful</a></b> (🥇33 ·  ⭐ 6.5K) - Quickly building REST APIs for Flask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/flask-restful/flask-restful) (👨‍💻 160 · 🔀 970 · 📦 81K · 📋 540 - 16% open · ⏱️ 04.03.2022):

	```
	git clone https://github.com/flask-restful/flask-restful
	```
- [PyPi](https://pypi.org/project/flask-restful) (📥 1.3M / month):
	```
	pip install flask-restful
	```
- [Conda](https://anaconda.org/conda-forge/flask-restful) (📥 130K · ⏱️ 30.05.2021):
	```
	conda install -c conda-forge flask-restful
	```
</details>
<details><summary><b><a href="https://github.com/sanic-org/sanic">sanic</a></b> (🥈32 ·  ⭐ 16K) - A Python 3.6+ web server and web framework that's written to go fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sanic-org/sanic) (👨‍💻 320 · 🔀 1.4K · 📦 7.6K · 📋 1.2K - 4% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/huge-success/sanic
	```
- [PyPi](https://pypi.org/project/sanic) (📥 920K / month):
	```
	pip install sanic
	```
- [Conda](https://anaconda.org/conda-forge/sanic) (📥 220K · ⏱️ 11.08.2022):
	```
	conda install -c conda-forge sanic
	```
</details>
<details><summary><b><a href="https://github.com/tiangolo/fastapi">fastapi</a></b> (🥈30 ·  ⭐ 49K) - A modern, fast, web framework for building APIs with Python 3.6+ based on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tiangolo/fastapi) (👨‍💻 390 · 🔀 3.9K · 📋 3.1K - 35% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/tiangolo/fastapi
	```
- [PyPi](https://pypi.org/project/fastapi) (📥 8.6M / month):
	```
	pip install fastapi
	```
- [Conda](https://anaconda.org/conda-forge/fastapi) (📥 930K · ⏱️ 15.09.2022):
	```
	conda install -c conda-forge fastapi
	```
</details>
<details><summary><b><a href="https://github.com/hugapi/hug">hug</a></b> (🥉28 ·  ⭐ 6.7K · 💀) - A Python 3 framework for cleanly exposing APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hugapi/hug) (👨‍💻 120 · 🔀 370 · 📦 1.5K · 📋 460 - 35% open · ⏱️ 10.08.2020):

	```
	git clone https://github.com/hugapi/hug
	```
- [PyPi](https://pypi.org/project/hug) (📥 46K / month):
	```
	pip install hug
	```
- [Conda](https://anaconda.org/conda-forge/hug) (📥 160K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge hug
	```
</details>
<details><summary><b><a href="https://github.com/flask-api/flask-api">flask-api</a></b> (🥉26 ·  ⭐ 1.3K) - Browsable Web APIs for Flask. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/flask-api/flask-api) (👨‍💻 32 · 🔀 170 · 📦 5.3K · 📋 63 - 19% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/flask-api/flask-api
	```
- [PyPi](https://pypi.org/project/flask-api) (📥 280K / month):
	```
	pip install flask-api
	```
- [Conda](https://anaconda.org/conda-forge/flask-api):
	```
	conda install -c conda-forge flask-api
	```
</details>
<details><summary><b><a href="https://github.com/pyeve/eve">eve</a></b> (🥉25 ·  ⭐ 6.5K) - REST API framework powered by Flask, MongoDB and good intentions. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyeve/eve) (👨‍💻 210 · 🔀 730 · 📦 1K · 📋 960 - 2% open · ⏱️ 07.09.2022):

	```
	git clone https://github.com/pyeve/eve
	```
- [PyPi](https://pypi.org/project/eve) (📥 23K / month):
	```
	pip install eve
	```
- [Conda](https://anaconda.org/conda-forge/eve):
	```
	conda install -c conda-forge eve
	```
</details>
<details><summary><b><a href="https://github.com/encode/apistar">apistar</a></b> (🥉24 ·  ⭐ 5.6K · 💀) - A smart Web API framework, designed for Python 3. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/encode/apistar) (👨‍💻 89 · 🔀 420 · 📦 680 · 📋 310 - 7% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/encode/apistar
	```
- [PyPi](https://pypi.org/project/apistar) (📥 11K / month):
	```
	pip install apistar
	```
- [Conda](https://anaconda.org/conda-forge/apistar) (📥 100K · ⏱️ 03.04.2019):
	```
	conda install -c conda-forge apistar
	```
</details>
<details><summary><b><a href="https://github.com/Cornices/cornice">cornice</a></b> (🥉23 ·  ⭐ 370) - A RESTful framework for Pyramid. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Cornices/cornice) (👨‍💻 120 · 🔀 140 · 📦 750 · 📋 240 - 19% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/Cornices/cornice
	```
- [PyPi](https://pypi.org/project/cornice) (📥 25K / month):
	```
	pip install cornice
	```
- [Conda](https://anaconda.org/conda-forge/cornice):
	```
	conda install -c conda-forge cornice
	```
</details>
<details><summary><b><a href="https://github.com/jeffknupp/sandman2">sandman2</a></b> (🥉20 ·  ⭐ 1.9K · 💀) - Automated REST APIs for existing database-driven systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jeffknupp/sandman2) (👨‍💻 23 · 🔀 210 · 📦 22 · 📋 83 - 37% open · ⏱️ 21.12.2020):

	```
	git clone https://github.com/jeffknupp/sandman2
	```
- [PyPi](https://pypi.org/project/sandman2) (📥 240 / month):
	```
	pip install sandman2
	```
- [Conda](https://anaconda.org/conda-forge/sandman2):
	```
	conda install -c conda-forge sandman2
	```
</details>
<br>

## Robotics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for robotics._

🔗&nbsp;<b><a href="http://wiki.ros.org/rospy">rospy</a></b>  - This is a library for ROS (Robot Operating System).

<details><summary><b><a href="https://github.com/AtsushiSakai/PythonRobotics">PythonRobotics</a></b> (🥇17 ·  ⭐ 16K) - This is a compilation of various robotics algorithms.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/AtsushiSakai/PythonRobotics) (👨‍💻 100 · 🔀 4.9K · 📋 300 - 5% open · ⏱️ 12.09.2022):

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

## RPC Servers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_RPC-compatible servers._

<details><summary><b><a href="https://github.com/0rpc/zerorpc-python">zeroRPC</a></b> (🥇16 ·  ⭐ 3K · 💤) - zerorpc is a flexible RPC implementation based on.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/0rpc/zerorpc-python) (👨‍💻 38 · 🔀 360 · 📋 160 - 30% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/0rpc/zerorpc-python
	```
- [PyPi](https://pypi.org/project/zerorpc-python):
	```
	pip install zerorpc-python
	```
- [Conda](https://anaconda.org/conda-forge/zerorpc-python) (📥 1.1K · ⏱️ 06.06.2022):
	```
	conda install -c conda-forge zerorpc-python
	```
</details>
<br>

## Science

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for scientific computing._

🔗&nbsp;<b><a href="http://www.astropy.org/">astropy</a></b>  - A community Python library for Astronomy.

🔗&nbsp;<b><a href="http://biopython.org/wiki/Main_Page">Biopython</a></b>  - Biopython is a set of freely available tools for biological computation.

🔗&nbsp;<b><a href="http://cclib.github.io/">cclib</a></b>  - A library for parsing and interpreting the results of computational chemistry packages.

🔗&nbsp;<b><a href="http://colour-science.org/">Colour</a></b>  - Implementing a comprehensive number of colour theory transformations and algorithms.

🔗&nbsp;<b><a href="https://networkx.github.io/">NetworkX</a></b>  - A high-productivity software for complex networks.

🔗&nbsp;<b><a href="http://nipy.org">NIPY</a></b>  - A collection of neuroimaging toolkits.

🔗&nbsp;<b><a href="http://www.numpy.org/">NumPy</a></b>  - A fundamental package for scientific computing with Python.

🔗&nbsp;<b><a href="http://openbabel.org/wiki/Main_Page">Open Babel</a></b>  - A chemical toolbox designed to speak the many languages of chemical data.

🔗&nbsp;<b><a href="http://www.pydy.org/">PyDy</a></b>  - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.

🔗&nbsp;<b><a href="http://qutip.org/">QuTiP</a></b>  - Quantum Toolbox in Python.

🔗&nbsp;<b><a href="http://www.rdkit.org/">RDKit</a></b>  - Cheminformatics and Machine Learning Software.

🔗&nbsp;<b><a href="https://www.scipy.org/">SciPy</a></b>  - A Python-based ecosystem of open-source software for mathematics, science, and engineering.

🔗&nbsp;<b><a href="https://gitlab.com/team-simpy/simpy">SimPy</a></b>  - A process-based discrete-event simulation framework.

<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇35 ·  ⭐ 9.6K) - A Python library for symbolic mathematics. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.2K · 🔀 3.6K · 📥 460K · 📦 46K · 📋 12K - 32% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 2.7M / month):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 2.4M · ⏱️ 23.08.2022):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">statsmodels</a></b> (🥈32 ·  ⭐ 7.7K) - Statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 380 · 🔀 2.4K · 📥 26 · 📦 70K · 📋 4.8K - 46% open · ⏱️ 27.08.2022):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 9.2M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 7.2M · ⏱️ 09.06.2022):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/zipline">Zipline</a></b> (🥈30 ·  ⭐ 15K · 💀) - A Pythonic algorithmic trading library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/zipline) (👨‍💻 160 · 🔀 4K · 📦 880 · 📋 970 - 32% open · ⏱️ 14.10.2020):

	```
	git clone https://github.com/quantopian/zipline
	```
- [PyPi](https://pypi.org/project/zipline) (📥 2.9K / month):
	```
	pip install zipline
	```
- [Conda](https://anaconda.org/conda-forge/zipline) (📥 6.3K · ⏱️ 05.10.2020):
	```
	conda install -c conda-forge zipline
	```
</details>
<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC</a></b> (🥉26 ·  ⭐ 7K) - Markov Chain Monte Carlo sampling toolkit. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pymc-devs/pymc) (👨‍💻 410 · 🔀 1.6K · 📥 1.9K · 📦 720 · 📋 2.8K - 5% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/pymc-devs/pymc3
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 380K / month):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 450K · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥉23 ·  ⭐ 1.7K) - Unsupervised machine learning toolbox for graph structured data. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/karateclub) (👨‍💻 16 · 🔀 210 · 📦 100 · ⏱️ 04.09.2022):

	```
	git clone https://github.com/benedekrozemberczki/karateclub
	```
- [PyPi](https://pypi.org/project/karateclub) (📥 2.7K / month):
	```
	pip install karateclub
	```
- [Conda](https://anaconda.org/conda-forge/karateclub) (📥 12K · ⏱️ 28.01.2022):
	```
	conda install -c conda-forge karateclub
	```
</details>
<details><summary><b><a href="https://github.com/bcbio/bcbio-nextgen">bcbio-nextgen</a></b> (🥉21 ·  ⭐ 900) - Providing best-practice pipelines for fully automated high.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bcbio/bcbio-nextgen) (👨‍💻 93 · 🔀 340 · 📋 3K - 3% open · ⏱️ 06.07.2022):

	```
	git clone https://github.com/chapmanb/bcbio-nextgen
	```
- [PyPi](https://pypi.org/project/bcbio-nextgen) (📥 180 / month):
	```
	pip install bcbio-nextgen
	```
- [Conda](https://anaconda.org/conda-forge/bcbio-nextgen):
	```
	conda install -c conda-forge bcbio-nextgen
	```
</details>
<details><summary><b><a href="https://github.com/chapmanb/bcbb">bccb</a></b> (🥉18 ·  ⭐ 550 · 💤) - Collection of useful code related to biological analysis. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/chapmanb/bcbb) (👨‍💻 32 · 🔀 220 · 📦 230 · 📋 73 - 19% open · ⏱️ 18.11.2021):

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
<details><summary><b><a href="https://github.com/obspy/obspy">ObsPy</a></b> (🥉17 ·  ⭐ 940) - A Python toolbox for seismology. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/obspy/obspy) (🔀 480 · 📥 6.7K · 📋 1.6K - 16% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/obspy/obspy/wiki/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Search

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and software for indexing and performing search queries on data._

🔗&nbsp;<b><a href="https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html">elasticsearch-py</a></b>  - The official low-level Python client for..

🔗&nbsp;<b><a href="http://whoosh.readthedocs.io/en/latest/">whoosh</a></b>  - A fast, pure Python search engine library.

<details><summary><b><a href="https://github.com/django-haystack/django-haystack">django-haystack</a></b> (🥇30 ·  ⭐ 3.3K) - Modular search for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-haystack/django-haystack) (👨‍💻 200 · 🔀 1.2K · 📦 8.2K · 📋 1.2K - 36% open · ⏱️ 27.07.2022):

	```
	git clone https://github.com/django-haystack/django-haystack
	```
- [PyPi](https://pypi.org/project/django-haystack) (📥 110K / month):
	```
	pip install django-haystack
	```
- [Conda](https://anaconda.org/conda-forge/django-haystack) (📥 4.8K · ⏱️ 31.05.2018):
	```
	conda install -c conda-forge django-haystack
	```
</details>
<details><summary><b><a href="https://github.com/django-haystack/pysolr">pysolr</a></b> (🥉27 ·  ⭐ 620) - A lightweight Python wrapper for [Apache.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-haystack/pysolr) (👨‍💻 65 · 🔀 300 · 📦 2.7K · 📋 140 - 14% open · ⏱️ 12.04.2022):

	```
	git clone https://github.com/django-haystack/pysolr
	```
- [PyPi](https://pypi.org/project/pysolr) (📥 220K / month):
	```
	pip install pysolr
	```
- [Conda](https://anaconda.org/conda-forge/pysolr) (📥 19K · ⏱️ 28.04.2020):
	```
	conda install -c conda-forge pysolr
	```
</details>
<details><summary><b><a href="https://github.com/elastic/elasticsearch-dsl-py">elasticsearch-dsl-py</a></b> (🥉24 ·  ⭐ 3.5K) - The official high-level Python client for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elastic/elasticsearch-dsl-py) (👨‍💻 130 · 🔀 730 · 📥 140 · 📦 6.5K · 📋 1.2K - 8% open · ⏱️ 14.07.2022):

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

## Serialization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for serializing complex data types_

<details><summary><b><a href="https://github.com/marshmallow-code/marshmallow">marshmallow</a></b> (🥇30 ·  ⭐ 6.2K) - A lightweight library for converting complex objects to and from.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marshmallow-code/marshmallow) (👨‍💻 200 · 🔀 590 · 📦 54K · 📋 1.1K - 11% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/marshmallow-code/marshmallow
	```
- [PyPi](https://pypi.org/project/marshmallow) (📥 18M / month):
	```
	pip install marshmallow
	```
- [Conda](https://anaconda.org/conda-forge/marshmallow) (📥 1.2M · ⏱️ 23.08.2022):
	```
	conda install -c conda-forge marshmallow
	```
</details>
<details><summary><b><a href="https://github.com/python-rapidjson/python-rapidjson">python-rapidjson</a></b> (🥈23 ·  ⭐ 460) - A Python wrapper around.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/python-rapidjson/python-rapidjson) (👨‍💻 19 · 🔀 41 · 📦 2.7K · 📋 100 - 10% open · ⏱️ 07.07.2022):

	```
	git clone https://github.com/python-rapidjson/python-rapidjson
	```
- [PyPi](https://pypi.org/project/python-rapidjson) (📥 830K / month):
	```
	pip install python-rapidjson
	```
- [Conda](https://anaconda.org/conda-forge/python-rapidjson) (📥 1M · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge python-rapidjson
	```
</details>
<details><summary><b><a href="https://github.com/TkTech/pysimdjson">pysimdjson</a></b> (🥉22 ·  ⭐ 550) - A Python bindings for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TkTech/pysimdjson) (👨‍💻 14 · 🔀 41 · 📦 430 · 📋 76 - 13% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/TkTech/pysimdjson
	```
- [PyPi](https://pypi.org/project/pysimdjson) (📥 230K / month):
	```
	pip install pysimdjson
	```
- [Conda](https://anaconda.org/conda-forge/pysimdjson) (📥 35K · ⏱️ 13.09.2022):
	```
	conda install -c conda-forge pysimdjson
	```
</details>
<details><summary><b><a href="https://github.com/ultrajson/ultrajson">ultrajson</a></b> (🥉15 ·  ⭐ 3.8K) - A fast JSON decoder and encoder written in C with Python.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ultrajson/ultrajson) (👨‍💻 82 · 🔀 320 · 📋 330 - 7% open · ⏱️ 15.09.2022):

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

## Serverless Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Frameworks for developing serverless Python code._

<details><summary><b><a href="https://github.com/Miserlou/Zappa">Zappa</a></b> (🥇27 ·  ⭐ 12K · 💀) - A tool for deploying WSGI applications on AWS Lambda and API Gateway. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Miserlou/Zappa) (👨‍💻 260 · 🔀 1.2K · 📥 280 · 📋 1.3K - 47% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/Miserlou/Zappa
	```
- [PyPi](https://pypi.org/project/Zappa) (📥 84K / month):
	```
	pip install Zappa
	```
- [Conda](https://anaconda.org/conda-forge/Zappa):
	```
	conda install -c conda-forge Zappa
	```
</details>
<details><summary><b><a href="https://github.com/nficano/python-lambda">python-lambda</a></b> (🥉21 ·  ⭐ 1.4K) - A toolkit for developing and deploying Python code in AWS Lambda. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/nficano/python-lambda) (👨‍💻 48 · 🔀 220 · 📦 160 · 📋 90 - 41% open · ⏱️ 03.06.2022):

	```
	git clone https://github.com/nficano/python-lambda
	```
- [PyPi](https://pypi.org/project/python-lambda) (📥 4.4K / month):
	```
	pip install python-lambda
	```
- [Conda](https://anaconda.org/conda-forge/python-lambda):
	```
	conda install -c conda-forge python-lambda
	```
</details>
<br>

## Shell

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Shells based on Python._

<details><summary><b><a href="https://github.com/xonsh/xonsh">xonsh</a></b> (🥇15 ·  ⭐ 6.3K) - A Python-powered, cross-platform, Unix-gazing shell language and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/xonsh/xonsh) (🔀 560 · 📥 8K · 📋 2.4K - 10% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/xonsh/xonsh/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<br>

## Specific Formats Processing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for parsing and manipulating specific text formats._

🔗&nbsp;<b><a href="https://openpyxl.readthedocs.io/en/stable/">openpyxl</a></b>  - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.

🔗&nbsp;<b><a href="https://www.reportlab.com/opensource/">ReportLab</a></b>  - Allowing Rapid creation of rich PDF documents.

🔗&nbsp;<b><a href="http://pyyaml.org/">PyYAML</a></b>  - YAML implementations for Python.

<details><summary><b><a href="https://github.com/lepture/mistune">Mistune</a></b> (🥇33 ·  ⭐ 2.1K) - Fastest and full featured pure Python parsers of Markdown. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lepture/mistune) (👨‍💻 35 · 🔀 210 · 📦 170K · 📋 230 - 8% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/lepture/mistune
	```
- [PyPi](https://pypi.org/project/mistune) (📥 9.7M / month):
	```
	pip install mistune
	```
- [Conda](https://anaconda.org/conda-forge/mistune) (📥 8.6M · ⏱️ 15.07.2022):
	```
	conda install -c conda-forge mistune
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/tablib">tablib</a></b> (🥇32 ·  ⭐ 4.2K) - A module for Tabular Datasets in XLS, CSV, JSON, YAML. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/tablib) (👨‍💻 120 · 🔀 540 · 📦 15K · 📋 240 - 12% open · ⏱️ 11.07.2022):

	```
	git clone https://github.com/jazzband/tablib
	```
- [PyPi](https://pypi.org/project/tablib) (📥 1.2M / month):
	```
	pip install tablib
	```
- [Conda](https://anaconda.org/conda-forge/tablib) (📥 76K · ⏱️ 09.04.2022):
	```
	conda install -c conda-forge tablib
	```
</details>
<details><summary><b><a href="https://github.com/jmcnamara/XlsxWriter">XlsxWriter</a></b> (🥇32 ·  ⭐ 3K) - A Python module for creating Excel .xlsx files. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jmcnamara/XlsxWriter) (👨‍💻 47 · 🔀 570 · 📦 50K · 📋 800 - 1% open · ⏱️ 05.09.2022):

	```
	git clone https://github.com/jmcnamara/XlsxWriter
	```
- [PyPi](https://pypi.org/project/XlsxWriter) (📥 10M / month):
	```
	pip install XlsxWriter
	```
- [Conda](https://anaconda.org/conda-forge/XlsxWriter) (📥 2.1M · ⏱️ 27.02.2022):
	```
	conda install -c conda-forge XlsxWriter
	```
</details>
<details><summary><b><a href="https://github.com/py-pdf/PyPDF2">PyPDF2</a></b> (🥈29 ·  ⭐ 4.7K) - A library capable of splitting, merging and transforming PDF pages. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/py-pdf/PyPDF2) (👨‍💻 140 · 🔀 980 · 📦 35K · 📋 580 - 10% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/mstamy2/PyPDF2
	```
- [PyPi](https://pypi.org/project/PyPDF2) (📥 3.6M / month):
	```
	pip install PyPDF2
	```
- [Conda](https://anaconda.org/conda-forge/PyPDF2) (📥 290K · ⏱️ 15.09.2022):
	```
	conda install -c conda-forge PyPDF2
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/csvkit">csvkit</a></b> (🥈28 ·  ⭐ 5.1K) - Utilities for converting to and working with CSV. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/csvkit) (👨‍💻 100 · 🔀 570 · 📦 1.2K · 📋 860 - 6% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/wireservice/csvkit
	```
- [PyPi](https://pypi.org/project/csvkit) (📥 150K / month):
	```
	pip install csvkit
	```
- [Conda](https://anaconda.org/conda-forge/csvkit) (📥 69K · ⏱️ 20.03.2022):
	```
	conda install -c conda-forge csvkit
	```
</details>
<details><summary><b><a href="https://github.com/xlwings/xlwings">xlwings</a></b> (🥈28 ·  ⭐ 2.4K) - A BSD-licensed library that makes it easy to call Python from.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/xlwings/xlwings) (👨‍💻 57 · 🔀 430 · 📥 31K · 📦 25K · 📋 1.6K - 15% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/ZoomerAnalytics/xlwings
	```
- [PyPi](https://pypi.org/project/xlwings) (📥 600K / month):
	```
	pip install xlwings
	```
- [Conda](https://anaconda.org/conda-forge/xlwings) (📥 460K · ⏱️ 29.08.2022):
	```
	conda install -c conda-forge xlwings
	```
</details>
<details><summary><b><a href="https://github.com/euske/pdfminer">PDFMiner</a></b> (🥉27 ·  ⭐ 4.9K · 💀) - A tool for extracting information from PDF documents. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/euske/pdfminer) (👨‍💻 28 · 🔀 990 · 📦 3.2K · 📋 240 - 82% open · ⏱️ 18.01.2020):

	```
	git clone https://github.com/euske/pdfminer
	```
- [PyPi](https://pypi.org/project/pdfminer) (📥 120K / month):
	```
	pip install pdfminer
	```
- [Conda](https://anaconda.org/conda-forge/pdfminer) (📥 24K · ⏱️ 15.02.2021):
	```
	conda install -c conda-forge pdfminer
	```
</details>
<details><summary><b><a href="https://github.com/pyexcel/pyexcel">pyexcel</a></b> (🥉25 ·  ⭐ 1K) - Providing one API for reading, manipulating and writing csv, ods,.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pyexcel/pyexcel) (👨‍💻 20 · 🔀 150 · 📥 160 · 📦 2.7K · 📋 200 - 6% open · ⏱️ 09.09.2022):

	```
	git clone https://github.com/pyexcel/pyexcel
	```
- [PyPi](https://pypi.org/project/pyexcel) (📥 130K / month):
	```
	pip install pyexcel
	```
- [Conda](https://anaconda.org/conda-forge/pyexcel) (📥 47K · ⏱️ 13.02.2022):
	```
	conda install -c conda-forge pyexcel
	```
</details>
<details><summary><b><a href="https://github.com/Python-Markdown/markdown">Python-Markdown</a></b> (🥉24 ·  ⭐ 3K) - A Python implementation of John Grubers Markdown. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Python-Markdown/markdown) (👨‍💻 160 · 🔀 730 · 📦 210K · 📋 790 - 3% open · ⏱️ 31.08.2022):

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
<details><summary><b><a href="https://github.com/unoconv/unoconv">unoconv</a></b> (🥉23 ·  ⭐ 2.3K · 💤) - Convert between any document format supported by.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/unoconv/unoconv) (👨‍💻 52 · 🔀 360 · 📦 99 · 📋 480 - 16% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/unoconv/unoconv
	```
- [PyPi](https://pypi.org/project/unoconv) (📥 27K / month):
	```
	pip install unoconv
	```
- [Conda](https://anaconda.org/conda-forge/unoconv):
	```
	conda install -c conda-forge unoconv
	```
</details>
<details><summary><b><a href="https://github.com/python-openxml/python-docx">python-docx</a></b> (🥉22 ·  ⭐ 3.3K · 💀) - Reads, queries and modifies Microsoft Word 2007/2008 docx files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-openxml/python-docx) (👨‍💻 14 · 🔀 800 · 📋 970 - 47% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/python-openxml/python-docx
	```
- [PyPi](https://pypi.org/project/python-docx) (📥 3.1M / month):
	```
	pip install python-docx
	```
- [Conda](https://anaconda.org/conda-forge/python-docx) (📥 120K · ⏱️ 27.05.2021):
	```
	conda install -c conda-forge python-docx
	```
</details>
<details><summary><b><a href="https://github.com/scanny/python-pptx">python-pptx</a></b> (🥉22 ·  ⭐ 1.6K · 💤) - Python library for creating and updating PowerPoint (.pptx) files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/scanny/python-pptx) (👨‍💻 12 · 🔀 360 · 📋 730 - 45% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/scanny/python-pptx
	```
- [PyPi](https://pypi.org/project/python-pptx) (📥 870K / month):
	```
	pip install python-pptx
	```
- [Conda](https://anaconda.org/conda-forge/python-pptx) (📥 170K · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge python-pptx
	```
</details>
<details><summary><b><a href="https://github.com/elapouya/python-docx-template">docxtpl</a></b> (🥉20 ·  ⭐ 1.4K) - Editing a docx document by jinja2 template. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/elapouya/python-docx-template) (👨‍💻 49 · 🔀 320 · 📦 1.4K · 📋 360 - 17% open · ⏱️ 11.09.2022):

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
<details><summary><b><a href="https://github.com/mitsuhiko/unp">unp</a></b> (🥉10 ·  ⭐ 410 · 💀) - A command line tool that can unpack archives easily. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mitsuhiko/unp) (👨‍💻 2 · 🔀 57 · 📦 10 · 📋 7 - 85% open · ⏱️ 26.08.2014):

	```
	git clone https://github.com/mitsuhiko/unp
	```
- [PyPi](https://pypi.org/project/unp) (📥 43 / month):
	```
	pip install unp
	```
- [Conda](https://anaconda.org/conda-forge/unp):
	```
	conda install -c conda-forge unp
	```
</details>
<br>

## Static Site Generator

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Static site generator is a software that takes some text + templates as input and produces HTML files on the output._

<details><summary><b><a href="https://github.com/getpelican/pelican">pelican</a></b> (🥇32 ·  ⭐ 11K) - Static site generator that supports Markdown and reST syntax. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/getpelican/pelican) (👨‍💻 430 · 🔀 1.7K · 📥 650 · 📦 6K · 📋 1.6K - 3% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/getpelican/pelican
	```
- [PyPi](https://pypi.org/project/pelican) (📥 14K / month):
	```
	pip install pelican
	```
- [Conda](https://anaconda.org/conda-forge/pelican) (📥 130K · ⏱️ 11.07.2022):
	```
	conda install -c conda-forge pelican
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥈29 ·  ⭐ 2.3K) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 230 · 🔀 350 · 📦 440 · 📋 2.1K - 2% open · ⏱️ 03.09.2022):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 1.6K / month):
	```
	pip install nikola
	```
- [Conda](https://anaconda.org/conda-forge/nikola) (📥 5.5K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge nikola
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥉28 ·  ⭐ 15K) - Markdown friendly documentation generator. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (🔀 2K · 📦 25K · 📋 1.7K - 6% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/mkdocs/mkdocs/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/lektor/lektor">lektor</a></b> (🥉23 ·  ⭐ 3.6K) - An easy to use static CMS and blog engine. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lektor/lektor) (👨‍💻 92 · 🔀 290 · 📥 7K · 📋 600 - 36% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/lektor/lektor
	```
- [PyPi](https://pypi.org/project/lektor) (📥 2.2K / month):
	```
	pip install lektor
	```
- [Conda](https://anaconda.org/conda-forge/lektor) (📥 55K · ⏱️ 28.07.2022):
	```
	conda install -c conda-forge lektor
	```
</details>
<details><summary><b><a href="https://github.com/sunainapai/makesite">makesite</a></b> (🥉14 ·  ⭐ 1.6K · 💀) - Simple, lightweight, and magic-free static site/blog generator ( 130.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sunainapai/makesite) (👨‍💻 8 · 🔀 260 · 📋 13 - 38% open · ⏱️ 03.01.2021):

	```
	git clone https://github.com/sunainapai/makesite
	```
- [PyPi](https://pypi.org/project/makesite) (📥 13 / month):
	```
	pip install makesite
	```
- [Conda](https://anaconda.org/conda-forge/makesite):
	```
	conda install -c conda-forge makesite
	```
</details>
<br>

## Tagging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for tagging items._

<details><summary><b><a href="https://github.com/jazzband/django-taggit">django-taggit</a></b> (🥇22 ·  ⭐ 2.9K) - Simple tagging for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-taggit) (👨‍💻 140 · 🔀 560 · 📋 390 - 18% open · ⏱️ 08.09.2022):

	```
	git clone https://github.com/jazzband/django-taggit
	```
- [PyPi](https://pypi.org/project/django-taggit) (📥 360K / month):
	```
	pip install django-taggit
	```
- [Conda](https://anaconda.org/conda-forge/django-taggit) (📥 97K · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge django-taggit
	```
</details>
<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with task queues._

🔗&nbsp;<b><a href="https://docs.celeryproject.org/en/stable/">celery</a></b>  - An asynchronous task queue/job queue based on distributed message passing.

<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇32 ·  ⭐ 8.5K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 270 · 🔀 1.3K · 📦 11K · 📋 980 - 19% open · ⏱️ 21.08.2022):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 730K / month):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 77K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥈28 ·  ⭐ 4.2K) - Little multi-threaded task queue. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 66 · 🔀 350 · 📦 990 · ⏱️ 18.08.2022):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 86K / month):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 26K · ⏱️ 16.10.2019):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/Bogdanp/dramatiq">dramatiq</a></b> (🥉27 ·  ⭐ 3.3K) - A fast and reliable background task processing library for Python.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Bogdanp/dramatiq) (👨‍💻 84 · 🔀 230 · 📥 33 · 📦 500 · 📋 290 - 10% open · ⏱️ 03.09.2022):

	```
	git clone https://github.com/Bogdanp/dramatiq
	```
- [PyPi](https://pypi.org/project/dramatiq) (📥 110K / month):
	```
	pip install dramatiq
	```
- [Conda](https://anaconda.org/conda-forge/dramatiq) (📥 35K · ⏱️ 03.04.2022):
	```
	conda install -c conda-forge dramatiq
	```
</details>
<details><summary><b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉20 ·  ⭐ 870 · 💀) - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pricingassistant/mrq) (👨‍💻 40 · 🔀 110 · 📦 29 · 📋 170 - 30% open · ⏱️ 13.12.2020):

	```
	git clone https://github.com/pricingassistant/mrq
	```
- [PyPi](https://pypi.org/project/mrq) (📥 150 / month):
	```
	pip install mrq
	```
- [Conda](https://anaconda.org/conda-forge/mrq):
	```
	conda install -c conda-forge mrq
	```
</details>
<br>

## Template Engine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools for templating and lexing._

🔗&nbsp;<b><a href="https://genshi.edgewall.org/">Genshi</a></b>  - Python templating toolkit for generation of web-aware output.

🔗&nbsp;<b><a href="http://www.makotemplates.org/">Mako</a></b>  - Hyperfast and lightweight templating for the Python platform.

<details><summary><b><a href="https://github.com/pallets/jinja">Jinja2</a></b> (🥇23 ·  ⭐ 8.8K) - A modern and designer friendly templating language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/jinja) (👨‍💻 300 · 🔀 1.4K · 📥 53K · 📋 900 - 4% open · ⏱️ 01.09.2022):

	```
	git clone https://github.com/pallets/jinja
	```
- [PyPi](https://pypi.org/project/jinja) (📥 6.6K / month):
	```
	pip install jinja
	```
- [Conda](https://anaconda.org/conda-forge/jinja):
	```
	conda install -c conda-forge jinja
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing codebases and generating test data._

🔗&nbsp;<b><a href="https://docs.pytest.org/en/latest/">pytest</a></b>  - A mature full-featured Python testing tool.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - (Python standard library) Unit testing framework.

🔗&nbsp;<b><a href="http://nestorsalceda.github.io/mamba/">mamba</a></b>  - The definitive testing tool for Python. Born under the banner of BDD.

🔗&nbsp;<b><a href="https://tox.readthedocs.io/en/latest/">tox</a></b>  - Auto builds and tests distributions in multiple Python versions.

🔗&nbsp;<b><a href="https://pypi.org/project/selenium/">Selenium</a></b>  - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.

🔗&nbsp;<b><a href="https://pypi.org/project/doublex/">doublex</a></b>  - Powerful test doubles framework for Python.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.mock.html">mock</a></b>  - (Python standard library) A mocking and patching library.

🔗&nbsp;<b><a href="https://pypi.org/project/coverage/">coverage</a></b>  - Code coverage measurement.

🔗&nbsp;<b><a href="https://pypi.org/project/radar/">radar</a></b>  - Generate random datetime / time.

<details><summary><b><a href="https://github.com/joke2k/faker">faker</a></b> (🥇37 ·  ⭐ 15K) - A Python package that generates fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/faker) (👨‍💻 470 · 🔀 1.6K · 📦 71K · 📋 580 - 2% open · ⏱️ 31.08.2022):

	```
	git clone https://github.com/joke2k/faker
	```
- [PyPi](https://pypi.org/project/faker) (📥 7.5M / month):
	```
	pip install faker
	```
- [Conda](https://anaconda.org/conda-forge/faker) (📥 640K · ⏱️ 01.09.2022):
	```
	conda install -c conda-forge faker
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">Robot Framework</a></b> (🥇35 ·  ⭐ 7.3K) - A generic test automation framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 170 · 🔀 2K · 📥 540 · 📦 5.9K · 📋 3.9K - 5% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📥 1.6M / month):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 93K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇32 ·  ⭐ 6.2K) - Hypothesis is an advanced Quickcheck style property based.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 290 · 🔀 500 · 📦 14K · 📋 1.3K - 2% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 3.2M / month):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 6.2M · ⏱️ 05.09.2022):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/responses">responses</a></b> (🥇32 ·  ⭐ 3.7K) - A utility library for mocking out the requests Python library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/getsentry/responses) (👨‍💻 110 · 🔀 290 · 📥 68 · 📦 15K · 📋 240 - 1% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/getsentry/responses
	```
- [PyPi](https://pypi.org/project/responses) (📥 7.8M / month):
	```
	pip install responses
	```
- [Conda](https://anaconda.org/conda-forge/responses) (📥 1.2M · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge responses
	```
</details>
<details><summary><b><a href="https://github.com/cobrateam/splinter">splinter</a></b> (🥇32 ·  ⭐ 2.5K) - Open source tool for testing web applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cobrateam/splinter) (👨‍💻 170 · 🔀 500 · 📦 5.7K · 📋 510 - 8% open · ⏱️ 11.09.2022):

	```
	git clone https://github.com/cobrateam/splinter
	```
- [PyPi](https://pypi.org/project/splinter) (📥 96K / month):
	```
	pip install splinter
	```
- [Conda](https://anaconda.org/conda-forge/splinter):
	```
	conda install -c conda-forge splinter
	```
</details>
<details><summary><b><a href="https://github.com/kevin1024/vcrpy">VCR.py</a></b> (🥈31 ·  ⭐ 2.3K) - Record and replay HTTP interactions on your tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kevin1024/vcrpy) (👨‍💻 120 · 🔀 290 · 📦 4.2K · 📋 340 - 24% open · ⏱️ 31.08.2022):

	```
	git clone https://github.com/kevin1024/vcrpy
	```
- [PyPi](https://pypi.org/project/vcrpy) (📥 1.7M / month):
	```
	pip install vcrpy
	```
- [Conda](https://anaconda.org/conda-forge/vcrpy) (📥 260K · ⏱️ 01.09.2022):
	```
	conda install -c conda-forge vcrpy
	```
</details>
<details><summary><b><a href="https://github.com/locustio/locust">locust</a></b> (🥈29 ·  ⭐ 20K) - Scalable user load testing tool written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/locustio/locust) (👨‍💻 260 · 🔀 2.5K · 📋 1.4K - 1% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/locustio/locust
	```
- [PyPi](https://pypi.org/project/locust) (📥 990K / month):
	```
	pip install locust
	```
- [Conda](https://anaconda.org/conda-forge/locust) (📥 76K · ⏱️ 07.09.2022):
	```
	conda install -c conda-forge locust
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">PyAutoGUI</a></b> (🥈29 ·  ⭐ 7.1K · 💤) - PyAutoGUI is a cross-platform GUI automation Python module for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 51 · 🔀 920 · 📦 17K · 📋 590 - 63% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📥 530K / month):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 160K · ⏱️ 10.09.2022):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/gabrielfalcao/HTTPretty">httpretty</a></b> (🥈29 ·  ⭐ 2K · 💤) - HTTP request mock tool for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gabrielfalcao/HTTPretty) (👨‍💻 100 · 🔀 250 · 📦 6.5K · 📋 230 - 39% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/gabrielfalcao/HTTPretty
	```
- [PyPi](https://pypi.org/project/HTTPretty) (📥 520K / month):
	```
	pip install HTTPretty
	```
- [Conda](https://anaconda.org/conda-forge/HTTPretty) (📥 220K · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge HTTPretty
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥉25 ·  ⭐ 3.7K) - is a Python library that help you generate fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 290 · 📥 360 · 📋 310 - 0% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 160K / month):
	```
	pip install mimesis
	```
- [Conda](https://anaconda.org/conda-forge/mimesis) (📥 42K · ⏱️ 08.08.2022):
	```
	conda install -c conda-forge mimesis
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥉24 ·  ⭐ 3.4K) - Travel through time by mocking the datetime module. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 110 · 🔀 230 · 📋 260 - 34% open · ⏱️ 12.08.2022):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 5.2M / month):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 440K · ⏱️ 12.08.2022):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/schemathesis/schemathesis">Schemathesis</a></b> (🥉24 ·  ⭐ 1.4K) - A tool for automatic property-based testing of web applications.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/schemathesis/schemathesis) (👨‍💻 47 · 🔀 100 · 📋 670 - 15% open · ⏱️ 27.08.2022):

	```
	git clone https://github.com/kiwicom/schemathesis
	```
- [PyPi](https://pypi.org/project/schemathesis) (📥 85K / month):
	```
	pip install schemathesis
	```
- [Conda](https://anaconda.org/conda-forge/schemathesis) (📥 930 · ⏱️ 28.08.2022):
	```
	conda install -c conda-forge schemathesis
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉23 ·  ⭐ 2.9K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 340 · 📋 520 - 29% open · ⏱️ 17.08.2022):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 2.2M / month):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 110K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉23 ·  ⭐ 730) - The successor to `nose`, based on `unittest2`. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 74 · 🔀 130 · 📦 5.2K · 📋 260 - 18% open · ⏱️ 11.09.2022):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 590K / month):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 65K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉22 ·  ⭐ 1.7K · 💀) - A language-agnostic A/B Testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/sixpack/sixpack) (👨‍💻 56 · 🔀 190 · 📦 10 · 📋 190 - 35% open · ⏱️ 26.08.2020):

	```
	git clone https://github.com/seatgeek/sixpack
	```
- [PyPi](https://pypi.org/project/sixpack) (📥 200 / month):
	```
	pip install sixpack
	```
- [Conda](https://anaconda.org/conda-forge/sixpack):
	```
	conda install -c conda-forge sixpack
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉21 ·  ⭐ 740) - A clean, colorful test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 38 · 🔀 73 · 📦 720 · 📋 180 - 2% open · ⏱️ 26.07.2022):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 16K / month):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 100K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/patrys/httmock">httmock</a></b> (🥉20 ·  ⭐ 440 · 💀) - A mocking library for requests for Python 2.6+ and 3.2+. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/patrys/httmock) (👨‍💻 29 · 🔀 49 · 📦 1.8K · 📋 26 - 42% open · ⏱️ 28.10.2020):

	```
	git clone https://github.com/patrys/httmock
	```
- [PyPi](https://pypi.org/project/httmock) (📥 190K / month):
	```
	pip install httmock
	```
- [Conda](https://anaconda.org/conda-forge/httmock) (📥 6.5K · ⏱️ 23.10.2017):
	```
	conda install -c conda-forge httmock
	```
</details>
<details><summary><b><a href="https://github.com/mindflayer/python-mocket">mocket</a></b> (🥉20 ·  ⭐ 240) - A socket mock framework with gevent/asyncio/SSL support. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mindflayer/python-mocket) (👨‍💻 22 · 🔀 40 · 📦 69 · ⏱️ 29.08.2022):

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
<details><summary><b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - Fake database generator. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/emirozer/fake2db) (👨‍💻 18 · 🔀 110 · 📦 21 · 📋 22 - 31% open · ⏱️ 25.11.2019):

	```
	git clone https://github.com/emirozer/fake2db
	```
- [PyPi](https://pypi.org/project/fake2db) (📥 270 / month):
	```
	pip install fake2db
	```
- [Conda](https://anaconda.org/conda-forge/fake2db):
	```
	conda install -c conda-forge fake2db
	```
</details>
<details><summary><b><a href="https://github.com/berinhard/model_mommy">model_mommy</a></b> (🥉18 ·  ⭐ 920 · 💀) - Creating random fixtures for testing in Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/berinhard/model_mommy) (👨‍💻 100 · 🔀 140 · ⏱️ 21.10.2019):

	```
	git clone https://github.com/vandersonmota/model_mommy
	```
- [PyPi](https://pypi.org/project/model_mommy) (📥 79K / month):
	```
	pip install model_mommy
	```
- [Conda](https://anaconda.org/conda-forge/model_mommy):
	```
	conda install -c conda-forge model_mommy
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉17 ·  ⭐ 850) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy,.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 43 · 🔀 88 · 📋 82 - 40% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 86K / month):
	```
	pip install mixer
	```
- [Conda](https://anaconda.org/conda-forge/mixer):
	```
	conda install -c conda-forge mixer
	```
</details>
<br>

## Text Processing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for parsing and manipulating plain texts._

🔗&nbsp;<b><a href="https://docs.python.org/3/library/difflib.html">difflib</a></b>  - (Python standard library) Helpers for computing deltas.

🔗&nbsp;<b><a href="https://pypi.org/project/Unidecode/">unidecode</a></b>  - ASCII transliterations of Unicode text.

🔗&nbsp;<b><a href="http://pygments.org/">pygments</a></b>  - A generic syntax highlighter.

<details><summary><b><a href="https://github.com/pyparsing/pyparsing">pyparsing</a></b> (🥇35 ·  ⭐ 1.6K) - A general purpose framework for generating parsers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyparsing/pyparsing) (👨‍💻 50 · 🔀 220 · 📥 7.2K · 📦 590K · 📋 270 - 11% open · ⏱️ 29.08.2022):

	```
	git clone https://github.com/pyparsing/pyparsing
	```
- [PyPi](https://pypi.org/project/pyparsing) (📥 120M / month):
	```
	pip install pyparsing
	```
- [Conda](https://anaconda.org/conda-forge/pyparsing) (📥 27M · ⏱️ 14.07.2022):
	```
	conda install -c conda-forge pyparsing
	```
</details>
<details><summary><b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥇30 ·  ⭐ 8.7K · 💤) - Fuzzy String Matching. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/seatgeek/fuzzywuzzy) (👨‍💻 70 · 🔀 870 · 📦 14K · 📋 180 - 43% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/seatgeek/fuzzywuzzy
	```
- [PyPi](https://pypi.org/project/fuzzywuzzy) (📥 7.2M / month):
	```
	pip install fuzzywuzzy
	```
- [Conda](https://anaconda.org/conda-forge/fuzzywuzzy) (📥 390K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge fuzzywuzzy
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">textdistance</a></b> (🥈29 ·  ⭐ 2.9K) - Compute distance between sequences with 30+ algorithms. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 12 · 🔀 230 · 📥 840 · 📦 2.7K · ⏱️ 08.09.2022):

	```
	git clone https://github.com/orsinium/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 670K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 200K · ⏱️ 21.08.2022):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/andialbrecht/sqlparse">sqlparse</a></b> (🥈26 ·  ⭐ 3K) - A non-validating SQL parser. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/andialbrecht/sqlparse) (👨‍💻 100 · 🔀 570 · 📋 480 - 41% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/andialbrecht/sqlparse
	```
- [PyPi](https://pypi.org/project/sqlparse) (📥 29M / month):
	```
	pip install sqlparse
	```
- [Conda](https://anaconda.org/conda-forge/sqlparse) (📥 1M · ⏱️ 10.09.2021):
	```
	conda install -c conda-forge sqlparse
	```
</details>
<details><summary><b><a href="https://github.com/pwaller/pyfiglet">pyfiglet</a></b> (🥈26 ·  ⭐ 1K) - An implementation of figlet written in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pwaller/pyfiglet) (👨‍💻 21 · 🔀 98 · 📦 23K · 📋 44 - 22% open · ⏱️ 11.06.2022):

	```
	git clone https://github.com/pwaller/pyfiglet
	```
- [PyPi](https://pypi.org/project/pyfiglet) (📥 940K / month):
	```
	pip install pyfiglet
	```
- [Conda](https://anaconda.org/conda-forge/pyfiglet) (📥 110K · ⏱️ 18.05.2019):
	```
	conda install -c conda-forge pyfiglet
	```
</details>
<details><summary><b><a href="https://github.com/chardet/chardet">chardet</a></b> (🥈24 ·  ⭐ 1.8K) - Python 2/3 compatible character encoding detector. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/chardet/chardet) (👨‍💻 48 · 🔀 240 · 📋 120 - 37% open · ⏱️ 22.07.2022):

	```
	git clone https://github.com/chardet/chardet
	```
- [PyPi](https://pypi.org/project/chardet) (📥 65M / month):
	```
	pip install chardet
	```
- [Conda](https://anaconda.org/conda-forge/chardet) (📥 17M · ⏱️ 25.06.2022):
	```
	conda install -c conda-forge chardet
	```
</details>
<details><summary><b><a href="https://github.com/skorokithakis/shortuuid">shortuuid</a></b> (🥈24 ·  ⭐ 1.7K) - A generator library for concise, unambiguous and URL-safe UUIDs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/skorokithakis/shortuuid) (👨‍💻 27 · 🔀 100 · 📋 52 - 3% open · ⏱️ 21.08.2022):

	```
	git clone https://github.com/skorokithakis/shortuuid
	```
- [PyPi](https://pypi.org/project/shortuuid) (📥 4.2M / month):
	```
	pip install shortuuid
	```
- [Conda](https://anaconda.org/conda-forge/shortuuid) (📥 220K · ⏱️ 29.06.2022):
	```
	conda install -c conda-forge shortuuid
	```
</details>
<details><summary><b><a href="https://github.com/un33k/python-slugify">python-slugify</a></b> (🥈22 ·  ⭐ 1.2K) - A Python slugify library that translates unicode to ASCII. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/un33k/python-slugify) (👨‍💻 30 · 🔀 87 · 📋 56 - 3% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/un33k/python-slugify
	```
- [PyPi](https://pypi.org/project/python-slugify) (📥 8.8M / month):
	```
	pip install python-slugify
	```
- [Conda](https://anaconda.org/conda-forge/python-slugify) (📥 1M · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge python-slugify
	```
</details>
<details><summary><b><a href="https://github.com/dabeaz/ply">ply</a></b> (🥉21 ·  ⭐ 2.3K · 💤) - Implementation of lex and yacc parsing tools for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/dabeaz/ply) (👨‍💻 32 · 🔀 370 · 📋 180 - 18% open · ⏱️ 09.01.2022):

	```
	git clone https://github.com/dabeaz/ply
	```
- [PyPi](https://pypi.org/project/ply) (📥 21M / month):
	```
	pip install ply
	```
- [Conda](https://anaconda.org/conda-forge/ply) (📥 1.7M · ⏱️ 07.07.2018):
	```
	conda install -c conda-forge ply
	```
</details>
<details><summary><b><a href="https://github.com/selwin/python-user-agents">python-user-agents</a></b> (🥉21 ·  ⭐ 1.3K · 💤) - Browser user agent parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/selwin/python-user-agents) (👨‍💻 31 · 🔀 190 · 📦 4.7K · 📋 69 - 55% open · ⏱️ 14.12.2021):

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
<details><summary><b><a href="https://github.com/mozillazg/python-pinyin">pypinyin</a></b> (🥉20 ·  ⭐ 4K) - Convert Chinese hanzi () to pinyin (). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mozillazg/python-pinyin) (👨‍💻 22 · 🔀 560 · 📋 230 - 8% open · ⏱️ 28.08.2022):

	```
	git clone https://github.com/mozillazg/python-pinyin
	```
- [PyPi](https://pypi.org/project/python-pinyin) (📥 32 / month):
	```
	pip install python-pinyin
	```
- [Conda](https://anaconda.org/conda-forge/python-pinyin):
	```
	conda install -c conda-forge python-pinyin
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥉20 ·  ⭐ 3.3K · 💤) - Makes Unicode text less broken and more consistent automagically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 110 · 📦 6.8K · 📋 130 - 9% open · ⏱️ 09.02.2022):

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
<details><summary><b><a href="https://github.com/mozilla/unicode-slugify">unicode-slugify</a></b> (🥉20 ·  ⭐ 310 · 💤) - A slugifier that generates unicode slugs with Django as a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mozilla/unicode-slugify) (👨‍💻 14 · 🔀 47 · 📦 2K · 📋 18 - 55% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/mozilla/unicode-slugify
	```
- [PyPi](https://pypi.org/project/unicode-slugify) (📥 50K / month):
	```
	pip install unicode-slugify
	```
- [Conda](https://anaconda.org/conda-forge/unicode-slugify):
	```
	conda install -c conda-forge unicode-slugify
	```
</details>
<details><summary><b><a href="https://github.com/voronind/awesome-slugify">awesome-slugify</a></b> (🥉19 ·  ⭐ 470 · 💀) - A Python slugify library that can preserve unicode. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/voronind/awesome-slugify) (👨‍💻 11 · 🔀 41 · 📦 3.1K · 📋 24 - 54% open · ⏱️ 20.01.2017):

	```
	git clone https://github.com/dimka665/awesome-slugify
	```
- [PyPi](https://pypi.org/project/awesome-slugify) (📥 73K / month):
	```
	pip install awesome-slugify
	```
- [Conda](https://anaconda.org/conda-forge/awesome-slugify) (📥 61K · ⏱️ 28.06.2019):
	```
	conda install -c conda-forge awesome-slugify
	```
</details>
<details><summary><b><a href="https://github.com/ztane/python-Levenshtein">Levenshtein</a></b> (🥉18 ·  ⭐ 1.2K · 💀) - Fast computation of Levenshtein distance and string.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/ztane/python-Levenshtein) (🔀 150 · 📦 14K · 📋 65 - 76% open · ⏱️ 01.02.2021):

	```
	git clone https://github.com/ztane/python-Levenshtein/
	```
- [Conda](https://anaconda.org/conda-forge/):
	```
	conda install -c conda-forge 
	```
</details>
<details><summary><b><a href="https://github.com/derek73/python-nameparser">python-nameparser</a></b> (🥉17 ·  ⭐ 560 · 💤) - Parsing human names into their individual components. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/derek73/python-nameparser) (👨‍💻 20 · 🔀 88 · 📦 900 · 📋 99 - 20% open · ⏱️ 08.02.2022):

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
<details><summary><b><a href="https://github.com/daviddrysdale/python-phonenumbers">python-phonenumbers</a></b> (🥉14 ·  ⭐ 3.1K) - Parsing, formatting, storing and validating.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/daviddrysdale/python-phonenumbers) (👨‍💻 26 · 🔀 370 · 📋 150 - 2% open · ⏱️ 09.09.2022):

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
<details><summary><b><a href="https://github.com/vinta/pangu.py">pangu.py</a></b> (🥉13 ·  ⭐ 190 · 💀) - Paranoid text spacing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vinta/pangu.py) (👨‍💻 7 · 🔀 20 · 📦 89 · 📋 8 - 37% open · ⏱️ 09.02.2019):

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

- [GitHub](https://github.com/davidaurelio/hashids-python) (👨‍💻 10 · 🔀 94 · 📋 24 - 25% open · ⏱️ 07.09.2020):

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

## Third-party APIs

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for accessing third party services APIs._

🔗&nbsp;<b><a href="https://libcloud.apache.org/">apache-libcloud</a></b>  - One Python library for all clouds.

<details><summary><b><a href="https://github.com/boto/boto3">boto3</a></b> (🥇37 ·  ⭐ 7.5K) - Python interface to Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/boto/boto3) (👨‍💻 140 · 🔀 1.6K · 📦 200K · 📋 2.7K - 7% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/boto/boto3
	```
- [PyPi](https://pypi.org/project/boto3) (📥 380M / month):
	```
	pip install boto3
	```
- [Conda](https://anaconda.org/conda-forge/boto3) (📥 12M · ⏱️ 15.09.2022):
	```
	conda install -c conda-forge boto3
	```
</details>
<details><summary><b><a href="https://github.com/burnash/gspread">gspread</a></b> (🥈35 ·  ⭐ 6.1K) - Google Spreadsheets Python API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/burnash/gspread) (👨‍💻 150 · 🔀 840 · 📥 170 · 📦 18K · 📋 760 - 6% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/burnash/gspread
	```
- [PyPi](https://pypi.org/project/gspread) (📥 9M / month):
	```
	pip install gspread
	```
- [Conda](https://anaconda.org/conda-forge/gspread) (📥 230K · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge gspread
	```
</details>
<details><summary><b><a href="https://github.com/googleapis/google-api-python-client">google-api-python-client</a></b> (🥈35 ·  ⭐ 5.9K) - Google APIs Client Library for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googleapis/google-api-python-client) (👨‍💻 180 · 🔀 2.1K · 📦 110K · 📋 930 - 6% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/google/google-api-python-client
	```
- [PyPi](https://pypi.org/project/google-api-python-client) (📥 27M / month):
	```
	pip install google-api-python-client
	```
- [Conda](https://anaconda.org/conda-forge/google-api-python-client) (📥 1.5M · ⏱️ 13.09.2022):
	```
	conda install -c conda-forge google-api-python-client
	```
</details>
<details><summary><b><a href="https://github.com/ryanmcgrath/twython">twython</a></b> (🥉29 ·  ⭐ 1.8K · 💀) - A Python wrapper for the Twitter API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryanmcgrath/twython) (👨‍💻 100 · 🔀 390 · 📦 5.4K · 📋 320 - 6% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/ryanmcgrath/twython
	```
- [PyPi](https://pypi.org/project/twython) (📥 180K / month):
	```
	pip install twython
	```
- [Conda](https://anaconda.org/conda-forge/twython) (📥 260K · ⏱️ 17.07.2021):
	```
	conda install -c conda-forge twython
	```
</details>
<details><summary><b><a href="https://github.com/mobolic/facebook-sdk">facebook-sdk</a></b> (🥉26 ·  ⭐ 2.7K · 💀) - Facebook Platform Python SDK. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mobolic/facebook-sdk) (👨‍💻 99 · 🔀 910 · 📦 3.6K · 📋 240 - 8% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/mobolic/facebook-sdk
	```
- [PyPi](https://pypi.org/project/facebook-sdk) (📥 180K / month):
	```
	pip install facebook-sdk
	```
- [Conda](https://anaconda.org/conda-forge/facebook-sdk):
	```
	conda install -c conda-forge facebook-sdk
	```
</details>
<details><summary><b><a href="https://github.com/jcarbaugh/django-wordpress">django-wordpress</a></b> (🥉12 ·  ⭐ 330 · 💀) - WordPress models and views for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jcarbaugh/django-wordpress) (👨‍💻 10 · 🔀 79 · 📦 6 · 📋 11 - 18% open · ⏱️ 24.01.2018):

	```
	git clone https://github.com/istrategylabs/django-wordpress
	```
- [PyPi](https://pypi.org/project/django-wordpress) (📥 13 / month):
	```
	pip install django-wordpress
	```
- [Conda](https://anaconda.org/conda-forge/django-wordpress):
	```
	conda install -c conda-forge django-wordpress
	```
</details>
<br>

## URL Manipulation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for parsing URLs._

<details><summary><b><a href="https://github.com/marshmallow-code/webargs">webargs</a></b> (🥇26 ·  ⭐ 1.3K) - A friendly library for parsing HTTP request arguments with built-in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marshmallow-code/webargs) (👨‍💻 65 · 🔀 150 · 📦 4.5K · 📋 280 - 2% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/marshmallow-code/webargs
	```
- [PyPi](https://pypi.org/project/webargs) (📥 670K / month):
	```
	pip install webargs
	```
- [Conda](https://anaconda.org/conda-forge/webargs) (📥 170K · ⏱️ 13.07.2022):
	```
	conda install -c conda-forge webargs
	```
</details>
<details><summary><b><a href="https://github.com/ellisonleao/pyshorteners">pyshorteners</a></b> (🥈23 ·  ⭐ 340) - A pure Python URL shortening lib. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ellisonleao/pyshorteners) (👨‍💻 24 · 🔀 59 · 📦 6.5K · ⏱️ 06.06.2022):

	```
	git clone https://github.com/ellisonleao/pyshorteners
	```
- [PyPi](https://pypi.org/project/pyshorteners) (📥 120K / month):
	```
	pip install pyshorteners
	```
- [Conda](https://anaconda.org/conda-forge/pyshorteners):
	```
	conda install -c conda-forge pyshorteners
	```
</details>
<details><summary><b><a href="https://github.com/codeinthehole/purl">purl</a></b> (🥉22 ·  ⭐ 280 · 💀) - A simple, immutable URL class with a clean API for interrogation and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/codeinthehole/purl) (👨‍💻 18 · 🔀 35 · 📦 2K · 📋 20 - 25% open · ⏱️ 15.05.2021):

	```
	git clone https://github.com/codeinthehole/purl
	```
- [PyPi](https://pypi.org/project/purl) (📥 47K / month):
	```
	pip install purl
	```
- [Conda](https://anaconda.org/conda-forge/purl):
	```
	conda install -c conda-forge purl
	```
</details>
<details><summary><b><a href="https://github.com/gruns/furl">furl</a></b> (🥉20 ·  ⭐ 2.3K) - A small Python library that makes parsing and manipulating URLs easy. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gruns/furl) (👨‍💻 15 · 🔀 130 · 📋 110 - 23% open · ⏱️ 01.08.2022):

	```
	git clone https://github.com/gruns/furl
	```
- [PyPi](https://pypi.org/project/furl) (📥 1.5M / month):
	```
	pip install furl
	```
- [Conda](https://anaconda.org/conda-forge/furl) (📥 200K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge furl
	```
</details>
<br>

## Video

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for manipulating video and GIFs._

🔗&nbsp;<b><a href="https://zulko.github.io/moviepy/">moviepy</a></b>  - A module for script-based movie editing with many formats, including animated GIFs.

<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥇24 ·  ⭐ 2.4K) - Most Powerful multi-threaded Video Processing framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 13 · 🔀 190 · 📥 660 · 📦 230 · 📋 230 - 2% open · ⏱️ 06.07.2022):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 5.6K / month):
	```
	pip install vidgear
	```
- [Conda](https://anaconda.org/conda-forge/vidgear):
	```
	conda install -c conda-forge vidgear
	```
</details>
<details><summary><b><a href="https://github.com/aizvorski/scikit-video">scikit-video</a></b> (🥉11 ·  ⭐ 110 · 💀) - Video processing routines for SciPy. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/aizvorski/scikit-video) (👨‍💻 2 · 🔀 22 · 📋 7 - 57% open · ⏱️ 28.05.2016):

	```
	git clone https://github.com/aizvorski/scikit-video
	```
- [PyPi](https://pypi.org/project/scikit-video) (📥 21K / month):
	```
	pip install scikit-video
	```
- [Conda](https://anaconda.org/conda-forge/scikit-video) (📥 20K · ⏱️ 20.09.2018):
	```
	conda install -c conda-forge scikit-video
	```
</details>
<br>

## Web Asset Management

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools for managing, compressing and minifying website assets._

🔗&nbsp;<b><a href="http://www.fanstatic.org/en/latest/">fanstatic</a></b>  - Packages, optimizes, and serves static file dependencies as Python packages.

🔗&nbsp;<b><a href="http://wimleers.com/fileconveyor">fileconveyor</a></b>  - A daemon to detect and sync files to CDNs, S3 and FTP.

<details><summary><b><a href="https://github.com/jazzband/django-pipeline">django-pipeline</a></b> (🥇29 ·  ⭐ 1.4K) - An asset packaging library for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-pipeline) (👨‍💻 170 · 🔀 350 · 📦 2K · 📋 440 - 27% open · ⏱️ 06.08.2022):

	```
	git clone https://github.com/jazzband/django-pipeline
	```
- [PyPi](https://pypi.org/project/django-pipeline) (📥 48K / month):
	```
	pip install django-pipeline
	```
- [Conda](https://anaconda.org/conda-forge/django-pipeline):
	```
	conda install -c conda-forge django-pipeline
	```
</details>
<details><summary><b><a href="https://github.com/miracle2k/webassets">webassets</a></b> (🥇29 ·  ⭐ 910 · 💀) - Bundles, optimizes, and manages unique cache-busting URLs for.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/miracle2k/webassets) (👨‍💻 160 · 🔀 250 · 📦 5.9K · 📋 290 - 20% open · ⏱️ 01.05.2021):

	```
	git clone https://github.com/miracle2k/webassets
	```
- [PyPi](https://pypi.org/project/webassets) (📥 200K / month):
	```
	pip install webassets
	```
- [Conda](https://anaconda.org/conda-forge/webassets) (📥 49K · ⏱️ 24.12.2019):
	```
	conda install -c conda-forge webassets
	```
</details>
<details><summary><b><a href="https://github.com/miracle2k/flask-assets">flask-assets</a></b> (🥉26 ·  ⭐ 430 · 💀) - Helps you integrate webassets into your Flask app. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/miracle2k/flask-assets) (👨‍💻 38 · 🔀 85 · 📦 6.5K · 📋 96 - 21% open · ⏱️ 29.02.2020):

	```
	git clone https://github.com/miracle2k/flask-assets
	```
- [PyPi](https://pypi.org/project/flask-assets) (📥 110K / month):
	```
	pip install flask-assets
	```
- [Conda](https://anaconda.org/conda-forge/flask-assets) (📥 35K · ⏱️ 24.12.2019):
	```
	conda install -c conda-forge flask-assets
	```
</details>
<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥉24 ·  ⭐ 2.2K) - A collection of custom storage back ends for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 230 · 🔀 720 · 📋 600 - 26% open · ⏱️ 10.08.2022):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 1.9M / month):
	```
	pip install django-storages
	```
- [Conda](https://anaconda.org/conda-forge/django-storages) (📥 38K · ⏱️ 06.08.2022):
	```
	conda install -c conda-forge django-storages
	```
</details>
<details><summary><b><a href="https://github.com/django-compressor/django-compressor">django-compressor</a></b> (🥉21 ·  ⭐ 2.6K) - Compresses linked and inline JavaScript or CSS into a.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-compressor/django-compressor) (👨‍💻 210 · 🔀 550 · 📋 630 - 15% open · ⏱️ 14.08.2022):

	```
	git clone https://github.com/django-compressor/django-compressor
	```
- [PyPi](https://pypi.org/project/django-compressor) (📥 310K / month):
	```
	pip install django-compressor
	```
- [Conda](https://anaconda.org/conda-forge/django-compressor):
	```
	conda install -c conda-forge django-compressor
	```
</details>
<br>

## Web Content Extracting

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for extracting web contents._

<details><summary><b><a href="https://github.com/psf/requests-html">requests-html</a></b> (🥇30 ·  ⭐ 13K · 💀) - Pythonic HTML Parsing for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/requests-html) (👨‍💻 62 · 🔀 850 · 📦 8.6K · 📋 370 - 44% open · ⏱️ 10.05.2020):

	```
	git clone https://github.com/psf/requests-html
	```
- [PyPi](https://pypi.org/project/requests-html) (📥 750K / month):
	```
	pip install requests-html
	```
- [Conda](https://anaconda.org/conda-forge/requests-html) (📥 2.8K · ⏱️ 26.06.2021):
	```
	conda install -c conda-forge requests-html
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">sumy</a></b> (🥈26 ·  ⭐ 2.9K) - A module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 23 · 🔀 470 · 📦 1.4K · 📋 110 - 14% open · ⏱️ 26.08.2022):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 19K / month):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 2.3K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/codelucas/newspaper">newspaper</a></b> (🥈24 ·  ⭐ 12K · 💀) - News extraction, article extraction and content curation in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/codelucas/newspaper) (👨‍💻 100 · 🔀 1.9K · 📋 650 - 59% open · ⏱️ 02.09.2020):

	```
	git clone https://github.com/codelucas/newspaper
	```
- [PyPi](https://pypi.org/project/newspaper) (📥 13K / month):
	```
	pip install newspaper
	```
- [Conda](https://anaconda.org/conda-forge/newspaper):
	```
	conda install -c conda-forge newspaper
	```
</details>
<details><summary><b><a href="https://github.com/deanmalmgren/textract">textract</a></b> (🥈23 ·  ⭐ 3.3K) - Extract text from any document, Word, PowerPoint, PDFs, etc. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deanmalmgren/textract) (👨‍💻 40 · 🔀 470 · 📋 210 - 39% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/deanmalmgren/textract
	```
- [PyPi](https://pypi.org/project/textract) (📥 110K / month):
	```
	pip install textract
	```
- [Conda](https://anaconda.org/conda-forge/textract) (📥 16K · ⏱️ 10.03.2022):
	```
	conda install -c conda-forge textract
	```
</details>
<details><summary><b><a href="https://github.com/Alir3z4/html2text">html2text</a></b> (🥈23 ·  ⭐ 1.3K · 💤) - Convert HTML to Markdown-formatted text. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Alir3z4/html2text) (👨‍💻 76 · 🔀 220 · 📋 200 - 39% open · ⏱️ 22.02.2022):

	```
	git clone https://github.com/Alir3z4/html2text
	```
- [PyPi](https://pypi.org/project/html2text) (📥 1.4M / month):
	```
	pip install html2text
	```
- [Conda](https://anaconda.org/conda-forge/html2text) (📥 19K · ⏱️ 09.02.2020):
	```
	conda install -c conda-forge html2text
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/micawber">micawber</a></b> (🥉22 ·  ⭐ 580 · 💀) - A small library for extracting rich content from URLs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/micawber) (👨‍💻 27 · 🔀 84 · 📦 790 · ⏱️ 12.07.2021):

	```
	git clone https://github.com/coleifer/micawber
	```
- [PyPi](https://pypi.org/project/micawber) (📥 27K / month):
	```
	pip install micawber
	```
- [Conda](https://anaconda.org/conda-forge/micawber) (📥 4.9K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge micawber
	```
</details>
<details><summary><b><a href="https://github.com/michaelhelmick/lassie">lassie</a></b> (🥉18 ·  ⭐ 560 · 💀) - Web Content Retrieval for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/michaelhelmick/lassie) (👨‍💻 15 · 🔀 46 · 📦 28 · 📋 39 - 25% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/michaelhelmick/lassie
	```
- [PyPi](https://pypi.org/project/lassie) (📥 2.3K / month):
	```
	pip install lassie
	```
- [Conda](https://anaconda.org/conda-forge/lassie):
	```
	conda install -c conda-forge lassie
	```
</details>
<details><summary><b><a href="https://github.com/buriy/python-readability">python-readability</a></b> (🥉17 ·  ⭐ 2.2K) - Fast Python port of arc90's readability tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/buriy/python-readability) (👨‍💻 39 · 🔀 330 · 📋 97 - 34% open · ⏱️ 10.04.2022):

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
<details><summary><b><a href="https://github.com/gaojiuli/toapi">toapi</a></b> (🥉16 ·  ⭐ 3.3K · 💀) - Every web site provides APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gaojiuli/toapi) (👨‍💻 12 · 🔀 220 · 📋 53 - 9% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/gaojiuli/toapi
	```
- [PyPi](https://pypi.org/project/toapi) (📥 120 / month):
	```
	pip install toapi
	```
- [Conda](https://anaconda.org/conda-forge/toapi):
	```
	conda install -c conda-forge toapi
	```
</details>
<br>

## Web Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to automate web scraping._

🔗&nbsp;<b><a href="https://pythonhosted.org/feedparser/">feedparser</a></b>  - Universal feed parser.

🔗&nbsp;<b><a href="https://scrapy.org/">scrapy</a></b>  - A fast high-level screen scraping and web crawling framework.

<details><summary><b><a href="https://github.com/binux/pyspider">pyspider</a></b> (🥇28 ·  ⭐ 16K · 💀) - A powerful spider system. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/binux/pyspider) (👨‍💻 62 · 🔀 3.5K · 📦 310 · 📋 820 - 32% open · ⏱️ 02.08.2020):

	```
	git clone https://github.com/binux/pyspider
	```
- [PyPi](https://pypi.org/project/pyspider) (📥 1.7K / month):
	```
	pip install pyspider
	```
- [Conda](https://anaconda.org/conda-forge/pyspider):
	```
	conda install -c conda-forge pyspider
	```
</details>
<details><summary><b><a href="https://github.com/lorien/grab">grab</a></b> (🥈26 ·  ⭐ 2.2K) - Site scraping framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lorien/grab) (👨‍💻 64 · 🔀 260 · 📦 360 · 📋 220 - 3% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/lorien/grab
	```
- [PyPi](https://pypi.org/project/grab) (📥 2.6K / month):
	```
	pip install grab
	```
- [Conda](https://anaconda.org/conda-forge/grab):
	```
	conda install -c conda-forge grab
	```
</details>
<details><summary><b><a href="https://github.com/scrapinghub/portia">portia</a></b> (🥈23 ·  ⭐ 8.6K · 💀) - Visual scraping for Scrapy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scrapinghub/portia) (👨‍💻 50 · 🔀 1.3K · 📥 200 · 📦 43 · 📋 450 - 24% open · ⏱️ 10.07.2019):

	```
	git clone https://github.com/scrapinghub/portia
	```
- [PyPi](https://pypi.org/project/portia) (📥 240 / month):
	```
	pip install portia
	```
- [Conda](https://anaconda.org/conda-forge/portia):
	```
	conda install -c conda-forge portia
	```
</details>
<details><summary><b><a href="https://github.com/MechanicalSoup/MechanicalSoup">MechanicalSoup</a></b> (🥉21 ·  ⭐ 4.1K) - A Python library for automating interaction with websites. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MechanicalSoup/MechanicalSoup) (👨‍💻 51 · 🔀 350 · 📥 43 · 📋 160 - 16% open · ⏱️ 03.07.2022):

	```
	git clone https://github.com/MechanicalSoup/MechanicalSoup
	```
- [PyPi](https://pypi.org/project/MechanicalSoup) (📥 110K / month):
	```
	pip install MechanicalSoup
	```
- [Conda](https://anaconda.org/conda-forge/MechanicalSoup) (📥 130K · ⏱️ 31.05.2021):
	```
	conda install -c conda-forge MechanicalSoup
	```
</details>
<details><summary><b><a href="https://github.com/jmcarp/robobrowser">robobrowser</a></b> (🥉21 ·  ⭐ 3.6K · 💀) - A simple, Pythonic library for browsing the web without a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jmcarp/robobrowser) (👨‍💻 10 · 🔀 340 · 📦 840 · 📋 73 - 58% open · ⏱️ 07.06.2015):

	```
	git clone https://github.com/jmcarp/robobrowser
	```
- [PyPi](https://pypi.org/project/robobrowser) (📥 15K / month):
	```
	pip install robobrowser
	```
- [Conda](https://anaconda.org/conda-forge/robobrowser) (📥 4.5K · ⏱️ 23.03.2018):
	```
	conda install -c conda-forge robobrowser
	```
</details>
<details><summary><b><a href="https://github.com/qinxuye/cola">cola</a></b> (🥉16 ·  ⭐ 1.4K · 💀) - A distributed crawling framework. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/qinxuye/cola) (👨‍💻 3 · 🔀 530 · 📦 14 · 📋 65 - 20% open · ⏱️ 01.03.2020):

	```
	git clone https://github.com/chineking/cola
	```
- [PyPi](https://pypi.org/project/cola) (📥 98 / month):
	```
	pip install cola
	```
- [Conda](https://anaconda.org/conda-forge/cola):
	```
	conda install -c conda-forge cola
	```
</details>
<br>

## Web Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Traditional full stack web frameworks._

🔗&nbsp;<b><a href="https://www.djangoproject.com/">Django</a></b>  - The most popular web framework in Python.

🔗&nbsp;<b><a href="https://github.com/shahraizali/awesome-django">awesome-django</a></b> ( ⭐ 910)  - The Best Django Resource, Awesome Django for mature packages.

🔗&nbsp;<b><a href="http://flask.pocoo.org/">Flask</a></b>  - A microframework for Python.

🔗&nbsp;<b><a href="https://github.com/humiaozuzu/awesome-flask">awesome-flask</a></b> ( ⭐ 11K · 💀)  - A curated list of awesome Flask resources and plugins.

🔗&nbsp;<b><a href="https://pylonsproject.org/">Pyramid</a></b>  - A small, fast, down-to-earth, open source Python web framework.

🔗&nbsp;<b><a href="https://github.com/uralbash/awesome-pyramid">awesome-pyramid</a></b> ( ⭐ 530 · 💀)  - A curated list of awesome Pyramid apps, projects and resources.

🔗&nbsp;<b><a href="http://www.tornadoweb.org/en/latest/">Tornado</a></b>  - A web framework and asynchronous networking library.

<details><summary><b><a href="https://github.com/MasoniteFramework/masonite">Masonite</a></b> (🥇26 ·  ⭐ 1.9K) - The modern and developer centric Python web framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MasoniteFramework/masonite) (👨‍💻 81 · 🔀 120 · 📦 440 · 📋 360 - 4% open · ⏱️ 10.08.2022):

	```
	git clone https://github.com/MasoniteFramework/masonite
	```
- [PyPi](https://pypi.org/project/masonite) (📥 3.9K / month):
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

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for working with WebSocket._

<details><summary><b><a href="https://github.com/django/channels">channels</a></b> (🥇29 ·  ⭐ 5.4K) - Developer-friendly asynchrony for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django/channels) (👨‍💻 250 · 🔀 710 · 📦 19K · 📋 1.2K - 4% open · ⏱️ 14.09.2022):

	```
	git clone https://github.com/django/channels
	```
- [PyPi](https://pypi.org/project/channels) (📥 540K / month):
	```
	pip install channels
	```
- [Conda](https://anaconda.org/conda-forge/channels) (📥 100K · ⏱️ 24.06.2022):
	```
	conda install -c conda-forge channels
	```
</details>
<details><summary><b><a href="https://github.com/aaugustin/websockets">websockets</a></b> (🥇29 ·  ⭐ 4.2K) - A library for building WebSocket servers and clients with a focus.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aaugustin/websockets) (👨‍💻 62 · 🔀 430 · 📦 68K · 📋 910 - 2% open · ⏱️ 10.09.2022):

	```
	git clone https://github.com/aaugustin/websockets
	```
- [PyPi](https://pypi.org/project/websockets) (📥 12M / month):
	```
	pip install websockets
	```
- [Conda](https://anaconda.org/conda-forge/websockets) (📥 1.5M · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge websockets
	```
</details>
<details><summary><b><a href="https://github.com/crossbario/autobahn-python">autobahn-python</a></b> (🥉24 ·  ⭐ 2.4K) - WebSocket & WAMP for Python on Twisted and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/crossbario/autobahn-python) (👨‍💻 130 · 🔀 730 · 📦 21K · 📋 870 - 20% open · ⏱️ 23.08.2022):

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

## WSGI Servers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_WSGI-compatible web servers._

🔗&nbsp;<b><a href="https://uwsgi-docs.readthedocs.io/en/latest/">uWSGI</a></b>  - A project aims at developing a full stack for building hosting services, written in C.

<details><summary><b><a href="https://github.com/benoitc/gunicorn">gunicorn</a></b> (🥇37 ·  ⭐ 8.5K) - Pre-forked, ported from Ruby's Unicorn project. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/benoitc/gunicorn) (👨‍💻 370 · 🔀 1.6K · 📥 100 · 📦 750K · 📋 1.9K - 20% open · ⏱️ 25.08.2022):

	```
	git clone https://github.com/benoitc/gunicorn
	```
- [PyPi](https://pypi.org/project/gunicorn) (📥 26M / month):
	```
	pip install gunicorn
	```
- [Conda](https://anaconda.org/conda-forge/gunicorn) (📥 1.3M · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge gunicorn
	```
</details>
<details><summary><b><a href="https://github.com/pallets/werkzeug">werkzeug</a></b> (🥈36 ·  ⭐ 6.2K) - A WSGI utility library for Python that powers Flask and can easily be.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pallets/werkzeug) (👨‍💻 460 · 🔀 1.6K · 📥 250 · 📦 810K · 📋 1K - 1% open · ⏱️ 01.09.2022):

	```
	git clone https://github.com/pallets/werkzeug
	```
- [PyPi](https://pypi.org/project/werkzeug) (📥 110M / month):
	```
	pip install werkzeug
	```
- [Conda](https://anaconda.org/conda-forge/werkzeug) (📥 5.5M · ⏱️ 09.08.2022):
	```
	conda install -c conda-forge werkzeug
	```
</details>
<details><summary><b><a href="https://github.com/jonashaag/bjoern">bjoern</a></b> (🥉23 ·  ⭐ 2.8K) - Asynchronous, very fast and written in C. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jonashaag/bjoern) (👨‍💻 44 · 🔀 180 · 📦 480 · 📋 150 - 15% open · ⏱️ 11.09.2022):

	```
	git clone https://github.com/jonashaag/bjoern
	```
- [PyPi](https://pypi.org/project/bjoern) (📥 38K / month):
	```
	pip install bjoern
	```
- [Conda](https://anaconda.org/conda-forge/bjoern) (📥 80K · ⏱️ 12.09.2022):
	```
	conda install -c conda-forge bjoern
	```
</details>
<details><summary><b><a href="https://github.com/Pylons/waitress">waitress</a></b> (🥉22 ·  ⭐ 1.1K) - Multi-threaded, powers Pyramid. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Pylons/waitress) (👨‍💻 45 · 🔀 140 · 📋 210 - 7% open · ⏱️ 31.07.2022):

	```
	git clone https://github.com/Pylons/waitress
	```
- [PyPi](https://pypi.org/project/waitress) (📥 2.6M / month):
	```
	pip install waitress
	```
- [Conda](https://anaconda.org/conda-forge/waitress) (📥 78K · ⏱️ 31.05.2022):
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
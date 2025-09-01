# Python学习路线图（中阶）脑图

## 1. 数据存储与处理
### 1.1 时间日期处理
- time
- datetime

### 1.2 文件读写
- Excel / CSV / HDF / netCDF 数据文件读写

### 1.3 数据库
- 数据库概述
- 安装配置
- SQL 语句
- SQLite
- MySQL
- MongoDB

## 2. 操作系统与环境
- os / sys 模块使用
- 线程、进程与协程
  - threading
  - multiprocessing
  - queue
  - gevent
- 加锁与解锁基础概念
- pyinstaller 源码打包

## 3. 网络编程
- socket 网络编程
- smtplib 发送邮件
- urllib 模块使用

## 4. Web开发
### 4.1 前端基础
- HTML / CSS / JavaScript
- MVC架构
- REST 与 Ajax

### 4.2 Django
- Django 简介与安装配置
- DTL（Django Template Language）
- 路由定义
- 请求数据解析
- 数据库操作
- 表单提交
- Django Rest Framework
- 部署、日志与安全
- 开发案例

### 4.3 Tornado
- Tornado 简介与安装配置
- 模板与表单提交
- 数据库操作
- 异步 Web 服务
- 外部服务认证（auth）
- 部署、日志与安全
- 开发案例

### 4.4 Flask
- Flask 简介与安装配置
- HTTP 请求与响应
- Cookie 与 Session
- 模板
- 表单提交
- Bootstrap-Flask
- REST Web 服务
- 部署、日志与安全
- 开发案例

### 4.5 Web可视化
- ECharts 网站可视化

## 5. 网络爬虫
### 5.1 基础概念
- 什么是网络爬虫
- HTML 与 DOM 树分析
- 常用工具
- 法律及注意事项

### 5.2 页面解析
- 正则表达式（RE）基础语法
- XPath 选择器（find / findall）
- CSS 选择器
- BeautifulSoup
  - 简介与安装配置
  - BeautifulSoup 对象
  - 元素定位
  - 文档树遍历与搜索
- lxml
  - 安装配置
  - lxml.etree 使用

### 5.3 数据抓取
- requests
  - 安装配置
  - 发送请求与 HTTP 请求类型
  - URL 参数传递
  - 响应内容
  - 定制请求头
  - Cookie 与 POST 请求
  - 身份认证
- Selenium
  - 简介与安装配置
  - 元素定位（单元素 / 多元素）
  - 键盘和鼠标操作
  - 表单交互
  - WebDriver API
- Scrapy 框架
  - 简介与安装配置
  - 框架组成（Item Pipeline / Downloader / Spiders / Scheduler）
  - 数据存储（文件存储 / 数据库存储）

### 5.4 高级爬虫技术
- 渲染动态网页（WebKit / Selenium / headless / PhantomJS）
- 表单交互处理
- 超时异常处理（timeout）
- 验证码处理（自动输入 / OCR字符识别）
- 高并发处理（多线程爬虫）
- 网站高并发处理

## 6. 桌面应用开发
### 6.1 Tkinter
- 简介与安装配置
- Tkinter 模块与控件
- 标准属性
- 几何管理
- 事件处理
- 对话框
- 拖拽与绘图

### 6.2 PyQT
- 简介与安装配置
- PyQT 模块
- 布局管理
- 菜单和工具栏
- 事件和信号
- 对话框与控件
- 拖拽与绘图

### 6.3 WxPython
- 简介与安装配置
- WxPython 常用类
- 布局管理
- 事件处理
- 对话框
- 组件
- 拖拽处理
- 绘图 API
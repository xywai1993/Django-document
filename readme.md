# django 文档

官网有现成的[中文翻译](https://docs.djangoproject.com/zh-hans/3.1/),有需要的请直接看官网翻译~~。

下面为对照[官网英文 PDF](doc/django.pdf)版的个人翻译练习 👇👇👇

---

# Django 文档 版本 3.1.3.dev

## Django 软件基金会

### 2020.10.09

# 目录

1. Django 文档

    - 1.1 [第一步](doc/1.md#11-第一步)
    - 1.2 [获取帮助](doc/1.md#12-获取帮助)
    - 1.3 [文档的组织方式](doc/1.md#13-如何组织文档)
    - 1.4 [模型层](doc/1.md#14-模块层)
    - 1.5 [视图层](doc/1.md#15-视图层)
    - 1.6 [模板层](doc/1.md#16-模板层)
    - 1.7 [表单](doc/1.md#17-表单)
    - 1.8 [部署流程](doc/1.md#18-部署流程)
    - 1.9 [管理后台](doc/1.md#19-管理后台)
    - 1.10 [安全](doc/1.md#110-安全性)
    - 1.11 [国际化与本地化](doc/1.md#111-国际化和本地化)
    - 1.12 [性能和优化](doc/1.md#112-性能和优化)
    - 1.13 [地理学框架？](doc/1.md#113-地理学框架)
    - 1.14 [常见的 web 应用程序工具](doc/1.md#114-常用-web-应用程序工具)
    - 1.15 [其他核心功能](doc/1.md#115-其他核心功能)
    - 1.16 [Django 开源项目](doc/1.md#116-django-开源项目)

2. 开始

    - [2.1 Django 大致一览](doc/2/2.1.md)
    - [2.2 快速安装教程](doc/2/2.2.md)
    - [2.3 编写第一个 Django APP ，第一部分](doc/2/2.3.md)
    - [2.4 编写第一个 Django APP ，第二部分](doc/2/2.4.md)
    - [2.5 编写第一个 Django APP ，第三部分](doc/2/2.5.md)
    - [2.6 编写第一个 Django APP ，第四部分](doc/2/2.6.md)
    - [2.7 编写第一个 Django APP ，第五部分](doc/2/2.7.md)
    - [2.8 编写第一个 Django APP ，第六部分](doc/2/2.8.md)
    - [2.9 编写第一个 Django APP ，第七部分](doc/2/2.9.md)
    - [2.10 进阶指南：如何编写可复用的程序](doc/2/2.10.md)
    - [2.11 接下来看什么](doc/2/2.11.md)
    - [2.12 为 Django 编写第一个补丁](doc/2/2.12.md)

3. 使用 Django

    - [3.1 如何安装 Django](doc/3/3.1.md)
    - [3.2 模型和数据库](doc/3/3.2.md)
    - 3.3 传递 HTTP 请求
    - 3.4 使用表单（Forms）工作？
    - 3.5 模板
    - 3.6 基本类（class）视图 ？
    - 3.7 迁移
    - 3.8 管理字段？
    - 3.9 Django 测试
    - 3.10 Django 用户认证
    - 3.11 Django 缓存框架
    - 3.12 视图里的条件处理
    - 3.13 密码签注
    - 3.14 发送邮件
    - 3.15 国际化与本地化
    - 3.16 日志
    - 3.17 分页
    - 3.18 Django 的安全
    - 3.19 性能和优化
    - 3.20 序列化 Django 对象
    - 3.21 Django 设置
    - 3.22 信号？
    - 3.23 系统检测框架（System check framework）
    - 3.24 外部包
    - 3.25 异步支持

4. “如何” 指南

    - 4.1 认证使用 REMOTE-USER
    - 4.2 编写自定义 django-admin 命令
    - 4.3 编写自定义模型字段
    - 4.4 自定义查询
    - 4.5 自定义模板标签和字段
    - 4.6 编写自定义存储系统
    - 4.7 部署 Django
    - 4.8 更新 Django 到最新版本
    - 4.9 提供初始数据模型
    - 4.10 集成 Django 旧的数据库？
    - 4.11 在 Django 中输出 CSV
    - 4.12 在 Django 中输出 PDFs
    - 4.13 覆写模板
    - 4.14 管理静态文件（例如 js css image)
    - 4.15 如何在 Windows 中安装 Django
    - 4.16 编写数据库迁移？

5. Django 常见问题

    - 5.1 FAQ：常规？
    - 5.2 FAQ：安装
    - 5.3 FAQ：使用 Django
    - 5.4 FAQ：获取帮助
    - 5.5 FAQ：数据库和模型
    - 5.6 FAQ：管理后台
    - 5.7 FAQ：贡献代码
    - 5.8 疑难解答

6. API 参考

    - 6.1 应用程序（Applications）
    - 6.2 System check framework
    - 6.3 内置类视图 API
    - 6.4 点击劫持
    - 6.5 contrib 包
    - 6.6 跨站点请求伪造保护
    - 6.7 数据库
    - 6.8 _django-admin_ and _manage.py_
    - 6.9 从你的代码里运行管理命令？
    - 6.10 Django 异常处理？
    - 6.11 文件处理
    - 6.12 表单（Forms）
    - 6.13 中间件
    - 6.14 迁移业务？
    - 6.15 模型
    - 6.16 分页
    - 6.17 请求（request）和响应（response）对象
    - 6.18 架构编辑器（SchemaEditor ）
    - 6.19 设置
    - 6.20 信号（Signals）?
    - 6.21 模板
    - 6.22 模板响应（TemplateResponse ）和简单的模板响应（SimpleTemplateResponse ）
    - 6.23 Unicode 数据
    - 6.24 django.urls 实用方法
    - 6.25 在 URLconfs 中使用 django.urls 的方法
    - 6.26 在 URLconfs 中使用 django.conf.urls 的方法
    - 6.27 Django 工具
    - 6.28 验证
    - 6.29 内置视图

7. 元文件和汇编

    - 7.1 API 稳定性
    - 7.2 设计哲学
    - 7.3 Django 第三方分布

8. 词汇表

9. 版本注释

    - 9.1 最后版本
    - 9.2 安全版本

10. Django 内部相关

    - 10.1 贡献
    - 10.2 邮件列表
    - 10.3 项目组织
    - 10.4 Django 的安全策略
    - 10.5 Django 发布流程
    - 10.6 反对时间线？
    - 10.7 Django 开源仓库
    - 10.8 Django 如何形成的

11. 指数、术语表和表

Python 模块索引

索引

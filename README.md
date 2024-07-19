# Basearch

中文 | [English](README.en.md)

## 简介

Basearch 是一款浏览器插件，旨在通过深度爬取用户收藏夹的内容，并加以先进的自然语言处理和机器学习技术处理，以允许用户通过文字描述快速定位个人收藏内容。

<img width="600" alt="image" src="https://github.com/user-attachments/assets/d81fe67f-674c-47e9-b883-5cf7d5397042">

## 功能特点

- **智能搜索**：支持用户通过自然语言描述来查找收藏夹中的文章网址，无需记住具体的书签名称或 URL。
- **向量化技术**：对收藏夹的网址进行数学向量化处理，确保搜索结果的高精确度。
- **易于使用**：简单直观的用户界面，方便用户快速上手。
- **跨浏览器兼容**：支持主流的浏览器平台，保证了广泛的适用性。

## 源代码

### 前端

实现了浏览器端插件，自定义浏览器启动页，支持个人收藏夹搜索、传统搜索引擎等，拥有美观的界面布局、优雅的界面动画。  
源码：https://github.com/shareAI2/basearch-app

### 后端 API

与前端配合工作，实现用户收藏夹数据同步、目标网址文章标题、内容、截图抓取等功能，直接负责所有业务相关数据的共享和服务提供。  
源码：https://github.com/shareAI2/basearch-api

### 数据引擎

与后端配合工作，实现读写收藏夹数据库、向量数据库，对收藏文章内容抽取生成总结摘要、分块插入个人知识库以及相似度计算等。  
源码：https://github.com/shareAI2/basearch-engine

## 使用方法

- Chrome：https://github.com/shareAI2/basearch-app/releases/download/v0.1.0/basearch.zip
- Edge：https://github.com/shareAI2/basearch-app/releases/download/v0.1.0/basearch.zip

1. 下载浏览器 AI 插件压缩包并解压为文件夹，选择“设置-扩展-安装解压缩的扩展程序”安装插件，打开浏览器新标签使用 basearch。
2. 在搜索栏中输入您对目标网址的描述，例如：“与数据科学相关的博客”。
3. 插件将根据描述在收藏夹中查找匹配的网址，并显示搜索结果。

## 贡献

我们欢迎任何形式的贡献！如果您有任何建议、问题或需求，请提交 issue 或创建 pull request。感谢您的支持！

## 许可证

该项目采用 [Apache 许可证](LICENSE)。

## 联系我们

如有任何问题，请通过以下方式联系我们：

- 邮箱: ai-lab@foxmail.com

感谢您使用 basearch!

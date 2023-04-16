 # LangChain-ChatGLM-Webui
 <p align="center">
  <a href="https://github.com/thomas-yanxin/LangChain-ChatGLM-Webui"><img src="https://img.shields.io/badge/GitHub-24292e" alt="github"></a>
  <a href="https://modelscope.cn/studios/AI-ModelScope/LangChain-ChatLLM/summary"><img src="https://img.shields.io/badge/ModelScope-blueviolet" alt="gitee"></a>
  <a href="https://openi.pcl.ac.cn/Learning-Develop-Union/LangChain-ChatGLM-Webui"><img src="https://img.shields.io/badge/-OpenI-337AFF" alt="OpenI"></a>
   <a href="https://www.bilibili.com/video/BV1So4y1L7Hb/?share_source=copy_web&vd_source=8162f92b2a1a94035ca9e4e0f6e1860a"><img src="https://img.shields.io/badge/-bilibili-ff69b4" alt="bilibili"></a>
</p>

## 🔥项目体验

本项目提供基于ModelScope魔搭社区的[在线体验](https://modelscope.cn/studios/AI-ModelScope/LangChain-ChatLLM/summary), 欢迎尝试和反馈!

## 👏项目介绍

受[langchain-ChatGLM](https://github.com/imClumsyPanda/langchain-ChatGLM)启发, 利用LangChain和ChatGLM-6B系列模型制作的Webui, 提供基于本地知识的大模型应用.

目前支持上传 txt、docx、md 等文本格式文件, 提供包括ChatGLM-6B系列的模型文件以及[GanymedeNil/text2vec-large-chinese](https://huggingface.co/GanymedeNil/text2vec-large-chinese)、[nghuyong/ernie-3.0-base-zh](https://huggingface.co/nghuyong/ernie-3.0-base-zh)、[nghuyong/ernie-3.0-nano-zh](https://huggingface.co/nghuyong/ernie-3.0-nano-zh)的Embedding模型.

效果如下:
![](./img/demo_new.jpg)
![](./img/demo_ms.jpg)

## 🚀使用方式

提供ModelScope版本和HuggingFace版本. 其中ModelScope版本下载更稳定、效果更优.  
**需要Python>=3.8.1**

1. git clone本项目: `git clone https://github.com/thomas-yanxin/LangChain-ChatGLM-Webui.git`
2. 进入本项目目录：`cd LangChain-ChatGLM-Webui`
3. 安装依赖包：`pip3 install -r requirements.txt`
4. 执行app.py：`python3 app.py`

### 模型下载

若存在网络问题可点击以下链接快速下载:
1. [ChatGLM-6B](https://openi.pcl.ac.cn/attachments/b33c55bb-8e7c-4e9d-90e5-c310dcc776d9?type=0)
2. [ChatGLM-6B-int4](https://openi.pcl.ac.cn/attachments/b2c7f23f-6864-40da-9c81-2c0607cb1d02?type=0)
3. [ChatGLM-6B-int8](https://openi.pcl.ac.cn/attachments/3aad10d1-ac8e-48f8-ac5f-cea8b54cf41b?type=0)

## 💪Todo

* [x] 多个模型选择
* [x] 支持上下文
* [ ] 支持上传多个文本文件
* [x] 提供ModelScope版本
* [ ] 支持用户自定义Embedding模型

## ❤️引用

1. [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B): ChatGLM-6B: 开源双语对话语言模型
2. [LangChain](https://github.com/hwchase17/langchain): Building applications with LLMs through composability
3. [langchain-ChatGLM](https://github.com/imClumsyPanda/langchain-ChatGLM): 基于本地知识的 ChatGLM 应用实现

## 🙇‍感谢

1. [langchain-ChatGLM](https://github.com/imClumsyPanda/langchain-ChatGLM)提供的基础框架
2. [魔搭ModelScope](https://modelscope.cn/home)提供展示空间
3. [OpenI启智社区](https://openi.pcl.ac.cn/)提供调试算力

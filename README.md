# AI艺术鉴赏 - 看画猜作者

### 项目概述

“看画猜作者”是一个基于AI的艺术作品识别项目，旨在通过图像识别技术自动识别出艺术作品的创作者。用户可以通过Web界面上传画作图像，系统将返回作者的预测结果，并展示艺术家简介及其代表作。本项目采用敏捷开发方法，以提升软件的开发效率和迭代效果。

### 目标

- 利用深度学习模型识别上传图像的艺术家。
- 提供艺术家的基本信息和代表作推荐，帮助用户更好地了解艺术作品。

------

## 技术栈

- **前端**：Vue.js - 提供用户界面，支持图像上传及结果展示。
- **后端**：Django - 处理图像分类请求，调用AI模型并返回结果。
- **模型**：EfficientNet-B3 - 基于深度学习的图像分类模型，用于识别艺术作品的作者。
- **数据**：使用来自49位知名艺术家的画作数据集，包括乔托·迪·邦多纳、毕加索、梵高、安德烈·鲁勃廖夫、提香·韦切利奥等。
- **爬虫**：计划使用Python爬虫获取艺术家的简介和代表作介绍，增强用户体验。

------

## 项目功能

1. **图片上传**
   用户可以上传一张画作图片，通过前端界面发送给后端进行处理。
2. **作者识别**
   后端调用EfficientNet-B3模型，分析图像内容并返回预测的作者名称。
3. **艺术家简介与推荐**
   系统提供艺术家的基本信息和代表作品推荐，帮助用户更深入地了解该作者及其作品。

------

## 项目结构

```
├── frontend/                  # 前端代码（Vue.js）
│   ├── src/                   # Vue源文件
│   └── public/                # 静态资源
│
├── backend/                   # 后端代码（Django）
│   ├── app/                   # Django应用
│   └── static/                # 静态文件
│
├── model/                     # AI模型和权重文件
│
├── data/                      # 数据集和预处理脚本
│
├── docs/                      # 项目文档
└── README.md                  # 项目说明文件
```

------

## 使用方法

### 环境要求

- Python 3.8或更高版本
- Node.js 14.x或更高版本
- Django 4.1或更高版本
- Vue CLI 4.x

### 安装步骤

1. **克隆仓库**

   ```
   git clone https://github.com/完成以后补充
   cd your-repository
   ```

2. **安装后端依赖**

   ```
   cd backend
   pip install -r requirements.txt
   ```

3. **安装前端依赖**

   ```
   cd ../frontend
   npm install
   ```

4. **启动项目**

   - 后端（Django）：在

     ```
     backend
     ```

     目录中运行

     ```
     bash
     
     
     manage.py runserver
     ```

   - 前端（Vue）：在

     ```
     frontend
     ```

     目录中运行

     ```
     bash
     
     
     run serve
     ```

------

## 开发进度

- **项目分工和仓库搭建**：完成
- **前端框架设计与实现**：进行中
- **后端框架设计与API接口**：进行中
- **AI模型选择与训练**：已选定EfficientNet-B3
- **数据采集与预处理**：进行中
- **艺术家信息爬虫**：设计中

------

## 团队分工

- **王子琳**：项目管理、后端开发、仓库初始化
- **缪纬韬**：前端设计与实现
- **时晓天**：前端设计与实现
- **陈正元**：后端开发与数据处理

------

## 项目展示

将在项目完成后发布演示视频和图片，以展示项目的最终功能。
![ebbf3b4a5aa0732c528b0bcac839e7c1](https://github.com/user-attachments/assets/793eee10-26d0-4b23-9a5e-23ffc371bcdc)
![defa7f939daa792021d307002108bb6c](https://github.com/user-attachments/assets/3333cd6a-7fe1-4cfe-b1ae-dccd93012f4e)
![c4b8a24bf741856cbc6b5dabe470f47a](https://github.com/user-attachments/assets/da76ae85-1a4f-4d75-b0a5-9b43d2cfb144)
![02c76e024cedefb45fcc267ffd276b55](https://github.com/user-attachments/assets/88716ff6-3be3-417f-9ea1-6a8983738cd6)

------

## 贡献

欢迎对本项目提出意见和建议！如有疑问，您可以在Issue区进行反馈。

------

### 许可证

本项目遵循MIT许可证 - 详见LICENSE。

------

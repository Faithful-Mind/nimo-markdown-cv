---
layout: cv
title: YUAN Ye
pdf: true
---
# __袁__ 野

<div id="webaddress">
<i class="fi-mobile" style="margin-left:1em"></i>
<a href="tel:18223619838" style="margin-left:0.5em">18223619838</a>
<i class="fi-mail" style="margin-left:1em"></i>
<a href="mailto:lpyy15@qq.com" style="margin-left:0.5em">lpyy15@qq.com</a>
<i class="fi-home" style="margin-left:1em"></i>
<a href="https://github.com/Faithful-Mind" style="margin-left:0.5em">github.com/Faithful-Mind</a>
</div>

### __期望职位：__ Node.js 工程师

<br />


## Education

### __太原理工大学__ `2013 - 2017`
```
山西，太原（211工程院校）
```
- 光电信息科学与工程
  B.S. in Opto-Electronics Information Science and Engineering

- 大学英语六级证书 (CET-6)、计算机二级证书 (Java)

<br />


## Experience

### __北京中天联科科技有限公司__ `2018.8 - 2018.10`
_Software Engineer_<br />
维护其 Node.js 视频信息交易系统 (Express + Sequelize + apiDoc)，为其项目撰写设计文档；汇总描述数据库各表的定义和相关关系，对业务模型给出了 UML 类图和关键业务逻辑的流程图等。

适配机顶盒端视频信息源；完成了 Al Jazeera 半岛电视台、Dailymotion 等网站的视频爬虫，通过操纵 Headless 浏览器监听有效请求、自动对比差异、生成可重用规律等，实现了较高的自动化程度。

### __成都京东方光电科技有限公司, B7 柔性 AMOLED 面板产线__ `2017.9 - 2018.8`
_Array 工艺工程师_<br />
从事柔性 AMOLED 显示面板集成电路的生产工艺改善，产品良率提升，不良数据分析。期间独立完成了所在科室的 <strong>FDC 异常侦测与分类系统（统计过程控制）</strong>的上线和数据分析建模，获 B7 CIM (计算机集成制造)应用大赛前5强。

<br />


## Tech

本人有9个月的 Node.js 相关经验；责任心强，能接受有意义的加班。

具有较好的英文文档阅读能力，熟悉 GreenUML 绘制 UML 类图和流程图。

<br />

后端： Express / Koa 开发技术和 RESTful API 资源定义风格，了解 Egg.js 企业级开发框架

数据库： MongoDB 及其 ODM 框架 Mongoose；了解 Redis、MySQL 和 HediSQL 管理工具

爬虫： Cheerio 和 lxml (Python) DOM 解析器，Puppeteer 库操控 Headless Chrome 浏览器，熟练运用 Chrome 开发者工具分析数据；了解 XPath、Selenium

运维： Ubuntu/Debian Linux 配置、Docker 容器技术和编排 docker-compose.yml

CS： 常用数据结构与算法，计算机网络分层架构及常见协议，熟悉 HTTP

<br />

熟悉 TypeScript 与 JSDoc，了解 Java (部分Spring)、Python、前端部分 React 和 Vue。

熟悉 Office 技能、工艺数据分析（统计过程控制）建模，了解数字图像处理。 <br />

<br />


## Projects

### __图书库小程序__ `2019.8 - 2019.9`
类豆瓣图书小程序，实现了二维码扫描(微信小程序API)和搜索两种方式添加图书。
初期采用mpvue，后采用Taro (类React) + TypeScript重构，并改用FlexBox布局。豆瓣API不对外开放后，遂采用爬虫获取数据，对照还原了原豆瓣图书API的主要功能。

### __Node.js Headless Chrome 视频爬虫__ `2018.10`
利用 puppeteer 库控制 Headless 浏览器，根据视频相关通用特征（视频和HLS的MIME类型）实现<b>自动监听有效请求</b>（分析response事件），获取视频播放链接。
比对多次监听结果生成相关正则表达式用于提取网站视频 API 的参数，之后不再监听直接通过获得的视频 API 获取播放链接。

### __Array-Implant FDC__ `2017.11 - 2018.6`
独立完成了科室的 FDC 异常侦测与分类系统（统计过程控制）的上线和数据分析建模。将设备的工艺参数实时导入 FDC 系统，根据产线工艺特点建立数据监控模型，实现了关键工艺参数超标时自动预警。定期将各批次的工艺数据导出报告。发现产品不良时将批次工艺数据进行相关性分析匹配，找出异常所在点，便于分析改善。<br />
本项目获2018年度 B7 CIM (计算机集成制造)应用大赛前5强

### __Node.js Express Mongoose 实现的 RESTful 论坛 API__ `2018.7`
Express 控制路由部分，通过 Mongoose 子文档实现了 Model 中帖子和评论的对应关系，并采用 express-validator 进行输入数据的验证。

### __人的行为图像处理算法实验研究__ `2017.5`
利用MATLAB介绍数字图像处理中的高斯滤波空域变换、Canny边缘检测算子、Hough变换边缘跟踪等应用效果。<br />
对图像与静态背景帧相减作差识别出运动人体的前景图像，经二值化和形态学开启运算后，描绘8连通前景区域的外接特征标签矩形，通过计算前景占标签矩形像素比和形心高度变化比值实现了初步的行人跌倒检测。<br />
最后对业界前端的基于方向梯度直方图(HOG)和支持向量机(SVM)的分类器进行了介绍。

### __基于 Google Maps 和图遍历算法的地图路径规划应用__ `2016.11`
将地图路口导出为图类数据，采用层序遍历和 Dijkstra 算法，在 JavaFX UI 和 Google Maps API 上实现了路径规划功能。

<br />


## Hobbies
爱好骑行、乒乓球等


<!-- ### Footer

Last updated: Sept. 2019 -->

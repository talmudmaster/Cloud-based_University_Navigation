<div align="center">

![logo](https://s1.ax1x.com/2023/05/16/p92Ux9U.png) 
    <h1> 2023042719 - 云上高校导航 </h1>

中国大学生计算机设计大赛 广西赛区  
软件应用与开发 - 移动应用开发（非游戏类） 三等奖  

[![gitee_star](https://gitee.com/talmudmaster/Cloud-based_University_Navigation/badge/star.svg?theme=dark)](https://gitee.com/talmudmaster/GLU-Campus-Guide)
[![github_star](https://img.shields.io/github/stars/talmudmaster/Cloud-based_University_Navigation)](https://github.com/talmudmaster/Cloud-based_University_Navigation)
[![license](https://img.shields.io/badge/license-MulanPSL-green)](LICENSE)
[![platform](https://img.shields.io/badge/platform-微信小程序-green)](https://developers.weixin.qq.com/miniprogram/dev/component/)

“云上高校导航”是一套基于小程序云开发的校园导航类系统开发方案。  
该开发方案可供开发者进行二次开发，用于解决师生和访客的校园出行需求。

**[B站演示视频](https://www.bilibili.com/video/BV1xV4y1r7de/)**&emsp;&emsp;**[CSDN开发教程](https://blog.csdn.net/weixin_45940369/category_12316374.html)**

仅需修改部分代码和云端数据，即可**适配任意校园**  

☑️地图选点与搜索  ☑️地图路线规划  ☑️校园信息展示  ☑️在线管理数据

</div>

---
# 📖 作品简介

## 背景

&emsp;&emsp;随着高校规模的扩大和建筑物复杂程度的增加，以及高校对外交流日益频繁，师生和访客在校园内的出行、寻找目的地等问题越来越突出。而市面上存在的校园导航类小程序或APP存在诸多不足。为了解决这些问题，一种高效快捷的校园导航软件迫在眉睫。

## 项目简介

&emsp;&emsp;我们以此为切入点，设计了“云上高校导航”开发方案。“云上高校导航”是一套基于小程序云开发的校园导航类系统开发方案，该开发方案可供开发者进行二次开发，用于解决师生和访客的校园出行需求。

&emsp;&emsp;该型小程序运行在微信平台上，可在Android和IOS系统的手机设备上运行，目标用户为学生和教职工，以及来访的游客。用户可使用该型小程序进行地图浏览、地点查询、路线规划、查看校园信息等操作。该型小程序致力于为学生、教职工和游客提供便利，包括但不限于方便快捷、提升效率、促进交流、宣传学校和改善体验。

&emsp;&emsp;该型小程序采用云开发，结合校园地图，运用微信提供的地图接口、腾讯位置服务API以及腾讯位置服务路线规划插件。该小程序具备路线导航和校园信息介绍功能，并能通过地理位置接口获取实时位置，利用腾讯位置服务路线规划插件实现路线规划和导航功能。

&emsp;&emsp;测试表明，该小程序能够稳定运行，定位速度快，路线规划最短，反应速度快。该小程序的应用价值广泛，可以推广至其他高校，便利师生和访客的出行。

## 项目现状

&emsp;&emsp;我们以本校为案例进行分析、设计、开发、实现、部署和发行了该型小程序，目前用户数累计破千。

&emsp;&emsp;同时，我们也将该方案的项目代码开源于Gitee和GitHub代码托管平台，开发文档公开于CSDN社区，期望可以借此可以推广至其他高校。

## 开源代码使用说明

&emsp;&emsp;借鉴了Gitee代码托管平台上的《信科校园导览》等项目。

---
# 🛠 作品安装说明
&emsp;&emsp;本作品属于小程序，免安装，可直接使用。

&emsp;&emsp;我们以本校为案例进行开发的小程序已经发行，使用微信对小程序码进行扫码查看。

<div align=center>

![](https://s1.ax1x.com/2023/05/28/p9OgTj1.jpg)
</div>

---
# 🤩 作品效果图

1. 主要页面实际效果:
![show_1](https://s1.ax1x.com/2023/05/12/p9sRh4I.png)  

2. 主要页面实际效果
![show_2](https://s1.ax1x.com/2023/04/16/p99G0Jg.png)   

3. 校园信息相关页面实际效果：
![show_3](https://s1.ax1x.com/2023/05/12/p9sRfUA.png)  

4. 校园信息相关页面实际效果：
![show_4](https://s1.ax1x.com/2023/04/16/p99GYLt.png)  

---
# 🔍 设计思路

## 设计思路如下：  

1. 使用小程序作为载体进行开发，免安装，即开即用；
2. 绘制校园地图并将其覆盖在电子地图上展示，使校园地点展示更加清晰明了；
3. 考虑到目标人群的实际需求，对地点进行分类，根据类别展示不同的地点；
4. 图文并茂展示介绍校园的方方面面，让用户在使用时感受到浓厚的校园氛围；
5. 将地图相关数据上云。同时移植数据管理功能到手机上，使数据管理更加便捷；

## 具体设计如下：  

1. 地图界面设计
根据用户的使用场景和需求，设计具有良好视觉效果的地图界面。在地图上标识出重要的建筑物和地点等信息，为用户展示更加清晰的地点信息。

2. 路线规划与导航功能
通过定位接口获取用户当前位置，并利用腾讯位置服务路线规划插件实现路线规划功能，为用户提供最优路线推荐。

3. 校园信息展示
介绍学校、院系、交通出行等信息，并提供相关图片和文字信息。

4. 在线管理
在线管理地点信息和媒体文件。对地点数据进行增加、修改和删除，并能实时在地图上反映变化。

---
# ✨ 设计重点难点

1. 地图数据获取与处理  
&emsp;&emsp;地图数据的获取与处理是校园导航的基石，尤其是地点坐标，这是设计难点之一。获取详细的校园地图数据，并进行数据处理，确保地图数据的准确性。  
&emsp;&emsp;其中地点的坐标获取方式为，在地图选点页面选择地点后小程序会自动获取坐标。无需手动输入。

2. 界面设计  
&emsp;&emsp;由于面向大学师生和访客使用，界面需要友好简洁。需要提供清晰的地图展示和路线规划结果，信息展示也要简明直观。这需要设计人员既要关注美观，也要确保功能的合理性和易用性。  
&emsp;&emsp;在进行界面设计时参考了市面上相似的产品的界面风格。

3. 功能设计  
&emsp;&emsp;要根据用户需求设计合适的功能，如地图和路线展示功能是核心，信息展示也很重要。但加入太多功能会造成小程序过于臃肿和用户体验差，所以功能设计需要慎重考虑,确保每项功能的必要性。  
&emsp;&emsp;在进行功能设计时参考了市面上相似的产品的功能设计，借鉴了一些论文的想法。

4. 系统性能  
&emsp;&emsp;小程序作为轻量级系统，性能有瓶颈，特别是地图功能打开后，会有较大性能消耗。所以在设计地图和路线规划功能的时候，要考虑优化性能，使得小程序体验流畅。

&emsp;&emsp;综上，校园导航小程序的设计难点主要集中在地图与定位的实现，以及与此相关的界面友好性和系统性能。要综合考虑这几个方面，提供一个易于使用且高效的校园导航小程序。谨慎的页面设计和功能设计也是关键点。 

---
# 🗃 其他说明

1. 作品开源情况  
&emsp;&emsp;我们将该方案的项目代码开源于Gitee和GitHub代码托管平台，开发文档公开于CSDN社区，期望可以借此可以推广至其他高校。

<div align=center>

|  平台  |  网址  |
|  ----  | ----  |
|  Gitee  | [云上高校导航](https://gitee.com/talmudmaster/Cloud-based_University_Navigation)  |
|  GitHub  | [Cloud-based_University_Navigation](https://github.com/talmudmaster/Cloud-based_University_Navigation)  |
|  CSDN  | [云上高校导航 小程序 开发教程](https://blog.csdn.net/weixin_45940369/category_12316374.html)  |
</div>

2. 小程序运行现状  
&emsp;&emsp;我们以本校为案例进行分析、设计、开发、实现、部署和发行了该型小程序，目前用户数累计破千。

---
# ⚙ 安装教程

&emsp;实在太长了就放CSDN了，见谅

1. [导入与配置教程](https://blog.csdn.net/weixin_45940369/article/details/130918816)

2. 修改项目/二次开发：
- CSDN：[云开发项目复刻教程](https://blog.csdn.net/weixin_45940369/article/details/130693234) **不感兴趣或没时间可以不看，直接看下面的**
- CSDN：[云开发项目二次开发教程](https://blog.csdn.net/weixin_45940369/article/details/130695720)

3. **刷新或重启** 项目

4. CSDN：[小程序 发行 / 发布 教程](https://blog.csdn.net/weixin_45940369/article/details/130693653)

5. CSDN：[开发指引 与 注意事项](https://blog.csdn.net/weixin_45940369/article/details/130918773)

---
# 🧾 参考资料

- [微信官方文档 · 小程序](https://developers.weixin.qq.com/miniprogram/dev/framework/)
- [莞香广科 · 校园导览](https://gitee.com/hm_anwei/school-map)
- [信科校园导览](https://gitee.com/talmudmaster/GIIT-campus-guide)
- [地大校园导航](https://gitee.com/min_yue/CUG_Campus-navigation)
- [案例分享丨如何设计校园导航系统](https://itc.jnmc.edu.cn/2021/0621/c1949a121868/pagem.htm)

---
# 📒 开源许可证
 
请 **认真阅读并遵守** 开源协议 [MulanPSL-2.0](LICENSE)

项目开源，持续维护，欢迎 [反馈](https://gitee.com/talmudmaster/GLU-Campus-Guide/issues) 、[拉取](https://gitee.com/talmudmaster/GLU-Campus-Guide/pulls) 和 STAR⭐️！

允许任何人对该项目进行变动

同时 **欢迎各位开发者参与到该项目** (在软件声明与致谢页面加入参与贡献者名称)

**禁止用于商业和非法目的**，使用代码 **请标明出处或有所声明**  

---
# ❤ 致谢

&emsp;&emsp;非常感谢以下的小程序开发者和B站up，以及教会、锻炼我PS能力的校红会小伙伴。让我学到了很多，得以把小程序做到今天这样完整。  

![thank](https://s1.ax1x.com/2023/04/16/p99GwFS.png)

&emsp;&emsp;同时也要感谢b站 @宙克儿 帮忙测试云开发项目的安装，帮我找出了许多问题。
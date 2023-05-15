<div align="center">

![logo](https://s1.ax1x.com/2023/05/16/p92Ux9U.png) 
    <h1> 云上高校导航 小程序 </h1>

[![gitee_star](https://gitee.com/talmudmaster/Cloud-based_University_Navigation/badge/star.svg?theme=dark)](https://gitee.com/talmudmaster/GLU-Campus-Guide)
[![github_star](https://img.shields.io/github/stars/talmudmaster/Cloud-based_University_Navigation)](https://github.com/talmudmaster/Cloud-based_University_Navigation)
[![license](https://img.shields.io/badge/license-MulanPSL-green)](LICENSE)
[![platform](https://img.shields.io/badge/platform-微信小程序-green)](https://developers.weixin.qq.com/miniprogram/dev/component/)

提供**校园导航和校园信息**服务，具有出色的用户体验  

同时也对**小屏手机和平板**做了前端适配优化

**[B站讲解演示教学视频合集](https://space.bilibili.com/384844986/channel/collectiondetail?sid=1197124)**&emsp;**[CSDN开发笔记](https://blog.csdn.net/weixin_45940369/category_12257059.html)**

仅需修改部分代码和云端数据，即可**适配任意校园**  

☑️地图选点与搜索  ☑️地图路线规划  ☑️校园信息展示  ☑️在线管理数据

</div>

---
# 📖 介绍  

&emsp;&emsp;“云上高校导航”是一套基于小程序云开发的校园导航类系统开发方案，该开发方案可供开发者进行二次开发，用于解决师生和访客的校园出行需求。

&emsp;&emsp;该型小程序致力于为学生、教职工和游客提供便利，包括但不限于方便快捷、提升效率、促进交流、宣传学校和改善体验。

---
# 🤩 预览

![show_1](https://s1.ax1x.com/2023/05/12/p9sRh4I.png)  

![show_2](https://s1.ax1x.com/2023/04/16/p99G0Jg.png)   

![show_3](https://s1.ax1x.com/2023/05/12/p9sRfUA.png)  

![show_4](https://s1.ax1x.com/2023/04/16/p99GYLt.png)  

---
# ✨ 项目优势及创新

- 使用小程序作为载体进行开发，免安装，即开即用
- 绘制校园地图并将其覆盖在电子地图上展示，使校园地点展示更加清晰明了
- 考虑到目标人群的实际需求，对地点进行分类，根据类别展示不同的地点
- 图文并茂展示介绍校园的方方面面，让用户在使用时感受到浓厚的校园氛围
- 将地图相关数据上云。同时移植数据管理功能到手机上，使数据管理更加便捷
- 项目及开发文档现已开源，可以进行二次开发以拓展到其他高校

---
# ⚡️ 功能

- ✅ 校园地点分类动态展示
- ✅ 地点选择与搜索
- ✅ 路线规划
- ✅ 校园信息
- ✅ 可跳转至学校官微/招生小程序
- ✅ 在线管理地点数据、媒体文件（校园地图、封面、轮播图及视频）

---
# 📝 使用说明

![instruction](https://s1.ax1x.com/2023/04/16/p99GGQA.png)

---
# ⚙ 安装教程

1. 开通 **云开发** 功能（首月免费，次月19.9），**激活** 云数据库、云存储和云函数 功能。

2. 将 项目 文件夹下 **最新版本的** 文件夹下的 **Cloud-based_University_Navigation** 整个文件夹 复制到项目路径下（比如 D:\WeChatProjects），**强烈建议不要直接扔桌面上**。

3. 使用 微信开发者工具 **导入项目**（导入时要**点进项目文件夹里**，AppID改为自己的）

![import](https://s1.ax1x.com/2023/04/20/p9kmUO0.png)

4. 填写 utils.js 中的 [腾讯位置服务API](https://blog.csdn.net/weixin_45940369/article/details/130529860) 和 [和风天气API](https://blog.csdn.net/weixin_45940369/article/details/130531131) 的 key（点击查看教程）

![write_api](https://s1.ax1x.com/2023/04/20/p9kmNyq.png)

5. 进入 [小程序管理后台](https://mp.weixin.qq.com/) ，申请 [小程序地理位置接口](https://blog.csdn.net/weixin_45940369/article/details/128951841) 和 [腾讯位置路线规划插件](https://blog.csdn.net/weixin_45940369/article/details/129927351)（点击查看教程）

6. 进入 [小程序管理后台](https://mp.weixin.qq.com/) - 开发 - 开发管理 - 开发设置 - 服务器域名，填写 **request合法域名**（地图和天气API的域名）
```
https://devapi.qweather.com
https://geoapi.qweather.com
https://restapi.amap.com
https://servicewechat.com
```

7. 修改项目/二次开发（实在太长了就放CSDN了，见谅）：
- CSDN：[云开发项目复刻教程](https://blog.csdn.net/weixin_45940369/article/details/130693234) **不感兴趣或没时间可以不看，直接看下面的**
- CSDN：[云开发项目二次开发教程](https://blog.csdn.net/weixin_45940369/article/details/130695720)

8. **刷新或重启** 项目

9. CSDN：[小程序 发行 / 发布 教程](https://blog.csdn.net/weixin_45940369/article/details/130693653)

---
# 🔬 注意事项

1. 大部分数据存储在utils.js中的，页面通过引入utils.js方式渲染数据

2. 图标全部存储在项目images文件夹里,均下载自 [iconfont网站](https://www.iconfont.cn/)（自行替换）

3. 部分图片引用自 **免费图床** - [CDN加速图床](https://cdnjson.com/)（自行替换）

4. 若图片过大加载较慢，可 **压缩图片** 再上传 [图片压缩网站](http://jisu123.cn/)

5. 还有一些细节，之后会在 [b站教学视频](https://space.bilibili.com/384844986/channel/collectiondetail?sid=1197124) 里说明

6. 因个人小程序限制，无法使用web-view渲染外部网站，故使用跳转外部小程序（**小外链**）方式打开外部网页（自行测试，部分网页打不开。**小外链只是渲染网页，不是真实网站**） 

7. 在 微信开发者工具 的 路线规划页面 会出现奇怪的一直向下拉动画面的情况。这个是bug，不用管，在手机上预览是正常的。

![bug](https://s1.ax1x.com/2023/05/07/p9dpNYF.png)

---
# 🧭 开发指引

本小程序开发所使用技术及外部接口  

![technology](https://s1.ax1x.com/2023/05/07/p9dpUW4.png)

如不想花太多时间在前端，可考虑使用 **UI组件库**。  

|  UI组件库  |  介绍  |  官网  |
|  ----  | ----  |  ---- |
|  weui  |  官方量身设计的基础样式库  |  [官网链接](https://weui.io/)  |
|  ColorUI  |  专注视觉的小程序组件库  |  [官网链接](http://docs.xzeu.com/#/)  |
|  Vant Weapp  |  轻量、可靠的小程序 UI 组件库  |  [官网链接](https://vant-contrib.gitee.io/vant-weapp/#/home)  |
|  其他  |  点击文章查看更多小程序 UI 组件库  |  [文章链接](https://www.cnblogs.com/pwindy/p/15964029.html)  |


---
# ⭐️ bilibili技术视频推荐

|  类别  |  up  |  视频  |
|  ----  | ----  |  ---- |
| 小程序开发  |    |    |
|    |  @yinghua--p  |  [从零开始制作微信小程序](https://www.bilibili.com/video/av821561390/)  |
|  地图开发  |    |    |
|    |  @流红艳紫  |  [20200222微信小程序第三次课(地图与定位)](https://www.bilibili.com/video/av90942776/)  |
|    |  @greengis  |  [湖师 \| 微信小程序 \| 03 \| 小程序地图与导航](https://www.bilibili.com/video/av338851271/)  |
|    |  @riny的前端冒险之旅   |  [2021全网最新微信小程序地图及导航功能](https://www.bilibili.com/video/av459485208/)  |
|    |  @毕业设计和教育  |  [微信小程序-定位和地图](https://www.bilibili.com/video/av60522448/)  |
|  小程序云开发  |    |    |
|   |  @编程小石头  |  [零基础入门小程序云开发](https://www.bilibili.com/video/av843732850/)  |
|   |  @big曾  |  [微信小程序云开发教程](https://www.bilibili.com/video/av861130789/)  |
|  作者  |     |     |
|    |  @奇妙方程式  |  [毕设-桂院导航小程序](https://space.bilibili.com/384844986/channel/collectiondetail?sid=1197124)  |

---
# 🎈 远期构想
对于外校（或未来本校扩建）而言，小程序是需要修改的。如果想在此基础上开发，需注意：
- 多校区的学校的开发者要思考下如何修改项目   
- 校园地图需重新绘制（以后在b站出0基础画简单地图的教程），本校的可在我的地图上用PS继续绘制。

- 如果腾讯地图的展示效果原本就很好，就无需再覆盖校园地图。

- **更好的路线导航方式** 是自己绘制“图”，并使用最短路径算法实现（下面给出案例图和讲解）。     
![build_map](https://s1.ax1x.com/2023/04/16/p99GJsI.png) 
图中红色点为地点，蓝色点为道路点。蓝色线段即为点之间的关系（一个道路点能够到达其他的什么点）。就可以模拟出“图”以及其所有点之间的关系。点与点之间“路”的长度可以通过公式计算出（**注意地球是球体-曲面，经纬度计算距离的公式可以百度**）。有了点之间的关系以及“路”（边）的长度，通过最短路径算法计算出最短路经过的所有点并通过ployline显示到地图上（可以尝试使用动画/轨迹来渲染路线）。  

- **更好的展示效果** 可以考虑加入室内（外）导航功能、AR实景导航功能  

- **更加充实的校园功能** 可以考虑加入校园信息公告栏、留言栏等功能。如果可以连上学校的教务系统，那就可以实现更多功能（课表、上课提醒、选课、成绩、自动计算学分绩点、活动通知、会议提醒、提交材料等）。  

-  **渲染外部网站** 有渠道的开发者可以申请企业小程序（或者能够使用学校官方小程序进行开发），使用web-view渲染外部网站（全景地图、学校官网、学生系统等），展示效果会非常棒。

---
# 🧾 参考资料

- [微信官方文档 · 小程序](https://developers.weixin.qq.com/miniprogram/dev/framework/)
- [莞香广科 · 校园导览](https://gitee.com/hm_anwei/school-map)
- [信科校园导览](https://gitee.com/talmudmaster/GIIT-campus-guide)
- [地大校园导航](https://gitee.com/min_yue/CUG_Campus-navigation)
- [案例分享丨如何设计校园导航系统](https://itc.jnmc.edu.cn/2021/0621/c1949a121868/pagem.htm)

---
# 📒 开源许可证
 
请 **认真阅读并遵守** 以下开源协议

[MulanPSL-2.0](LICENSE)

项目开源，持续维护，欢迎 [反馈](https://gitee.com/talmudmaster/GLU-Campus-Guide/issues) 、[拉取](https://gitee.com/talmudmaster/GLU-Campus-Guide/pulls) 和 STAR⭐️！

允许任何人对该项目进行变动

同时 **欢迎各位开发者参与到该项目** (在软件声明与致谢页面加入参与贡献者名称)

**禁止用于商业和非法目的**，使用代码 **请标明出处或有所声明**  

---
# ❤ 致谢

&emsp;&emsp;非常感谢以下的小程序开发者和B站up，以及教会、锻炼我PS能力的校红会小伙伴。让我学到了很多，得以把小程序做到今天这样完整。  

![thank](https://s1.ax1x.com/2023/04/16/p99GwFS.png)

&emsp;&emsp;同时也要感谢b站 @宙克儿 帮忙测试云开发项目的安装，帮我找出了许多问题。
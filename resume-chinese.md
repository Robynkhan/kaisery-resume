# 简历

## 个人信息

|  姓名  |  性别  |  生年  | 所在地  |        手机        |            邮箱            |
| :--: | :--: | :--: | :--: | :--------------: | :----------------------: |
|  岳洋  |  男   | 1991 |  天津  | MTM4MjEwNjc0MDc= | OTk1MTM3MzAyQHFxLmNvbQ== |

## 简述

- 靠谱软件开发者，善于解决技术问题，期望从事全栈开发工作
- 编程语言： `Java`、`Typescript`
- 技术来源：`Hacker News`、`InfoQ`、`36Kr`、`DZone`、`Phoronix`、`V2EX`
- 科学上网：`Vultr Tokyo + SSR + BBR`
- 英语：`CET6`、[rust book 第一版翻译][rust-book-chinese]、[rust book 第二版翻译][trpl-zh-cn]
- 日语：`N1`

[rust-book-chinese]: https://github.com/KaiserY/rust-book-chinese
[trpl-zh-cn]: https://github.com/KaiserY/trpl-zh-cn

## 教育

天津科技大学 国际学院 计算机科学与技术专业 `2009 - 2013` 本科

## 工作经历

---

### 天津书生云科技有限公司

> 2016 年 4 月 - 至今

#### *项目：书生企业云盘 2.x*

> 2016 年 4 月 - 2017 年 4 月

- 企业级云盘产品，多节点高可用以及文件加密。本人主要负责 2.1 - 2.3 版本的迭代开发；文件在线预览模块；前端浏览器兼容性；以及一些客户现场定制。
- 帮助团队维护新版 GitLab 与开发环境服务器。
- 预览模块支持 `mp3/mp4`、文本、`PDF`、图片等，根据插件的不同 Office 文件可以实现在线编辑与协同办公。

#### *项目：书生企业云盘 3.0*

> 2017 年 - 至今

- 2.x 云盘的新版本，支持多数据中心，前后端分离，高定制化。本人主要负责 web 前端构架设计与开发；文件预览在线模块；单点登陆模块。
- 前端框架为 `Avalon 2`、UI 框架为 `Bootstrap 3`、开发语言为 `TypeScript`；兼容到 `IE8`，支持多语言、换肤、消息通知等；采用 `Webpack` 打包，支持压缩、混淆；
- 前端采用 `MVVM` 模式开发，充分利用 `TypeScript` 的类型优势，将模型与服务从 VM 中分离，提高性能和兼容性；充分利用框架的组件功能提高代码复用和控制数据流；API 接口层全部采用 Promise 实现，提供了更好的异步开发体验。

---

### 天津南大通用数据技术股份有限公司 

> 2015 年 4 月 - 2016 年 4 月

#### *项目：数据观（shujuguan.cn）*

> 2015 年 4 月 - 2016 年 4 月

- 互联网+ 数据可视化分析产品（SaaS），意在与 `SiSence` 和 `DataHero` 等产品竞争。敏捷团队，Scrum + Kanban。
- 用户故事：
  - Spring MVC 后台服务：数据类型与格式识别、第三方数据源支持（OAuth 2.0）、单元测试。
  - 帮助团队从 SVN 迁移到 Git：维护 GitLab；制定 Git Workflow；以 `Sprint` 为周期（每两周）的集成分支；Git submodule。
  - 基于 Express 的百度位置查询服务 & 图表推荐服务。CORS、node cluster、MongoDB 缓存。
  - 基于 ELK 的系统日志 & 用户行为收集系统。
- **程序栈：** **Spring MVC**、**JUnit**、**JMeter**、**Findbugs**、**Apache POI**、`Morphia`、`Logback`、**Express**、`Babel`、`Jasmine`、`TypeScript`
- **数据栈：** **MongoDB**、`GBase 8a`、`Redis`、`MySQL`
- **DevOps 栈：** **GitLab**、**Asana**、**Jenkins**、**Maven**、**Gulp**、**ELK**、`Docker`
- **总结：** 在敏捷的互联网团队工作。有机会对各种技术和系统构架都进行了尝试。

---

### 皖通科技研发中心（天津） 

> 2012 年 11 月 - 2015 年 4 月

#### *项目：安徽省高速公路收费系统*

> 2012 年 11 月 - 2014 年 1 月

- 桌面客户端软件。本人主要负责维护硬件交互接口和按照新需求添加功能。
- 技术主要涉及串口连接，自定义 TCP 协议以及调用动态库。
- **技术栈：** **C#(.NET 4.0)**、**WinForm**、`SQL Server`、`SVN`、`JIRA`
- **总结：** 这个项目的工作经历教会了我使用 C# 开发企业级应用，熟悉了版本控制(SVN)以及项目管理(JIRA)。

#### *项目：安徽省高速收费扁平化项目*

> 2014 年 1 月 - 2015 年 4 月

- 此为之前项目的新版本，规模更大，涉及到整个系统。全部由 Java 编写，主要运行环境由 Windows 切换到 Linux。
- 参与到项目车道收费部分的设计和开发。主要负责设计和实现整个硬件交互接口，Windows 与 Linux 平台兼容性以及新老系统业务数据的转换。
- 整个设备层采用多线程异步回调实现。每个设备对应一个执行线程，由一个状态线程监控所有设备执行线程的状态，适时回收资源和应对异常。大部分设备接口是异步的，通过回调发事件通知流程图。
- 解决技术问题，例如分析 JVM 的 heapdump 查找内存泄漏；使用 jmc、jvisualvm 等工具监控 JVM 状态；修改设备驱动代码以方便 JNA 调用。
- **技术栈：** **Spring**、**Maven**、**Hudson**、**Findbugs**、**Xuggle**、**SWT**、**AWT**、**LINQ**、`H2`、`Activiti`、`Kafka`、`Sigar`、`SVN`、`JIRA`、`SQL Server`
- **总结：** 这是一次比较完整的 Java 项目经历，本人参与了从设计到试运行的阶段。

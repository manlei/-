<h1 align=center> SchoolInApp工作日志 </h1>  

## 目录  

1. 项目前期准备  

2. 项目客户端工作日志  

3. 项目服务器端工作日志  

### (1) 项目前期准备  

* 确立用户需求和第一次讨论（2017/3/17）  
>由李聪，满磊，冯伟赞，陆萍，朱修宇五位同学组成SchoolInApp开发小组，由葛笑飞学长指导我们开发。张天老师扮演用户，提出用户需求，2017/3/17日小组进行第一次讨论，会议主要包括git、gitlab使用；前后端分工，李聪为机动人员，满磊、陆萍负责前端开发，冯伟赞、朱修宇负责服务器端开发；确定近期目标，设计RESTful API；前端开发人员熟悉Android开发，服务器端开发人员了解springMVC；参考RESTful API如何设计；前端设计人员需要设计界面初稿；项目成员完成RESTful API的设计之后提交到gitlab dev分支；每周五开一次组会。

* 第一次组会（2017/3/24）  
>前端设计人员讲解自己对Android开发的了解进度，同时前端开发人员需要每人提交一份对前端界面设计的初稿，大家商议选取哪些作为我们最终的界面；前端开发人员和服务器端开发人员都需要设计RESTful API，对RESTful API设计进行分工。

* 第二次讨论（2017/3/27）
>讨论工作室的运行模式（谁来回答、其他人是否可见、推送到谁等问题）；合作设计一套 RESTful API，在设计时可能要提前/一并考虑各种数据对象在数据库中的储存；
前端先搭建一个简单可运行的完整 Android 项目，可以只包含注册、登录界面；后端相应提供一个带有注册、登录功能的服务，将两者连接起来。

* 小组会议(2017/4/5)  
>RESTful_API修改建议，
统一一下标识符，保证不同地方对同一个东西的描述一定要一致
加强对RESTful的理解，什么是资源？什么是API自描述？
Content与Details一定要对应，且保证一定可以跳转
写文档时编辑器把tab大小设置成2个空格，并用空格代替tab
每个API的详细描述后面加一个back to Content跳转
代码缩进缩好
GET方法的template和POST请求体一定要一致
所有API一定以/api/开头，以/结尾
与id相关的需要添加404(DELETE方法不用添加)
user,question,answer的API提出修改意见。
回答和评论的删除权限归谁掌管？答主和评论者还是问题提问者或者工作室?
关注者的管理权限问题，同上。


### (2) 客户端工作日志  


### (3) 服务器端工作日志  

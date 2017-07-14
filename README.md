<h1 align=center> SchoolInApp工作日志 </h1>  

## 目录  

1. 项目前期准备  

2. 项目客户端工作日志  

3. 项目服务器端工作日志  

### (1) 项目前期准备  

* 确立用户需求和第一次讨论（2017/3/17）  
    
    * 李聪，满磊，冯伟赞，陆萍，朱修宇五位同学组成SchoolInApp开发小组  
    
    * 由葛笑飞学长指导开发  
    
    * 张天老师扮演用户，提出用户需求  
    
    * 2017/3/17日小组进行第一次讨论
    
      * git、gitlab使用  
      
      * 前后端分工，李聪为机动人员，满磊、陆萍负责前端开发，冯伟赞、朱修宇负责服务器端开发  
      
      * 确定近期目标  
      
      * 设计RESTful API  
      
      * 前端开发人员熟悉Android开发，服务器端开发人员了解springMVC  
      
      * 参考RESTful API如何设计  
      
      * 前端设计人员需要设计界面初稿  
      
      * 项目成员完成RESTful API的设计之后提交到gitlab dev分支  
      
      * 每周五开一次组会  
        
        
* 第一次组会（2017/3/24）  

    * 前端设计人员讲解自己对Android开发的了解进度  
    
    * 前端开发人员需要每人提交一份对前端界面设计的初稿  
    
    * 大家商议选取哪些作为我们最终的界面  
    
    * 对RESTful API设计进行分工,前端开发人员和服务器端开发人员都需要设计RESTful API  
        
        * 满磊负责回答的 API  
        
        * 李聪负责工作室 API  
        
        * 冯伟赞负责用户 API  
        
        * 朱修宇负责文章、评论 API  
        
        * 陆萍负责问题 API  
          
          
* 第二次讨论（2017/3/27）  

    * 讨论工作室的运行模式（谁来回答、其他人是否可见、推送到谁等问题）  
    
    * 合作设计一套 RESTful API，在设计时可能要提前/一并考虑各种数据对象在数据库中的储存  
    
    * 前端先搭建一个简单可运行的完整 Android 项目，可以只包含注册、登录界面  
    
    * 后端相应提供一个带有注册、登录功能的服务，将两者连接起来  
      
      
* RESTful API 修改意见(2017/4/5)  
    
    * 提出RESTful_API修改建议  
    
    * 统一标识符，保证不同地方对同一个东西的描述一定要一致  
    
    * 加强对RESTful的理解，什么是资源？什么是API自描述？  
    
    * Content与Details一定要对应，且保证一定可以跳转  
    
    * 写文档时编辑器把tab大小设置成2个空格，并用空格代替tab  
    
    * 每个API的详细描述后面加一个back to Content跳转  
    
    * 代码缩进缩好  
    
    * GET方法的template和POST请求体一定要一致  
    
    * 所有API一定以/api/开头，以/结尾  
    
    * 与id相关的需要添加404(DELETE方法不用添加)  
    
    * user,question,answer的API提出修改意见。  
    
    * 回答和评论的删除权限归谁掌管？答主和评论者还是问题提问者或者工作室?  
    
    * 关注者的管理权限问题，同上。  
      
      
* 讨论总结（2017/4/7）  
    
    * 大家各自介绍了自己API的设计 
    
    * 返回体冗余，返回了许多不必要的东西  
    
    * 冗余的东西造成流量浪费  
    
    * 前端搭建一个简单可运行的完整 Android 项目，可以只包含注册、登录界面  
    
    * 后端相应提供一个带有注册、登录功能的服务，将两者连接起来。  
      
      
* 需求更改（2017/4/22）  
    
    * 与客户(张老师团队)的会议讨论，我们进一步明确了需求  
    
    * RESTful_API修改与讨论  
    
    * 明确界面跳转及设计  
    
    * 初步确定迭代开发周期  
      
      
* 确定RESTful API(2017/4/28)  

    * 小组成员分别讲述自己设计的API  
    
    * 由其他成员提出修改意见  
    
    * 讨论未来客户端的分工问题，服务器端的分工问题

### (2) 客户端工作日志  

* 客户端项目启动（2017/4/23）  

    * 项目创建SchoolInApp仓库，每个人分别建立各自的分支  
    
    * 每个组员分配任务，满磊负责搜索的设计，陆萍负责评论、答案、问题、文章的显示  
    
    * 李聪负责个人信息的显示  
        
        
* 第一次合并分支（2017/5/8）  

    * 前端人员合并自己的分支到dev分支，并报告自己的任务进展  
    
    * 小组成员完后界面的展示，但是没有网络连接，暂时不能显示网络数据。

* 第二次合并分支（2017/5/26）  

    * 小组成员报告自己的项目进展  
    
    * 添加网络请求模块  
    
    * 每个成员都需要按照RESTful API在自己的模块里添加网络请求，使用自己的界面显示网络数据。  
      
      
* 第三次合并分支（2017/5/30）  
    
    * 小组成员针对上一次出现的bug进行测试，修改  
    
* 第四次合并分支（2017/6/6）  
    
    * 增加新的功能，增加提问和发文章功能  
    
    * 发布普通文本的问题和文章  
    
    * 及时修改在测试中发现的问题  
      
      
* 第五次合并分支（2017/6/16）  

    * 增加新功能，发布富文本的问题和文章  
    
    * 添加通知页面  
    
    * 添加全局用户信息  
    
    * 继续修改上一次出现的bug  
      
      
* 第六次合并分支（2017/6/24）

    * 在回答页面添加富文本编辑器  
    
    * 修改之前合并出现的BUG

* 第七次合并分支 （2017/7/10） 

    * 增加新功能，增加HTTPS功能  
    
    * 添加语音提问和语音发布文章  
    
    * 增加长按删除按钮  
    
    * 修改发现的新的bug

* 下一次（暂时未定）

### (3) 服务器端工作日志  

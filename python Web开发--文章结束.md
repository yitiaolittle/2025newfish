## python Web开发：

在web开发中往往采用前后端分离的设计，即前端主要处理页面响应、与用户的界面交互，一般将数据按照json格式规范化后以表单，url等形式传递到后端对应的函数入口，由后端统一处理。这里介绍的flask主要用于后端处理，不涉及前端界面。

1. **后端（快速上手部分）：**
    
    [Flask 中文网](https://flask.net.cn/)
    
2. **前端**（推荐使用VUE，不做要求限制，可自行根据目前主流前端框架选择）
    
    [Vue3 教程 | 菜鸟教程](https://www.runoob.com/vue3/vue3-tutorial.html)
    
3. **中间件交互**（在高并发、或数据处理时间较长的任务中使用）。在web开发过程中，部分任务页面响应有一定速度要求，但是该任务中存在大量的数据运算步骤，此时需要使用高并发中间件起到缓冲作用（类似与提交工单，页面反馈已经收到数据处理要求，此时前端界面已经完成，后端开始数据处理任务，此时前端不在与后端进行交互，等后端完成后，通过中间件向前端发送消息，前端可以以邮件、弹窗等方式通知用户查看数据处理结果）。

    中间件的安装与使用：

    https://github.com/nsqio/nsq

    基于python的nsq包使用和说明文档

    https://github.com/nsqio/pynsq




## python 时序数列分析：


1. 必须要掌握的库：[Numpy](https://www.numpy.org.cn/user/)、[Pandas](https://www.pypandas.cn/docs/)
2. 学习资料。
    
    [JoinQuant聚宽量化投研平台](https://www.joinquant.com/)
    
    [量化课堂 - JoinQuant](https://www.joinquant.com/study?f=home&m=memu)
    

# SpringBoot

练习时常用的环境配置：

1. jdk8
2. maven
3. IDEA
4. Tomcat
5. mysql

不要从0开始，直接实现一个项目。

[2小时急速上手SpringBoot（儿童版）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Es4y1Q7Ms/?spm_id_from=333.337.search-card.all.click&vd_source=be08cd9cc4a3d6f3fec83590352fca21)

[1天搞定SpringBoot+Vue全栈开发_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1nV4y1s7ZN/?spm_id_from=333.337.search-card.all.click&vd_source=be08cd9cc4a3d6f3fec83590352fca21)

知道开发流程后，可以细看铁路项目。

#

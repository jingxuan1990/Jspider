# Jspider
想法来自于Python的框架Pysider和Scrapy，以求实现一个能支持400站点以上规模的，高效的基于分布式的爬虫。这里我们选择重复造车轮子，完全采用Java实现（或者基于JVM的语言），目的在于提供给Java开发者一个便携式的爬虫解决方案。

# 设计目标
 1. 支持任何类型网站的爬取。
 2. 支持分布式部署。
 3. 支持海量的url去重（设计目标100亿 ）。
 4. 宕机自动恢复；断点续爬等。
 5. 爬虫脚本的动态修改，在线编辑和Debug功能。
 6. 提供强大的UI监控。
 7. 支持Ajax的方式的爬取，支持第三方组件PhantomJs等。
 8. 支持常见的中间件，如RabbitMQ, Kafka, Redis等。
 9. 支持MySQL, MongoDB, Elasticsearchb, HBase, Hadoop等的存储支持。
 10. 支持js, python语法和可视化界面的url规则编写。
 11. 支持Cookie跟踪，自动论坛回复，自动登录功能。
 12. 验证码识别（基于人工打码或者机器学习）。
 13. ...

# Todo List
 1. 核心组件的架构设计(WelUI, Scheduler, Fetcher, Processor)。
 - WebUI
 - dwf 

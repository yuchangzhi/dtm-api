# 数据共享交换

#### 介绍
主要作用于不通数据库的数据共享交换,数据拆分聚合,可实现点对点,点对多点,多点对多点网状拓扑结构,性能数据测试mysql单表过亿数据,抽取2000条耗时,30到400毫秒,插入2000条数据平均耗时100毫秒到6秒.具体以机器性能cpu8核,内存32G固态硬盘2T为研判标准.

这个工具主要是我做大数据时设计的.
当时的业务场景是需要从很多部门迁移基础数据,清洗转换后存到基础信息库里.因为当时涉及当单项网闸,传统的数据库不能直接同步,所以开发了这个插件.他的主要用途就是数据传输,数据清洗,多库数据交换.

http端口8095
https端口8096试用版未开放
#### 软件架构

spring boot与vue


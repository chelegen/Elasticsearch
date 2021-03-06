# Summary

-----
* [序言](README.md)

-----
* [前言](1Preface.md)
  * [谁应该读这本书](1Preface.md#谁应该读这本书)
  * [为什么我们要写这本书](1Preface.md#为什么我们要写这本书)
  * [Elasticsearch版本](1Preface.md#Elasticsearch版本)
  * [如何读这本书](1Preface.md#如何读这本书)
  * [本书导航](1Preface.md#本书导航)
  * [在线资源](1Preface.md#在线资源)
  * [本书协议约定](1Preface.md#本书协议约定)
  * [使用代码示例](1Preface.md#使用代码示例)
  * [鸣谢](1Preface.md#鸣谢)
  
-----
* [基础入门](2_1_Introductory.md)
  * [你知道的, 为了搜索…](2_1_Introductory.md#你知道的为了搜索)
    * [安装并运行Elasticsearch](2_1_Introductory.md#安装并运行Elasticsearch)
    * [安装Sense](2_1_Introductory.md#安装Sense)
    * [和Elasticsearch交互](2_1_Introductory.md#和Elasticsearch交互)
    * [面向文档](2_1_Introductory.md#面向文档)
    * [适应新环境](2_1_Introductory.md#适应新环境)
    * [索引雇员文档](2_1_Introductory.md#索引雇员文档)
    * [检索文档](2_1_Introductory.md#检索文档)
    * [轻量搜索](2_1_Introductory.md#轻量搜索)
    * [使用查询表达式搜索](2_1_Introductory.md#使用查询表达式搜索)
    * [更复杂的搜索](2_1_Introductory.md#更复杂的搜索)
    * [全文搜索](2_1_Introductory.md#全文搜索)
    * [短语搜索](2_1_Introductory.md#短语搜索)
    * [高亮搜索](2_1_Introductory.md#高亮搜索)
    * [分析](2_1_Introductory.md#分析)
    * [教程结语](2_1_Introductory.md#教程结语)
    * [分布式特性](2_1_Introductory.md#分布式特性)
    * [后续步骤](2_1_Introductory.md#)
  * [集群内的原理](2_1_Introductory.md#集群内的原理)
    * [空集群](2_1_Introductory.md#空集群)
    * [集群健康](2_1_Introductory.md#集群健康)
    * [添加索引](2_1_Introductory.md#添加索引)
    * [添加故障转](2_1_Introductory.md#添加故障转)
    * [水平扩容](2_1_Introductory.md#水平扩容)
    * [应对故障](2_1_Introductory.md#应对故障)
  * [数据输入和输出](2_1_Introductory.md#数据输入和输出)
    * [什么是文档?](2_1_Introductory.md#什么是文档)
    * [文档元数据](2_1_Introductory.md#文档元数据)
    * [索引文档](2_1_Introductory.md#索引文档)
    * [取回一个文档](2_1_Introductory.md#取回一个文档)
    * [检查文档是否存在](2_1_Introductory.md#检查文档是否存在)
    * [更新整个文档](2_1_Introductory.md#更新整个文档)
    * [创建新文档](2_1_Introductory.md#创建新文档)
    * [删除文档](2_1_Introductory.md#删除文档)
    * [处理冲突](2_1_Introductory.md#处理冲突)
    * [乐观并发控制](2_1_Introductory.md#乐观并发控制)
    * [文档的部分更新](2_1_Introductory.md#文档的部分更新)
    * [取回多个文档](2_1_Introductory.md#取回多个文档)
    * [代价较小的批量操作](2_1_Introductory.md#代价较小的批量操作)
  * [分布式文档存储](2_2_Introductory.md#分布式文档存储)
    * [路由一个文档到一个分片中](2_2_Introductory.md#路由一个文档到一个分片中)
    * [主分片和副本分片如何交互](2_2_Introductory.md#主分片和副本分片如何交互)
    * [新建、索引和删除文档](2_2_Introductory.md#新建索引和删除文档)
    * [取回一个文档](2_2_Introductory.md#取回一个文档)
    * [局部更新文档](2_2_Introductory.md#局部更新文档)
    * [多文档模式](2_2_Introductory.md#多文档模式)
  * [搜索——最基本的工具](2_2_Introductory.md#搜索最基本的工具)
    * [空搜索](2_2_Introductory.md#空搜索)
    * [多索引，多类型](2_2_Introductory.md#多索引多类型)
    * [分页](2_2_Introductory.md#分页)
    * [轻量搜索](2_2_Introductory.md#轻量搜索)
  * [映射和分析](2_2_Introductory.md#映射和分析)
    * [精确值 VS 全文](2_2_Introductory.md#精确值VS全文)
    * [倒排索引](2_2_Introductory.md#倒排索引)
    * [分析与分析器](2_2_Introductory.md#分析与分析器)
    * [映射](2_2_Introductory.md#映射)
    * [复杂核心域类型](2_2_Introductory.md#复杂核心域类型)
  * [请求体查询](2_3_Introductory.md#请求体查询)
    * [空查询](2_3_Introductory.md#空查询)
    * [查询表达式](2_3_Introductory.md#查询表达式)
    * [查询与过滤](2_3_Introductory.md#查询与过滤)
    * [最重要的查询](2_3_Introductory.md#最重要的查询)
    * [组合多查询](2_3_Introductory.md#组合多查询)
    * [验证查询](2_3_Introductory.md#验证查询)
  * [排序与相关性](2_3_Introductory.md#排序与相关性)
    * [排序](2_3_Introductory.md#排序)
    * [字符串排序与多字段](2_3_Introductory.md#字符串排序与多字段)
    * [什么是相关性?](2_3_Introductory.md#什么是相关性)
    * [Doc Values 介绍](2_3_Introductory.md#DocValues介绍)
  * [执行分布式检索](2_3_Introductory.md#执行分布式检索)
    * [查询阶段](2_3_Introductory.md#查询阶段)
    * [取回阶段](2_3_Introductory.md#取回阶段)
    * [搜索选项](2_3_Introductory.md#搜索选项)
    * [游标查询 Scroll](2_3_Introductory.md#游标查询Scroll)
  * [索引管理](2_4_Introductory.md#索引管理)
    * [创建一个索引](2_4_Introductory.md#创建一个索引)
    * [删除一个索引](2_4_Introductory.md#删除一个索引)
    * [索引设置](2_4_Introductory.md#索引设置)
    * [配置分析器](2_4_Introductory.md#配置分析器)
    * [自定义分析器](2_4_Introductory.md#自定义分析器)
    * [类型和映射](2_4_Introductory.md#类型和映射)
    * [根对象](2_4_Introductory.md#根对象)
    * [动态映射](2_4_Introductory.md#动态映射)
    * [自定义动态映射](2_4_Introductory.md#自定义动态映射)
    * [缺省映射](2_4_Introductory.md#缺省映射)
    * [重新索引你的数据](2_4_Introductory.md#重新索引你的数据)
    * [索引别名和零停机](2_4_Introductory.md#索引别名和零停机)
  * [分片内部原理](2_4_Introductory.md#分片内部原理)
    * [使文本可被搜索](2_4_Introductory.md#使文本可被搜索)
    * [动态更新索引](2_4_Introductory.md#动态更新索引)
    * [近实时搜索](2_4_Introductory.md#近实时搜索)
    * [持久化变更](2_4_Introductory.md#持久化变更)
    * [段合并](2_4_Introductory.md#段合并)
    
-----
* [深入搜索](3_1_DeepSearch.md#深入搜索)
  * [结构化搜索](3_1_DeepSearch.md#结构化搜索)
    * [精确值查找](3_1_DeepSearch.md#精确值查找)
    * [组合过滤器](3_1_DeepSearch.md#组合过滤器)
    * [查找多个精确值](3_1_DeepSearch.md#查找多个精确值)
    * [范围](3_1_DeepSearch.md#范围)
    * [处理 Null 值](3_1_DeepSearch.md#处理Null值)
    * [关于缓存](3_1_DeepSearch.md#关于缓存)
  * [全文搜索](3_1_DeepSearch.md#全文搜索)
    * [基于词项与基于全文](3_1_DeepSearch.md#基于词项与基于全文)
    * [匹配查询](3_1_DeepSearch.md#匹配查询)
    * [多词查询](3_1_DeepSearch.md#多词查询)
    * [组合查询](3_1_DeepSearch.md#组合查询)
    * [如何使用布尔匹配](3_1_DeepSearch.md#如何使用布尔匹配)
    * [查询语句提升权重](3_1_DeepSearch.md#查询语句提升权重)
    * [控制分析](3_1_DeepSearch.md#控制分析)
    * [被破坏的相关度！](3_1_DeepSearch.md#被破坏的相关度)
  * [多字段搜索](3_1_DeepSearch.md#多字段搜索)
    * [多字符串查询](3_1_DeepSearch.md#多字符串查询)
    * [单字符串查询](3_1_DeepSearch.md#单字符串查询)
    * [最佳字段](3_1_DeepSearch.md#最佳字段)
    * [最佳字段查询调优](3_1_DeepSearch.md#最佳字段查询调优)
    * [multi_match 查询](3_1_DeepSearch.md#multi_match查询)
    * [多数字段](3_1_DeepSearch.md#多数字段)
    * [跨字段实体搜索](3_1_DeepSearch.md#跨字段实体搜索)
    * [字段中心式查询](3_1_DeepSearch.md#字段中心式查询)
    * [自定义 _all 字段](3_1_DeepSearch.md#自定义all字段)
    * [cross-fields 跨字段查询](3_1_DeepSearch.md#crossfields跨字段查询)
    * [Exact-Value 精确值字段](3_1_DeepSearch.md#ExactValue精确值字段)
  * [近似匹配](3_2_DeepSearch.md#近似匹配)
    * [短语匹配](3_2_DeepSearch.md#短语匹配)
    * [混合起来](3_2_DeepSearch.md#混合起来)
    * [多值字段](3_2_DeepSearch.md#多值字段)
    * [越近越好](3_2_DeepSearch.md#越近越好)
    * [使用邻近度提高相关度](3_2_DeepSearch.md#使用邻近度提高相关度)
    * [性能优化](3_2_DeepSearch.md#性能优化)
    * [寻找相关词](3_2_DeepSearch.md#寻找相关词)
  * [部分匹配](3_2_DeepSearch.md#部分匹配)
    * [邮编与结构化数据](3_2_DeepSearch.md#邮编与结构化数据)
    * [prefix 前缀查询](3_2_DeepSearch.md#prefix前缀查询)
    * [通配符与正则表达式查询](3_2_DeepSearch.md#通配符与正则表达式查询)
    * [查询时输入即搜索](3_2_DeepSearch.md#查询时输入即搜索)
    * [索引时优化](3_2_DeepSearch.md#索引时优化)
    * [Ngrams 在部分匹配的应用](3_2_DeepSearch.md#Ngrams在部分匹配的应用)
    * [索引时输入即搜索](3_2_DeepSearch.md#索引时输入即搜索)
    * [Ngrams 在复合词的应用](3_2_DeepSearch.md#Ngrams在复合词的应用)
  * [控制相关度](3_2_DeepSearch.md#控制相关度)
    * [相关度评分背后的理论](3_2_DeepSearch.md#相关度评分背后的理论)
    * [Lucene 的实用评分函数](3_2_DeepSearch.md#Lucene的实用评分函数)
    * [查询时权重提升](3_2_DeepSearch.md#查询时权重提升)
    * [使用查询结构修改相关度](3_2_DeepSearch.md#使用查询结构修改相关度)
    * [Not Quite Not](3_2_DeepSearch.md#NotQuiteNot)
    * [忽略 TF/IDF](3_2_DeepSearch.md#忽略TFIDF)
    * [function_score 查询](3_2_DeepSearch.md#functionscore查询)
    * [按受欢迎度提升权重](3_2_DeepSearch.md#按受欢迎度提升权重)
    * [过滤集提升权重](3_2_DeepSearch.md#过滤集提升权重)
    * [随机评分](3_2_DeepSearch.md#随机评分)
    * [越近越好](3_2_DeepSearch.md#越近越好)
    * [理解 price 价格语句](3_2_DeepSearch.md#理解price价格语句)
    * [脚本评分](3_2_DeepSearch.md#脚本评分)
    * [可插拔的相似度算法](3_2_DeepSearch.md#可插拔的相似度算法)
    * [更改相似度](3_2_DeepSearch.md#更改相似度)
    * [调试相关度是最后 10% 要做的事情](3_2_DeepSearch.md#调试相关度是最后10要做的事情)

-----
* [处理人类语言](4_1_Dealing_with_language.md#处理人类语言)
  * [开始处理各种语言](4_1_Dealing_with_language.md#开始处理各种语言)
    * [使用语言分析器](4_1_Dealing_with_language.md#使用语言分析器)
    * [配置语言分析器](4_1_Dealing_with_language.md#配置语言分析器)
    * [混合语言的陷阱](4_1_Dealing_with_language.md#混合语言的陷阱)
    * [每份文档一种语言](4_1_Dealing_with_language.md#每份文档一种语言)
    * [每个域一种语言](4_1_Dealing_with_language.md#每个域一种语言)
    * [混合语言域](4_1_Dealing_with_language.md#混合语言域)
  * [词汇识别](4_1_Dealing_with_language.md#词汇识别)
    * [标准分析器](4_1_Dealing_with_language.md#标准分析器)
    * [标准分词器](4_1_Dealing_with_language.md#标准分词器)
    * [安装 ICU 插件](4_1_Dealing_with_language.md#安装ICU插件)
    * [icu_分词器](4_1_Dealing_with_language.md#icu分词器)
    * [整理输入文本](4_1_Dealing_with_language.md#整理输入文本)
  * [归一化词元](4_1_Dealing_with_language.md#归一化词元)
    * [举个例子](4_1_Dealing_with_language.md#举个例子)
    * [如果有口音](4_1_Dealing_with_language.md#如果有口音)
    * [Unicode的世界](4_1_Dealing_with_language.md#Unicode的世界)
    * [Unicode 大小写折叠](4_1_Dealing_with_language.md#Unicode大小写折叠)
    * [Unicode 字符折叠](4_1_Dealing_with_language.md#Unicode字符折叠)
    * [排序和整理](4_1_Dealing_with_language.md#排序和整理)
  * [将单词还原为词根](4_1_Dealing_with_language.md#将单词还原为词根)
    * [词干提取算法](4_1_Dealing_with_language.md#词干提取算法)
    * [字典词干提取器](4_1_Dealing_with_language.md#字典词干提取器)
    * [Hunspell 词干提取器](4_1_Dealing_with_language.md#Hunspell词干提取器)
    * [选择一个词干提取器](4_1_Dealing_with_language.md#选择一个词干提取器)
    * [控制词干提取](4_1_Dealing_with_language.md#控制词干提取)
    * [原形词干提取](4_1_Dealing_with_language.md#原形词干提取)
  * [停用词: 性能与精度](4_2_Dealing_with_language.md#停用词性能与精度)
    * [停用词的优缺点](4_2_Dealing_with_language.md#停用词的优缺点)
    * [使用停用词](4_2_Dealing_with_language.md#使用停用词)
    * [停用词与性能](4_2_Dealing_with_language.md#停用词与性能)
    * [词项的分别管理](4_2_Dealing_with_language.md#词项的分别管理)
    * [停用词与短语查询](4_2_Dealing_with_language.md#停用词与短语查询)
    * [common_grams 过滤器](4_2_Dealing_with_language.md#commongrams过滤器)
    * [停用词与相关性](4_2_Dealing_with_language.md#停用词与相关性)
  * [同义词](4_2_Dealing_with_language.md#同义词)
    * [使用同义词](4_2_Dealing_with_language.md#使用同义词)
    * [同义词格式](4_2_Dealing_with_language.md#同义词格式)
    * [扩展或收缩](4_2_Dealing_with_language.md#扩展或收缩)
    * [同义词和分析链](4_2_Dealing_with_language.md#同义词和分析链)
    * [多词同义词和短语查询](4_2_Dealing_with_language.md#多词同义词和短语查询)
    * [符号同义词](4_2_Dealing_with_language.md#符号同义词)
  * [拼写错误](4_2_Dealing_with_language.md#拼写错误)
    * [模糊性](4_2_Dealing_with_language.md#模糊性)
    * [模糊查询](4_2_Dealing_with_language.md#模糊查询)
    * [模糊匹配查询](4_2_Dealing_with_language.md#模糊匹配查询)
    * [模糊性评分](4_2_Dealing_with_language.md#模糊性评分)
    * [语音匹配](4_2_Dealing_with_language.md#语音匹配)

-----
* [聚合](5_1_Aggregations.md#聚合)
  * [高阶概念](5_1_Aggregations.md#高阶概念)
    * [桶](5_1_Aggregations.md#桶)
    * [指标](5_1_Aggregations.md#指标)
    * [桶和指标的组合](5_1_Aggregations.md#桶和指标的组合)
  * [尝试聚合](5_1_Aggregations.md#尝试聚合)
    * [添加度量指标](5_1_Aggregations.md#添加度量指标)
    * [嵌套桶](5_1_Aggregations.md#嵌套桶)
    * [最后的修改](5_1_Aggregations.md#最后的修改)
  * [条形图](5_1_Aggregations.md#条形图)
  * [按时间统计](5_1_Aggregations.md#按时间统计)
    * [返回空 Buckets](5_1_Aggregations.md#返回空Buckets)
    * [扩展例子](5_1_Aggregations.md#扩展例子)
    * [潜力无穷](5_1_Aggregations.md#潜力无穷)
  * [范围限定的聚合](5_1_Aggregations.md#范围限定的聚合)
  * [过滤和聚合](5_2_Aggregations.md#过滤和聚合)
    * [过滤](5_2_Aggregations.md#过滤)
    * [过滤桶](5_2_Aggregations.md#过滤桶)
    * [后过滤器](5_2_Aggregations.md#后过滤器)
    * [小结](5_2_Aggregations.md#小结5_2)
  * [多桶排序](5_2_Aggregations.md#多桶排序)
    * [内置排序](5_2_Aggregations.md#内置排序)
    * [按度量排序](5_2_Aggregations.md#按度量排序)
    * [基于“深度”度量排序](5_2_Aggregations.md#基于深度度量排序)
  * [近似聚合](5_2_Aggregations.md#近似聚合)
    * [统计去重后的数量](5_2_Aggregations.md#统计去重后的数量)
    * [百分位计算](5_2_Aggregations.md#百分位计算)
  * [通过聚合发现异常指标](5_2_Aggregations.md#通过聚合发现异常指标)
    * [significant_terms 演示](5_2_Aggregations.md#significantterms演示)
  * [Doc Values and Fielddata](5_2_Aggregations.md#DocValuesandFielddata)
    * [Doc Values](5_2_Aggregations.md#DocValues)
    * [深入理解 Doc Values](5_2_Aggregations.md#深入理解DocValues)
    * [聚合与分析](5_2_Aggregations.md#聚合与分析)
    * [限制内存使用](5_2_Aggregations.md#限制内存使用)
    * [Fielddata 的过滤](5_2_Aggregations.md#Fielddata的过滤)
    * [预加载 fielddata](5_2_Aggregations.md#预加载fielddata)
    * [优化聚合查询](5_2_Aggregations.md#优化聚合查询)
  * [总结](5_2_Aggregations.md#总结5_2)

-----
* [地理位置](6_Geolocation.md#地理位置)
  * [地理坐标点](6_Geolocation.md#地理坐标点)
    * [经纬度坐标格式](6_Geolocation.md#经纬度坐标格式)
    * [通过地理坐标点过滤](6_Geolocation.md#通过地理坐标点过滤)
    * [地理坐标盒模型过滤器](6_Geolocation.md#地理坐标盒模型过滤器)
    * [地理距离过滤器](6_Geolocation.md#地理距离过滤器)
    * [按距离排序](6_Geolocation.md#按距离排序)
  * [Geohashes](6_Geolocation.md#Geohashes6)
    * [Geohashes 映射](6_Geolocation.md#Geohashes映射)
    * [Geohash 单元查询](6_Geolocation.md#Geohash单元查询)
  * [地理位置聚合](6_Geolocation.md#地理位置聚合)
    * [地理距离聚合](6_Geolocation.md#地理距离聚合)
    * [Geohash 网格聚合](6_Geolocation.md#Geohash网格聚合)
    * [地理边界聚合](6_Geolocation.md#地理边界聚合)
  * [地理形状](6_Geolocation.md#地理形状)
    * [映射地理形状](6_Geolocation.md#映射地理形状)
    * [索引地理形状](6_Geolocation.md#索引地理形状)
    * [查询地理形状](6_Geolocation.md#查询地理形状)
    * [在查询中使用已索引的形状](6_Geolocation.md#在查询中使用已索引的形状)

-----
* [数据建模](7_Modeling_your_data.md#数据建模)
  * [关联关系处理](7_Modeling_your_data.md#关联关系处理)
    * [应用层联接](7_Modeling_your_data.md#应用层联接)
    * [非规范化你的数据](7_Modeling_your_data.md#非规范化你的数据)
    * [字段折叠](7_Modeling_your_data.md#字段折叠)
    * [非规范化和并发](7_Modeling_your_data.md#非规范化和并发)
    * [解决并发问题](7_Modeling_your_data.md#解决并发问题)
  * [嵌套对象](7_Modeling_your_data.md#嵌套对象)
    * [嵌套对象映射](7_Modeling_your_data.md#嵌套对象映射)
    * [嵌套对象查询](7_Modeling_your_data.md#嵌套对象查询)
    * [使用嵌套字段排序](7_Modeling_your_data.md#使用嵌套字段排序)
    * [嵌套聚合](7_Modeling_your_data.md#嵌套聚合)
  * [父-子关系文档](7_Modeling_your_data.md#父子关系文档)
    * [父-子关系文档映射](7_Modeling_your_data.md#父子关系文档映射)
    * [构建父-子文档索引](7_Modeling_your_data.md#构建父子文档索引)
    * [通过子文档查询父文档](7_Modeling_your_data.md#通过子文档查询父文档)
    * [通过父文档查询子文档](7_Modeling_your_data.md#通过父文档查询子文档)
    * [子文档聚合](7_Modeling_your_data.md#子文档聚合)
    * [祖辈与孙辈关系](7_Modeling_your_data.md#祖辈与孙辈关系)
    * [实际使用中的一些建议](7_Modeling_your_data.md#实际使用中的一些建议)
  * [扩容设计](7_Modeling_your_data.md#扩容设计)
    * [扩容的单元](7_Modeling_your_data.md#扩容的单元)
    * [分片预分配](7_Modeling_your_data.md#分片预分配)
    * [海量分片](7_Modeling_your_data.md#海量分片)
    * [容量规划](7_Modeling_your_data.md#容量规划)
    * [副本分片](7_Modeling_your_data.md#副本分片)
    * [多索引](7_Modeling_your_data.md#多索引)
    * [基于时间的数据](7_Modeling_your_data.md#基于时间的数据)
    * [索引模板](7_Modeling_your_data.md#索引模板)
    * [数据过期](7_Modeling_your_data.md#数据过期)
    * [基于用户的数据](7_Modeling_your_data.md#基于用户的数据)
    * [共享索引](7_Modeling_your_data.md#共享索引)
    * [利用别名实现一个用户一个索引](7_Modeling_your_data.md#利用别名实现一个用户一个索引)
    * [一个大的用户](7_Modeling_your_data.md#一个大的用户)
    * [扩容并不是无限的](7_Modeling_your_data.md#扩容并不是无限的)

-----
* [管理、监控和部署](8_Admin.md#管理监控和部署)
  * [监控](8_Admin.md#监控)
    * [Marvel 监控](8_Admin.md#Marvel监控)
    * [集群健康](8_Admin.md#集群健康)
    * [监控单个节点](8_Admin.md#监控单个节点)
    * [集群统计](8_Admin.md#集群统计)
    * [索引统计](8_Admin.md#索引统计)
    * [等待中的任务](8_Admin.md#等待中的任务)
    * [cat API](8_Admin.md#catAPI)
  * [部署](8_Admin.md#部署)
    * [硬件](8_Admin.md#硬件)
    * [Java 虚拟机](8_Admin.md#Java虚拟机)
    * [Transport Client 与 Node Client](8_Admin.md#TransportClient与NodeClient)
    * [配置管理](8_Admin.md#配置管理)
    * [重要配置的修改](8_Admin.md#重要配置的修改)
    * [不要触碰这些配置！](8_Admin.md#不要触碰这些配置)
    * [堆内存:大小和交换](8_Admin.md#堆内存大小和交换)
    * [文件描述符和 MMap](8_Admin.md#文件描述符和MMap)
    * [在生产之前，重温这个列表](8_Admin.md#在生产之前，重温这个列表)
  * [部署后](8_Admin.md#部署后)
    * [动态变更设置](8_Admin.md#动态变更设置)
    * [日志记录](8_Admin.md#日志记录)
    * [索引性能技巧](8_Admin.md#索引性能技巧)
    * [推迟分片分配](8_Admin.md#推迟分片分配)
    * [滚动重启](8_Admin.md#滚动重启)
    * [备份你的集群](8_Admin.md#备份你的集群)
    * [从快照恢复](8_Admin.md#从快照恢复)
    * [集群是活着的、呼吸着的生命](8_Admin.md#集群是活着的呼吸着的生命)

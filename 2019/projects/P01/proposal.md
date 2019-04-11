---
layout: page
mathjax: true
permalink: /2019/projects/p01/proposal/
---

> 注意: 上方的内容不要删除

## 项目题目 
**利用上市公司财务报表决策投资**

### 成员

姓名 | 学号
---- |-----|
李斌斌 | 3120181094
王文杰 | 3120181095
罗妹秋 | 3220180726
赵鹏飞 | 3220180904

### 问题描述

#### 1、问题背景分析
　　截止2019年4月2日，我国上海、深圳两大证券交易所的上市公司数量在3621家，面对这些公司每年披露的大量财务信息和数据，如何对其进行整理归纳，变成可以运用和分析的数据，进而挖掘其中隐含的有价值的信息，使之变为可以利用的资源，这对于我们进行投资决策，趋利避害有着非常重要的意义。
  
#### 2、问题描述

　　证券行业作为一个需要高度信息化的行业，每年产生的数据量都在急剧的增大，上市公司每个季度都会发布相应的财务报告，向所有者、债权人、政府及其他有关各方及社会公众等外部使用者披露企业当前的生产经营结果和财务活动的状况。其中财务报表作为财务报告的主要组成部分，它所提供的企业财务信息具有极其重要的价值。然而我们得到的财务报告往往都是不可编辑的电子格式，当我们想要对相同公司不同时期的财务项目和不同公司间的相同财务项目进行比较时，往往只能手工翻阅查看。并且财务报表所反映的财务内容往往是高度概括和抽象的，一项财务内容往往被分开为不同的报表项目来进行展现。这不利于相关的财报使用者清晰的了解到数据后更深层次的意义。
  
2.1 数据准备

　　直接从证券交易所抓取上市公司公布的财务报告文件，然后对其进行格式转换，变为可以用代码提取的结构化文件，自动提取其中的财务报表数据保存到数据库中。
  
2.2 模型建立

　　整个模型包括财务数据的提取模块、数据挖掘模块和数据展现模块。在数据挖掘模块主要从盈利能力、盈利质量、偿债能力、营运能力和发展能力五个方面选择变量。模型选择方面使用Logistic回归模型和决策树算法模型，进行对比实验。
  
2.3 预期的结果

　　从现有财务指标出发，找出了通过现有财务指标来预测未来净资产收益率的有价值规则，实现了对净资产收益率的预测分析，从而达到了对投资者进行辅助决策的目的。
  
### 项目评估  
　　1. 数据获取和清洗的完整性和有效性。  
　　2. 预测净资产收益率超过15％和低于15%的概率的准确性在80%以上。
### 项目分工

姓名 | 任务
---- | ----
李斌斌 | Logistic回归模型，撰写报告
王文杰 | 决策树算法模型，撰写报告
罗妹秋 | 分析预测结果，撰写报告
赵鹏飞 | 数据获取和清洗，撰写报告
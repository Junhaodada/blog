---
date: 2023-09-04T16:44:38+08:00
title: "2023秋数学建模准备"
description: ""
tags: ["math"]
series: []
---

> 2023研究生数学建模比赛……

<!--more-->

## 资料

[全国研究生数学建模竞赛(NPMCM)历年试题](https://www.shumo.com/wiki/doku.php?id=%E5%85%A8%E5%9B%BD%E7%A0%94%E7%A9%B6%E7%94%9F%E6%95%B0%E5%AD%A6%E5%BB%BA%E6%A8%A1%E7%AB%9E%E8%B5%9B_npmcm_%E5%8E%86%E5%B9%B4%E8%AF%95%E9%A2%98)

[全国研究生数学建模竞赛资料【2004-2021】【详细整理】](https://blog.csdn.net/weixin_44203471/article/details/126634552)

https://github.com/zhanwen/MathModel

## 经验

[中国研究生数学建模竞赛经验之谈](https://www.zhihu.com/tardis/zm/art/128081571?source_id=1003)

[华为杯数学建模竞赛百分百获奖经验分享（获奖 == 5分经验，4分实力，1分运气）](https://shuang96.blog.csdn.net/article/details/103097376?spm=1001.2101.3001.6650.5&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-103097376-blog-78058425.235%5Ev38%5Epc_relevant_anti_t3_base&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-103097376-blog-78058425.235%5Ev38%5Epc_relevant_anti_t3_base&utm_relevant_index=10)

## 历年优秀论文分析

### **2021年**

【A题】相关矩阵组的低复杂度计算和存储建模

- [svd分解](https://zh.wikipedia.org/zh-hans/%E5%A5%87%E5%BC%82%E5%80%BC%E5%88%86%E8%A7%A3)、QR分解
- [科列斯基分解](https://zh.wikipedia.org/zh-hans/%E7%A7%91%E5%88%97%E6%96%AF%E5%9F%BA%E5%88%86%E8%A7%A3)
- [AOR迭代算法](https://blog.csdn.net/weixin_40815892/article/details/93882941)
- [Strassen算法](https://zh.wikipedia.org/wiki/%E6%96%BD%E7%89%B9%E6%8B%89%E6%A3%AE%E6%BC%94%E7%AE%97%E6%B3%95)减少矩阵乘法复杂度
- 压缩算法-哈夫曼编码

【B题】空气质量预报二次建模

对于`数据分析类`问题，拿到数据之后需要`数据预处理`，常用的预处理方法有：

- 剔除缺失值
- 标准化 z-score

之后可以对数据的特征作`相关性分析`，如：皮尔逊相关系数，构建相关矩阵，分析不同特征之间的相关性。

之后可对样本作`聚类`并可视化。之后作分类或预测。

聚类算法

- K-means聚类
- 层次聚类
- 系统聚类

预测模型

- 多元线性回归

- BP神经网络
- 随机森林

- CNN/LSTM

【C题】帕金森病的脑深部电刺激治疗建模研究 

与脑科学相关，有点看不懂

【D题】抗乳腺癌候选药物的优化建模

【E题】信号干扰下的超宽带

【F题】航空公司机组优化排班问题

- xgboost
- 贪心算法
- 粒子群算法


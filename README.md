# providing-banks-with-precision-marketing-solutions
Kesci练习赛 「二分类算法」提供银行精准营销解决方案 

### 概述
这个项目源自kesci练习赛[提供精准营销解决方案](https://www.kesci.com/home/competition/5c234c6626ba91002bfdfdd3),我们需要根据葡萄牙某银行机构的
营销数据（例如：客户的职业、账户余额，与客户交流次数，是否有贷款、违约记录等），预测客户是否购买该银行的产品。

我最终的AUC得分为***0.93974093***，排名第**13**位，详见[排行榜](https://www.kesci.com/home/competition/5c234c6626ba91002bfdfdd3/leaderboard)。

### 开发环境与所需工具
* 开发环境：Windows10, anaconda5.3.0, jupyter notebook5.7.2, python3.7

* 库：numpy, pandas, matplotlib, seaborn, sklearn, scipy, lightgbm

### 数据集
该数据集可从[kesci下载](https://www.kesci.com/home/competition/5c234c6626ba91002bfdfdd3/content/2)

### 方法
1. 数据预处理

2. 特征工程

3. 模型训练与调优

## 总结与收获
1. 以类别特征为基础，构造两两交叉特征（均值、最大值、最小值、标准差）；

2. 文本型的类别特征处理方法。

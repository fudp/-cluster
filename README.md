# 一.数据分析背景与目标
## 背景
1. 业务竞争激烈，以产品为中心转化为客户为中心。
2. 针对不同类型客户，进行精准营销，实现利润最大化。
3. 建立客户价值评估模型，进行客户分类，是解决问题的办法
## 目标
1. 借助本公司客户数据，对客户进行分类。
2. 对不同的客户类别进行特征分析，比较不同类客户的客户价值
3. 对不同价值的客户类别提供个性化服务，制定相应的营销策略。
# 二.概念引用
##  什么是RMF模型?
1. RFM模型是一个被广泛使用的客户关系分析模型，主要以用户行为来区分客户，RFM分别是：
* R = Recency 最近一次消费　　
* F = Frequency 消费频率　　
* M = Monetary 消费金额
* ![image](https://github.com/xiaofan5d/-cluster/blob/master/RFM%E5%AE%9A%E4%B9%89%E5%9B%BE.jpg)
## 从实际业务出发
1.根据本公司业务角度出发加入 
* L=LOAD_TIME-FFP_DATE 会员加入时长
* C=AVG_DISCOUNT 会员平均折扣
# 三.数据分析工具
1. python3.6,jupyter notebook
* numpy
* pandas
* 数据建模:scikit-learn 
* 可视化:matolotlib

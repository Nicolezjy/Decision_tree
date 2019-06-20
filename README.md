# hw3_决策树

#### 项目介绍
在 Rental Listing Inquiries 数据上练习 xgboost 参数调优 

### 数据说明

Rental Listing Inquiries 数据集是 Kaggle 平台上的一个分类竞赛任务，需要根据 公寓的特征来预测其受欢迎程度（用户感兴趣程度分为高、中、低三类）。其 中房屋的特征 x 共有 14 维，响应值 y 为用户对该公寓的感兴趣程度。评价标准 为 logloss。 
数据链接：https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries 

### 使用说明
部分因为环境未运行完善，parse中读取稀疏数据，训练后，调用训练集测试，完毕后保存，生成测试文件


# 数据分析及可视化项目
数据来源： https://tianchi.aliyun.com/dataset/649
项目参考： https://blog.csdn.net/FontThrone/article/details/108128527
## python版本=3.11
使用Pandas, NumPy, Scikit-learn (KNN), Matplotlib, Seaborn, PyEcharts等库
基于淘宝用户行为数据，利用Pandas和NumPy构建了R（最近消费时间）、F（消费频率）、M（消费金额）三大核心指标。

采用K最近邻算法，基于已有的用户价值标签对全体用户进行精准分类，实现了用户的自动化、数据化分群。

通过Seaborn与PyEcharts进行多维度可视化，清晰展示了“高价值用户”、“潜力用户”等不同群体的特征与占比，为差异化运营提供了直接依据。

该项目旨在通过机器学习方法，对淘宝用户进行精准的价值分群。通过构建RFM模型，并应用KNN分类算法，将用户划分为不同的价值群体，从而帮助业务方理解用户结构，并制定针对性的留存、促活与转化策略。

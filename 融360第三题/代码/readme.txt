融3-rawdata.ipynb是所有特征所有样本建立xgboost和lightgbm模型。（其中包括数据的预处理和特征工程，数据结果保存在data文件夹中，模型结果保存在model文件夹中）
分层挑选样本bagging.ipynb是分层bootstrap采样的xgboost为基模型的bagging。模型结果保存在model文件夹中。
tag-predict.ipynb是对tag特征的预测，结果没有保存，仅在文件内有展示。
ronghe.ipynb是三个模型的融合。
shuchu文件夹保存了特征名和tag字段，在建模时有调用。

注：以上代码使用的是windows系统下的python3.6.5
# text_matching
文本匹配模型

本项目包含目前大部分文本匹配模型，持续更新中

数据集为QA_corpus，训练数据10w条，验证集和测试集均为1w条

训练方法：
`python train.py`

测试方法：
`python test.py`

其中对应模型文件夹下的`args.py`文件是超参数

模型|loss|acc|
--|--|--|
DSSM|0.7613157|0.6864

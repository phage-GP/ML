设置全局随机种子，以保证结果可复现
`random_state = 233`

```
sklearn.model_selection.train_test_split(*arrays, test_size=None, train_size=None, random_state=None, shuffle=True, stratify=None)

# 对于类别不平衡数据，可以指定根据标签划分stratify = label，这样在训练集、测试集中,1：0比例相同
# 保持测试集与整个数据集里 label 的数据分类比例一致。

```

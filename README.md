# 简述
路况状态时空预测
本次课设采用了LGBM模型进行训练与评估，没有用上topo数据集。
第一次运行需要把下面代码解注释：（合并几天的数据集）
#采用写入的方式
'''for i in tqdm(range(25,31)):
    with open(f'D:\\RoadStatusData\\traffic\\201907{i}.txt', 'r') as text:
      with open(r'D:\RoadStatusData\traffic\merge_25_30.txt', 'a') as txt:
        txt.writelines(text.readlines())'''
运行时长：大概一个半小时

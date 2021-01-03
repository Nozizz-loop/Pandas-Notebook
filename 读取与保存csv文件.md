1、是否保留列名 header: Whether to write out the column names (default True)

df.to_csv(‘path/Result.csv’,header=0) #不保存列名

2、是否保留行索引 index: whether to write row (index) names (default True)

df.to_csv(‘path/Result1.csv’,index=0) #不保存行索引

3、读取csv

test=pd.read_csv(“path/xxx.csv”)

# clustering
Diamonds are clustered based on various features using unsupervised learning techniques.
## Method
 - k-means:  
K-means是一種迭代算法，它將數據點分為K個類別，每個類別的中心點（稱為聚類中心）是平均數。K-means的目標是最小化數據點到它所屬的聚類中心的距離平方和，也就是SSE（sum of squared errors）。K-means的性能受初始聚類中心的選擇和K值的選擇影響。  
- c-means:  
C-means是一種基於模糊邏輯的聚類算法，它將每個數據點分配到每個類別的概率，每個類別有一個中心點。C-means的目標是最小化數據點到所有聚類中心的距離平方和的加權和，也就是FCM（fuzzy c-means）的目標函數。C-means的性能受初始聚類中心的選擇和模糊因子的選擇影響。
<img src='https://camo.githubusercontent.com/0e5b613b48b1caaf6aae7efd372a29554bc93004c7b90c7013d8144e143e77ee/68747470733a2f2f6d65676170782d6173736574732e64636172642e74772f696d616765732f35636232363162322d353131322d343435322d613333382d3534646531303062663637312f6f7269672e706e67'/>
- Hierarchical clustering:  
可以提供分群依據的資訊，因此運算成本較K-Means高，兩者可以合併使用(先做K-Means再做hierarchical clustering)
<img src='https://camo.githubusercontent.com/1a403efef0193542a82dfcec946f18509b21470e981d3325c2b1d92c86e71856/68747470733a2f2f6d65676170782d6173736574732e64636172642e74772f696d616765732f31623939623362352d373433642d346661652d616434362d3861383230393565656534662f6f7269672e706e67'/>

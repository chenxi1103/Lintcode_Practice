# 2019-06-24
我今天又刷题了！我坚持了两天了，我的妈可太不容易了ε-(´∀｀; )
今天的主题是并查集，并查集有固定的模版，主要用来解决图联通的问题，是bfs的替代品。
做某些题比如number of island II时会明显比bfs有优势，根据题意来判断要用并查集还是bfs，两者都要熟练掌握。

### 并查集Union Find
* find： 找父节点的时间复杂度是o(1)，找根父节点的时间复杂度是o(n) （优化 - 路径压缩，可把find的时间复杂度降为o(1))
* union：只合并boss节点，和儿子们没有关系。<br>
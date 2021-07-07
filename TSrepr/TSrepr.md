# 时间序列表示
为了有效存储和加快时间序列的处理过程，需要采用一种简洁的方法来表示高维的时间序列数据。一种有效的时间序列表示方法不仅能够允许序列间进行相似性比对，也可以较好地应用于不用的数据挖掘任务中。<br>
Definition：给定一条长度为m的时间序列T=t_1,t_2,…,t_m，若维度为d(d≪m)的模型T′与T非常接近，则称T′为时间序列T的表示。<br>
-能够显著降低数据维度；<br>
-在局部和总体上能够突出时间序列最根本的特征；<br>
-计算花费小；<br>
-从表达方式中重构数据拟合效果好；<br>
-对噪音不敏感或者能够处理噪音。<br>
每一种时间序列表示方法都从不同侧面强调了上述的多个基本特征。根据不同的转换方式，时间序列表示方法分类为：非数据适应性的、数据适应性的、基于模型的和数据表示的。

[https://cran.r-project.org/web/packages/TSrepr/vignettes/TSrepr_representations_of_time_series.html](https://cran.r-project.org/web/packages/TSrepr/vignettes/TSrepr_representations_of_time_series.html "TSrepr_representations_of_time_series")<br>

Laurinec, (2018). TSrepr R package: Time Series Representations. Journal of Open Source Software, 3(23), 577, https://doi.org/10.21105/joss.00577
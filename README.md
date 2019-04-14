# stock_prediction

项目目标：

利用历史数据预测上证综指走势

算法原理：

时间序列ARMA算法

项目心得：

使用ARMA算法进行时间序列预测,自回归滑动平均模型（英语：Autoregressive moving average model，简称：ARMA模型）。是研究时间序列的重要方法，由自回归模型（简称AR模型）与移动平均模型（简称MA模型）为基础“混合”构成。

其中，自回归AR模型描述的是当前值与历史值之间的关系。移动平均模型MA描述的是自回归部分的误差累计。ARMA(p,q)模型中包含了p个自回归项和q个移动平均项，说白了ARMA模型就是用过去一些时间点和噪声的线性组合来预测现在的时间，至于参数需要在训练的过程中调优，看选择几个点（p）几个（q）白噪声。
![AR模型](https://github.com/funfunhello2012/stock_prediction/blob/master/%E8%87%AA%E5%9B%9E%E5%BD%92AR%E6%A8%A1%E5%9E%8B.png)

![MA模型](https://github.com/funfunhello2012/stock_prediction/blob/master/%E8%87%AA%E5%9B%9E%E5%BD%92MA%E6%A8%A1%E5%9E%8B.png)

![ARMA模型](https://github.com/funfunhello2012/stock_prediction/blob/master/ARMA%E6%A8%A1%E5%9E%8B.png)

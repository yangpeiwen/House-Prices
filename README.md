# House-Prices
Kaggle competition

学https://zh.d2l.ai/的时候想要更深的探讨一下神经网络模型在传统图标类数据中的表现。
看了一些kaggle上面的讨论，大部分做法是需要选取一些特征的，通过可视化作图或者皮尔斯系数计算得到部分特征。然后使用传统机器学习模型，部分特征会比全部特征效果好。
在House_price.ipynb中，我尝试得到所有特征的Feature importance后渐渐减少特征数量，看看能否在同一个网络上面表现更好。使用的一个非常简单的非线性网络。
最后结论的截图在word文件中，只要特征减少就会使得效果降低，保留全部特征能得到最好的结果。如果需要改进，可能需要同时增加更多人工特征以及更多网络层级

参考内容：
https://www.kaggle.com/code/ohseokkim/house-price-all-about-house-price
https://www.kaggle.com/code/kobeerose/house-prices-a-beginner-s-notebook/notebook
https://zh.d2l.ai/

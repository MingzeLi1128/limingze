# AlphaStock: A Buying-Winners-and-Selling-Losers Investment Strategy using Interpretable Deep Reinforcement Attention Networks
Authors: Jingyuan Wang, Yang Zhang, Ke Tang, Junjie Wu, Zhang Xiong<br>
Publication: KDD2019<br>
Full-Text: https://www.kdd.org/kdd2019/accepted-papers/view/alphastock-buying-winners-and-selling-losers-in-deep<br>
<br>
## 摘要
本文所做的主要工作如下：<br>
* 结合夏普比率、注意力机制与强化学习，提出了一种风险与回报相平衡的投资策略；<br>
* 对资产间的相互关系进行了建模，从而避免了选择性偏误，提出了一种跨资产的注意力机制；<br>
* 首个可以给出可解释的策略的深度强化学习模型.<br>
## 关键词
`投资策略` `强化学习` `深度学习` `可解释预测`
## 介绍
传统量化交易策略（动量、均值回归等）的缺陷：<br>
· 往往仅考虑到了市场的少数几个特征，在复杂多变的市场条件下表现欠佳. <br>
深度学习方法面临的挑战：<br>
· 回报与风险间的平衡：多数现有的有监督深度学习方法往往只关注价格预测，缺乏风险意识，仅有少量的强化学习策略考虑到了这个问题；<br>
· 对资产间关系的建模：很多金融工具都能够在一定程度上利用资产间的相互关系规避风险，如套期保值、套利等，但现有的深度学习以及强化学习策略却很少关注资产间相互关系这一重要的信息；<br>

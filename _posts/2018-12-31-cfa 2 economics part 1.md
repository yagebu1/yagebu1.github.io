---
layout: post
title: CFA Level 2 经济 Part 1
categories: CFA2级笔记
---
## 目录
1. 汇率（exchange rate）
1. 国际平价关系（international parity relationship）
2. 国际收支账户（balance of payments）

<br><br>

## 1\. 汇率（exchange rate）
1. 基本概念
1. 价差（spread）
1. 三角套利（triangular arbitrage）
1. 盯市（mark to market value）

<br><br>

### a）基本概念

<br><br>

**名义汇率（nominal exchange rate） vs 实际汇率（real exchange rate）**

- 名义汇率（nominal exchange rate）：外汇市场观察到的汇率
- 实际汇率（real exchange rate）：从购买力上计算所得的汇率
- 名义汇率和实际汇率之间的换算：FX Real (d/f) = FX Nominal (d/f) × (CPI<sub>f</sub> / CPI<sub>d</sub>)

**直接标价法（Direct quotes） vs 间接标价法（Indirect quotes）**

- 直接标价法（Direct quotes）：本国货币每外国货币（domestic currency per foreign currency (DC/FC)）
- 间接标价法（Indirect quotes）：外国货币每本国货币（foreign currency per domestic currency (FC/DC)）

**三种报价格式：**
- AUD：USD = 0.6
- 0.6USD/AUD
- AUD = 0.6 USD

**即期汇率 vs 远期汇率**

- 即期汇率（Spot exchange rates）：当场交割时的汇率
- 远期汇率（forward exchange rate）：远期合约约定的汇率

<br><br>

### b）价差（spread）

<br><br>

**做市商（dealer）（一般是银行）的报价（quotation）：**

- 买价（Bid price）：做市商买入国外货币的价格
- 卖价（Ask price）：做市商卖出国外货币的价格
- （银行给出的价格一般是中间价）
- 价差（Spread）= 卖价 - 买价
- 价差单位 pips = 1/10,000

**做市商价差（dealer spread）：**

做市商（一般是银行）和客户之间的价差（零售市场）

- 受到银行间价差（interbank spread）（批发市场）的影响：
  - 银行间价差越大，做市商价差越大
- 交易规模（size of transation）
  - 交易规模越大，做市商价差越大，因为占用银行的“带宽”
- 客户和做市商的关系（relationship between the dealr and client）

**银行间价差（interbank spread）：**

银行之间的价差（批发市场）

- 货币对（currencies pair）
  - 高交易量的货币对趋向于更低的价差
- 时间（time of day）
  - 在纽约货币交易所和伦敦货币交易所都开市的时候价差变小，此时全球交易量最大
  - 1:00pm - 4:00 pm (GMT)
- 市场波动（market volatility）
  - 市场波动越大，价差越大

**远期合约价差（forward exchange rate spread）**

- 期限（maturity）越长，价差越大

**交叉汇率（cross rate with bid-ask spreads）**
解题技巧：相乘同边，相除对角（小的数字变得更小，大的数字变得更大）

<br><br>

### c）三角套利（triangular arbitrage）

<br><br>

**三角套利（triangular arbitrage）**

交叉汇率在三个货币对之间的的应用

### d）盯市（mark to market value）

<br><br>

**升水 vs 贴水（premium vs discount）：**

- 远期合约升水（forward premium）: 远期合约价格大于即期价格（forward price > spot price）
- 远期合约贴水（forward discount）: 远期合约价格小于即期价格（forward price < spot price）
- 升水/贴水：forward premium (discount) = F - S<sub>0</sub>



**远期合约的价值（value of forward contract）：**

- 到期时（at maturity）：
V<sub>T</sub> = ( FP<sub>T</sub> - FP<sub>0</sub> )(contract size)
- 到期前的价值（盯市）（value prior to expiration(mark-to-market value)）：
V<sub>t</sub> = ( FP<sub>t</sub> - FP<sub>0</sub> ) / (1 + R ( ( T - t )/360) )

<br><br>

## 2\. 国际平价关系（international parity relationship）
1. 抛补利率平价（covered interest rate parity）
2. 无抛补利率平价（uncovered interest rate parity）
3. 由 抛补利率平价 和 无抛补利率平价 得到的结论
4. 国际费雪效应（international Fisher effect）
5. 绝对购买力平价（absolute purchasing power parity）
6. 事后相对购买力平价（ex-post purchasing power parity）
7. 事前相对购买力平价（ex-ante purchasing power parity）
8. 总结

<br><br>

### a）抛补利率平价（covered interest rate parity）

<br><br>

投资期限为一年：
F<sub>(A/B)</sub> / S<sub>(A/B)</sub> = ( 1 + R<sub>A</sub> ) / ( 1 + R<sub>B</sub> )
投资期限小于一年：
F<sub>(A/B)</sub> / S<sub>(A/B)</sub> = ( ( 1 + R<sub>A</sub> ) ( Actual / 360 ) )/ ( ( 1 + R<sub>B</sub> ) ( Actual / 360 ) )

套利收益的计算（arbitrage profit）：

如果（1）F<sub>(A/B)</sub> / S<sub>(A/B)</sub> > ( 1 + R<sub>A</sub> ) / ( 1 + R<sub>B</sub> )
套利收益 = ( F<sub>(A/B)</sub> / S<sub>(A/B)</sub> ) × ( 1 + R<sub>B</sub> ) - ( 1 + R<sub>A</sub> )

如果（2）F<sub>(A/B)</sub> / S<sub>(A/B)</sub> < ( 1 + R<sub>A</sub> ) / ( 1 + R<sub>B</sub> )
套利收益 = ( S<sub>(A/B)</sub> / F<sub>(A/B)</sub> ) × ( 1 + R<sub>A</sub> ) - ( 1 + R<sub>B</sub> )


<br><br>

### b）无抛补利率平价（uncovered interest rate parity）
> 和抛补利率平价的区别是不存在远期合约

- E[S<sub>1(A/B)</sub>] / S<sub>0(A/B)</sub>   = ( 1 + R<sub>A</sub> ) / (1 + R<sub>B</sub> )
- 公式左边是其实是汇率变化，也就是说无抛补利率平价的结论是汇率变化等于利率变化：
%△E(S) = ( R<sub>A</sub> - R<sub>B</sub> )/ (1 + R<sub>B</sub> ) ≈ R<sub>A</sub> - R<sub>B</sub>

> 假设1 + R<sub>B</sub> 近似于 1

1. 无抛补利率平价的结论是汇率变化等于利率变化
2. 汇率变化的量近似于两个国家的利率差
3. 无抛补利率平价假设投资者风险中性（risk neutral）

> 投资海外存在汇率风险，而无抛补利率平价假设这位投资者不需要汇率风险溢价

<br><br>

### c）由 抛补利率平价 和 无抛补利率平价 得到的结论

<br><br>

1. 由抛补利率平价可算出不存在套利机会的汇率远期合约（no-arbitrage forward rate），由无抛补利率平价可以算出未来的即期汇率（expected future spot rate）
2. 抛补利率平价的假设是存在套利机制
3. 如果抛补利率平价和无抛补利率平价都成立，那么远期合约得价格是未来即期汇率是无偏预测（unbiased predictor）
**F = E(S<sub>1</sub>) → ( F - S<sub>0</sub> ) / S<sub>0</sub> = ( E(S<sub>1</sub>) - S<sub>0</sub> ) / S<sub>0</sub> → f = %△E(S) ≈ R<sub>A</sub> - R<sub>B</sub>**
4. 无抛补利率平价短期内不成立，但是长期成立

---


## 课外补充（知乎回答）：抛补利率平价与非抛补利率平价该如何区分理解？

作者：雅各布

链接：https://www.zhihu.com/question/19976990/answer/137215047

来源：知乎

著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。



### 简单回答：

#### 区别：
1. 抛补利率平价假设存在套利机制
2. 无抛补利率平价并没有假设存在套利机制

#### 理解：
1. 由抛补利率平价可算出不存在套利机会的汇率远期合约价格（no-arbitrage forward rate）
2. 由不抛补利率平价可以算出未来的即期汇率（expected future spot rate）

### 复杂回答：

抛补利率平价和不抛补利率平价的有不少前提假设，有些合理有些并不合理
咱们可以循序渐进的理解这个问题：

1. 什么是套利（arbitrage）？
2. 什么是远期合约（forward contract）？**
3. 什么是无风险利率（risk free rate）？
4. 什么是抛补利率平价（covered interest rate parity）？
5. 什么是不抛补利率平价（uncovered interest rate parity）？



#### 1. 什么是套利（arbitrage）？ 

其实海外代购就是一种套利机制，如果某一款Miu Miu女包的价格，在国内买比从外国买然后带回来还贵，这里就存在一个套利机会。
定义：
利用两个市场之间的价差，以较短的时间买入卖出获得低风险收益（或者同时，主要是金融资产）

#### 2. 什么是远期合约（forward contract）？
国庆想去西安玩，但是怕到了西安之后再去找旅店价格会太贵，所以提前使用信用卡在7天预定了。这个行为本质上和远期合约非常相似。
定义：
一项合约：在1）约定的日期；2）完成指定的交易

#### 3. 什么是无风险利率（risk free rate）？
其实这里谈的是名义无风险利润。某个国家的无风险利率等于她的国家政府发布的债券，因为纯粹理论上国家永远不会破产。

#### 4. 什么是抛补利率平价（covered interest rate parity）？

结合前3点的话，这里就玩一个游戏来理解第4点

**（1）假设抛补利率平价不成立**

如果日本国债回报特别高（违背抛补利率平价），那我可以靠这个赚很多钱。因为理论上日本国债不可能违约，最后我总能赚到他们承诺的日元金额。既然如此，我可以尽可能的借钱，然后全部投入日本国债市场，和别人约定一个远期合约锁定汇率（这样不用担心等到债券到期时，日元可能会出现的相对于人民币贬值的情况），等到合约到期再把日元换回人民币，还款，剩下的都是我白赚的。

*如果日本国债回报特别低（依然违背抛补利率平价），我作为一个国内投资者做不了什么，但是在日本的投资者可以做类似的操作，买入中国的国债，赚取人民币。*

继续重复之前的操作，滚雪球，利滚利。很快我就有了很多很多钱。别看有时候利差就一点点，不停的买卖的话钱会越来越多的。杨百万以前就是靠国债的价差赚了不少钱的。

**（2）但是如果资本自由流动，交易成本很低的话，抛补利率平价还是不得不成立的。**

抛补利率平价是用一个经济学的角度教我一个中国的谚语：“没有免费的午餐”。

很快大家就发现，原来靠雅各布这个小技巧能赚这么多，于是大家全部都参与进来，过不了多久，每一个中国人，都能靠这个方法白赚了越来越多的人民币。不过钱多如灾并可能并不是一件好事，全世界能买的东西就这么多，中国人手中的钱再多其实也没太大用。这个世界就这么多面包，你想出20块买，更想吃的人就只能30块竞价。所以实际上，人民币就陷入了一个持续的通货膨胀。因为人民币会出现可见性的上涨，大家都不会再和你制定原有的远期合约价格了，我们都懂，人民币都像纸一样不值钱了。

现在，让我们思考一下未来一年后的变化是什么：

**a.从汇率上说**

假设一年以后，原来6块人民币相当于100両，未来可能60块才能换100両。汇率是原来的1/10。

**b.从利率上说**

我们努力的买卖并没有产生任何实质上的社会价值，所以从真实利率来说，中国未发生过任何改变。但是从名义利率上讲，我们的共同努力导致我们所有的财富在未来都会在后面加个一个0。

名义利率收益率900%，汇率却缩水了900%，抛补利率平价了。

#### 5. 什么是无抛补利率平价（uncovered interest rate parity）？

无抛补利率平价的说法是，即使不存在远期合约，未来中日汇率也会变化到能使得（1）不可能。
无抛补利率平价的假设并不算很合理，它假设中日货币市场的人们供需关系能使得汇率移动到（1）赚不了钱的那个点。


---


<br><br>

### d）国际费雪效应（international Fisher effect）

> 1 + R = ( 1 + r ) × ( 1 + E(I))

- 两个国家的名义利率之差等于两个国家的通胀率之差
- 假设：各个国家的实际利率（real interest rate）是平稳而且相等的（stable over time and equal）
- 如果资本不能自由流动，那么假设不成立

**( 1 + R<sub>A</sub> ) / ( 1 + R<sub>B</sub> ) = ( 1 + E(I<sub>A</sub>) ) / (1 + E(I<sub>B</sub>)) → R<sub>A</sub> - R<sub>B</sub> = E(I<sub>A</sub>) - E(I<sub>B</sub>)**

<br><br>

### e）绝对购买力平价（absolute purchasing power parity）

<br><br>

S<sub>(A/B)</sub> = CPI<sub>A</sub> / CPI<sub>A</sub>

这是一个理论假设，但是每个国家的消费习惯不同（the weights (consumption patterns) of the various goods），所以CPI之间不存在完全可比性

一价定律（law of one price）：相同的商品应该在世界各地应该是有相同的价格

<br><br>

### f）事后相对购买力平价（ex-post relative purchasing power parity）

<br><br>

S<sub>1(A/B)</sub> / S<sub>0(A/B)</sub> = ( 1 + I<sub>A</sub>) / ( 1 + I<sub>B</sub>) → %△S ≈ I<sub>A</sub> - I<sub>B</sub>

- 高通胀率的国家贬值严重
- 因为不存在套利机制，所以这个公式短期内不一定成立
- 长期来看公式大概成立

<br><br>

### g）事前相对购买力平价（ex-ante relative purchasing power parity）

<br><br>

E[S<sub>1(A/B)</sub>] / S<sub>0(A/B)</sub> = ( 1 + E(I<sub>A</sub>)  / ( 1 + E(I<sub>B</sub>) ) → %△E(S) ≈ E(I<sub>A</sub>) - E(I<sub>B</sub>)

- 长期来看公式大概成立，短期内不一定成立

<br><br>

### h）总结
(1)Exprected change in spot exchange rate
(2)Expected inflation rate differential
(3)Forward discount or premium
(4)Interest rate differential

(1)(2) 事前相对购买力平价
(1)(3) 抛补利率平价 + 无抛补利率平价
(1)(4) 无抛补利率平价
(2)(3) N/A
(2)(4) 国际费雪效应
(3)(4) 抛补利率平价

国际费雪效应 + 无抛补利率平价 → 事前相对购买力平价
事前相对购买力平价 + 无抛补利率平价 → 国际费雪效应
事前相对购买力平价 + 国际费雪效应 → 无抛补利率平价

**均衡实质汇率（equilibrium real exchange rate）：**
- 如果相对购买力平价在短期内成立，真实汇率（real exchange rate）会保持不变
- 均衡实质汇率 = S<sub>(A/B)</sub> × ( CPI<sub>B</sub> / CPI<sub>A</sub> )
- 因为短期内常常不成立，所以实质汇率在这个均值回归平衡水平上下波动

**均衡实质汇率水平具体处哪个位置？**
1. 从维持宏观经济平衡性的方式（macroeconomic balance approach）来分析
均衡实质汇率水平处在能使得经常账户（current account）平衡的位置上
2. 从维持外资可持续性的方式（external sustainability approach）来分析
均衡实质汇率水平处在能使得国家的外资维持在可持续水平的位置上
3. 从简约形式计量经济模型的方式（reduced-form econometric model approach）来分析
相当于前两种方法的组合，通过相关宏观经济参数推算出

<br><br>

## 3. 国际收支账户（balance of payments）

<br><br>

### a）国际收支账户（balance of payments）的三个部分

<br><br>

**国际收支账户（balance of payments）分为三个部分**
- 经常账户（current account）
- 金融/资本账户（financial/capital account）
- 官方储备账户（official reserve account）

**经常账户（current account）：**
商品服务贸易，投资收入，单方面的转移（exchange of goods & services, exchange of investment income, and unilateral transfer (gifts to and from other nations)）

**金融/资本账户（financial/capital account）：**
权益债务投资（funds for debt and equity investment）
- 实体经济（foreign direct investment）
- 资本市场（capital market）

**官方储备账户（official reserve account）：**
经常账户和金融/资本账户的调平项目

经常账户 + 金融/资本账户 + 官方储备账户 = 0

因为中国存在经常账户和资本账户的双盈余，所以中国外汇储备大

> 双盈余（顺差）是不健康的经济情况：
>
> 1. 中国大量出口导致经常账户的盈余
> 2. 大量的外资投资中国导致金融/资本账户盈余
> 3. 双顺差双管齐下导致人民币升值，中国商品的价格上升。大量外资投资也导致中国经济存在不确定性，如果中国经济出现动荡，可能会导致外国人大量撤资，恶性循环。
> 4. 外币在中国中国进行消费和投资的时候必须先兑换成人民币，所以中国人民银行被动发放大量人民币
> 5. 央行为了减少流通的人民币，就提高银行准备金率，但是准备金需要支付利息，所以这一行为加重了央行的负担

金融/资本账户对于货币汇率的影响更加直接

### b）从国际收支账户分析影响汇率的机制（influence of balance of payment on exchange rate）

<br><br>

**1\. 经常账户影响（current account influence）本币汇率的三个原因：**

**I\. 流动性机制（flow mechanism）**

- 贸易逆差来自于对外国商品服务的购入，这个过程使得外币的需求大，本币需求小，所以导致货币贬值（depreciation）
- 但是随着本币贬值，本国商品变得廉价，会刺激出口，有可能进而消除逆差
- 有三个要素决定逆差消除是否能生效：
  1. 初始时进出口的差距（initial gap between imports and exports）
  2. 汇率对于进口和出口商品价格的影响（influence of exchange rate on domestic import and export prices）
  3. 贸易商品的需求价格弹性（price elasticity of demand of the traded goods）

**II\. 投资组合组成机制（portfolio composition mechanism）**

- 在浮动汇率制的经济体中，经常账户赤字的时候金融/资本账户就会盈余
- 国外投资者意识到大量资本投入到了该国，处于投资组合再平衡的角度考虑，会减少持有该国金融资产
- 减持金融资产并被兑换回外币时产生了本币抛售，进而贬值

**III\. 外资可持续性机制（debt sustainability mechanism）**

- 在浮动汇率制的经济体中，经常账户赤字的时候金融/资本账户就会盈余
- 外国人意识到本国外债高柱，担心该国经济不再能够健康增长
- 资本撤离并被兑换回外币时产生了本币抛售，进而贬值

<br><br>

**2\. 资本账户赤字导致（capital account influence）本币贬值（depreciation）的原因：**

- 外资流入本国，为了能进行投资，会兑换成本币，这个过程会导致本币需求增大，造成升值
- 本国储蓄短缺（stortage of internal saving）的时候需要吸引外资
- 新兴市场（emerging market）出现过量资本流入（excessive capital inflows）的潜在问题：
  1. 本币过度升值（excessive real appreciation）
  2. 金融资产和/或房产泡沫（real estate bubble）
  3. 外债增加（external debt）
  4. 超额信贷消费（excessive consumption in the domestic market fueled by credit）

 > 本国资产升值导致大量投资者跟风，刺激借贷消费和杠杆投资

**国家如何通过影响外汇市场影响资本流动**

短期来看，实质汇率在长期均值回归平衡水平上下波动（fluctuate around）
>前面均衡实质汇率（equilibrium real exchange rate）提到，因为短期内常常不成立，所以实质汇率在这个均值回归平衡水平上下波动

real exchange rate <sub>(A/B)</sub> = equilibrium real exchange rate + ( real interest rate<sub>B</sub> - real interest rate<sub>A</sub> ) - ( risk premium<sub>B</sub> - risk premium<sub>A</sub> )

货币的实际价值和实际汇率之差呈现正相关，风险溢价之差呈现负相关

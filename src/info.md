# Factor Investing

To Read
https://github.com/UFund-Me/Qbot/blob/main/docs/02-%E7%BB%8F%E5%85%B8%E7%AD%96%E7%95%A5/01-%E8%82%A1%E7%A5%A8/Alpha%E5%AF%B9%E5%86%B2.md
https://github.com/apachecn/quant-learning/tree/master
https://github.com/tomchaos/hello-world


## 0612 (因子投资-方法与实践 石川)
CAMP:
E_i - E_f = beta * (E_m - E_f)
beta = cov(R_i, R_m) / Var(R_m)
Arbitrage Pricing Theory (APT): E[R_i] = beta_i * lambda
- E[R_i]: Expected return. For long only, it's R_i - R_m; For long-short, it's R_i
- beta_i: factor exposure
- lambda: factor expected return / factor risk premium 


短评 https://www.book123.info/detail/9787121394287#google_vignette

第1 章因子投资基础
1.1 统一视角下的因子投资 1
1.1.1 一个公式 1
1.1.2 因子、多因子模型和异象3
1.1.3 再论异象和因子 5
1.1.4 因子投资包含的内容6
1.1.5 实证资产定价与因子投资9
1.2 因子投资的学术起源 11
1.2.1 实证资产定价 11
1.2.2 研究现状 13
1.3 因子投资的业界发展 14
1.3.1 因子投资和管理人15
1.3.2 因子投资和投资者16
1.4 本书的结构 19
第2 章因子投资方法论
2.1 投资组合排序法 22
2.1.1 因子模拟投资组合22
2.1.2 排序法及其检验 24
2.1.3 多重排序法 28
2.1.4 因子命名约定 33
2.2 多因子模型的回归检验 34
2.2.1 时间序列回归 36
2.2.2 截面回归 39
2.2.3 时序回归vs 截面回归42
2.2.4 Fama–MacBeth 回归45
2.2.5 不同回归方法比较48
2.3 因子暴露和因子收益率 48
2.3.1 引入工具变量 50
2.3.2 使用公司特征 51
2.3.3 两类模型 52
2.4 异象检验 53
2.4.1 时序回归检验异象54
2.4.2 计量经济学问题 55
2.4.3 White 估计量和Newey–West 估计量57
2.4.4 截面回归检验异象59
2.5 多因子模型比较 60
2.5.1 GRS 检验 61
2.5.2 均值--方差张成检验62
2.5.3 从几何角度比较GRS 和均值--方差张成 66
2.5.4 α 检验 70
2.5.5 贝叶斯方法 70
2.6 因子正交化 72
2.6.1 简单一元回归 73
2.6.2 回归的几何意义 73
2.6.3 用正交化过程求解多元回归 75
2.7 广义矩估计 78
2.7.1 样本均值的方差 78
2.7.2 分析框架 80
2.7.3 数学基础 84
2.7.4 有效性 86
2.7.5 不应成为黑箱 88
2.8 研究方法建议 89
第3 章主流因子解读
3.1 数据和流程 91
3.1.1 数据来源 91
3.1.2 量价数据处理 92
3.1.3 财务数据处理 95
3.1.4 因子构造流程 102
3.1.5 实证设定 106
3.2 市场因子 107
3.2.1 市场因子起源 107
3.2.2 对CAPM 的质疑108
3.2.3 市场因子实证 109
3.3 规模因子 112
3.3.1 规模因子起源 112
3.3.2 规模因子成因 113
3.3.3 规模因子实证 113
3.4 价值因子 117
3.4.1 价值因子起源 117
3.4.2 价值因子成因 118
3.4.3 价值因子实证 119
3.5 动量因子 124
3.5.1 动量因子起源 124
3.5.2 动量因子成因 125
3.5.3 动量因子实证 127
3.6 盈利因子 131
3.6.1 盈利因子起源 131
3.6.2 盈利因子成因 132
3.6.3 盈利因子实证 134
3.7 投资因子 138
3.7.1 投资因子起源 138
3.7.2 投资因子成因 139
3.7.3 投资因子实证 140
3.8 换手率因子 146
3.8.1 换手率因子起源 146
3.8.2 换手率因子成因 147
3.8.3 换手率因子实证 148
第4 章多因子模型
4.1 主流多因子模型综述 153
4.1.1 Fama–French 三因子模型154
4.1.2 Carhart 四因子模型156
4.1.3 Novy–Marx 四因子模型 157
4.1.4 Fama–French 五因子模型158
4.1.5 Hou–Xue–Zhang 四因子模型 161
4.1.6 Stambaugh–Yuan 四因子模型 164
4.1.7 Daniel–Hirshleifer–Sun 三因子模型 167
4.2 A 股中被定价的因子 171
4.2.1 Fama–MacBeth 回归实证设定 171
4.2.2 Fama–MacBeth 回归结果172
4.3 多因子模型比较：来自A 股的例子 173
4.3.1 两个模型 173
4.3.2 BM、ROE 与预期收益174
4.3.3 模型比较的实证结果176
4.4 多因子模型的简约性 187
第5 章异象研究
5.1 估值高低中的异象 191
5.1.1 价值因子与价值投资192
5.1.2 F-Score 193
5.1.3 G-Score 195
5.1.4 通过预期差获取超额收益198
5.2 基本面锚定反转 202
5.2.1 金融学依据 203
5.2.2 A 股市场中的基本面锚定反转 204
5.3 特质性波动率 210
5.3.1 套利不对称性和特质性波动率 212
5.3.2 A 股市场中的特质性波动率异象 213
第6 章因子研究现状
6.1 p-hacking 和“因子动物园”222
6.1.1 何为p-值 222
6.1.2 在追逐p-值的道路上狂奔223
6.1.3 硬科学与软科学 224
6.1.4 正确认识p-值的含义224
6.1.5 多重假设检验 226
6.1.6 先验的重要性 229
6.2 从“因子动物园”到“因子大战” 231
6.2.1 形同意不同的投资因子232
6.2.2 q5 模型 233
6.2.3 因子大战 234
6.3 用行为金融学解释异象和因子236
6.3.1 套利限制 238
6.3.2 预期中的偏差 240
6.3.3 风险偏好中的偏差244
6.3.4 认知限制 250
6.3.5 行为金融学与市场异象251
6.3.6 行为有效市场 255
6.4 投资者情绪 256
6.4.1 投资者情绪的度量257
6.4.2 投资者情绪与异象表现259
6.4.3 投资者情绪与市场表现261
6.5 风险补偿、错误定价还是数据窥探 262
6.5.1 风险补偿检验 262
6.5.2 错误定价检验 263
6.5.3 数据窥探检验 266
6.6 因子样本外失效风险 268
6.6.1 曝光导致错误定价减弱269
6.6.2 因子拥挤 270
6.6.3 交易成本 271
6.7 因子投资难以取代基本面分析273
6.7.1 基本面分析 274
6.7.2 基本面量化投资 275
6.7.3 基本面投资“因子化”的不足 277
6.7.4 思考和讨论 279
6.8 机器学习与因子投资 280
6.8.1 线性模型 281
6.8.2 非线性模型 283
6.8.3 模型评估与实证研究285
6.8.4 主成分分析和因子选择287
6.8.5 机器学习的问题 290
第7 章因子投资实践
7.1 收益率模型：获取“阿尔法”293
7.1.1 基本术语 293
7.1.2 寻找预测变量 294
7.1.3 挑选预测变量 295
7.1.4 收益率预测 299
7.2 风险模型：以Barra 为例307
7.2.1 Barra 多因子模型307
7.2.2 模型求解 309
7.2.3 纯因子投资组合 311
7.2.4 协方差矩阵求解及调整313
7.3 投资组合优化 319
7.3.1 错位的收益与风险模型319
7.3.2 目标函数 322
7.3.3 不同目标函数的比较324
7.3.4 约束条件 326
7.3.5 交易成本模型 330
7.4 Smart Beta：因子投资的捷径331
7.4.1 因子指数和Smart Beta332
7.4.2 为什么要投资Smart Beta339
7.4.3 如何投资Smart Beta342
7.4.4 应用实践 348
7.4.5 更多讨论 356
7.5 因子择时 357
7.5.1 按因子估值择时 357
7.5.2 按因子动量择时 359
7.5.3 按因子波动择时 359
7.5.4 按市场情绪择时 360
7.5.5 按宏观因素择时 361
7.5.6 因子择时很难 363
7.6 风格分析 363
7.6.1 经典风格分析 364
7.6.2 基于多空因子的风格分析366
7.6.3 实例：巴菲特的投资风格367
7.7 风险归因 370
7.7.1 两种传统风险归因方法371
7.7.2 风险的三要素 371
7.7.3 从风险角度看收益相关性373
7.7.4 将三要素公式应用于多因子模型 375
7.8 因子投资展望 376
7.8.1 另类数据 376
7.8.2 用因子实现大类资产配置381
后记
附录A 　理解资产价格
参考文献



## 0611 (paper links and book links)
- Paper
https://www.top1000funds.com/wp-content/uploads/2014/03/Factor-investing-in-practice.pdf

https://www.savvyinvestor.net/blog/awards-best-factor-investing-white-paper-2020

- Books
https://shop.elsevier.com/books/factor-investing/jurczenko/978-1-78548-201-4?country=US&format=print&utm_source=google_ads&utm_medium=paid_search&utm_campaign=usapmax&gclid=CjwKCAjw4ZWkBhA4EiwAVJXwqYX-CN7Sc5tPh9V0ucz_dlvrXtwit3LnuJtQ9ZQz35s-2OWz4rRQ8xoCM90QAvD_BwE&gclsrc=aw.ds

https://www.amazon.com/Equity-Smart-Factor-Investing-Practitioners/dp/1119583225/ref=asc_df_1119583225/?tag=hyprod-20&linkCode=df0&hvadid=344057888328&hvpos=&hvnetw=g&hvrand=799877748453148483&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9030987&hvtargid=pla-769810246289&psc=1&tag=&ref=&adgrpid=69543898472&hvpone=&hvptwo=&hvadid=344057888328&hvpos=&hvnetw=g&hvrand=799877748453148483&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9030987&hvtargid=pla-769810246289

https://www.amazon.com/Machine-Learning-Factor-Investing-Mathematics/dp/0367639726/ref=sr_1_1?keywords=machine+learning+for+factor+investing+python+version&qid=1686493811&s=books&sprefix=machine+learning+for+factor%2Cstripbooks%2C430&sr=1-1

https://www.twocenturies.com/blog/2019/4/29/12-factor-investing-books-by-asset-managers
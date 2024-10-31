---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



Selected Publications
------

+ **[Trend Factor in China: The Role of Large Individual Trading](https://ssrn.com/abstract=3402038)**, with Guofu Zhou and Yingzi Zhu
  + **<font color="blue">Review of Asset Pricing Studies</font>**<font color="blue">, 2024.</font>
  + *Best Paper Award in 2020 FMA Annual Meeting <small>(Semi-finalist)</small>, Best Paper Award in 2020 THU-PKU-RUC EMDS*
  + Presented at: 2018 CFRIC, 2018 IAFDS, <font color="blue"> 2019 CICF </font>, 2019 WRADSP, 2019 NZFM, 2019 AFBC, 2020 THU-PKU-RUC EMDS, 2020 FMA, <font color="blue"> 2021 AFA </font> (Ph.D. Poster).
  + You can download the [Factor Data](https://yangliu-finance.github.io/files/LZZ4_TrendFactor_Monthly&Daily.xls) (monthly and daily) here. 
  + We propose a novel trend factor for the Chinese stock market, which incorporates both price and volume information to capture dominant individual trading, momentum, and liquidity. We find that volume plays a more significant role in the trend factor for China than for the US, reflecting the greater retail participation in China. By incorporating this trend factor into the 3-factor model of Liu et al. (2019), we propose a 4-factor model that explains a wide range of stylized facts and 60 representative anomalies. Our study highlights the important role of individual trading in asset pricing, especially in China.
  <!---
  seminars at Gothenburg University, Lund University, Southwestern University of Finance and Economics, Stockholm University, Tsinghua University, University of Cincinnati, UIUC, and Washington University in St. Louis;
  -->

+ **[Technical Analysis in the Stock Market: A Review](https://ssrn.com/abstract=3850494)**, with Yufeng Han, Guofu Zhou, and Yingzi Zhu
  + **<font color="blue">Handbook of Investment Analysis, Portfolio Management, and Financial Derivatives</font>**<font color="blue">, forthcoming.</font>
  + Technical analysis is the study for forecasting future asset prices with past data. In this survey, we review and extend studies on not only the time-series predictive power of technical indicators on the aggregated stock market and various portfolios, but also the cross-sectional predictability with various firm characteristics. While we focus on reviewing major academic research on using traditional technical indicators, but also discuss briefly recent studies that apply machine learning approaches, such as Lasso, neural network and genetic programming, to forecast returns both in the time-series and in the cross-section.


Working Papers
------

+ **[Different Opinions or Information Asymmetry: Machine-based Measurement and Consequences](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5004801)**, with Kang Guo and Tianyu Wang
+ Presented at:  the 2024 Yuelu Asset Pricing Workshop (Hunan University), and seminars at the Southwestern University of Finance and Economics, Zhongnan University of Economics and Law
+ We leverage machine learning to introduce belief dispersion measures to distinguish two key sources of disagreement, i.e., interpretation heterogeneity (IH) and information asymmetry (IA). IA and
IH significantly outperform the human decision-based measure with superior pricing power and are irreplaceable components of disagreement. While IA negatively predicts the cross-section of
stock returns, IH exhibits an asymmetric pricing pattern: IH positively predicts returns among underpriced stocks but negatively among overpriced stocks, consistent with the theoretical model
of Atmaz and Basak (2018) in that disagreement amplifies expectation bias. Although limits-to arbitrage and sentiment contribute to both measures’ predictability, each has its distinct economic
rationale, rooted in different sources of disagreement. Our results underscore that the structure of belief dispersion has important heterogeneous effects on market equilibrium.


+ **[Maximizing the Sharpe Ratio: A Genetic Programming Approach](https://ssrn.com/abstract=3726609)**, with Guofu Zhou and Yingzi Zhu 
  + Presented at:  <font color="blue">  AFA</font>, <font color="blue">  CICF</font>, <font color="blue">  AMES</font>, IAFDS,  CFPDS,  CFRIC,  and China FinTech Conference.
  + While common machine learning algorithms focus on minimizing the mean-square errors of model fit, 
  we show that genetic programming, GP, is well-suited to maximize an economic objective, the Sharpe ratio of 
  the usual spread portfolio in the cross-section of expected stock returns. In contrast to popular regression-based 
  learning tools and the neural network, GP can double their performance in the US, and outperform them internationally. 
  We find that, while the economic objective plays a role, GP captures nonlinearity in comparison with methods like Lasso, 
  and it requires smaller sample than neural network.
  <!---
  seminars in London Business School, Sichuan University, Tsinghua University, Washington University in St. Louis, and Zhejiang University;
  -->

+ **[Optimal Portfolio Choice with Economic Constraints: A Genetic Programming Approach](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4674858)**, with Guofu Zhou
  + Presented at:  <font color="blue">  AsianFA </font>, AI&Econometrics Conference (Xiamen Univ).
  + We develop a new approach to construct the mean-variance efficient portfolio by directly targeting the optimal weight with economic-motivated regularization that incorporates economic constraints to guard against overfitting and enhance interpretability. Instead of struggling with noisy estimators of expected return and covariance matrix, we interpret a portfolio rule as a mapping from historical data to optimal weights and take advantage of the vigorous searching capability of genetic programming (GP) to estimate this weighting function directly. While conventional penalties, such as L1 and L2 norms, are not feasible in our model due to GP's non-parametricity, we propose a trading-frictions-based regularization to control model complexity while preserving interpretability. The out-of-sample Sharpe ratio of our GP approach more than doubles those of existing methods. Beyond portfolio choice,  we also derive a model-implied expected return measure from the GP-optimal weight and find that it subsumes the predictability of other machine learning methods in the cross-section of stock returns. Our study highlights the importance of marrying machine learning and economic rationale for interpretable machine learning applications in asset pricing.

+ **[Overnight-Intraday Reversal Everywhere](https://ssrn.com/abstract=4605208)**, with Chun Liu, Tianyu Wang, Guofu Zhou, and Yingzi Zhu
  + Presented at: <font color="blue"> AsianFA,  CICF </font>
  + A strategy that buys securities with low past overnight returns and sells securities with high past overnight returns generates sizeable out-of-sample intraday returns and Sharpe ratios in all major asset classes. This strategy – labeled as overnight-intraday reversal – delivers an average return that is about two to five times larger than those generated by the conventional reversal strategy. Investor heterogeneity, sentiment, market uncertainty and market-wide illiquidity fail to explain this overnight-intraday reversal return. Our findings are consistent with an asset class-specific market maker liquidity provision mechanism, and we find that cross-sectional return dispersion can predict the strategy returns in every asset class.
A global two-factor model, consisting of the market and overnight-intraday reversal factor, well explains the intraday return variation of diversified portfolios across asset classes.


+ **股票收益率非对称性：新测度与新发现**, 合作者： 朱英姿, 郭康 (湖南大学研究生)，焦宇晓
  + 会议: <font color="blue">  CICF </font> (scheduled)
  + 摘要：本文提出了一个基于概率分布、反应收益率总体非对称性的新测度（RA，return asymmetry）。实证结果发现：（1）RA能负向预测A股横截面收益率。其不仅吸收了已有测度的解释力，还能提供新预测力，且该新预测力随收益率分布复杂度而提升；（2）关于定价优势来源，本文发现系统和特质不对称之间存在显著的交互定价效应，已有指标忽视了此效应，而基于总体概率分布的RA能捕捉其影响；（3）经济解释上，RA定价力随投资者博彩偏好、情绪及关注度、散户参与度以及套利限制而增强，但风险因子、交易摩擦等因素不能解释其表现；（4）稳健性上，控制前景理论、 收益率突显性等因素，RA仍有显著定价力；（5）特质非对称在A股的定价力强于系统指标，美股结果则相反，这说明A股的独特性。RA综合两部分信息，在国际股市上的定价能力也优于已有测度。


<!---
+ **股票收益率非对称性：新测度与新发现**, 合作者： 朱英姿, 郭康 (湖南大学研究生)
  + 会议: <font color="blue"> 2024 CICF </font>(scheduled)
  + 摘要：We propose a new asymmetry measure (RA, return asymmetry) based on the return probability distribution to capture overall asymmetry. Empirical results show that: (1) RA can negatively predict the cross-sectional stock return. It not only absorbs the explanatory power of existing measures but also provides new predictability that increases with the complexity of the return distribution; (2) There is an interactive pricing effect between systematic and idiosyncratic asymmetry components, which is ignored by existing measures but captured by RA; (3) RA pricing power increases with investors’ gaming preferences, sentiment, attention, retail investor participation, and arbitrage restrictions; (4) RA's performance is robust to risk factors and other behavioral effects such as the prospect and salience theory; (5) The idiosyncratic asymmetry component is more important than the systematic counterpart in China, while the results in the US are the opposite. Combining the two components, our RA measure exhibits robust performance in the global stock markets.
-->

Conference Discussions
------


+ **[金融科技研究前沿](https://yangliu-finance.github.io/files/Discuss_2023_Hong_FinTech.pdf)**
  + 洪永淼， 李玉婷， 姚加权
  + 2023《经济研究》-互联网数字经济论坛
    
+ **[Teaching Economics to the Machine](https://yangliu-finance.github.io/files/Discuss_2023AMES_Chen_TeachingEconomicsToTheMachine.pdf)**
  + Hui Chen, Yuhan Cheng, Yanchu Liu, and Ke Tang
  + 2023 AMES (Asian Meeting of Econometric Society)
  

+ **[Green or Brown? Choosing an Overpriced Stock to Short Sell](https://yangliu-finance.github.io/files/Discuss_2023CFRI_Zhang_GreenOrBrown.pdf)**
  +  Weiming (Elaine) Zhang and Xintong Zhan
  + 2023 CFRI&CIRF Joint Conference

<!---
Work in Progress
-----
+ **Choosing Factors: Explanatory Power vs Model Parsimony**
  + We examine which factor collection, in the model space spanned by existing factors, performs best in terms of the balance between explanatory power and model parsimony. Taking the union of the factors in the recent notable models, our comparison of 512 models shows that Liu, Zhou, and Zhu’s (2020) four factor model achieves the greatest explanatory power measured by the Sharpe ratio among all those satisfying model parsimony condition. Moreover, this model exhibits greater ability in explaining various test assets, and it also earns persistent premium.
-->


<!---
+ **Overnight-intraday Reversal in China**, (in Chinese) with Ronghua Qu and Tianyu Wang
  + We find a significant overnight-intraday reversal effect in the Chinese A share stock market, i.e., the
stocks with lower (higher) overnight returns will on average earn higher (lower) future intraday returns.
This overnight-intraday reversal effect substantially outperforms the traditional reversal effect by earning
a much higher daily return of 1.12% and a greater annualized Sharpe ratio up to 18.02. Moreover, this
effect increases with the stock illiquidity, the short-sale constraint, and individual ownership, indicating
that the illiquidity premium and investor sentiment are the two driving forces behind this reversal effect.
-->

<!---
  + In this paper, we examine the effect.
  + Download [here](https://yangliu-finance.github.io/files/WorkingPaper.pdf)
-->


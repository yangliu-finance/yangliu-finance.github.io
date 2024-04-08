---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



Publications
------

+ **Trend Factor in China: The Role of Large Individual Trading**, with Guofu Zhou and Yingzi Zhu
  + **<font color="blue">Review of Asset Pricing Studies</font>**<font color="blue">, forthcoming.</font>
  + *Best Paper Award in 2020 FMA Annual Meeting <small>(Semi-finalist)</small>, Best Paper Award in 2020 THU-PKU-RUC EMDS*
  + Presented at: 2018 CFRIC, 2018 IAFDS, 2019 CICF, 2019 WRADSP, 2019 NZFM, 2019 AFBC, 2020 THU-PKU-RUC EMDS, 2020 FMA, 2021 AFA Ph.D. Poster.
  + Available at: [https://ssrn.com/abstract=3402038](https://ssrn.com/abstract=3402038)
  + We propose a novel trend factor for the Chinese stock market, which incorporates both price and volume information to capture dominant individual trading, momentum, and liquidity. We find that volume plays a more significant role in the trend factor for China than for the US, reflecting the greater retail participation in China. By incorporating this trend factor into the 3-factor model of Liu et al. (2019), we propose a 4-factor model that explains a wide range of stylized facts and 60 representative anomalies. Our study highlights the important role of individual trading in asset pricing, especially in China.
  + You can download my [Curriculum Vitae](https://yangliu-finance.github.io/files/CV_YangLiu_231204_update1.pdf) here. 
  + [Factor data]:(https://yangliu-finance.github.io/files/LZZ4_TrendFactor_Monthly&Daily.xls) here. 
  <!---
  seminars at Gothenburg University, Lund University, Southwestern University of Finance and Economics, Stockholm University, Tsinghua University, University of Cincinnati, UIUC, and Washington University in St. Louis;
  -->

+ **Technical Analysis in the Stock Market: A Review**, with Yufeng Han, Guofu Zhou, and Yingzi Zhu
  + **<font color="blue">Handbook of Investment Analysis, Portfolio Management, and Financial Derivatives</font>**<font color="blue">, forthcoming.</font>
  + Available at: [https://ssrn.com/abstract=3850494](https://ssrn.com/abstract=3850494)
  + Technical analysis is the study for forecasting future asset prices with past data. In this survey, we review and extend studies on not only the time-series predictive power of technical indicators on the aggregated stock market and various portfolios, but also the cross-sectional predictability with various firm characteristics. While we focus on reviewing major academic research on using traditional technical indicators, but also discuss briefly recent studies that apply machine learning approaches, such as Lasso, neural network and genetic programming, to forecast returns both in the time-series and in the cross-section.


Working Papers
------


+ **Maximizing the Sharpe Ratio: A Genetic Programming Approach**, with Guofu Zhou and Yingzi Zhu 
  + Presented at:  2018 IAFDS, 2019 CFPDS, 2019 CFRIC, 2020 China FinTech Conference, 2021 CICF, 2023 AMES, 2024 AFA.
  + Available at: [https://ssrn.com/abstract=3726609](https://ssrn.com/abstract=3726609)
  + While common machine learning algorithms focus on minimizing the mean-square errors of model fit, 
  we show that genetic programming, GP, is well-suited to maximize an economic objective, the Sharpe ratio of 
  the usual spread portfolio in the cross-section of expected stock returns. In contrast to popular regression-based 
  learning tools and the neural network, GP can double their performance in the US, and outperform them internationally. 
  We find that, while the economic objective plays a role, GP captures nonlinearity in comparison with methods like Lasso, 
  and it requires smaller sample than neural network.
  <!---
  seminars in London Business School, Sichuan University, Tsinghua University, Washington University in St. Louis, and Zhejiang University;
  -->

+ **Optimal Portfolio Choice under Economic Constraints: A Genetic Programming Approach**, with Guofu Zhou
  + Presented at: 2024 AI&Econometrics Conference (Xiamen Univ), 2024 AsianFA (scheduled)
  + We develop a new machine-learning-based approach to construct the mean-variance efficient portfolio by directly targeting the optimal weight with economic-motivated regularization that incorporates economic constraints to guard against overfitting and enhance interpretability. Instead of
struggling with noisy estimators of expected return and covariance matrix, we interpret a portfolio rule as a mapping from historical data to optimal weights and take advantage of the vigorous
searching capability of genetic programming (GP) to directly estimate this weighting function.
While conventional penalties, such as L1 and L2 norms, are not feasible in our model due to GP’s
non-parametricity, we propose a trading-frictions-based regularization to control model complexity
while preserving interpretability. The out-of-sample Sharpe ratio of our GP approach more than
doubles those of existing methods. Beyond portfolio choice, we also derive a model-implied expected return measure from the GP-optimal weight and find that it subsumes the predictability
of other machine learning methods in the cross-section of stock returns. Our study highlights the
importance of marrying machine learning and economic rationale for interpretable machine learning
applications in asset pricing.
  
+ **Stock Return Asymmetry: New measure and New Evidences**, (in Chinese) with Yingzi Zhu, and Guokang (HNU student)
  + Presented at: 2024 CICF (scheduled)
  + We propose a new asymmetry measure (RA, return asymmetry) based on the return probability distribution to capture overall asymmetry. Empirical results show that: (1) RA can negatively predict the cross-sectional stock return. It not only absorbs the explanatory power of existing measures but also provides new predictability that increases with the complexity of the return distribution; (2) There is an interactive pricing effect between systematic and idiosyncratic asymmetry components, which is ignored by existing measures but captured by RA; (3) RA pricing power increases with investors’ gaming preferences, sentiment, attention, retail investor participation, and arbitrage restrictions; (4) RA's performance is robust to risk factors and other behavioral effects such as the prospect and salience theory; (5) The idiosyncratic asymmetry component is more important than the systematic counterpart in China, while the results in the US are the opposite. Combining the two components, our RA measure exhibits robust performance in the global stock markets.


+ **Overnight-Intradat Reversal Everywhere**, with Robert Kosowski, Chun Liu, and Tianyu Wang
  + Presented at 2016 AsianFA, 2016 CICF
  + Available at: [https://ssrn.com/abstract=4605208](https://ssrn.com/abstract=4605208)
  + A strategy that buys securities with low past overnight returns and sells securities with high past overnight returns generates sizeable out-of-sample intraday returns and Sharpe ratios in all major asset classes. This strategy – labeled as overnight-intraday reversal – delivers an average return that is about two to five times larger than those generated by the conventional reversal strategy. Investor sentiment, macro-news announcements, and market uncertainty fail to explain this overnight-intraday reversal return. Our findings are consistent with an asset class-specific market maker liquidity provision mechanism, and we find that cross sectional return dispersion could well predict the strategy returns.




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


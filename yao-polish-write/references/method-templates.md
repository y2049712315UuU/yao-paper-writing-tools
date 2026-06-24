# 计量方法英文段落模板

## DID 平行趋势检验

```latex
\subsection{Parallel Trend Test}
The validity of the DID estimator relies on the parallel trend 
assumption. We test this using an event study specification:

\[
Y_{it} = \sum_{k=-K}^{-2} \beta_k D_{it}^k + \sum_{k=0}^{L} \beta_k D_{it}^k + \gamma X_{it} + \mu_i + \lambda_t + \varepsilon_{it}
\]

where $D_{it}^k$ are leads and lags of the policy variable, with 
$k=0$ indicating the first treatment year. The coefficients $\beta_k$ 
for $k<0$ should not be statistically different from zero if the 
parallel trend assumption holds.
```

## 多期 DID

```latex
\subsection{Staggered DID}
Given the staggered implementation of [policy], we follow Callaway 
and Sant'Anna (2021) to address potential bias in the two-way fixed 
effects estimator when treatment timing varies across units.
```

## PSM-DID

```latex
\subsection{PSM-DID}
To address potential selection bias from observable characteristics, 
we combine propensity score matching with DID estimation. Probit 
regression is used to predict treatment status, and treated units 
are matched to the nearest neighbor (caliper = 0.05) on the 
propensity score. The DID estimator is then applied to the matched 
sample.
```

## 工具变量

```latex
\subsection{Instrumental Variable Approach}
To address potential endogeneity of [变量], we employ an instrumental 
variable approach. The instrument [IV 名称] is relevant because 
[相关性理由] and satisfies the exclusion restriction because 
[外生性理由]. The first-stage F-statistic [值] exceeds the 
conventional threshold of 10 (Stock and Yogo, 2005), confirming 
instrument relevance.
```

## 稳健标准误

```
Standard errors are clustered at the [county/village/province] level 
to account for within-cluster correlation in the error terms.
```

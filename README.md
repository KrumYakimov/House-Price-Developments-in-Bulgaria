# House-Price-Developments-in-Bulgaria

Data Science SoftUni 2023 course project

## Abstract
This study investigates trends and dynamics of housing prices in Bulgaria across distinct time frames. Our central focus is to address a pivotal question: Is the current housing price surge indicative of a new bubble? In our pursuit of answering this critical query, we deploy a comprehensive approach encompassing a simultaneous assessment of a predefined set of conditions. We meticulously evaluate whether the annual growth rate in the deflated house prices index surpasses the 6% threshold, seeking any signs of dislocations or distortions within the real economy. These dislocations could manifest as rapid credit expansion, housing growth rates that far outpace rising rents, or an influx of excessive capital into the housing market. To decipher the stability and sustainability of house price growth, we encompase an array of rigorous statistical techniques. These include correlation analysis and hypothesis tests. By unraveling these intricate facets and harnessing the power of these statistical methods, our comprehensive analysis collectively signals that there is no housing price bubble on the horizon for Bulgaria as of the conclusion of 2022 and the first quarter of 2023.

### **1. Indroduction**

The real estate market is a critical component of any economy, influencing both financial stability and social dynamics. As housing prices fluctuate, their impacts reverberate through various sectors, from construction and mortgage lending to consumer spending and overall economic sentiment. One of the key concerns in the realm of housing markets is the potential emergence of housing bubbles, where rapid and unsustainable price growth is followed by a sharp decline, resulting in economic instability.

In the context of Bulgaria, a country that has experienced significant changes in its housing market over the past decades, assessing the presence of a housing bubble is of paramount importance. This investigation delves into the realm of house price developments in Bulgaria, employing rigorous statistical tools and hypothesis tests to ascertain whether a housing bubble is forming in the country.

The term "bubble" denotes a significant and prolonged mispricing of an asset. The challenge in identifying a housing price bubble arises due to the lack of consensus within the economic field about the precise definition of a housing bubble and the appropriate methods (methodology and tools) to confirm its presence [[1]](#7.-References).

Characteristics commonly indicating the presence of a housing price bubble encompass [[1]](#7.-References):

- Decoupling of house prices from local incomes
- Exceptionally high growth rate in deflated house prices
- Accelerated rise in house prices relative to rents
- Aberrations in the real economy, such as excessive credit supply or capital flows directed towards the housing market, as well as a surplus of construction activity.

The primary objective of this study is to meticulously examine the trends and dynamics of housing prices in Bulgaria across distinct time frames. Our central focus is to address a pivotal question: Do housing prices reflect a new bubble? To tackle this inquiry, we employ a simultaneous assessment of a predefined set of conditions.

The first set of conditions encompasses two crucial factors: a) evaluating whether the annual growth rate in the deflated house prices index surpasses the 6% threshold, and b) determining whether the ratio of housing prices to rents remains below 1.6x. This analytical aspect is referred to as the "price sustainability analysis." 

The second set of conditions hones in on identifying interrelated imbalances within the broader real economy context. This facet of the analysis is aptly termed the "dislocations analysis." 

To comprehensively evaluate the stability and viability of house price growth, we employ an array of statistical techniques. These include correlation analysis, which enables us to discern relationships between variables, and hypothesis tests, which furnish insights into the statistical significance of our findings.

By unraveling these intricate aspects and employing rigorous statistical methods, our study endeavors to shed light on the critical question of whether Bulgaria's housing market is undergoing the formation of a new housing bubble.

The OECD database is a common source for housing price data, while additional data from the Bulgarian National Statistical Institute, Bulgarian National Bank, and Eurostat are used for this study.


The notebook follows this structure:

**Section 2: Price Sustainability Analysis**
In this section, we assess the sustainability of housing prices by utilizing various indices and ratios associated with house prices, rent prices, and income. This step is pivotal to comprehend the current status of the housing market and establish a baseline for subsequent analyses.

**Section 3: Dislocations Analysis**
This segment of the analysis aims to identify any distortions or dislocations within the real economy that could indicate a potential housing price bubble. Factors such as credit supply, foreign capital inflows, and construction sector dynamics will be examined. These indicators are crucial in determining whether external factors are influencing the housing market beyond conventional supply and demand dynamics.

**Section 4: Descriptive Statistics and Correlation Analysis**
We utilize descriptive statistics and correlation analysis to illuminate the complex interactions among variables that impact housing prices. Through the examination of metrics such as central tendency, variability, and skewness, our goal is to develop a comprehensive grasp of the distribution and attributes of house price data in Bulgaria. Moreover, we delve into the relationships between various factors influencing housing prices. Through the computation of correlation coefficients and p-values, we can evaluate both the strength and significance of the associations between house prices and other key economic indicators.

**Section 5: Hypothesis Tests**
We employ hypothesis tests to compare proportions, assess the significance of coefficients, and determine the stationarity of time series data. By applying these tests to the Bulgarian housing market data, we aim to discern any significant departures from normal behavior that might indicate the formation of a housing bubble.

**Section 6: Conclusion**
Summarizing our key findings, this section delves into whether the evidence substantiates the existence of a housing price bubble. Additionally, we discuss the implications of our findings and potential policy recommendations grounded in our insights.

# An event study was conducted to assess the impact of the Cambridge Analytica scandal on the stock returns of IT companies. The event study utilized the Market Model and examined a specific event window.

Event Study Settings:

· Risk Model: The Market Model was chosen as the risk model for this study. It assumes that stock returns are influenced by broad market movements.

· Estimation Window: The estimation window is the period used to estimate the expected returns of the IT companies. The length of the estimation window is not specified in the provided information.

· Event Window: The event window captures the period around the Cambridge Analytica scandal. It spans from 10 days before the event (-10) to 10 days after the event (10).

On March 17, 2018, the Cambridge Analytica scandal came to light, revealing the unauthorized access and exploitation of personal data from millions of Facebook users by the political consulting firm Cambridge Analytica.(Humble, 2021) This watershed event had profound implications for the IT industry, as it exposed significant issues related to data privacy, security, and ethical practices. The Cambridge Analytica scandal sent shockwaves through the IT industry, highlighting the potential risks associated with data collection and usage(Giraudo, 2022). It was estimated that the personal data of approximately 87 million Facebook users was improperly obtained, raising widespread concerns about privacy and data protection(Peruzzi et al., 2018). This incident brought attention to the vulnerability of user information and triggered a global conversation on the responsible handling of personal data.

The Cambridge Analytica scandal was chosen for this report due to its significant impact on the IT industry and the broader implications for data privacy and security (The Guardian, 2018). The selected IT companies (SIC code 7370-7374) (Wikipedia, 2023) were chosen because they operate in sectors closely related to data-driven services. The study aims to assess the direct impact of the scandal on these companies' stock performance and examine if it acted as a catalyst for industry-wide changes in data protection practices. This analysis provides insights into the consequences of data breaches and privacy violations and informs decision-making in the sector.

In this data analysis, we aim to quantify the impact of the Cambridge Analytica scandal on publicly listed IT sector companies in the United States. Specifically, we will focus on abnormal stock returns as a measure of the event's impact on the company’s performance.

### H1: The Cambridge Analytica scandal has a negative impact on the stock returns of IT companies.

#### Test Results:

The following table presents the event study results using the Market Model:

![image](https://github.com/abhinavliverpool/CambridgeAnalytica/assets/124881241/f14bb5bc-08c3-4b41-905a-7e8963640cb2)

#### Interpretation:

Considering the cumulative impact, the Cumulative Abnormal Return (CAR) for the event window (-10,10) is -1.90%. The associated p-value for the Cross-sectional t-statistic of the CAR is 0.02, which indicates statistical significance.

Based on these results, it can be concluded that the Cambridge Analytica scandal had a significant impact on the stock returns of the IT companies during the event window. The statistically significant abnormal returns and the significant CAR suggest that the event had a negative and lasting effect on the cumulative abnormal returns of the IT companies.

Therefore, H1, which hypothesized that the Cambridge Analytica scandal would have a negative impact on the stock returns of IT companies, is supported by the event study results. The observed abnormal returns and the significant CAR provide evidence of a statistically significant association between the event and the IT industry's stock performance.

It is important to note that these findings are based on the chosen event study settings, including the Market Model as the risk model and the specified event and estimation windows. Further analysis and consideration of other factors could provide a more comprehensive understanding of the overall impact of the Cambridge Analytica scandal on the IT industry(Peruzzi et al., 2018).

**As the Cambridge Analytica scandal had a negative impact on the IT industry (CAR =-1.90%) and their impact was statistically significant (P<0.05) therefore hypothesis 1 is supported.**

### H2: There is a significant difference in abnormal stock returns between companies with large market capitalization and companies with small market capitalization in response to the Cambridge Analytica scandal.

![image](https://github.com/abhinavliverpool/CambridgeAnalytica/assets/124881241/182f4f42-c402-423a-bbe2-c8e80d37b59a)

The intergroup comparison was performed by dividing the sample companies into two groups based on their market capitalization. The high market capitalization group consisted of 220 companies, while the low market capitalization group consisted of 219 companies. The mean abnormal stock return for the high market capitalization group was 0.0085, indicating a positive return, while the mean abnormal stock return for the low market capitalization group was -0.0477, indicating a negative return. An independent samples t-test was conducted, resulting in a p-value of <0.001. This indicates a statistically significant difference in abnormal stock returns between IT companies with large market capitalization and IT companies with small market capitalization in response to the Cambridge Analytica scandal. 

**So, from our above analysis we can conclude that the hypothesis 2 is accepted.**

### H3: There is a significant difference in abnormal stock returns between companies with high R&D intensity and companies with low R&D intensity in response to the Cambridge Analytica scandal.

![image](https://github.com/abhinavliverpool/CambridgeAnalytica/assets/124881241/e7c37ddd-bb76-413b-8ab0-ca6166109992)

The intergroup comparison was performed by dividing the sample companies into two groups based on their research and development expenses/Sales (R&D Intensity). The high R&D intensity group consisted of 187 companies, while the low R&D intensity group consisted of 188 companies. The mean abnormal stock return for the high R&D intensity group was -0.0258, indicating a negative return, while the mean abnormal stock return for the low R&D intensity group was -0.0093, also indicating a negative return. An independent samples t-test

was conducted, resulting in a p-value of 0.353. This indicates that there is no statistically significant difference in abnormal stock returns between companies with high R&D intensity and companies with low R&D intensity in response to the Cambridge Analytica scandal. 

**So, from our above analysis we can conclude that the hypothesis 3 is rejected and this is a null hypothesis.**

## Discussion

The discussion of the test results obtained from the Event Study and Intergroup Comparison provides valuable insights into the impact of the Cambridge Analytica scandal on the IT industry.

### Test Results:

The test results obtained in Sections 3 and 4 provide valuable insights into the impact of the Cambridge Analytica scandal on the IT industry. Here is a critical, in-depth discussion addressing the questions:

· Event Study: The event study results revealed a significant negative abnormal stock return of IT industry on the Cambridge Analytica scandal. The cumulative abnormal return over the (-10,10) event window was -1.90% with a p-value of 0.02.

![image](https://github.com/abhinavliverpool/CambridgeAnalytica/assets/124881241/0d83355b-dffe-4b62-a92a-8d550b41df3d)

The above graph explains the negative impact of the 488 companies in the IT industry sector due to the Cambridge Analytica Scandal event on 17th March 2018.

· Intergroup Comparison (H2): The intergroup comparison results indicated a significant difference in abnormal stock returns between companies with large market capitalization and companies with small market capitalization. The high market capitalization group had

a positive mean abnormal stock return of 0.0085, while the low market capitalization group had a negative mean abnormal stock return of -0.0477.

· Intergroup Comparison (H3): The intergroup comparison results did not show a significant difference in abnormal stock returns between companies with high R&D intensity and companies with low R&D intensity.

#### Consistency with Predictions:

· H1: The test results are consistent with the prediction stated in H1. The negative abnormal stock return supports the expectation that the Cambridge Analytica scandal had a significant adverse impact on the IT industry.

· H2: The test results align with the prediction in H2, demonstrating that there is a significant difference in abnormal stock return of the companies with large market capitalization and small market capitalization.

· H3: However, the test results for H3 do not support the hypothesis, indicating that there was no significant difference in abnormal stock returns between companies with high R&D intensity and companies with low R&D intensity.

#### Comparison with Past Studies:

· The findings of H1 are similar to previous studies that have shown negative impacts of high-profile scandals on stock returns in various industries(Peruzzi et al., 2018).

· The results of H2 are consistent with existing research suggesting that there is a significant difference between the companies return based on their market capitalization during crisis events (Indrayono, 2021).

· The non-significant results for H3 differ from some past studies that have found that there has been a significant difference between the companies with high R&D intensity and low R&D intensity and firm performance during crisis(Biswas, 2022). This could be due to the unique nature of the Cambridge Analytica scandal and the specific characteristics of the IT industry. R&D investments are crucial for innovation and competitive advantage, they may not always act as a significant buffer against the negative consequences of privacy breaches(Lin et al., 2019). Future research could delve deeper into the specific mechanisms and contextual factors that influence the relationship between R&D investments and firm performance in the face of data privacy breaches.

#### Limitations of Data Analysis:

· The data analysis assumes that abnormal stock returns are solely attributable to the Cambridge Analytica scandal. Other confounding factors or events could have influenced stock returns during the same period, which may have impacted the results(Peruzzi et al., 2018)

· The time frame taken for this analysing only covers a window of 21 days for performing the event study analysis(Peruzzi et al., 2018).

· Our sample size is only restricted to IT industries whereas there could other industries and other events as well that could have affected the stock prices and which were not taken into consideration(Wiles and Danielova, 2009).

# LUMOS Consulting
UNSW

Team: Lumos

Team members: Dongmei Jin, Hao Wang, Linyao Zhang, Mu Li 

Faculty advisor: Xiao Xu

--- 
## 1. Executive Summary
Storslysia is threatened by the increasing catastrophes caused by the escalating impact of climate change. The actuary team at Lumos consulting are working closely with the government to design a multi-peril social insurance program that covers all Storslysia population. The proposed objectives of the social insurance program include:
-	To evaluate Storslysia's short- and long-term displacement cost arising from catastrophes, considering both voluntary and involuntary relocation.
-	To encourage more residents to relocate voluntarily, thus reducing the potential property damage value in high-risk regions.
-	To ensure the cost of the program is strictly under 10% of Storslysia's GDP.

To ensure the feasibility and sustainability of our proposed program, the following metrics require continuous monitoring in both short and long term.
-	The actual frequency and severity of the disasters. 
-	The relocation rates among the regions in Storslysia.
-	The current government policy, inflation rates and risk-free rates. 
-	The trends of material and labor cost associated with construction.
-	The trend of climate change with impact on the environment.

Regions in Storslysia are categorised into 6 different risk levels based on a predetermined hazard risk index. The program design consists of a variety of incentives to encourage voluntary relocation. The report also considers the potential risks associated with the program and their corresponding mitigation measures.

By assessing the impact of the program on economic costs including displacement and incentive cost, there will be an average 8.3% and 6.2% reduction in cost compared with those without the program in the short and long term respectively. Sensitivity analysis is carried out to ensure the program's feasibility during extreme scenarios. The short- and long-term impact on economic capital is also considered in the report.

Overall, the program achieves the objectives of reducing the overall post-hazard displacement cost in both short and long term. The incentive proposed per potential victim is crucial to encourage voluntary relocation.

## 2. Program Design 
### 2.1 Policy 
#### Policy Requirements 
- Only homeowners/landlords in Storslysia are covered under the insurance. 
- Only residents assessed as potential catastrophe victims are entitled to incentives for voluntary relocation. 

#### Claim Coverage 
- The insurance covers the aggregate of property damage values, material and labor cost, cost of replacing household goods and temporary housing cost 
- There is a deductible at 15% of the aggregate cost resulting from disasters averaged on each policyholder. 、

#### Incentives for Voluntary Relocation 
- The present dollar value of incentive is Ꝕ7500 per person per 10 years. Residents eligible for incentives can choose to receive the benefit through one of the methods below: 
  - Lump sum of payments at the time of relocation. 
  - Water and council payments subsidy. 
  - Land tax reduction when purchasing the new relocated property. 

### 2.2 Features 
Disaster Index and moving rate 
Based on historical data on different levels of disasters, a disaster index can be defined as the degree of severity for a whole region. Different grades are assigned for different levels of disasters. I.e., 1 for low damage disasters, 5 for median disasters, and 10 for high severity disasters: 

𝐷𝑖𝑠𝑎𝑠𝑡𝑒𝑟 𝐼𝑛𝑑𝑒𝑥= 1×𝑁𝑜. 𝑜𝑓 𝑙𝑜𝑤 𝑑𝑖𝑠𝑎𝑠𝑡𝑒𝑟𝑠 + 5×𝑁𝑜. 𝑜𝑓 𝑚𝑒𝑑𝑖𝑎𝑛 𝑑𝑖𝑠𝑎𝑠𝑡𝑒𝑟𝑠 + 10×𝑁𝑜. 𝑜𝑓 ℎ𝑖𝑔ℎ 𝑑𝑖𝑠𝑎𝑠𝑡𝑒𝑟𝑠
 
Moving rate is defined as the percentage of population at risk for each region in each year. In general, the higher risk regions will have a higher moving rate. Based on the disaster index, different scenarios will have different moving rates according to Table 1. 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/fee55c472253431b09bd9919bde800bec87539c3/Table%201.png" width = "100%"></picture>

## 3. Assumptions 
- Each household is assumed to have only one owner-occupied house/apartment. 
- Short-term analysis includes yearly data from 2022 to 2026. Long-term analysis includes data from 2030 to 2150 on a 10-year basis. 
- Properties in Storslysia do not have investment value, value increase is only associated with time value of money. 
- The model assumes a completely competitive market where people purchase and sell houses/land in an instant with no opportunity cost. 
- All regions are available for relocation, but people are only willing to move from high disaster index regions to low disaster index regions. 
- There is no voluntary relocation in the short term without the program. 
- Voluntary relocation rate increases with the frequency of disasters, this implies more residents are willing to relocate voluntarily in the long term. 
- Future inflation rate and one-year risk-free rate are simulated using the log-normal assumption based on the fitting of the historical data (Appendix 1: Fitted and simulated results of the rates). 
- Future economic growth is not influenced by the severity of the hazard. 
- The social insurance program does not consider the correlation among the types of hazards.  
- Furniture in rental properties is assumed to belong to the landlords, tenants will not be compensated for furniture damage. 
- In the baseline model, we assume Storslysia follows SSP3-6.0 emission rules. During emergency displacement, 90% of victims will return to their original region after a temporary relocation in a safer region. The remaining 10% are not granted temporary relocation and they will stay permanently in the new region. The material and labor cost increases 25% post-hazard. The cost of replacing furniture and goods is 55% of the median housing costs per household.  

## 4. Economic Costs 
### 4.1 Projection Method 
The base cost contains four parts which are property damage 𝑃𝐷 (Appendix 2: Projection of future property damage), material and labour cost 𝑀𝐿, replacing household goods cost 𝑅𝐻 and temporary housing cost 𝑇𝐻. When a resident moves out from a region, the potential hazard cost associated with the individual is reduced from the base cost. The reduction in percentage of population at risk is denoted as 𝑝. The program includes a deductible which is a percentage 𝑑 of the base costs. 𝐼𝐶  corresponds to the incentive benefit provided for potential victim willing to relocate voluntarily (Appendix 3: Detailed derivation of the formulas). In different situations, the economic cost has different components and the formulas for each situation are shown below: 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/fee55c472253431b09bd9919bde800bec87539c3/Table%202.png" width = "100%"></picture>
 

### 4.2 Economic cost without Program vs with Program 
#### Short Term 
The predicted short-term economic cost with and without the program is displayed in Figure 1. The economic costs without the program are higher than those with the program. In other words, there is a cost reduction due to the implementation of the program and the average cost reduction is around 8.3%. (Appendix 4: Detailed data of the economic costs in the short term) 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%201.png" width = "100%"></picture>


#### Long Term 
Figure 2 depicts the estimated long-term economic cost with and without the program. The inclusion of the program reduces the potential economic costs. The average cost reduction is around 6.2%. Comparing to the short-term, the reduction percentage is smaller which can be explained by the different moving rates. Reduction in cost increases with the moving rates. In short term, there is no voluntary relocation without the program comparing to the large moving rate under program intervention. (Appendix 5: Detailed data of the economic costs in the long term) 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%202.png" width = "100%"></picture>

### 4.3 Displacement and incentive with program 
#### Short Term 
In short term, the frequency of disasters follows a negative binomial distribution. According to Figure 3, the incentive payments are small than displacement costs in the next five years. The incentive cost is Ꝕ 7500 per person for the risk population, and the average displacement cost is about Ꝕ 81806 per person in short term. There is a significant reduction if citizens are willing to move out from high-risk regions voluntarily under the program (Appendix 6: Short term displacement and incentive cost).  

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%203.png" width = "100%"></picture>

#### Long-term 
In long term, the frequency of disasters is predicted based on the SSP model. Figure 4 depicts that the incentive costs are small than displacement costs in the next 120 years. The average displacement cost is about Ꝕ63530 per person in long term, which is smaller than it is in the short term since more citizens are voluntarily moving out from the high-risk region. The average displacement cost per person is still larger than the incentive cost indicating that there is a reduction in cost by implementing of the program (Appendix 7: Long term displacement and incentive cost). 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%204.png" width = "100%"></picture>

### 4.4 10% of GDP Comparison 
According to Figure 5, Storslysia’s GDP increases in the future. However, when comparing the economic costs from the above analysis to the 10% of the predicted average GDP, the cost never exceeds the GDP value which reinforces our objective of cost controlling under 10% projected GDP (Appendix 8: Projection of Storslysia GDP). 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%205.png" width = "100%"></picture>

### 4.5 Economic Capital 
Maximum economic costs can be obtained by considering the worst scenario: 
- Choosing the 95 percentiles of the highest property damage among each hazard level (Appendix 9) 
- Hazard frequency is evaluated under SSP5-Baseline assumption.  
- 50% increase in post hazard labor and material cost, cost of replacing household goods after a catastrophe is 75% of housing cost and 100% of the hazard victims require temporary relocation. 

The economic capital is the difference between the maximum and the base economic costs. Figure 6 displays an increasing trend in the future comparing the capital with and without the program. In the long term, the economic capital with the program will be significantly lower than that without the program (Appendix 10: Projection of the program economic capital). 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%206.png" width = "100%"></picture>

## 5. Risk Management 
### 5.1 Risk 
Below is a Risk Categorization and Definition (RCD) analysis of the potential risks, the numbers range from 1 to 5 where 1 is the lowest severity and likelihood, vice versa. 

|Risk Category |Risk |Risk Division |Severity, likelihood |Explanation |
|:----|:----|:----|:----|:----|
| | | | | |
|Financial Risk |Unexpected economic downturn |GDP |(4, 2) |Low inflation and interest rate results in low GDP growth which impacts the budget of the program. |
|Financial Risk |Black swan event |Economy |(5, 1) |Unexpected large-scale events such as pandemic leading to massive shocks to the economy, causing problems such as unemployment, economic downturn. |
|Financial Risk |Change in currency value |Currency |(3, 2) |Change in Storslysia dollar against foreign currency influences the amount of foreign investment, leading to changes in output. |
|Ethical Risk |Equity risk |Ethic |(1, 4) |Different regions occupy different severity levels, but risk is shared evenly to all population under the program. |
|Ethical Risk |Discrimination risk |Incentives |(2, 4) |Same incentives across all disaster levels, discourage high risky population to move voluntarily |
|Environment Risk |Underestimate the hazard severity |Liquidity |(5, 1) |More frequent large-scale catastrophes bring more property damage than projected. |
|Environment Risk |Unexpected environment deterioration |Disaster |(3, 2) |The environment deteriorates more quickly than expected, making Storslysia more hazard prone. |
|Operational Risk |Administrative failures |Reserve |(4, 2) |Corruption in executive level which significantly reduces the catastrophe reserves. |
|Operational Risk |Underwriting risk |Reserve |(3, 2) |Incorrect identification of the potential residents at risk, causing increasing benefit payments. |
|Operational Risk |Human error |Reserve |(2, 2) |Error when building the model, causing miscalculation of the property damage and reserve requirements. |

### 5.2 Mitigation 
#### Financial risk  
- Collect historical data for large scale economic events, create a new variable in the model to account for the abnormal downturn caused by such events. Thus, the impact the impact of these unusual downturns and regular economic shocks can be studied separately, allowing the policy makers to react to such situations readily. 
- Storslysia’s central bank is suggested to flexibly use fiscal and monetary policies to control the economic market and improve the resilience of the economy. In addition, policy makers must continuously monitor the shifts in politics and financial markets to revise the model. It ensures adequate preparation for currency and economy shocks. 

#### Ethical risk 
- Change incentives corresponding to disaster risk levels to avoid potential discrimination risk. Higher incentives should be granted to areas with greater risk, which could encourage residents in such regions to move out more voluntarily. 

#### Environment risk 
- The government is advised to promote the concept of environmental sustainability through different measures. For example, increasing the use of renewable energy instead of fossil fuels, which will reduce greenhouse emissions and decelerate climate change. 
- Strengthen the regional infrastructure to enhance the capabilities to cope with hazards. In addition, establishing stricter building standards to build more hazard-resistant houses, reducing the potential severity of property damage. 
- Introduce a comprehensive climate disaster data system, including risk maps for monitoring and management of disasters in medium- and high-risk areas. It helps develop appropriate disaster plans intended for different forms of catastrophes. 
- Adequate planning in government land use. Avoid residential planning in high-risk areas. 

#### Operational risk  
- Disclose the information of cash flow intended for the insurance program.  
- Set a dynamic program assessment system for the residents at risk. The system must be periodically monitored with the trend of disasters. 
- Develop more comprehensive and detailed dataset for modelling. Continuously monitor and update the model also assists in mistake revision in the primary model. 

### 5.3 Sensitivity Analysis 
The sensitivity analysis is constructed to demonstrate the financial impact of key assumptions. In the analysis, the percentage of victims returning to their original region after a temporary relocation range from 80% to 100%, the rate of replacing household goods ranges from 40% to 75%, and the increasing rate of labor and material cost ranges from 0% to 50%. The difference in forecast hazard frequencies from SSP1-2.6 to SSP5-Baseline will also be considered. 

#### Short Term 
In the short term, the program reduces all three types of cost according to Figure 7. The change in the growth rate of labor and material cost has the greatest impact on the short-term cost, while the temporary relocation expense exhibits the least impact. The presence of the program contributes to a 15% overall reduction in cost of material and labor where low indicates 0% increase and high indicates 50% increase. However, it exhibits minimal impact on changes in furniture acquisition and temporary relocation costs. 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%207.png" width = "100%"></picture>

#### Long Term 
Like the short-term scenario, the change in labor and materials costs have the highest impact on the long-term cost observed in Figure 8. Choice of SSP assumption also plays a crucial role in the long-term cost. The cost increases 7% moving from SSP1-2.6 to SSP5-Baseline. The government must consider thoroughly about the emission plan in the future. 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%208.png" width = "100%"></picture>

#### Stress Test 
Based on the sensitivity analysis above, the projected scenario exhibits to two extremes cases under the four sensitivity indexes, including SSP, temporary housing cost index (TH_i), Replacing Household goods Cost index (RH_i), and Labor & Material cost index (ML_i). 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/fee55c472253431b09bd9919bde800bec87539c3/Table%203.png" width = "100%"></picture>
Comparing the two scenarios over time in Figure 8, the cost changes in the SSP1 scenario is significantly lower than that in the SSP5 case, which is approximately 5% of the cost changes in SSP5. Under SSP5 assumption, the program costs gradually increase. 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%209.png" width = "100%"></picture>

It is obvious that the presence of the insurance program reduces the economic costs. A comparison is made between the cost under SSP5 and the 10% of minimum of the projected GDP. The highest program cost is about 7% of 10% of GDP (As shown in Figure 9 for year 2150). It indicates that the cost is still under 10% of GDP in the most extreme case. 

<picture align = "center"> <img src= "https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/raw/cda6796b7a836a23263b6da5ef030411e15f623b/Figure%2010.png" width = "100%"></picture>

Based on selected long-term and short-term economic growth, the frequency and severity of climate catastrophes, there is approximately 99% confidence that the cost with the policy will be lower than that without the policy under the baseline scenario. As the incentive increases, the number of people willing to move voluntarily will increase. The incentive benefit can be raised to Ꝕ9185 before the cost without the program will be lower under the SSP1-2.6 assumption. When incentive payment is greater than Ꝕ14450, the program is ineffective in all SSP scenarios, i.e., the confidence level is at 0% as the cost without the program will be lower in every scenario (Appendix 11: Detailed analysis of the critical value). 

## 6. Data and Limitations  
### 6.1 Data Selection 
In this proposal, no external datasets are used to construct the analysis. 

### 6.2 Data Limitations 
Insufficient historical data 
When estimating the future GDP, there are only two historical GDPs which is insufficient for a reliable projection of the future GDP. Time series cannot be applied as it requires a minimum of 5 GDPs. In addition, the inflation and risk-free rates is inconsistent with the GDP growth over 2019 to 2020. There is also no historical data for climate change. It limits the ability to observe a previous trend between the 
𝐶𝑂2 emission, property damage and disaster frequencies.  

The classification of hazards requires refinement 
Hazard event categories are complicated. If each event’s category is determined by the type of hazard which caused the most damage, the hazard classification process will be more efficient. For example, when a thunderstorm results in a flood which is the more disastrous hazard between the two, the classification of this event should specifically be flood. 

The geographic information is not given 
Climate is highly related to the geographical location. For example, precipitation in coastal or riparian areas is usually higher which results in the higher probability of flooding than other regions. Therefore, flood-related policy must be design more carefully for this area. In addition, there are regions exhibiting concentrated occurrence of a particular hazard such as the Tornado Alley in Mid-America. Thus, a comprehensive tornado insurance can be developed according to the extensive amount of historical data. 

The information of victims is not fully provided 
In this analysis, since the disaster severity is only categorised according to property damage, the number of victims is calculated based on the distribution of property value and persons per household. However, this could be inaccurate as victims experience different extent of property damage. Thus, the number of potential voluntary relocations will be underestimated. If the geographic information of disasters and the location of residents are provided. The number of affected residents could be estimated with less bias.  

Lack of historical post-hazard relocation rates  
For involuntarily movers, it is reasonable that some of them would become voluntarily movers after a hazard. Thus, the number of voluntary movers in the future can be projected with less error. 

## 7. Conclusion 

In conclusion, the proposed policy design achieves the required objectives. In the short term, the baseline program reduces 8.3% of economic costs on average. In the long term, the cost reduction is 6.2%. The projected economic costs associated with the program is always under 10% of Storslysia’s GDP. The program also survives the stress test and sensitivity analysis with high degree of certainty. In the long term, the proportion of voluntary movers increase under the incentive scheme. 

## 8. Reference

• Adapting to Rising Flood Risk: An Analysis of Insurance Solutions for Canada (2023). Available at: https://www.publicsafety.gc.ca/cnt/rsrcs/pblctns/dptng-rsng-fld-rsk-2022/index-en.aspx (Accessed: 4 March 2023). 

• Economic Capital and the Assessment of Capital Adequacy (2004), Available at: https://www.fdic.gov/regulations/examinations/supervisory/insights/siwin04/siwinter04-article1.pdf (Accessed:  4 March 2023). 

• Financial governance and risk management of social security (2023). Available at: https://ww1.issa.int/sites/default/files/documents/publications/TR-15-2_en-25493.pdf (Accessed: 20 March 2023). 

• Flood Insurance (2023). Available at: https://www.fema.gov/flood-insurance (Accessed: 3 March 2023). 

• Home insurance affordability and socioeconomic equity in a changing climate, Actuaries Institute (2022 August), Available at: https://actuaries.asn.au/Library/Opinion/2022/HIAGreenPaper.pdf (Accessed: 2 February 2023) 

• Introduction to the National Flood Insurance Program (NFIP) (2023 January). Available at: https://sgp.fas.org/crs/homesec/R44593.pdf (Accessed:  4 March 2023). 

• National Flood Insurance Program (NFIP) (2023). Available at: https://www.benefits.gov/benefit/435 (Accessed: 2 March 2023). 

• Tornado Alley (2023). Available at: https://en.wikipedia.org/wiki/Tornado_Alley (Accessed: 15 March 2023). 

## 9. [Appendices](https://github.com/Actuarial-Control-Cycle-Part-A-2023-T1/Lumos/blob/033691ec6d750b04ed18cd88af5897b21aa908ae/Lumos%20Social%20Insurance%20Report%20Appendix.pdf)

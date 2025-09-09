# Datacosmart_supply_chain_analysis
The goal of this DA project is to perform a thorough analyst on a supply chain datasets to find insights and places to improve.
We process as following : Cleaning data - EDA - categorizing issues - insights & suggestion.

## Repository notes:
1. [DataCo_SMART_Supply_Chain_Analysis.ipynb](https://github.com/DongVND/datacosmart_supply_chain_analysis/blob/main/DataCo_SMART_Supply_Chain_Analysis.ipynb): This is the main file where my analysis performed.
2. [DescriptionDataCoSupplyChain.csv](https://github.com/DongVND/datacosmart_supply_chain_analysis/blob/main/DescriptionDataCoSupplyChain.csv): this file shows the data structure
3. [Presentation of DataCo SMART supply chain analysis.pdf](https://github.com/DongVND/datacosmart_supply_chain_analysis/blob/main/Presentation%20of%20DataCo%20SMART%20supply%20chain%20analysis.pdf): this pdf file presents my analysis progress as well as key findings.
4. [Readme.md](https://github.com/DongVND/datacosmart_supply_chain_analysis/blob/main/README.md): visit this file for guidance
5. [Supply Chain DataCo smart.pbix](https://github.com/DongVND/datacosmart_supply_chain_analysis/blob/main/Supply%20Chain%20DataCo%20smart.pbix): a brief BI dashboard for the key statistics.

**DataCo SMART supply chain analysis is my DA project made on Google Colab.*

The dataset is from DataCo company. 
It includes data of a Global Retailer company on  Provisioning, Production, Sales, Commercial Distribution.
Data source: https://data.mendeley.com/datasets/8gx2fvg2k6/5

## Key findings:
 The data shows a **very high delay delivery rate**.
 The rate remain fluctuating **52% ~ 56%** during 2015-2017 and seems to be increasing in late 2017.
 Late Delivery Rate is affected by many factors. In the scope of our available data, we may point out these **causes**:
-  **Long processing time** from order to actual shipping (4 days instead of the required 2 days)
-  Some **special products require more shipping time** than others (such as Cleats, Men's footwear, Women's apparel etc.) supposed to be on-time or advanced.
- **Shipping Classes are under-performing**. Especially First and Second Classed are often late while they are 
- The **schedule shipping time is not precise**. Especially for 1-2 days delivery orders. We need to improve the precision and consider more about actual average shipping time 3.5 days.

**Suggestions:**
- Focus on improving Average Order Process Time from 4 days down to 2 days.
- Re-qualify the quality of premium shipping modes (First Class and Second Class).
- Optimize delivery routes to Central America, South America and Western Europe.
- Carefully consider schedule shipping time before inputting.
- Finally, be well prepared around the end of year period since it often has more late delivery count than others

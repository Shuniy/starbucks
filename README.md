# Starbucks Rewards Analysis

## Overview
Main objective of this project is to perform RFM(Recency, Frequency, Monetary) Analysis and check whether it is good to promote offers to all the customers or to selected customers with high scores(Uplift Score). 

The metrics used to perform this analysis are **RFM, NIR (Net Incremental Revenue) and rate of return.**

### Dataset
*The [dataset](https://github.com/ZippySphinx/starbucks/tree/main/data) contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that was the challenge to solve with this data set. Our task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.*

### Steps performed:
All steps and procedures performed are mentioned inside the notebooks in the following order:
- [Data Wrangling](https://github.com/ZippySphinx/starbucks/blob/main/Starbucks_Data_Wrangling.ipynb)
- [Data Analysis](https://github.com/ZippySphinx/starbucks/blob/main/Starbucks_Data_Analysis.ipynb)
- [RFM Analysis](https://github.com/ZippySphinx/starbucks/blob/main/Starbucks_RFM.ipynb)
- [Uplift Modeling](https://github.com/ZippySphinx/starbucks/blob/main/starbucks_uplift_modeling.ipynb)

## Requirements

- Python = 3.8
- Anaconda, Jupyter Notebooks (Optional)
- pandas
- numpy
- json
- matplotlib
- seaborn
- sklearn
- imblearn
- tqdm

### References
- [Medium](https://towardsdatascience.com/uplift-modeling-e38f96b1ef60)
- [TowardsDataScience](https://towardsdatascience.com/a-quick-uplift-modeling-introduction-6e14de32bfe0)
- [Investopedia](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)
- [Medium](https://medium.com/gobeyond-ai/rfm-analysis-a-complete-guide-2283a3aa6885)
# Bank-Marketing-Analysis
Introduction

In recent years the number of banks have increased from 270 in 20181 to 362 in 20242, in the Uk. To stay competitive within this dynamic industry, a good marketing strategy is needed to attract and engage old and new customers. Thus the global banking sector tends to spend over $82 billion (in 2023)3 on marketing campaigns to retain and attract new customers. These campaigns need to be customer focused to ensure success or else banks will be burning millions on ineffective campaigns. A report from The Financial Brand found that 63% of banks view that return on investment from marketing campaigns to be their most important performance indicator. For success customer and marketing analysis is needed for banks to understand their customers. 
Aim:
Identify clients that are more likely to subscribe to the bank’s term deposit.

Dataset:
The dataset used has relation to a direct marketing campaign from a Portuguese banking institution. The campaign used phone calls to communicate with potential clients. The dataset contains 17 columns and 45211 rows. Information in the dataset is categorised based on customers personal and non-personal characteristics, response to past marketing campaigns, marketing statistics and result to current term deposit subscription. 

The dataset contained no null values and did not need to be standardised.

For the analysis process, multiple data frames were made based on the customers personal and nin-personal characteristics. Plus a dataframe was made to show the overall likelihood of  customers subscribing to a term deposit subscription.

Key Insights

    • Overall clients were less likely to subscribe to a bank’s term deposit.
    • Clients who had a positive response to past marketing campaigns were more likely to subscribe to a term deposit subscription, with a 64.73 % positive response.
    • Followed by clients who had regular contact (50+) with the bank before the campaign, with a 50% likelihood of subscribing to a term deposit. 
    • Clients who were contacted 40 or more times never subscribed to the bank’s term deposit. This category had the highest level of negative response to ban term deposit subscription
The most important categories:

| Categories | Pos Rsp % mean | Neg Rsp % mean |
|-----:|-----------|-----------|
| 0 | Age Groups | 19.79 | 80.21 |
| 1 | Balance Groups | 11.89 | 88.11 |
| 2 | Duration Groups | 11.89 | 88.11 |
| 3 | Campaign groups | 4.68 | 95.32 |
| 4 | No. of contacts performed before this campaign | 24.13 | 75.87 |
| 5 | Jobs | 13.40 | 86.60 |
| 6 | Marital Status | 12.34 | 87.66 |
| 7 | Education | 11.94 | 88.06 |
| 8 | Default | 9.09 | 90.91 |
| 9 | Housing | 12.20 | 87.80 |
| 10 | Loan | 9.67 | 90.33 |
| 11 | Contact Methods | 10.80 | 89.20 |
| 12 | Previous Outcome | 25.80 |74.20 |


| Categories | Pos Rsp % median | Neg Rsp % median |
|-----:|-----------|-----------|
| 0 | Age Groups | 14.09 | 85.91 |
| 1 | Balance Groups | 11.82 | 88.18 |
| 2 | Duration Groups | 11.82 | 88.18 |
| 3 | Campaign Groups | 3.31 | 96.69 |
| 4 | Contacts performed before this campaign groups | 23.08 | 76.92 |
| 5 | Jobs | 11.82 | 88.18 |
| 6 | Marital Status | 11.95 | 88.05 |
| 7 | Education | 12.07 | 87.94 |
| 8 | Default | 9.09 | 90.91 |
| 9 | Housing | 12.20 | 87.80 |
| 10 | Loan | 9.67 | 90.33 |
| 11 | Contact Methods | 13.42 | 86.58 |
| 12 | Previous Outcome | 14.64 | 85.35 |


Calculating the average and median response change for each category, further proves that previous outcome is the most important category from this bank marketing analysis, followed by contact performed before this campaign. Though it should be noted that the median positive response for Contact performed before this campaign is 23.08%, this is higher compared to the Previous Outcome category, 14.64%. The reason for this is that the distribution for the Previous Outcome category is more skewed compared to the Contact performed before this campaign category. As a result of this, contact performed before this campaign category can be considered the most important category because regardless of the response presented in the category, there is a higher likelihood of clients responding positively to a bank term deposit subscription, compared to the Previous Outcome category. 




Charts
















Recommendations
When marketing to clients for term deposits subscription,the marketing teams should focus on marketing to clients who responded positively to past marketing campaigns and clients who have regular contact with the bank. Plus, sales executives should contact clients approximately 5 times or less when promoting new term deposits. Anymore, than this can reduce the likelihood of clients subscribing to current term deposits. 

The personal characteristics of clients who have a higher likely of subscribing to future term deposits are:

    • Students 
    • Single
    • Have a tertiary education level
    • Have no bank default
    • Have no bank loans
    • Normally contacted via mobile/cellular phones
    • Age group of 70+
    • Have a bank balance of 10,000+

Additional:
A simple prediction model using the information from this dataset can be found in the jupyter notebook. The model has an accuracy level of 1 and no information was pruned in the creation of the tree prediction model. 

____________________________________________________________________________

Definition:
Bank term deposit: A saving account where you make one off deposit, in which you are not supposed to touch. There is a fixed interest rate that you receive from the account for a certain period.  



Links:
Dataset







Bibliography:

    1. Bhattacharya, Joydeep. ‘Bank Marketing Statistics: Investment, Revenue & ROI Trends’. SEO Sandwitch (blog), 6 April 2025. https://seosandwitch.com/bank-marketing-statistics/.
    2. ‘Number of Banks - Office for National Statistics’. Accessed 16 May 2025. https://www.ons.gov.uk/aboutus/transparencyandgovernance/freedomofinformationfoi/numberofbanks.
    3. Statista. ‘Topic: Banking in the UK’. Accessed 16 May 2025. https://www.statista.com/topics/11974/banking-industry-in-the-uk/.


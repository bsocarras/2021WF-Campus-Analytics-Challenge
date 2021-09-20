# 2021 Wells Fargo Campus Analytics Challenge Solution
## Challenge Background
Banks are required to report suspected vulnerable (elder and dependent adult) financial exploitation. Today, much of this activity is limited to human interaction (bankers working with customers on the phone or in person), through which bankers may pick up queues, or red flags or customers self-reporting scams or financial abuse to their financial institution. Digital payments have a degree of reported fraud and claims, with the assumption that much more unreported losses occur, especially perpetrated against older adults (60 years of age or older). As digital payments continue to expand across all demographics, research shows that older adults are showing the biggest uptick in adoption during the 2020/21 period due to the pandemic. Currently, digital payment data is not analyzed specifically under the vulnerable (elder and dependent adult) financial exploitation lens. Banks are required to report elder financial abuse but, unless a customer reports fraud and files a claim, financial abuse can go undetected and repeated fraud via digital payments can continue without the banks’ knowledge. Without detection models, a large amount of fraud is left unreported by consumers and elder and vulnerable adult populations will be at greater risk of being targeted and losing savings to fraudulent payments.

Banks need better methods to help protect elder and vulnerable adults against fraud in the digital payments landscape. Predictive modeling may also be applied in some form to alert consumers and bankers in advance of a fraud attempt and potentially pre-empt certain transactions and monetary losses. As the older adult segment continues to adopt digital technology, including digital payments, banks need better ways to predict and analyze transaction data to detect high risk payment patterns or transaction attributes that signal high risk for fraud, especially for older and vulnerable adult customers, which could be targeted by scammers.

## Challenge Objective
The Challenge is for you to develop a machine learning model to predict suspected elder fraud in the digital payments space as described in the Challenge Background. Your machine learning model (“Solution”) must meet: (a) the Challenge Criteria, (b) follow the Challenge Instructions and Requirements, and (c) incorporate the Key Deliverables, each described in detail below. 

## Challenge Criteria
Build a classification model for predicting elder fraud in the digital payments space as described in Challenge Background, which:
a)	handles missing variables
b)	maximizes the F1 score, 
c)	uses the given data set, 
d)	includes suitable encoding schemes, and
e)	has the least set of feature variables.

The dataset provided on the Challenge page is synthetic. Conditional GAN (“CTGAN”) was used to generate the synthetic dataset for this Challenge. CTGAN is a neural network model that helps to detect the distributions for the dataset and tries to generate data records with similar distribution compared with the original datasets. It can deal with both continuous and categorical features.


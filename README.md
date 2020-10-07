# Loan Prediction


#### •	Background:

LendingClub is an American peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform. The company claims that $15.98 billion in loans had been originated through its platform up to December 31, 2015.

LendingClub enables borrowers to create unsecured personal loans between $1,000 and $40,000. The standard loan period is three years. Investors can search and browse the loan listings on LendingClub website and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. LendingClub makes money by charging borrowers an origination fee and investors a service fee.

#### •	Introduction: 
Before a loan is issued to a borrower, lending club will collect information on a certain individual, generally including two aspects. The first one is personal information which includes age, sex, annual income, and etc. The second is information from third-party which includes FICO score, credit history, delinquency records, and etc. Lending club will then use a predictive model to predict whether this individual will default on loan, in order to make a final decision. The application of machine learning in fraud detection and risk management is very important to Lending Club. In additional to operational expense, default risk is a major component of a company’s loss. Default risk refers to loss exposure when a borrower fails to fulfill its debt obligation, in other words, losing the ability to pay back its loans. Generally, lending club tends to avoid ‘bad’ loans because trivial increase in net profit could leads to tremendous loss due to default. Often, both internal such as individual attributes and external factors such as economic change need to be considered to find an optimal strategy. In the project, we will focus on building internal model to predict the probability of default and classify loan application into default and non-default. The incentive behind this project is to help Lending Club perform better risk management as well as maximize its profit.

#### •	The Data
We will be using a subset of the LendingClub DataSet obtained from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club

#### •	Our Goal
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict whether a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. Keep in mind classification metrics when evaluating the performance of your model!

The "loan_status" column contains our label.

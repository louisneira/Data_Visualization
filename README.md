# Data_Visualization

Loan data from Prosper, a peer-to-peer lending marketplace, is analyzed using Python visualization tools, including matplotlib.pyplot and seaborn libraries. The goal of this analysis is to gain insight into factors that affect estimated rates of return.

Loan data provided by Prosper Funding LLC contained information for 113,397 peer-to-peer loans. Data about the loans includes items associated with credit risk such as borrower credit rating, delinquent loan information, and employment status. Also included were data such as Prosper Funding’s custom ratings and investment from friends. Investment data such as estimated loss and rate of return were also included.

Data cleaning for this set was dropping null data from the columns containing debt to income ratio and delinquent loan amount information. After dropping these data, the data set contained 97,905 loans that were analyzed as discussed below.

The analysis of this data set focused on delinquent loan amount at the time credit information was pulled, homeownership status, and debt to income ratio. Exploratory analysis found no significant impact of homeownership on estimated rate of return. Debt to income ratio for the vast majority of homeowners was under 0.30, and 99.9 percent of borrowers had a debt to income ratio under 1.0. Heat maps and bar graphs were used to explore the effects of debt to income ratio and delinquent loan amounts on estimated rates of return. Based on rates of return, loans to borrowers who had delinquent loan amounts under $50,000 yielded the lowest returns. Returns of loans to borrowers with debt to income ratios between 0.11 and 0.20 appeared to be lower than returns for other debt to income ratio ranges. 

This analysis is done to fulfill the requirements for the Data Visualization course in Udacity's Data Analyst Nanodegree program.

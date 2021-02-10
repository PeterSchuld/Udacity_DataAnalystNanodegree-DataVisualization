# Prosper Loan Data
## by Peter H. Schuld

#### Mentor:
 Lucrezia Morvilli, London

## Dataset

The dataset contains 113,937 observations of Prosper consumer loans from 2006 until early 2014 with 81 variables each (e.g. ProsperRating, BorrowerAPR). I have deleted 1027 observations with duplicate entries or missing data. For each of the remaining 112,910 loans I have calculated the variables Profit & Loss (P&L) and a Total Return (TOT) based on its cash flows. 

The data set was provided by Udacity in a .csv file. 
I have used Prosper's company webside https://www.prosper.com/ to get information about their business model. 

## Summary of Findings

There is a dichotomy in the Prosper loan data with different average credit quality before and after the 2008-2009 Financial Crisis. From the start in 2006 Prosper's loan portfolio grew strongly until coming to a complete standstill in late 2008. Since its SEC registration in 2009, Prosper has provided the proprietary "Prosper Rating" for prospective borrowers based on the company's estimation of that borrower's "estimated loss rate". Correspondingly, the number of defaults is lower in loan vintages post 2009, albeit at lower overall origination activity. However, the number of charged-offs has picked up again in the 2011 and 2012 vintages. Since 2012, Prosper shows a strong growth in new loan origination surpassing pre crisis levels.

The rate of credit impairments (i.e. defaults and charged-offs) were highest for loans issued before 2009 (i.e. Vintage 2006, 2007 and 2008). While the default rates have kept low thereafter, the rate of charged-offs has picked-up again. Both defaults and charged-offs have a similar negative impact on investors total return. I have looked at the ex-ante Expected Return issued by Prosper and the realized Total Return by rating for the loan vintage years 2010-2013. The expected return by rating is a rough forecast of realized total return, typically overstating the annualized investment return by a high margin. 

## Key Insights for Presentation

The annualized total return in Prosper's best performing closed vintage year, 2010, were approx. 2.3% for AA, 2.0% for A , 4.8% for C and D, 6.8% for E and 6.3% for HR. However, in the following years charged-offs have picked-up again and rates keep coming down. A credit impairment rate of 15-20% per vintage year should be expected in normal times, and an economic downturn can lead to a sharp increase. For most vintage years, the medium credit quality ratings B, C and D have the most attractive risk-adjusted profile. Loans from borrowers of lower quality E and high risk HR have generated similar or even lower total returns in 2011-2013 vintages so far, but with a much higher volatility, making 'stock picking' very dangerous. Given the idiosyncratic risk, a high diversification with 100+ loans in a portfolio is advisable for investments in Prosper loans (e.g. USD 50-100 each). Investors should allocate to high rating classes AA and A as well to improve the quality mix of the portfolio. By applying these guidelines an investment return of approx. 5% p.a. can be expected for a well-diversified portfolio. However, economic downturns could significantly reduce the performance. Furthermore, I have looked at the relationship between the variables Employment Status and Income Range and credit impairment rates. The categories can serve as indicators for credit risk. A very low or very high income is a good predictor of increased credit impairment risk. An Employment Status of Employed signals the lowest risk of delinquencies while a status of Self-employed is significantly riskier.

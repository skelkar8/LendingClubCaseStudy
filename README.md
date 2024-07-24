## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

### Project Information

> The project is a data science case study that uses the Lending Club data set to predict the driving factors for loan defaults.

### Project Background

> The company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **\'91risky\'92** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> Find the driving factors which lead to defaulted loans, resulting in losses for the company.

### Data Set

> The data set is a .csv file with the loan data for the Lending Club.

## Conclusions

- The number of loans issued over time increased almost exponentially from 2007 to 2011. This could suggest that the Lending Club business is expanding, and thus presents a greater need to be cautious about who the loans are being issued to.
- There are some very high interest rates and could indicate that some of the borrowers have bad credit scores and are taking risky loans. It could also be related to the Loan amount, as the graphs follow similar patters. Higher loan amounts result in higher interest rates.
- Although most loans are between grades of A, B and C, there are a substantial number of grade D and below that could have higher default rates.
- Although most loans are of 36 months, there a significant number of long term (60 month) loans, these could be riskier compared to short term ones.
- Renters could potentially have higher default rates as compared to owners. Further, owners also have a higher collateral, and could get better loans with lower interest rates.
- Higher loan amounts tend to default more than lower loan amounts.\
- Although most of the borrowers who defaulted have been employed for 10 or more years, Employment Length is not much of a differentiator for knowing whether borrowers will default or not. When we plot ratios, they are pretty much equal for all lengths of employment.
- Borrowers whose primary purpose for the loan is "small business" default significantly more than other categories. This could be since a business is naturally a risky venture, and it might be possible that several of these business have gone bust, resulting in borrowers not making loan payments on time.
- From the state-map, we notice that Nebraska has a very high default rate of 0.6, followed by Nevada (0.22) and New Mexico (0.17).

## Recommendations

1. Certain loan purposes such as "Small Business" may have higher charge-off rates, so consider adjusting approval criteria based on loan purpose.
2. If higher debt-to-income ratios increased risk, consider setting limits on acceptable DTI ratios.
3. Since higher interest rates always lead to more charge offs, consider reducing interest rates slightly for certain borrowers who are categorized as low-risk
4. Be more mindful of lower grade (B, C, D) loans, and try to reduce giving out these loan grades as these are most likely to be charged off.
5. Since longer loans are more likely to default, Lending Club should be more careful when handing out loans of longer periods (60 months). This could also mean limiting the maximum term length for the loans given out.
6. Have stricter rules for loans in states like Nebraska, Nevada and New Mexico, as these states have a higher rate of default as compared to others.

## Technologies Used

- Python - version 3.11.7
- Pandas - version 3.7
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0

## Acknowledgements

This project was inspired by UpGrad IIITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Swapnil Kelkar - @skelkar8
Kritika Singh - @naina-ds

## License

This project is open source and available without restrictions.

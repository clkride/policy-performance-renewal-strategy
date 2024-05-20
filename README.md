<a name="readme-top"></a>
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/clkride/Amazon_Sales_Analytics?style=flat-square)
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/clkride/Amazon_Sales_Analytics?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors/clkride/Amazon_Sales_Analytics?style=flat-square)
![GitHub watchers](https://img.shields.io/github/watchers/clkride/Amazon_Sales_Analytics?style=flat-square)
![GitHub Repo stars](https://img.shields.io/github/stars/clkride/Amazon_Sales_Analytics?style=flat-square)
![GitHub License](https://img.shields.io/github/license/clkride/Amazon_Sales_Analytics?style=flat-square)
<a href="https://linkedin.com/in/abbas-singapurwala">
<img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue">
</a>

# Policy Performance Analysis
Aim - 
1. Provide data-driven insights to support decision-making for the performance of various insurance policies
2. To analyze the relative performance of renewal offers to determine effective marketing campaigns

## Table of Contents
- [Project Description](#project-description)
- [About Data Set](#about-data-set)
- [PowerBI Dashboard](#powerbi-dashboard)
- [Key Business Insights](#key-business-insights)
- [Author](#author)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Description
In this project, 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About Data Set
* **Title**: Auto Insurance Marketing Analysis (with customer demographics)
* **Number of Rows**: 9134
* **Number of Columns**: 24

This dataset represents customer information for a hypothetical insurance company from January 2011 to February 2011, including various attributes related to their insurance policies and personal details. It also includes responses to offers made for policy renewal and the effective dates of those policies.

This data set is one of the publicly available datasets from IBM at the following link: https://www.ibm.com/communities/analytics/watson-analytics-blog/marketing-customer-value-analysis/ and is publicly available for research.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Column Description
1. **Customer:** A unique identifier for each customer.
2. **State:** The state where the customer resides.
3. **Customer Lifetime Value:** The total value a customer brings to the company over their lifetime.
4. **Response:** Indicates whether the customer responded to the last marketing campaign.
5. **Coverage:** The type of insurance coverage (Basic, Extended, Premium).
6. **Education:** The educational level of the customer.
7. **Effective To Date:** The date when the policy becomes effective.
8. **Employment Status:** The employment status of the customer.
9. **Gender:** The gender of the customer.
10. **Income:** The annual income of the customer.
11. **Location Code:** The type of area where the customer lives (e.g., Suburban).
12. **Marital Status:** The marital status of the customer.
13. **Monthly Premium Auto:** The monthly premium for the auto insurance.
14. **Months Since Last Claim:** The number of months since the customer last filed a claim.
15. **Months Since Policy Inception:** The number of months since the policy started.
16. **Number of Open Complaints:** The number of open complaints the customer has.
17. **Number of Policies:** The number of insurance policies the customer holds.
18. **Policy Type:** The type of insurance policy (e.g., Personal Auto, Corporate Auto).
19. **Policy:** The specific policy level.
20. **Renew Offer Type:** The type of offer given for policy renewal.
21. **Sales Channel:** The channel through which the policy was sold (e.g., Web, Branch, Call Center).
22. **Total Claim Amount:** The total amount claimed by the customer.
23. **Vehicle Class:** The classification of the vehicle (e.g., Four-Door Car, SUV).
24. **Vehicle Size:** The size of the vehicle (e.g., Small, Medsize).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Sample Rows
Here are a few sample rows from the dataset:

| Coverage | Education         | Effective To Date | EmploymentStatus | Gender | Income | Location Code | Marital Status | Monthly Premium Auto | Months Since Last Claim | Months Since Policy Inception | Number of Open Complaints | Number of Policies | Policy Type   | Policy      | Renew Offer Type | Sales Channel | Total Claim Amount | Vehicle Class  | Vehicle Size |
|----------|-------------------|-------------------|------------------|--------|--------|---------------|----------------|----------------------|-------------------------|------------------------------|---------------------------|--------------------|---------------|-------------|------------------|---------------|--------------------|----------------|--------------|
| Basic    | Bachelor          | 24-Feb-11         | Employed         | F      | 56274  | Suburban      | Married        | 69                   | 32                      | 5                            | 0                         | 1                  | Corporate Auto | Corporate L3 | Offer1           | Agent         | 384.811147         | Two-Door Car   | Medsize      |
| Extended | Bachelor          | 31-Jan-11         | Unemployed       | F      | 0      | Suburban      | Single         | 94                   | 13                      | 42                           | 0                         | 8                  | Personal Auto  | Personal L3  | Offer3           | Agent         | 1131.464935        | Four-Door Car  | Medsize      |
| Premium  | Bachelor          | 19-Feb-11         | Employed         | F      | 48767  | Suburban      | Married        | 108                  | 18                      | 38                           | 0                         | 2                  | Personal Auto  | Personal L3  | Offer1           | Agent         | 566.472247         | Two-Door Car   | Medsize      |
| Basic    | Bachelor          | 20-Jan-11         | Unemployed       | M      | 0      | Suburban      | Married        | 106                  | 18                      | 65                           | 0                         | 7                  | Corporate Auto | Corporate L2 | Offer1           | Call Center   | 529.881344         | SUV            | Medsize      |
| Basic    | Bachelor          | 03-Feb-11         | Employed         | M      | 43836  | Rural         | Single         | 73                   | 12                      | 44                           | 0                         | 1                  | Personal Auto  | Personal L1  | Offer1           | Agent         | 138.130879         | Four-Door Car  | Medsize      |
| Basic    | Bachelor          | 25-Jan-11         | Employed         | F      | 62902  | Rural         | Married        | 69                   | 14                      | 94                           | 0                         | 2                  | Personal Auto  | Personal L3  | Offer2           | Web           | 159.383042         | Two-Door Car   | Medsize      |


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## PowerBI Dashboard

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Key Business Insights

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Author
 @[Abbas S.](https://github.com/clkride)

## License
The MIT License (MIT)

Copyright (c) 2023 Abbas Singapurwala

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments
Inspiration, code snippets, etc.
* [Choose an Open Source License](https://choosealicense.com)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

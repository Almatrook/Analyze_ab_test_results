# Analyze_ab_test_results



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Overview](#overview)
* [Details](#details) 
* [Findings](#findings)
* [Statistical Analysis Scope](#statistical-analysis-scope)
* [Tools](#tools)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)


<!-- Overview -->
## Overview
A/B test is most commonly conducted by data analysts to prioritize what to do in the future.

The purpose of this project to apply an A/B testing by a company e-commerce website in regard to help promote their decision whether holding the old page or go forward to the new page transformation.

This project was completed as part of Udacity's Data Analyst Nanodegree certification.



<!-- Detail -->
## Details
A statistically significant result has been measured on a dataset by doing measure P values, confidence intervals. 


<!-- GETTING STARTED -->
## Findings
The most important findings are:

In A/B test, findings show that the p-value is 0.896 which is greater than type I error with α = 0.05, and the z-score is 1.2616 which is less than the critical z-score 1.9599. Therefore, the test fail to reject the null hypothesis which indicate that holding in the old page is equal or better than to convert to the new page.

In regression model for conversion based on which page a customer receives, there is a dependency relationship with them but with very small p-value this relation is unlikely to be significant statistically.

In regression model for conversion based on which country a user lives, the p-value associated with ab_page is 0.191 which means the relationship to conversion and these variables values mentioned in the last section is not statistically significant.

As a result, there is no evidence proved that the new page has a better conversion rate than the old page.


<!-- Statistical Analysis Scope -->
## Statistical Analysis Scope
Exploratory Data Analysis



<!-- Tools -->
## Tools

Python libraries : numpy, pandas, matplotlib, seaborn



<!-- Installation -->
## Installation

1. Clone the repo
```sh
git clone https://github.com/Almatrook/Analyze_ab_test_results.git
```


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under GNU General Public License v3.0. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Abdulbasit Almatrook - abdulbaset.almtrook@gmail.com
                     - https://sa.linkedin.com/in/abdulbasit-almatrook-b2689672


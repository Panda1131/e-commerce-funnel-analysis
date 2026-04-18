# E-commerce Funnel Analysis

##  Objective

the goal is to analyze user behavior across different stages of the funnel and identify where users drop off before completing a purchase.


##  Business Problem

The company is facing low conversion rates and wants to understand:

* How users move through each stage of the funnel
* Where the biggest drop-offs occur
* How to improve conversion rates and revenue


##  Dataset Description

The dataset tracks user activity across four stages:

* **Visited** → User visited the website
* **Signed_Up** → User created an account
* **Added_to_Cart** → User added items to cart
* **Purchased** → User completed a purchase

Each column contains:

* `1` = Yes
* `0` = No


##  Tools Used

* Python
* Pandas
* Matplotlib


##  Funnel Overview

We calculated the total number of users at each stage:

| Stage         | Users |
| ------------- | ----- |
| Visited       | 1895  |
| Signed Up     | 1408  |
| Added to Cart | 1010  |
| Purchased     |  619  |


##  Conversion Rates

* Visit → Signup: 74%
* Signup → Cart: 71%
* Cart → Purchase: 61%

These metrics show how efficiently users move through the funnel.


##  Drop-off Analysis

* Drop at Signup: 26%
* Drop at Cart: 28%
* Drop at Purchase: 38%

This helps identify bottlenecks in the user journey.


##  Visualization




##  Key Insights

* Significant drop-off between Visit and Signup → onboarding friction
* Drop-off at Cart to Purchase → checkout issues
* User engagement decreases after signup


##  Business Recommendations

* Simplify the signup process
* Improve product engagement
* Optimize checkout (UI, pricing clarity, payment methods)


##  Conclusion

The analysis highlights key drop-off points in the funnel. Addressing these issues can significantly improve conversion rates and overall business performance.


##  Future Improvements

* Build an interactive dashboard
* Perform A/B testing
* Apply machine learning for conversion prediction

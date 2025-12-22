# UCB-Module-5-Assignment

**Link to [notebook](https://github.com/thechiangsta/UCB-Module-5-Assignment/blob/main/coupon_analysis.ipynb)**

## Overview
This repo contains data analysis on a UCI Machine Learning repository dataset investigating the correlations between those who accept coupons. The goal is to identify key demographics and behaviors that correlate with higher acceptance rates, which could be used for business strategy. Specifically analyzing bar coupons and their acceptance rates. 

## Dataset
*   **Source:** UCI Machine Learning repository
*   **Description:**  The dataset contains information about coupon acceptance, driver demographics (age, marital status, etc.), visit frequency of different establishments (bar/restaurant/coffee house), passenger type, and other relevant features.
*   **Key Variables:**
    *   `Y`:  Binary indicator of coupon acceptance (1 = accepted, 0 = rejected).
    *   `passenger`: Type of passenger (e.g., Kid(s), Alone, Partner).
    *   `Bar`: .
    *   `maritalStatus`: Driver's marital status (e.g., Married, Single).
    *   `age`: Driver's age group (e.g., below21, 21, 50plus).
    *   `RestaurantLessThan20`: Spending at restaurants (<$20)
    *   `income`: Driver's income bracket.

## Findings: Factors Influencing Bar Coupon Acceptance

This analysis identified several demographic and behavioral factors linked to increased bar coupon acceptance.  The strongest predictor is frequent bar visitation, with drivers visiting at least once a month showing ~70% acceptance, increasing to nearly 77% for those visiting more than three times monthly.  Younger drivers (under 30) also exhibit a high acceptance rate (~72%).

Other contributing factors include:

* **Family Status:** Drivers without kid passengers are more likely to accept coupons.
* **Marital Status:**  Drivers who are not widowed show higher acceptance rates.
* **Occupation:** Drivers outside of Farming, Fishing & Forestry occupations demonstrate increased coupon acceptance.

These observations suggest that marketing campaigns should prioritize targeting frequent bar-goers, younger adults, and those without young children. Although further investigation into the underlying reasons for these would better inform business strategy.
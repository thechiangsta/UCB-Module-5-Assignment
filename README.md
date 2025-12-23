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


## Independent Investigation (Coffee House Coupons)
For the independent investigation, the coffee house coupons were analyzed. Coffee coupons as a whole had only a 49.63% acceptance rate. Which is a moderate, not high, rate of acceptance.

## Findings
This is similar to that of the bar coupons in that driver behavior is a huge indicator. We see higher acceptance with respect to specific categories.

* **Visit Frequency:** Those who already frequent coffee shops, with at least 1 to 3 visits and up, were highly likely to accept the coupon.
* **Age:** A trend downwards reveals those who are younger are more likely to accept coupons.
* **Passengers:** In the context of the company the driver is in, we see much higher acceptance rates when they are with friends or with a partner.
* **Temperature:** In cold, but not absolutely freezing weather, we see there is a higher rate of acceptance whether or not the driver is a frequent coffee-goer.

# Actionable Items
## Bar Coupons
Want to target:
* Younger demographics, ages 21 to 35
* Drivers without kid passengers
* Those who frequent bars

## Coffee Coupons
Want to target:
* Frequent coffee-goers (1 or more visits a month)
* Younger drivers, especially those under 21
* Drivers with friends or partners, with social like offers (BOGO and such)
* Drivers in cold weather (could be by location, or seasonal)

## Summary
Throughout my analysis with both of these explorations I was able to find correlations with driver habits, and how that coupled with their demographic, affected coupon acceptance rates. This type of analysis through data aggregation, and visualizations, can be incredibly powerful for business strategy. Informing both marketing campaigns and offers for different types of businesses. Both to encourage frequent visitors to continue doing so, or increase their visits; or by encouraging those who don't usually visit by decreasing friction in their decision to do so.
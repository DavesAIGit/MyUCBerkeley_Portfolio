# Coupon Acceptance Analysis

## Overview
This project explores a dataset from the UCI Machine Learning Repository that captures customer responses to various driving-related coupons. The goal is to understand the factors influencing whether a customer accepts a coupon.

## Dataset
The dataset includes survey responses from Amazon Mechanical Turk users. It contains information about driving scenarios such as destination, time, weather, passenger, and coupon type. The target variable `Y` indicates coupon acceptance:
- `1`: Accepted (either immediately or before expiration)
- `0`: Not accepted

## Methods
- **Data Cleaning**: Removed whitespace from column names and checked for missing values.
- **Statistical Summaries**: Used pandas to compute descriptive statistics and grouped summaries.
- **Visualizations**: Created bar plots using Matplotlib and Seaborn to show coupon acceptance across different features.

## Key Findings
- **Coupon Type**: Coffee House and Restaurant(<20) coupons had higher acceptance rates.
- **Time of Day**: Morning and afternoon times showed higher acceptance.
- **Passenger Influence**: Traveling alone or with a partner increased likelihood of acceptance.
- **Destination Impact**: Coupons were more accepted when heading to home or work.

## Recommendations
1. Focus on promoting Coffee House and Restaurant(<20) coupons.
2. Target morning and afternoon time slots for coupon distribution.
3. Personalize offers based on passenger type.
4. Use destination data to tailor coupon types.

## Files
- `Coupon_Acceptance_Analysis.ipynb`: Jupyter notebook with full analysis.
- `coupon_acceptance_by_type.png`: Visualization of coupon acceptance by type.
- `coupon_acceptance_by_time.png`: Visualization of coupon acceptance by time of day.
- `coupon_acceptance_by_passenger.png`: Visualization of coupon acceptance by passenger.
- `coupon_acceptance_by_destination.png`: Visualization of coupon acceptance by destination.

# VendBridge-Portfolio

## Table of Contents
1. [Project Overview](#Project-Overview)
2. [Project Aim](#Project-Aim)
3. [Objectives](#objectives)  
4. [Dashboard](#dashboard)
5. [Key insights](#key-insights)
6. [Recommendation](#Recommendation)

# Project Aim
To develop an interactive dashboard to monitor the adoption and user engagement on the VendBridge App since its launch.

# Objectives
- To track how the app has performed since its inception
- To understand  what extent VendBridge has been embraced by users, using KPIs such as daily active users, installation rates, and user sign-up figures
- To measure how engaged users are with the app. ​ By examining metrics like transaction counts and average time spent per user
- To track Key stability and retention indicators, such as uninstall counts and app crash instances, to ensure a smooth user experience.
- To pinpoint areas where VendBridge falls short and make data-driven recommendations to enhance user adoption and satisfaction. ​

# Tools & Technologies
- Excel / Google Sheets
- Tableau

# Dataset Description
List key fields and what they represent (e.g., CustomerId, Daily Active Users, Installations, etc.)

# Project Workflow
## Phase 1: Data Preparation
- Explore and clean the dataset
- Understand field definitions and business context

## Phase 2: KPI Definition
- Import the dataset into Tableau. Begin identifying and listing key product KPIs like DAU, sign-ups, transactions, installs and uninstalls.
- Define metrics like churn rate, DAU, transaction volume, engagement tiers, etc.
- Align KPIs with business goals

## Phase 3: Visualisation Development
- Connect the dataset to Tableau
### Create visualisations for:
- DAU, time spent, and transaction volume. 
- Churn analysis
- User acquisition & retention
- Regional engagement leaderboard
- App crashes, usage time, etc.
- Rank user engagement by region. Implement a tier system (Gold, Silver, Bronze, Newbie)
- Use Tableau’s exponential smoothing to project 30/60/90-day user activity. Display trends and confidence intervals.

## Phase 4: Forecasting 
- Use Tableau’s Exponential Smoothing to forecast user behaviour
- Visualise predictions with confidence intervals

# Phase 5: Dashboard Finalisation & Deployment
- Combine visuals into interactive dashboards
- Add filters and drill-down capabilities
- Publish on Tableau Public or present internally

# Phase 6: Reporting
Prepare an analytical report summarising findings and trends, and recommendations

# Dashboards

## Overview
![Image](https://github.com/user-attachments/assets/5383f20b-de3e-4867-9b86-67888d54b0d7)

## User Engagement
![Image](https://github.com/user-attachments/assets/9d4a5657-21fa-4ff9-859c-bdf468476f9e)

## Leaderboard
![Image](https://github.com/user-attachments/assets/8d763e6a-ba7e-49dd-8382-f03fc932cb69)

## Forecast
![Image](https://github.com/user-attachments/assets/a3fca310-59f4-4e78-89c5-56e534d1e7c8)

# Key Insights
### Platform Specific Insight
- Installs and sign-ups both increased for July compared to August, but the sign-up rate dipped slightly in August.
- Daily uninstalls continued to rise, while crash incidents remained elevated. Installs and sign-ups rose in both July and August, yet the sign-up rate trended downward.
- Uninstalls and crashes increased in July; August saw crashes continue upward, but uninstalls moderated.
- Churn rate peaked in July, but decreased in August.

### User engagement and transaction volume
- Daily active users increased month-to-month in July and August, driven primarily by Android users
- The USA led all regions in Daily active users throughout the period, followed by EMEA and APAC.
- July saw the USA top the regional trend with its transaction volume outperforming the previous month, while APAC, EMEA, Canada, and LATAM fell.
- In August, all regions experienced transaction growth versus July.
- Despite rising DAU, overall transaction volume declined slightly over the three-month span, suggesting a dip in per-user activity.

### Engagement Scores
- The USA achieved the highest engagement score across all regions, indicating strong user interaction and satisfaction relative to APAC, EMEA, Canada, and LATAM.
- The USA had the highest number of daily active users

### Forecast
- Forecast models with a 95% confidence interval project stable App crash rates and transaction volumes over the next 30, 60, and 90 days. The forecast quality is “OK,” suggesting lower expected error compared to naïve benchmarks.

# Recommendations:
1. Optimise Onboarding:
- Address the slight drop in sign-up conversion on Android and in LATAM by simplifying the registration flow and localizing onboarding content.
2. Enhance Stability:
- Prioritise crash investigations for iOS in August and Android in July to maintain the downward trend in the longer term.
3. Reduce Uninstalls:
- Implement in-app surveys for users at uninstall to capture exit feedback, particularly in APAC and LATAM, where uninstalls remain high.
4. Boost Engagement & Transactions:
- Introduce targeted promotions in regions where DAU rose but transactions lagged (e.g., EMEA).
5. Monitor Forecast Deviations:
- Set up weekly reviews of crash and transaction metrics against forecasted ranges to catch divergences early.

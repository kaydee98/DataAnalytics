# Ford GoBike System Data Analysis
## by Kayode Dada


## Dataset

>This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 183,412 entries with 16 columns. Each ride is represented by a single row in the dataset. The dataset contains information on bike-share trips and details of each trip's duration, start and end times, and station locations (start and end stations). It also includes user demographics, such as birth year, gender, and user type..


## Summary of Findings

> - A concentration of users in the younger age range (20-40 years), with a right-skewed age distribution that declines with age.
>- Trip durations were generally short across all ages, with most trips below 200 minutes.
>- User type (Customer vs. Subscriber) was more influential on trip duration patterns than gender, with Subscribers showing more consistent trip durations and Customers (occasional users) showing more variability.
>- Gender patterns were similar across categories, though Male users had the highest trip frequency.
>- Outliers, such as improbable ages over 100 and trip durations exceeding 600 minutes, indicated data quality issues.


## Key Insights for Presentation

>### Key Insights for Presentation
The notebook focuses on analyzing the Ford GoBike dataset to understand the influence of **age, gender, and user type** on bike-sharing trip durations. Here’s a summary of the main findings that can be polished and presented:

1. **Key Findings**:
   - **Age and Trip Duration**: Younger users, primarily within the 20-40 age range, dominate the usage, with most trips lasting under 200 minutes. The age distribution is right-skewed, tapering off as age increases.
   - **User Type Differences**: Trip duration patterns vary significantly between **Subscribers** (consistent and shorter trips) and **Customers** (occasional users with greater variability).
   - **Gender Influence**: Gender differences in trip frequency are minimal; however, Male users make the most trips.

2. **Design Adjustments**:
   - **Data Cleaning**: Outliers, like unrealistic ages (75+ years) and unusually long trips (over 250 minutes), required handling to enhance data reliability.
   - **Visual Emphasis**: Focusing on visuals that clearly separate Subscriber vs. Customer behavior will illustrate trip duration consistency and variability effectively.

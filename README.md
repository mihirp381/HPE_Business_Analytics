# HPE_Business_Analytics

Digital Marketing Budget Allocation based on Predictive and Prescriptive Analytics:

This project demonstrates the use of predictive and prescriptive analytics for optimum budget allocation for Digital Marketing. 
The problem set provides a dataset with over 1 million synthetic observations with the following columns:

Variables 
-----------------
1. Date - the date when the metrics data is collected
2. ID - Campaign ID
3. Goal Code - Campaign Goal Code - {Intent to Buy, Awareness, Engagement, Consideration}
4. Campaign Ad ID
5. Ad Digital Channel - Medium of display - {Search, Social, Programmatic Ad Display}
6. Ad Channel partner - Channel partner 1-9
7. Ad device 
8. Ad Group
9. Ad Content ID
10. Ad Content Type
11. Audience Type
------------------
Metrics
__________________
$ Spend
# Impressions
# Clicks
# Video Completes
# Social Likes
# Social Shares
# Web Visits
# Collateral Views
# Product Views 
# Form complete

The project demonstrates the use of Zero-Inflated Regressor model which was then used in a Non-linear optimization tool with required constraints to allocate optimum budget based on :
1. Click through rate
2. Video Completion rate
3. Social Media Engagement Rate
4. Conversion rate- {based on Goal code}
5. Excess returns

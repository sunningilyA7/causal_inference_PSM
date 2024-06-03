# causal_inference_PSM
# The impact of watching live streams on conversion rates

## Background


An e-commerce platform has recently started livestream delivery to improve the overall revenue. 

Users can place orders directly from online stores, or they can watch the live broadcast in a live broadcast room and place orders.

Now analysis is needed to show that users can effectively improve the conversion rate, and then determine whether to continue investing in the live broadcast.

Statistics have found that the conversion rate of users watching live broadcasts is higher, but whether it is because the conversion potential of users watching live broadcasts is high, it is necessary to exclude the influence of users themselves. Therefore, causal inference is used to evaluate.


## Data info
OPTUM_LAB_ID：row number 
CASE：Treatment, if watch live streams
gender：male 1, female 0
age
activedays_per_week： go to online stores weekly days
cv：conversion rate

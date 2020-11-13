# Subscription Retention Rate
# GOAL
The goal of this challenge is to model subscription retention rate.Subscriptions are a great business model. There are so many advantages for businesses in having subscribers compared to single purchase users: revenue by customer is much higher, it is possible to cross-sell to the subscribers, future revenue is easily predictable, there is a significant cost (time/effort/etc.) for the customer in canceling the subscription, etc.

# DESCRIPTION
Pull data from all the users who subscribed in January and see, for each month, how many of them unsubscribed.<br />

Goal of this project is to:<br />
1) A model that predicts monthly retention rate for the different subscription price points Based on your model, for each price point, what percentage of users is still subscribed after at least 12 months?<br />
2) How do user country and source affect subscription retention rate? How would you use these findings to improve the company revenue?<br />

# DATA
We have only one table called "subscription"<br />

subscription" - gives information about the user and her subscription status<br />

Columns:<br />
user_id : the id of the user. Unique by user.<br />
subscription_signup_date : when the user signed up for the subscription. It is always Jan, 2015 in this table.<br />
subscription_monthly_cost : how much the user pays each month for the subscription (USD)<br />
source : marketing acquisition channel (SEO/Ads/Friend Referral) billing_cycles : total billing cycles as of the end of August.<br />
is_active : whether the subscription is still active (1) or not (0). If billing cycles is 8, it means the user has still an active subscription.<br />

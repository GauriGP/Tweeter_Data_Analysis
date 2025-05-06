# Tweeter_Data_Analysis
Task 1
-----------------
Engagement Rate:
Only top 10% of tweets selected using percentile-based logic 
Likes:
Only tweets with more than 50 likes included to ensure significance.
Character Count:
Tweets with less than 30 characters are selected to focus on short, high-impact tweets. didn't applied this filter because there is not data for this filter it shows blank chart after applying this filter.
Time Constraint (IST):
Only tweets posted between 3 PM to 5 PM IST are considered.
Day of Week:
Weekdays only (Monday–Friday), as engagement tends to vary by day.

Task 2
------------------
I created a Clustered Bar Chart that:
Breaks down URL clicks, user profile clicks, and hashtag clicks.
Groups data by tweet categories (e.g., tweets with media, links, hashtags).
Includes only tweets that meet all of the following criteria:
Were posted between 3 PM – 5 PM IST
Occurred on an even-numbered date
Had at least one interaction (i.e., at least one of the click types > 0)
I chose not to apply the WordCount > 40 condition because:
Upon inspecting the dataset, very few or no tweets met this threshold, which would result in an empty chart 
Removing the condition allowed you to retain more relevant data and still meet the main interaction/time/date-based criteria.

Task 3
-----------------------
This clustered column chart shows the average engagement rate of tweets that included app opens versus those that didn’t.
We only analyzed tweets from weekdays, posted between 9 AM and 5 PM UTC.
We filtered tweets with even impressions, odd-numbered dates, and meaningful length (over 30 characters).
Additionally, this visual appears only during specific IST time windows, ensuring relevance in real-time dashboards.
All tweet content was cleaned to exclude words containing the letter 'D' for a controlled linguistic experiment.”

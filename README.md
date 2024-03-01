# message_phrase
Write a SQL query to count the number of messages that  include the following phrase:  “Miss you”  (Note: You should account for a capital “M” and lowercase “m”.)

Select count(*) as numOfMessages
From messages
Where message like ‘Miss you’ or message like ‘miss you’;

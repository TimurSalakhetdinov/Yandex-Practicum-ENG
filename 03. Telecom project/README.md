# Yandex-Practicum

**Project - Determination of a prospective tariff for a telecom company**

*Project Description*

Clients are offered two tariff plans of the company "Megaline": "Smart" and "Ultra". To adjust the advertising budget, the commercial department wants to understand which tariff brings in more money.

It is necessary to make a preliminary analysis of tariffs on a small sample of customers. The data of 500 Megaline users is available: who they are, where they are from, what tariff they use, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and draw a conclusion - which tariff is better.

*Description of tariffs*

Tariff "Smart"
Monthly fee: 550 rubles
Included 500 minutes of talk, 50 messages and 15 GB of internet traffic
The cost of services in excess of the tariff package: 1. minute of conversation: 3 rubles ("Megaline" always rounds up the values ​​of minutes and megabytes. If the user spoke only 1 second, a whole minute is counted in the tariff); 2. message: 3 rubles; 3. 1 GB of Internet traffic: 200 rubles.

Tariff "Ultra"
Monthly fee: 1950 rubles
Included 3000 minutes of calls, 1000 messages and 30 GB of internet traffic
Cost of services in excess of the tariff package: 1. minute of conversation: 1 ruble; 2. message: 1 ruble; 3. 1 GB of Internet traffic: 150 rubles.

Note:

Megaline always rounds seconds to minutes, and megabytes to gigabytes. Each call is rounded up separately: even if it lasted only 1 second, it will be counted as 1 minute.
For web traffic, individual sessions are not counted. Instead, the monthly total is rounded up. If a subscriber uses 1025 megabytes this month, they will be charged for 2 gigabytes.

*Description of data*

Table users (information about users):
- user_id - unique user ID
- first_name - username
- last_name - last name of the user
- age — user's age (years)
- reg_date — tariff activation date (day, month, year)
- churn_date — date of termination of the tariff use (if the value is omitted, then the tariff was still valid at the time of data upload)
- city — user's city of residence
- tarif — tariff plan name

The calls table (information about calls):
- id — unique call number
- call_date — call date
- duration — call duration in minutes
- user_id — identifier of the user who made the call

Messages table (message information):
- id — unique message number
- message_date — message date
- user_id — identifier of the user who sent the message

internet table (information about internet sessions):
- id — unique session number
- mb_used - the amount of Internet traffic spent per session (in megabytes)
- session_date — internet session date
- user_id - user ID

Tariffs table (tariff information):
- tariff_name — tariff name
- rub_monthly_fee — monthly subscription fee in rubles
- minutes_included - the number of minutes of conversation per month included in the subscription fee
- messages_included - number of messages per month included in the subscription fee
- mb_per_month_included - the amount of Internet traffic included in the subscription fee (in megabytes)
- rub_per_minute - the cost of a minute of conversation in excess of the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
- rub_per_message - the cost of sending a message in excess of the tariff package
- rub_per_gb - the cost of an additional gigabyte of Internet traffic in excess of the tariff package (1 gigabyte = 1024 megabytes)
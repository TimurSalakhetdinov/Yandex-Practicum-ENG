# Yandex-Practicum

**Project - Building a classification model to select the best rate**

*Project Description*

The mobile operator "Megaline" found out that many customers use archival tariffs. They want to build a system that can analyze customer behavior and offer users a new tariff: "Smart" or "Ultra".

We have at our disposal data on the behavior of customers who have already switched to these tariffs. We need to build a model for the classification problem that will select the appropriate rate. Data preprocessing is not required - we have already done it.

Let's build a model with the largest possible value of accuracy.

*Description of data*

Each object in the data set is information about the behavior of one user per month. Known:

* calls — number of calls,
* minutes — total duration of calls in minutes,
* messages - the number of sms messages,
* mb_used - used Internet traffic in Mb,
* is_ultra - what tariff did you use during the month ("Ultra" - 1, "Smart" - 0).
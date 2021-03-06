# Yandex-Practicum
This repository contains projects that I completed while studying at the Data Scientist course in Yandex Practice.

**List of projects:**

[**1. Credit scoring for a bank**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/01.Credit_score)

The customer is the credit department of the bank. It is necessary to find out whether the marital status and the number of children of the client affect the fact of repaying the loan on time. Input data from the bank - statistics on the solvency of customers.

The results of the study will be taken into account when building a credit scoring model - a special system, which evaluates the ability of a potential borrower to repay a loan to a bank.

[**2. Research of apartments for sale ads**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/02.Real_estate)

At the disposal of the data service Yandex.Realty - an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. The market value of the property must be determined. The task is to set the parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.

Two types of data are available for each apartment for sale. The first ones are entered by the user, the second ones are obtained automatically on the basis of cartographic data. For example, the distance to the center, airport, nearest park and reservoir.

[**3. Determination of a prospective tariff for a telecom company**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/03.Telecom_project)

Clients are offered two tariff plans of the company Megaline: "Smart" and "Ultra". To adjust the advertising budget, the commercial department wants to understand which tariff brings in more money.

It is necessary to make a preliminary analysis of tariffs on a small sample of customers. The data of 500 Megaline users is available : who they are, where they are from, what tariff they use, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and draw a conclusion - which tariff is better.

[**4. Analysis of data on computer games from the Steam Store**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/04.Games_project)

Steam online store sells computer games all over the world. Historical game sales data, user and expert ratings, genres and platforms (such as Xbox or PlayStation) are available from public sources. It is necessary to identify patterns that determine the success of the game. This will allow you to bid on a potentially popular product and plan advertising campaigns.

The abbreviation ESRB (Entertainment Software Rating Board) is an association that determines the age rating of computer games in the data set. The ESRB evaluates game content and assigns it to an appropriate age rating, such as Mature, Toddler, or Teen.

[**5. Building a classification model for choosing the best tariff**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/05.ML_mobile_tariff)

The mobile operator Megaline found out that many customers use archival tariffs. It wants to build a system that can analyze customer behavior and offer users a new tariff: "Smart" or "Ultra".

We have at our disposal data on the behavior of customers who have already switched to these tariffs. We need to build a model for the classification problem that will select the appropriate rate.

[**6. Customer churn**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/06.Beta-Bank)

Customers began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. We have been provided with historical data on customer behavior and termination of agreements with the bank.

Let's build a model with an extremely large value of the F1 score - we need to bring the metric to 0.59. Then we check the F1 score on the test sample.

Additionally, we measure the AUC-ROC, compare its value with the F1 score.

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

[**7. Choosing a location for a well**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/07.Oil_well_Rosneft)

The project is intended for the mining company GlavRosGosNeft. We need to decide where to drill a new well.

We have been provided with oil samples in three regions. The characteristics for each well in the region are already known. We will build a model to determine the region where mining will bring the greatest profit. Let's analyze the possible profit and risks using the Bootstrap technique.

[**8. Recovery of gold from ore**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/08.Gold_processing)

Let's prepare a prototype of a machine learning model for Zifra. The company develops solutions for the efficient operation of industrial enterprises.

The model should predict the recovery rate of gold from gold ore. We have data with extraction and purification parameters at our disposal.

The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

[**9. Insurance company customer data protection**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/09.Insurance_company_data)

It is necessary to protect the data of clients of the insurance company "Though the Flood". Develop a data transformation method that makes it difficult to recover personal information from them.

We need to protect the data so that the quality of the machine learning models does not deteriorate during the transformation.

[**10. Determining the cost of cars**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/10.Autos_cost_estimation)

Service for the sale of used cars "Not beaten, not beautiful" is developing an application to attract new customers. In it, you can quickly find out the market value of your car. We have historical data at our disposal: technical characteristics, configurations and prices of cars. We need to build a model to determine the cost.

For the customer it is important:
* quality of prediction;
* prediction speed;
* studying time.

[**11. Forecasting taxi orders**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/11.Time_series_forecast)

Clear Taxi has collected historical data on taxi orders at airports. To attract more drivers during the peak period, you need to predict the number of taxi orders for the next hour. Let's build a model for such a prediction.

[**12. Project for Wikishop**](https://github.com/TimurSalakhetdinov/Yandex-Practicum-ENG/tree/main/12.Project_for_Wikishop)

Online store Wikishop launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. The store needs a tool that will look for toxic comments and submit them for moderation.

Let's train the model to classify comments into positive and negative. We have at our disposal a dataset with markup on the toxicity of edits.

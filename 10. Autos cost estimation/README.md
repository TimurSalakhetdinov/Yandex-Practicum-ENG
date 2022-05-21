# Yandex-Practicum

**Project - Determining the cost of cars**

*Project Description*

Service for the sale of used cars "Not beaten, not beautiful" is developing an application to attract new customers. In it, you can quickly find out the market value of your car. We have historical data at our disposal: technical characteristics, configurations and prices of cars. We need to build a model to determine the cost.

The customer is important:
* quality of prediction;
* prediction speed;
* studying time.

*Instructions for the implementation of the project*

To enhance exploration, go beyond gradient boosting. Try simpler models - sometimes they work better. These are rare cases that are easy to miss if you always apply only boosting. Experiment and compare the characteristics of the models: the speed of work, the accuracy of the result.

* Download and prepare data.
* Train different models. For each, try different hyperparameters.
* Analyze the speed and quality of models.

Notes:
* To assess the quality of models, use the RMSE metric.
* Learn the LightGBM library on your own and use it to build gradient boosting models.
* The execution time of a Jupyter Notebook code cell can be obtained with a special command. Find her.
* Since the gradient boosting model can take a long time to train, change only two or three parameters for it.
* If Jupyter Notebook stops working, remove unnecessary variables with the del statement:
del features_train

*Description of data*

The data is in the /datasets/autos.csv file.

signs
* DateCrawled - date of downloading the profile from the database
* VehicleType - type of car body
* RegistrationYear - year of registration of the car
* Gearbox - type of gearbox
* Power - power (hp)
* Model - car model
* Kilometer - mileage (km)
* RegistrationMonth - month of car registration
* FuelType - type of fuel
* Brand - car brand
* NotRepaired - was the car under repair or not
* DateCreated - date of creation of the profile
* NumberOfPictures - the number of photos of the car
* PostalCode - postal code of the owner of the profile (user)
* LastSeen - date of last user activity

Target feature
* Price - price (EUR)
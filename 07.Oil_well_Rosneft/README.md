# Yandex-Practicum

**Project - Selection of a location for a well**

*Project Description*

The project is intended for the mining company GlavRosGosNeft. We need to decide where to drill a new well.

The steps for choosing a location are usually as follows:

* In the selected region, characteristics for wells are collected: the quality of oil and the volume of its reserves;
* Build a model to predict the volume of reserves in new wells;
* Choose the wells with the highest value estimates;
* Determine the region with the maximum total profit of selected wells.

We have been provided with oil samples in three regions. The characteristics for each well in the region are already known. We will build a model to determine the region where mining will bring the greatest profit. Let's analyze the possible profit and risks using the Bootstrap technique.

*Description of data*

Geological exploration data of three regions are in the files:
* /datasets/geo_data_0.csv. Download dataset
* /datasets/geo_data_1.csv. Download dataset
* /datasets/geo_data_2.csv. Download dataset
* id - unique identifier of the well;
* f0, f1, f2 - three signs of points (it doesn't matter what they mean, but the signs themselves are significant);
* product is the volume of reserves in the well (thousand barrels).
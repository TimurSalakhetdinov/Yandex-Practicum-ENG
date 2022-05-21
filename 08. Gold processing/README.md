# Yandex-Practicum

**Project - Recovery of gold from ore**

*Project Description*

Let's prepare a prototype of a machine learning model for Zifra. The company develops solutions for the efficient operation of industrial enterprises.

The model should predict the recovery factor for gold from gold ore. We have data with extraction and purification parameters at our disposal.

The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

*Technological process*

How is gold obtained from ore?

When the mined ore undergoes primary processing, a crushed mixture is obtained. It is sent for flotation (enrichment) and two-stage purification.

1. Flotation

A mixture of gold-bearing ore is fed into the flotation plant. After enrichment, a rough concentrate and “dump tails” are obtained, that is, product residues with a low concentration of valuable metals.
The stability of this process is affected by the unstable and non-optimal physico-chemical state of the flotation pulp (a mixture of solid particles and liquid).

2. Cleaning

The crude concentrate goes through two purifications. The output is the final concentrate and new final tailings.

*Description of data*

Technological process

* Rougher feed - feedstock
* Rougher additions (or reagent additions) - flotation reagents: Xanthate, Sulphate, Depressant
    * Xanthate ** - xanthate (promoter, or flotation activator);
    * Sulphate - sulfate (in this production, sodium sulfide);
    * Depressant - depressant (sodium silicate).
* Rougher process (English "rough process") - flotation
* Rougher tails - dump tails
* Float banks - flotation unit
* Cleaner process - cleaning
* Rougher Au - rough gold concentrate
* Final Au — final gold concentrate

Stage parameters

* air amount — air volume
* fluid levels - fluid level
* feed size — size of feed granules
* feed rate - feed rate

Name of features

The name of the features is:
[stage].[parameter_type].[parameter_name]
Example: rougher.input.feed_ag

Possible values ​​for block [stage]:

* rougher - flotation
* primary_cleaner - primary cleaning
* secondary_cleaner - secondary cleaning
* final - final characteristics

Possible values ​​for block [parameter_type]:

* input — raw material parameters
* output - product parameters
* state - parameters characterizing the current state of the stage
* calculation - calculated characteristics
# Past Research

## Worcester Polytechnic Institute: 2016 - Present

### 2018-2019
#### Sequential Document Classification
#### Attributed-Attention
#### Early Classification
#### Disentangled recurrent memory curation
#### Mentoring one new PhD student on time series missing value imputation
#### Internship with UMass Medical School
- Working with Jomol Matthew on a Microsoft Word plugin for automatically extracting and recommending eligibility criteria from the US NLM [clinical trials database](https://clinicaltrials.gov/) to assist clinicians with writing new clinical trials.

### 2017-2018
#### Published one paper studying multimodal data combination for MRSA predictions
#### Joke Generation
#### Thesis studying early time series classification
#### Mentoring NSF Research Experience for Undergraduates project - Classifying time series with missing values

### 2016-2017

#### Leading a Research Experience for Undergraduates Project - Early Prediction of MRSA Infections Using EHRs

- Worked with Sarah Brownell, an REU Intern, to generate Early Warnings for MRSA infections using historical clinical data.
- Used time series from the MIMIC III database and aligned them into a tabular format for use by common machine learning algorithms.
- Varying the number of days used to predict MRSA along with the number of days in advance of MRSA to generate prediction allowed us to understand what portions of a patient's stay should be used to make predictions.
- Our models detected signs of MRSA infections accurately far in advance of actual diagnosis dates.
- Our paper was published at BIOSTEC 2018 and I presented this work in January 2018 in Funchal, Madeira.
- Sarah also presented the poster version of this work at the 2017 IEEE MIT Undergraduate Research Technology Conference.

#### Leading a Research Experience for Undergraduates Project - Detecting Clostridium Difficile Infections Using Recurrent Neural Networks

- Worked with Sean Tocci, another REU Intern, to figure out a deep learning approach to infection prediction.
- We developed a [Python framework](https://github.com/Thartvigsen/Keras-LSTM-Experimental-Framework) for Recurrent Neural Networks using [Keras](https://keras.io/).
- Using the same patients as in CREST, we trained Long Short-Term Memory Recurrent Neural Networks to identify *Clostridium Difficile* infections, approaching similar results as in our prior work, CREST.

#### Clostridium Difficile Risk Estimation (CREST)
Clinical data offers many opportunities for impactful and technically fascinating research. Beginning in August, 2016, I worked with Cansu Sen using the [*MIMIC III Intensive Care Unit Database*](https://mimic.physionet.org/). **This database is publicly available**, consists of 12 years of clinical data from ~58,000 admissions. You can request access to the database [here](https://mimic.physionet.org/gettingstarted/access/). We focused on the detection of one infection, *Clostridium Difficile*, and therefore extracted patients who got this infection during their stay. As is required for supervised-learning algorithms, we also extracted a set of patients who did not get this infection and trained Logistic Regression, Random Forest, and Support Vector Machine models to detect patterns that indicate *C. Diff.* based on the following data sources:

- On-admission demographic information
- Clinical notes written upon admissions
- 80-dimensional time series of clinical measurements
- Hand-crafted features summarizing the time series to capture their temporal nature

We trained classifiers on each source of data, then merged their outputs to create a well-informed meta-learner to detect *C. Diff.* far in advance of the date of infection-confirmation. This work was published at the **European Conference of Machine Learning (ECML)**, presented by Cansu Sen on September 19, 2017 in Skopje, Macedonia. Our paper can be found [here](http://ecmlpkdd2017.ijs.si/papers/paperID487.pdf).

#### University of Arizona REU: Summer 2015

From June-August 2015, I took part in an NSF-funded Research Experience for Undergraduates at the University of Arizona in Tucson, AZ. I was stationed at [BioSphere 2](http://biosphere2.org/) and worked with Dr. Shirley Papuga in the School of Natural Resources and the Environment.

* Prior to my REU, Dr. Papuga and her students collected thousands of image sequences of creosote bushes over eight seasons.
* We worked with this sequence of images of one creosote bush to investigate how its health changed through the seasons and across three years.
* Using MATLAB, I trained decision trees to segment these color-images into sections consisting of *background*, *leaves*, *stems*, and *flowers*.
* We asked two main questions:
  * How does the image segmentation change through the seasons and over the years?
  * Can we use such segmented information to approximate the *normalized difference vegetation index* (NDVI), an expensive but reliable method for understanding global plant health?
* By the end of the summer we had uncovered that this method of segmenting images captured seasonal trends but did not approximate NDVI.
* I presented this work at a poster-session at the 2015 Undergraduate Research Opportunities Consortium (UROC 2015).

### SUNY Geneseo: 2012 - 2016

#### 2016: Scraped Movie Networks from IMDB
#### 2015: Text Mining of Song Lyrics
#### 2013-2014: Modeling Vaccination Strategies on Graphs

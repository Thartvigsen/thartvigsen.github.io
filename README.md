I am a Data Science Ph.D. student at Worcester Polytechnic Institute primarily focused on Recurrent Neural Networks and Reinforcement Learning. I am eventually aiming for a faculty position. 

Please feel free to contact me with questions regarding my research or Data Science at WPI at **twhartvigsen@wpi.edu**.

<img style="float: right;" src="/profile.png">
# Links
- [LinkedIn](http://linkedin.com/in/thartvigsen)
- [GitHub](https://github.com/Thartvigsen)
- [Resume](/Hartvigsen_resume.pdf)

# Research Interests

- Sequential Decision Making
- Recurrent Neural Networks
- Time Series Classification
- Healthcare data

# Current Research

I am currently interested in learning patterns in time series as early as possible, analogous to  predictions using the shortest possible time series prefixes. In many domains, the evaluation of a predictive model should not only be accuracy, but a trade-off between accuracy and earliness. For instance, detecting an infection perfectly immediately before a discriminative test is given has almost no potential impact, while a less accurate prediction made far in advance of infection has potential to positively impact a patient's stay. While so far my work has been evaluated on Electronic Health Records, I am far more interested in the techniques, and these problems are present in many domains. 

# Publications

- Teeple, E., **Hartvigsen, T.**, Sen, C., Rundensteiner, E. (2017) **Risk Stratification and Diagnostic Performance of a Machine Learning Algorithm for Clostridium Difficile Detection Using Electronic Health Records Data**. Currently in review at the Journal of Infection Control and Hospital Epidemiology.
- **Hartvigsen, T.**, Sen, C., Brownell, S., Teeple, E., Kong, X. and Rundensteiner, E. **Early Prediction of MRSA Infections using Electronic Health Records**. In Proceedings of the 11th International Joint Conference on Biomedical Engineering Systems and Technologies (BIOSTEC 2018) - Volume 5: HEALTHINF, pages 156-167, ISBN: 978-989-758-281-3. **Nominated for Best Student Paper**.
- Sen, C., **Hartvigsen, T.**, Claypool, K., Rundensteiner, E. (2017, September). **CREST - Risk Prediction for Clostridium Difficile Infection Using Multimodal Data Mining**. ECML/PKDD 2017.

# Past Research
## Worcester Polytechnic Institute: 2016 - Present

### 2016-2017

### Leading a Research Experience for Undergraduates Project - Early Prediction of MRSA Infections Using EHRs

- Worked with Sarah Brownell, an REU Intern, to generate Early Warnings for MRSA infections using historical clinical data.
- Used time series from the MIMIC III database and aligned them into a tabular format for use by common machine learning algorithms.
- Varying the number of days used to predict MRSA along with the number of days in advance of MRSA to generate prediction allowed us to understand what portions of a patient's stay should be used to make predictions.
- Our models detected signs of MRSA infections accurately far in advance of actual diagnosis dates.
- Our paper was published at BIOSTEC 2018 and I presented this work in January 2018 in Funchal, Madeira.
- Sarah also presented the poster version of this work at the 2017 IEEE MIT Undergraduate Research Technology Conference.

### Leading a Research Experience for Undergraduates Project - Detecting Clostridium Difficile Infections Using Recurrent Neural Networks

- Worked with Sean Tocci, another REU Intern, to figure out a deep learning approach to infection prediction.
- We developed a [Python framework](https://github.com/Thartvigsen/Keras-LSTM-Experimental-Framework) for Recurrent Neural Networks using [Keras](https://keras.io/).
- Using the same patients as in CREST, we trained Long Short-Term Memory Recurrent Neural Networks to identify *Clostridium Difficile* infections, approaching similar results as in our prior work, CREST.

### Clostridium Difficile Risk Estimation (CREST)
Clinical data offers many opportunities for impactful and technically fascinating research. Beginning in August, 2016, I worked with Cansu Sen using the [*MIMIC III Intensive Care Unit Database*](https://mimic.physionet.org/). **This database is publicly available**, consists of 12 years of clinical data from ~58,000 admissions. You can request access to the database [here](https://mimic.physionet.org/gettingstarted/access/). We focused on the detection of one infection, *Clostridium Difficile*, and therefore extracted patients who got this infection during their stay. As is required for supervised-learning algorithms, we also extracted a set of patients who did not get this infection and trained Logistic Regression, Random Forest, and Support Vector Machine models to detect patterns that indicate *C. Diff.* based on the following data sources:

- On-admission demographic information
- Clinical notes written upon admissions
- 80-dimensional time series of clinical measurements
- Hand-crafted features summarizing the time series to capture their temporal nature

We trained classifiers on each source of data, then merged their outputs to create a well-informed meta-learner to detect *C. Diff.* far in advance of the date of infection-confirmation. This work was published at the **European Conference of Machine Learning (ECML)**, presented by Cansu Sen on September 19, 2017 in Skopje, Macedonia. Our paper can be found [here](http://ecmlpkdd2017.ijs.si/papers/paperID487.pdf).

## University of Arizona REU: Summer 2015

From June-August 2015, I took part in an NSF-funded Research Experience for Undergraduates at the University of Arizona in Tucson, AZ. I was stationed at [BioSphere 2](http://biosphere2.org/) and worked with Dr. Shirley Papuga in the School of Natural Resources and the Environment.

- Over a few years prior to my REU, Dr. Papuga and her students collected thousands of image sequences of plants throughout the seasons.
- We worked with images of one such plant (a creosote bush) to  uncover how its health changed through the seasons and across many years.
- Using MATLAB, I trained decision trees to segment these color-images into sections consisting of *background*, *leaves*, *stems*, and *flowers*.
- We asked two main questions:
-- How does the image segmentation change through the seasons and over the years?
-- Can we use such segmented information to approximate the *normalized difference vegetation index* (NDVI), an expensive but reliable method for understanding global plant health?
- By the end of the summer we had uncovered that this method of segmenting images captured seasonal trends but did not approximate NDVI.
- I presented this work at a poster-session at the 2015 Undergraduate Research Opportunities Consortium (UROC 2015).

## SUNY Geneseo: 2012 - 2016

### 2016: IMDB-Scraped Movie Networks
### 2015: Text Mining of Song Lyrics
### 2013-2014: Modeling Vaccination Strategies on Graphs

# Conferences

Since beginning my studies at WPI, I have attended the following conferences:
- [BIOSTEC 2018](http://www.biostec.org/), Funchal, Madeira - Portugal
- [Machine Learning for Health Care 2017](http://mucmd.org/), Northeastern University
- [North East Database Day 2017](http://mitdbg.github.io/nedbday/2017/), Massachusetts Institute of Technology

# Education

- Ph.D. Data Science, 2021, Worcester Polytechnic Institute.
- B.A. Applied Mathematics, Minor in BioMathematics, 2016, SUNY Geneseo.

# Personal
Outside of research, I spend my time cycling (2016 Giant TCR Advanced Ultegra), rock climbing, and reading fantasy books (currently reading [The Shadow of What Was Lost](http://www.jamesislington.com/)). I am also training for my first Half Ironman: Ironman 70.3 Syracuse.

![bike](/bike.jpg)

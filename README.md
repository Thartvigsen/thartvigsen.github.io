# Introduction

I am a Data Science Ph.D student at Worcester Polytechnic Institute focused on Machine Learning with sequential data. I learned to love Machine Learning and Data Mining during my undergrad at SUNY Geneseo, where I worked on various research projects revolving around graph theory and natural language processing. Now, I get to fully invest myself in fascinating Machine Learning problems every day, eventually aiming for a faculty position. 

Here at WPI, I have invested myself in both the Data Science community, serving on the Data Science Council and organizing talks and colloquiums, and the Graduate Student community, serving as the Data Science representative on the Graduate Student Government Student Council. I also ride with the WPI cycling team.


<img style="float: right;" src="/profile.png">
# Links
- [LinkedIn](http://linkedin.com/in/thartvigsen)
- [GitHub](https://github.com/Thartvigsen)
- [Resume](/resume.pdf)

# Research Interests

- Machine Learning
- Deep Recurrent Models
- Sequential Data


# Current Research

I am currently interested in learning patterns in time series as early as possible, analogous to using the shortest possible subsequences. In many domains, the evaluation of a predictive model should not only be accuracy, but should be a trade-off between accuracy and timeliness. For instance, detecting an infectionperfectly immediately before a discriminative test is given has almost no potential impact, while a less accurate prediction made far in advance of infection has potential to positively impact a patient's stay. In this light, I am working on model-based early-classification of time series to be evaluated in multiple domains. I am currently targeting publication at SIGKDD 2018 with a submission deadline in February. 

# Past Research
## Worcester Polytechnic Institute
<img src="/wpilogo.png" style="width:10px; height:7px;">

### 2016-2017

### Leading Research Experiences for Undergraduates - Early Prediction of MRSA Infections Using EHRs

- Over the course of 10 weeks during summer 2017, I worked with Sarah Brownell, an REU Intern, to generate Early Warnings for MRSA infections using historical clinical data.
- We collected time series variables from the MIMIC III database, and aligned them in a tabular format.
- Varying the number of days used to predict MRSA along with the number of days in advance of MRSA to generate prediction allowed us to understand what portions of a patient's stay should be used to make predictions.
- We uncovered that our selected models could detect signs of MRSA infections accurately far in advance of actual diagnosis dates.
- This work was submitted to HealthInf 2018 on September 5, 2017 and we will hear back about the reviewers' decision in October.
- Sarah will be presenting the poster version of this work at the 2017 IEEE MIT Undergraduate Research Technology Conference.

### Leading Research Experiences for Undergraduates - Detecting Clostridium Difficile Infections Using Recurrent Neural Networks

- Built on top of the CREST framework, I worked with Sean Tocci, another REU Intern, to figure out a deep learning approach to infection prediction.
- We developed a [Python framework](https://github.com/Thartvigsen/Keras-LSTM-Experimental-Framework) for Recurrent Neural Networks using [Keras](https://keras.io/)\*.
- Using the same patients as in CREST, we trained Long Short-Term Memory Recurrent Neural Networks to identify *Clostridium Difficile* infections, approaching similar results as in CREST.

\*I have since moved away from my Keras framework to TensorFlow, which allows for more flexibility. However, Keras was a good starting place for quick implementation. 

### Clostridium Difficile Risk Estimation (CREST)
Clinical data offers many opportunities for impactful and technically fascinating research. Beginning in August, 2016, I worked with Cansu Sen using the [*MIMIC III Intensive Care Unit Database*](https://mimic.physionet.org/). **This database is publicly available**, consists of 12 years of clinical data from ~58,000 admissions. You can request access to the database [here](https://mimic.physionet.org/gettingstarted/access/). We focused on the detection of one infection, *Clostridium Difficile*, and therefore extracted patients who got this infection during their stay. As is required for supervised-learning algorithms, we also extracted a set of patients who did not get this infection and trained Logistic Regression, Random Forest, and Support Vector Machine models to detect patterns that indicate *C. Diff.* based on the following data sources:

- On-admission demographic information
- Clinical notes written upon admissions
- 80-dimensional time series of clinical measurements
- Hand-crafted features summarizing the time series to capture their temporal nature

We trained classifiers on each source of data, then merged their outputs to create a well-informed meta-learner to detect *C. Diff.* far in advance of the date of infection-confirmation. Our 
This work was published in the Applied Data Science Track of the **European Conference of Machine Learning (ECML)**, presented by Cansu Sen on September 19, 2017 in Skopje, Macedonia. The paper can be found [here](http://ecmlpkdd2017.ijs.si/papers/paperID487.pdf).

## SUNY Geneseo
<img style="float: right;" src="/geneseologo.jpg">
# Technology

I use **Python** for all of my programming due the overall speed of implementation. Testing ideas using Python is extremely rapid compared to lower-level languages and rapidly learning whether or not an idea may be fruitful is a great benefit. For Machine Learning I use [**NumPy**](http://www.numpy.org/) and [**Scikit-Learn**](http://scikit-learn.org/stable/), for Deep Learning I use [**TensorFlow**](https://www.tensorflow.org/). I have experience using R and MATLAB but have ultimately selected Python as my main language. Finally, I use only Linux on my personal computer and for experiments on the [WPI high performance computers](http://arc.wpi.edu/resources/hardware/hpc-clusters/) and am gaining experience writing shell scripts.

# Education

- Ph.D. Data Science, 2021, Worcester Polytechnic Institute
- B.A. Applied Mathematics, Minor in BioMathematics, 2016, SUNY Geneseo.

# Publications

- Sen, C., **Hartvigsen, T.**, Claypool, K., Rundensteiner, E. (2017, September). CREST - Risk Prediction for Clostridium Difficile Infection Using Multimodal Data Mining. ECML/PKDD 2017.
- **Hartvigsen, T.**, Sen, C., Brownell, S., Teeple, E., Rundensteiner, E. Early Prediction of MRSA Infections using Electronic Health Records. In submission to HealthInf 2018.
- **Hartvigsen, T.**, Sen, C., Teeple, E., Rundensteiner, E. Risk Stratification and Diagnostic Performance of a Machine Learning Algorithm for Clostridium Difficile Detection Using Electronic Health Records Data. Preparing for submission the the New England Journal of Medicine in October 2017.

# Personal
Outside of my research I spend time on my bike (2016 Giant TCR Advanced) and reading fantasy books.

![Image of My Bike](/bike.jpg)

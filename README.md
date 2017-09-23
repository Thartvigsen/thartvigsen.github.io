# Introduction

I am a second-year Data Science Ph.D student at Worcester Polytechnic Institute. I learned to love Machine Learning and Data Mining during my undergrad at SUNY Geneseo, where I worked on various research projects revolving around graph theory and natural language processing. Now, I get to fully invest myself in fascinating Machine Learning problems every day, eventually aiming for a faculty position. 

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

# Past Research
## Worcester Polytechnic Institute
### 2016-2017

### Leading Research Experience for Undergraduates - Early Prediction of MRSA Infections Using EHRs

Test

### Leading Research Experience for Undergraduates - Detecting Clostridium Difficile Infections Using Recurrent Neural Networks

Building on top of the CREST paper, we decided to move towards a deep learning approach to infection prediction. To prototype these models quickly, I developed a Python Framework, available [here](https://github.com/Thartvigsen/Keras-LSTM-Experimental-Framework), for Recurrent Neural Networks using [Keras](https://keras.io/). I have since moved away from this framework to [TensorFlow](https://www.tensorflow.org/), which allows for more flexibility, but Keras was a good starting place for quick implementation. We used the same patients as in CREST and trained Long Short-Term Memory Recurrent Neural Networks to identify *C. Diff.* infections, approaching the results obtained by CREST.

### Clostridium Difficile Risk Estimation (CREST)
Clinical data offers many opportunities for impactful and technically fascinating research. Beginning in August, 2016, I worked with Cansu Sen using the *MIMIC III Intensive Care Unit Database*. **This database is publicly available**, consists of 12 years of clinical data from ~58,000 admissions, and can be found [here](https://mimic.physionet.org/). We focused on the detection of one infection, *Clostridium Difficile*, and therefore extracted patients who got this infection during their stay. As is required for supervised-learning algorithms, we also extracted a set of patients who did not get this infection and trained Logistic Regression, Random Forest, and Support Vector Machine models to detect patterns that indicate *C. Diff.* based on the following data sources:

- On-admission demographic information
- Clinical notes written upon admissions
- 80-dimensional time series of clinical measurements
- Hand-crafted features summarizing the time series to capture their temporal nature

We trained classifiers on each source of data, then merged their outputs to create a well-informed meta-learner to detect *C. Diff.* far in advance of the date of infection-confirmation. Our 
This work was published in the Applied Data Science Track of the **European Conference of Machine Learning (ECML)**, presented by Cansu Sen on September 19, 2017 in Skopje, Macedonia. The paper can be found [here](http://ecmlpkdd2017.ijs.si/papers/paperID487.pdf).

# Technology

I use Python for all of my programming due the overall speed of implementation. Testing ideas using Python is extremely rapid compared to lower-level languages and rapidly learning whether or not an idea may be fruitful is a great benefit. For Machine Learning I use NumPy and Scikit-Learn, for Deep Learning I use TensorFlow.

# Education

- Ph.D. Data Science, 2021, Worcester Polytechnic Institute
- B.A. Applied Mathematics, Minor in BioMathematics, 2016, SUNY Geneseo.

# Publications

- Sen, C., Hartvigsen, T., Claypool, K., Rundensteiner, E. (2017, September). CREST - Risk Prediction for Clostridium Difficile Infection Using Multimodal Data Mining. ECML/PKDD 2017.
- Hartvigsen, T., Sen, C., Brownell, S., Teeple, E., Rundensteiner, E. Early Prediction of MRSA Infections using Electronic Health Records. In submission to HealthInf 2018.
- Hartvigsen, T., Sen, C., Teeple, E., Rundensteiner, E. Risk Stratification and Diagnostic Performance of a Machine Learning Algorithm for Clostridium Difficile Detection Using Electronic Health Records Data. Preparing for submission the the New England Journal of Medicine in October 2017.

# Extra
Outside of my research I spend time on my road bike (2016 Giant TCR Advanced) and reading fantasy books.

![Image of My Bike](/bike.jpg)

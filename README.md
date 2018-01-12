I am a Data Science Ph.D. student at Worcester Polytechnic Institute focused on Machine Learning on Time Series and am primarily working on Deep Learning and Reinforcement Learning. I am eventually aiming for a teaching faculty position. 

Here at WPI, I have invested myself in both the Data Science community and the Graduate Student community. I am organizing talks and colloquiums for our department and am serving as the Data Science representative on the Graduate Student Government Student Council. I also ride with the WPI cycling team.

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

I am currently interested in learning patterns in time series as early as possible, analogous to  predictions using the shortest possible subsequences. In many domains, the evaluation of a predictive model should not only be accuracy, but a trade-off between accuracy and timeliness. For instance, detecting an infection perfectly immediately before a discriminative test is given has almost no potential impact, while a less accurate prediction made far in advance of infection has potential to positively impact a patient's stay. I am currently targeting publication at KDD 2018 with a submission deadline in February. While so far my work has been evaluated solely on Electronic Health Records, I am far more interested in the techniques, and these problems are present in many domains. 

# Publications

- **Hartvigsen, T.**, Sen, C., Brownell, S., Teeple, E., Kong, X. and Rundensteiner, E. **Early Prediction of MRSA Infections using Electronic Health Records**. In Proceedings of the 11th International Joint Conference on Biomedical Engineering Systems and Technologies (**BIOSTEC 2018**) - Volume 5: HEALTHINF, pages 156-167, ISBN: 978-989-758-281-3. **Nominated for Best Student Paper**.
- Sen, C., **Hartvigsen, T.**, Claypool, K., Rundensteiner, E. (2017, September). **CREST - Risk Prediction for Clostridium Difficile Infection Using Multimodal Data Mining**. ECML/PKDD 2017.
- **Hartvigsen, T.**, Sen, C., Teeple, E., Rundensteiner, E. (2017) **Risk Stratification and Diagnostic Performance of a Machine Learning Algorithm for Clostridium Difficile Detection Using Electronic Health Records Data**. Preparing for submission the the New England Journal of Medicine in January 2018.

# Past Research
## Worcester Polytechnic Institute: 2016 - Present

### 2016-2017

### Leading Research Experiences for Undergraduates - Early Prediction of MRSA Infections Using EHRs

- Over the course of 10 weeks during summer 2017, I worked with Sarah Brownell, an REU Intern, to generate Early Warnings for MRSA infections using historical clinical data.
- We collected time series variables from the MIMIC III database, and aligned them in a tabular format.
- Varying the number of days used to predict MRSA along with the number of days in advance of MRSA to generate prediction allowed us to understand what portions of a patient's stay should be used to make predictions.
- We uncovered that our selected models could detect signs of MRSA infections accurately far in advance of actual diagnosis dates.
- I will be presenting this work at HealthInf in January 2018 in Funchal, Madeira.
- Sarah will also be presenting the poster version of this work at the 2017 IEEE MIT Undergraduate Research Technology Conference.

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

We trained classifiers on each source of data, then merged their outputs to create a well-informed meta-learner to detect *C. Diff.* far in advance of the date of infection-confirmation. This work was published in the Applied Data Science Track of the **European Conference of Machine Learning (ECML)**, presented by Cansu Sen on September 19, 2017 in Skopje, Macedonia. The paper can be found [here](http://ecmlpkdd2017.ijs.si/papers/paperID487.pdf).

## University of Arizona: Summer 2015

From June-August 2015, I took part in an NSF-funded Research Experience for Undergraduates at the University of Arizona in Tucson, AZ. I was stationed at [BioSphere 2](http://biosphere2.org/) and worked with Dr. Shirley Papuga in the School of Natural Resources and the Environment.

- Over a few years prior to my REU, Dr. Papuga and her students collected thousands of image sequences of plants throughout the seasons.
- We worked with images of one such plant (a creosote bush) to  uncover how its health changed through the seasons and across many years.
- Using MATLAB, I trained decision trees to segment these color-images into sections consisting of *background*, *leaves*, *stems*, and *flowers*.
- We asked two main questions:
-- How do the sections change through the seasons and over the years?
-- Can we use such image-segmentation information to approximate the *normalized difference vegetation index*, an expensive but reliable method for understanding global plant health?
- By the end of the summer we had uncovered that this method of segmenting images captured seasonal trends but did not approximate NDVI.
- I presented this work at a poster-session at the 2015 Undergraduate Research Opportunities Consortium (UROC 2015).

## SUNY Geneseo: 2012 - 2016

### 2016: IMDB-Scraped Movie Networks
### 2015: Text Mining of Song Lyrics
### 2013-2014: Modeling Vaccination Strategies on Graphs

# Conferences 

Since beginning my studies at WPI, I have attended the following conferences:

- [Machine Learning for Health Care 2017](http://mucmd.org/), Northeastern University
- [North East Database Day 2017](http://mitdbg.github.io/nedbday/2017/), Massachusetts Institute of Technology

# Technology

I use [**Python**](https://www.python.org/) for all of my programming due the overall speed of implementation. While run-time is significantly slower than a lower-level language, testing ideas using Python is extremely rapid, which in turn can provide feedback on the potential of research ideas. For general Machine Learning I use [**NumPy**](http://www.numpy.org/) and [**Scikit-Learn**](http://scikit-learn.org/stable/), for Deep Learning I use [**TensorFlow**](https://www.tensorflow.org/). I am also always building on top of my love for [**vim**](http://www.vim.org/).

I have experience using R and MATLAB but have ultimately selected Python as my main language. Finally, I use Linux on my personal computer and for experiments on the [WPI high performance computers](http://arc.wpi.edu/resources/hardware/hpc-clusters/) and am gaining experience writing shell scripts. Other technical skills include LaTeX and GitHub.

# Education

- Ph.D. Data Science, 2021, Worcester Polytechnic Institute.
- B.A. Applied Mathematics, Minor in BioMathematics, 2016, SUNY Geneseo.

# Personal
Outside of research, I spend my time cycling (2016 Giant TCR Advanced Ultegra), rock climbing, and reading fantasy books (currently on a [Brandon Sanderson](https://brandonsanderson.com/) kick). I am also beginning to train for my first Half Ironman: Ironman 70.3 Syracuse.

![bike](/bike.jpg)

---
title: "Recurrent Halting Chain for Early Multi-label Classification"
collection: publications
excerpt: 'This paper proposes the first solution to the open problem of Early Multi-Label Classification.'
venue: KDD
paperurl: 'https://thartvigsen.github.io/files/adaptive_halting_kdd19.pdf'
date: 2019-08-04
---

Early Multi-label Classification is the marriage of the Early Classification and
Multi-label Classification problems. Early Classification is the goal of
classifying time series while using as few timesteps as possible. Multi-label
classification is the goal of predicting a set of labels for each instance. The
problem of Early Multi-label Classification is to both predict each label in the
label set as early as possible while concurrently modeling the dependencies
between labels themselves.
This setting is extremely important in settings such as diagnosis, where a
person may have multiple ailments concurrently and their set of ailments often
come in groups (for instance, if a person has diabetes, there is a larger chance
that they have heart disease than bone spurs).  We solve this problem using a
novel combination of Classifier Chains for multi-label classification and
Adaptive-Halting Policy Networks for early classification, resulting in our
proposed Recurrent Halting Chain.

```
@inproceedings{hartvigsen2020recurrent,
title={Recurrent Halting Chain for Early Multi-label Classification},
author={Hartvigsen, Thomas and Sen, Cansu and Kong, Xiangnan and Rundensteiner, Elke},
booktitle={Proceedings of the 26th ACM SIGKDD international conference on Knowledge discovery and data mining},
pages={101--110},
year={2020},
organization={ACM}
} ```

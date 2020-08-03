---
title: "Recurrent Halting Chain for Early Multi-label Classification"
collection: publications
excerpt: 'This paper proposes the first solution to the open problem of Early Multi-Label Classification.'
venue: KDD
date: 2020-08-25
---

Early Multi-label Classification of the Time Series is the task of predicting a
label set for a time series instance while observing as few time steps per
class as possible. This is extremely important in time-sensitive domains such
as healthcare, finance, and weather prediction. A key example of this setting
is in Clinical Diagnosis: Given a patient's physiological stream, predict their
set of conditions early enough to allow a clinician to react in time. The key
challenge/opportunity in this problem is to use the correlations between labels
to predict more-accurate label sets earlier. We propose the first solution to
this open problem, combining a recurrent neural network, classifier chain, and
reinforcement-learning based halting policy network. At every time step, the
model chooses whether or not to halt and predict each class. Once a label is
predicted, it is added to a growing set of already-predicted labels which is fed
back into the model itself, serving as a classifier chain. We validate our
approach using human activity recognition data.

```
@inproceedings{hartvigsen2020recurrent,
  title={Recurrent Halting Chain for Early Multi-label Classification},
  author={Hartvigsen, Thomas and Sen, Cansu and Kong, Xiangnan and Rundensteiner, Elke},
  booktitle={Proceedings of the 26th ACM SIGKDD international conference on Knowledge discovery and data mining},
  year={2020},
  organization={ACM}
}
```

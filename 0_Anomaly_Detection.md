# Anomaly Detection

>Hold what you really know and tell what you do not know -this will lead to knowledge.
>--Confucious

>Machine knows I don't know
Machine knows I know

### Problem Formulation

- Given a set of training data ***x*** = {x<sup>1</sup>, x<sup>2</sup>, ..., x<sup>N</sup>}
- Anomaly Detector (AD) :
	- **x** similar to training data => AD => Normal
	- **x** different from training data => AD => Anomaly (outlier, novelty, exceptions)
- Different approaches use different ways to determine the similarity


### Application
- Fraud Detection
- Network Intrusion Detection
- Cancer Detection


### Binary Classification ?
- Given normal data **x** => Class 1
- Given anomaly data **x_** => Class 2
- Then training binary classifier...
- NOT **x** cannot considered as a class
- It is difficult to find anomaly example
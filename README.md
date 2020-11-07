# DDoS
Problem Statement:<br>
In this case study we will be working on computer network datasets in order to come up with a ML model which can detect DDoS attack with very high accuracy.
DoS (Denial of service) attacks cause denial of service to legitimate requests by exhausting the resources of network and services. To maximize the impact, the attack will be launched from
distributed sources, called distributed denial of service attack (DDoS).
In the majority of the cases, these attacks are launched by botnets. There are many challenges with the traditional detection methods. Most of them are signature based detection systems. Signature
for an attack cannot be developed on its own. Human intervention is needed for each attack to be modeled.
Moreover, it will take considerable time and effort to develop a signature and apply it, as a rule, to catch and stop a known attack. ML provides a way better solution to identify attacks, looking beyond
simple signatures, identifying similarities to what has happened before, and marking things that appear to be anomalies.

<br>
<br>
This repository contains ipython notebook and pickle files:<br>
DDoS_CS1_v2.ipynb : This file has the complete exploratory data analysis part<br>
DDoS.ipynb : data cleaning and processing and have tried various models and observe the performance of each model.<br>
ADB.pkl : AdaBoost pretrained model.<br>
Final.ipynb : This file is using the result of the best model and doing the predictions. You only have to pass the data and you will get the prediction.<br>
The other two files are the pickle file, are used to make the prdictions.

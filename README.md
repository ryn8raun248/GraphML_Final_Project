# Graph ML Final Project
### Author: Collin Quinn, Feb 2023

#### Introduction: 
Fraudulent activities severely impact many industries (i.e., e-commerce, social media, financial services), where users disguise as regular users to bypass anti-fraud systems to disperse disinformation or reap other end-user's privacy . In fact, American consumers reported losing more than $5.8 billion to frauds in 2021, up more than 70% over 2020. Many techniques have been used to detect fraudsters—rule-based filters, anomaly detection, and machine learning (ML) models, to name a few. However, these traditional/previous methods have not been sophisticated or flexible enough to detect the whole spectrum of suspicious online behaviors. For example, anyone who has browsed e-commerece websites such as Yelp or Amazon has likely come across a few product reviews that look a bit suspicious.

Now to introduce the concept of graph machine learning, which is the approach we are using in this report. In real-world data, entities often involve rich relationships with other entities. From these relationships, a graph structure can provide valuable information for anomaly detection. For example, in the following figure, users are connected via shared entities such as Wi-Fi IDs, physical locations, and phone numbers. Due to the large number of unique values of these entities, like phone numbers, it’s difficult to use them in the traditional feature-based models—for example, one-hot encoding all phone numbers wouldn’t be viable. But such relationships could help predict whether a user is a fraudster. If a user has shared several entities with a known fraudster, the user is more likely a fraudster.

![Screenshot](image001.jpg)

#### Abstract:
As discussed in the introduction, fraudelent activity for companies causes huge problems for both the companies and end users, costing billions of dollars in losses. Therefore, the ability to solve such an issue reaps huge rewards, especially since traditional methods of solving this issue aren't quite sophisticated enough. However, when reading the original [paper](https://arxiv.org/pdf/2008.08692.pdf) and [codebase](https://github.com/YingtongDou/CARE-GNN), they mentioned they used the Adam optimizer, but did not provide an explanation of why, and did not mention they tried any other alertnatives. Therefore, it was my goal to try different optimizers to see if I can improve upon their results. 

Hypothesis: 

#### Methods:
In this project, we are using graph machine learning to look at false reviews on a Yelp dataset, which includes hotel and restaurant reviews filtered (spam) and recommended (legitimate) by Yelp. 

#### Results:


#### Conclusion:







#### Sources:

Original Paper: [Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters](https://arxiv.org/pdf/2008.08692.pdf)

For orignal code, we used the follwing source. Minor tweaks were added to this code to change optimizers. 

@inproceedings{dou2020enhancing,
  title={Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters},
  author={Dou, Yingtong and Liu, Zhiwei and Sun, Li and Deng, Yutong and Peng, Hao and Yu, Philip S},
  booktitle={Proceedings of the 29th ACM International Conference on Information and Knowledge Management (CIKM'20)},
  year={2020}
}

[Codebase](https://github.com/YingtongDou/CARE-GNN)


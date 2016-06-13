---
layout: post
date:   2015-12-23 12:20:40 -0400
categories: paper

title: "How deceptive are deceptive visualizations?: An empirical analysis of common distortion techniques"
authors:
    - Anshul Vikram Pandey
    - Katharina Rall
    - Margaret L Satterthwaite
    - Oded Nov
    - Enrico Bertini
    
excerpt: In this paper, we present an empirical analysis of deceptive visualizations. We start with an in-depth analysis of what deception means in the context of data visualization, and categorize deceptive visualizations based on the type of deception they lead to. We identify popular distortion techniques and the type of visualizations those distortions can be applied to, and formalize why deception occurs with those distortions.

teaser: "deception.png"
conference: CHI 2015

paper: "http://nyuvis.github.io/infuse/paper.pdf"
source: "https://github.com/nyuvis/infuse-java/"

---
#Abstract
Predictive modeling techniques are increasingly being used by data scientists to understand the probability of predicted outcomes. However, for data that is high-dimensional, a critical step in predictive modeling is determining which features should be included in the models. Feature selection algorithms are often used to remove non-informative features from models. However, there are many different classes of feature selection algorithms. Deciding which one to use is problematic as the algorithmic output is often not amenable to user interpretation. This limits the ability for users to utilize their domain expertise during the modeling process. To improve on this limitation, we developed INFUSE, a novel visual analytics system designed to help analysts understand how predictive features are being ranked across feature selection algorithms, cross-validation folds, and classifiers. We demonstrate how our system can lead to important insights in a case study involving clinical researchers predicting patient outcomes from electronic medical records.
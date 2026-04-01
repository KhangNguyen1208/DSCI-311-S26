# DSCI-311-S26
WVU Symposium Poster Presentattion

Detecting Credit Card Fraud Using Statistical Distance Measures

Abstract:
Financial fraud costs the global economy billions of dollars annually, with credit card fraud representing a significant portion of these losses. Traditional detection systems rely on fixed methods that flag transactions exceeding predefined thresholds for specific features. The fundamental problem is that those approaches cannot learn evolving patterns of normal behavior. Here, we investigate whether modeling normal transaction behavior as a statistical distribution and measuring deviations using Wasserstein distance can provide a more adaptive fraud detection framework. We apply this approach to a dataset of 284,807 transactions from European cardholders in two days, including 492 confirmed fraud cases. We fit probability distributions to normal transaction patterns and compute the statistical distance of new transactions from this learned baseline. The proposed method includes using multiple testing to identify the most discriminative features and explores various distance thresholds to balance detection accuracy against false alarm rates. This offers potential advantages over fixed rules by continuously adapting to changing transaction patterns. We anticipate this work to be a starting point for applying statistical distance measures to other anomaly detection problems in cybersecurity and financial monitoring.

Data source:
Dal Pozzolo, A., Caelen, O., Le Borgne, Y.-A., Waterschoot, S., & Bontempi, G. (2014). Learned lessons in credit card fraud detection from a practitioner perspective.   Expert Systems with Applications, 41(10), 4915–4928.
Kaggle: https://www.kaggle.com/datasets/joebeachcapital/credit-card-fraud

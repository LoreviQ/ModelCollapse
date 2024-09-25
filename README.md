# Model Collapse in AI

This project explores the phenomenon of model collapse in AI, specifically how quickly AI models degrade when trained on data that they generate themselves. The primary focus is on sentiment analysis using Amazon reviews, where reviews are classified as either positive (4-5 stars) or negative (1-2 stars).

## Overview

The project investigates:

1. **Model Training**: Training a sentiment classification model on various dataset sizes.
2. **Total Collapse Scenario**: Simulating a scenario where the model generates its own training data, leading to performance degradation.
3. **Collapse Rates**: Analyzing how different rates of self-generated data affect model performance.
4. **Lower Collapse Rates**: Examining the effects of small proportions of AI-generated data on model accuracy.

## Technologies Used

- Python

## Dataset

The dataset used consists of Amazon reviews, focusing on sentiment classification based on star ratings.

[Dataset Link](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews?phase=FinishSSORegistration&returnUrl=%2Fdatasets%2Fbittlingmayer%2Famazonreviews%2Fversions%2F7%3Fresource%3Ddownload&SSORegistrationToken=CfDJ8F_DuqmsDTJPtLCFEKPd8dwctlS14SElqWAUDw0vb1k4GauGR9QwQu7OH82fntp2Kuwyn_Vc-yqzPf8AWK3ywkAQW49kHU1_e_vu95gjbs-Qs-Njnn8iUZFOFq4j1vXyfim4waahOw4vt8BIldhhcgnYtv2wh57ZK5AIb2cZC10jjOA2631Kh0pRgoqMKPELd_MBM_1ww95EMz21sr9OlOZ80cXNyGB80c0c1nQLTPqRBtO6uqlgnIfmq4MZPhLIfabttGJGo-4BCUbMXe94hDVwHsCxzplqaIupEypcjVmSrDR4EI2mIJRcShVNMj8RU63QlGaZ_s7IpnThOGAX_k_-Hw&DisplayName=Lorevi+Q)

The dataset is not stored on the github due to filesize.

## Results

The findings highlight the importance of curating high-quality, human-verified data for training AI models. The project demonstrates that even small amounts of AI-generated data can negatively impact model performance.

## Installation

To run the code, clone the repository and install the necessary dependencies

To see my results:
```bash
python plot.py 
```
To make your own investigate main.py. 


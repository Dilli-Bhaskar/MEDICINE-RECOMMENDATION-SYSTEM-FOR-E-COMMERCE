# MEDICINE-RECOMMENDATION-SYSTEM-FOR-E-COMMERCE

## Abstract

The "Enhancing E-Commerce: A Personalized Medicine Recommendation System for Optimal Healthcare Choices" project introduces a cutting-edge solution tailored to the realm of online pharmaceutical shopping. Leveraging advanced machine learning techniques, this system revolutionizes the way users discover and select medications. By analyzing individual medical histories, preferences, and requirements, the system offers personalized medicine recommendations, enabling users to make informed and effective choices. The integration of sophisticated algorithms ensures accuracy in suggesting medicines that align with users' needs and health profiles. This innovation aims to enhance user satisfaction and streamline the decision-making process within the E-Commerce pharmaceutical domain. In a rapidly evolving digital landscape, this project bridges the gap between consumers and a diverse range of medication options, prioritizing safety, efficacy, and convenience. As E-Commerce continues to reshape industries, this system stands as a pivotal advancement in optimizing healthcare choices for a diverse online audience.



## Dataset
We worked on a sample EHR dataset created only for testing purposes and it is obtained from Kaggle, the dataset contained Drug Name, Disease, Description, Manufacturer, NSE symbol, and its Rating. The dataset is visualized using matplotlib to check the feasibility of data values. A total of 22481 testing records were visualized. The figure visualized below shows the different manufacturers, NSE symbol, ratings, and industry type.


<em>CLAHE Algorithm:</em>
<p align="center" float="middle">
<img src="imgs/pie.png?raw=true" width="61.5%" />
</p>

## Proposed Methodology
<p align="center" float="middle">
<img src="imgs/block_dia.png?raw=true" width="61.5%" />
</p>

## Training Results 

| Model                      | Accuracy               | F1 Score               |
|----------------------------|------------------------|------------------------|
| Multinomial Naive Bayes    | 0.963302752293578     | 0.966360856269113     |
| Logistic Regression        | 0.963302752293578     | 0.963302752293578     |
| K - Nearest Neighbors      | 0.1559633027522936    | 0.20305810397553517   |
| Linear SVC                 | 0.963302752293578     | 0.963302752293578     |



## Conclusion
In the study presented an in-depth analysis of various machine learning models for a medicine recommendation system. Notably, the Multinomial Naive Bayes and Logistic Regression models consistently demonstrated impressive accuracy and F1 scores, showcasing their potential for accurate medication predictions. While the Linear SVC model performed similarly, the K-Nearest Neighbors model exhibited limitations in accuracy and effectiveness. These findings emphasize the significance of robust model selection in enhancing medical recommendations. Moving forward, further refinements and optimizations are needed to address the challenges posed by the K-Nearest Neighbors approach, with the ultimate aim of providing an efficient and reliable solution for personalized medicine suggestions.

## Citation
```

@inproceedings{komal_kumar_drug_2021,
	title = {A Drug Recommendation System for Multi-disease in Health Care Using Machine Learning},
	doi = {10.1007/978-981-15-5341-7_1},
	booktitle = {Advances in Communication and Computational Technology},
	publisher = {Springer Nature},
	author = {Komal Kumar, N. and Vigneswari, D.},
	date = {2021},
	keywords = {Data mining, Drug, Health care, Machine learning, Prescription},
}

```


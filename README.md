# MEDICINE-RECOMMENDATION-SYSTEM-FOR-E-COMMERCE

## Abstract

The "Enhancing E-Commerce: A Personalized Medicine Recommendation System for Optimal Healthcare Choices" project introduces a cutting-edge solution tailored to the realm of online pharmaceutical shopping. Leveraging advanced machine learning techniques, this system revolutionizes the way users discover and select medications. By analyzing individual medical histories, preferences, and requirements, the system offers personalized medicine recommendations, enabling users to make informed and effective choices. The integration of sophisticated algorithms ensures accuracy in suggesting medicines that align with users' needs and health profiles. This innovation aims to enhance user satisfaction and streamline the decision-making process within the E-Commerce pharmaceutical domain. In a rapidly evolving digital landscape, this project bridges the gap between consumers and a diverse range of medication options, prioritizing safety, efficacy, and convenience. As E-Commerce continues to reshape industries, this system stands as a pivotal advancement in optimizing healthcare choices for a diverse online audience.

<em>CLAHE Algorithm:</em>
<p align="center" float="middle">
<img src="pics/clache.png?raw=true" width="61.5%" />
</p>


## Installation
1. Set up Python environment with Conda:
```
conda create -n myenv python=3.10
conda activate particlesfm 
```
2. Clone the Repo:
```
git clone https://github.com/aathanush/PondFishDet
```
3.  Install Dependencies:
```
cd PondFishDet
pip pip install -r requirements.txt
```

## Proposed Methodology
<p align="center" float="middle">
<img src="pics/algorithm.PNG?raw=true" width="61.5%" />
</p>

## Training Results 

| Model                      | Accuracy               | F1 Score               |
|----------------------------|------------------------|------------------------|
| Multinomial Naive Bayes    | 0.963302752293578     | 0.966360856269113     |
| Logistic Regression        | 0.963302752293578     | 0.963302752293578     |
| K - Nearest Neighbors      | 0.1559633027522936    | 0.20305810397553517   |
| Linear SVC                 | 0.963302752293578     | 0.963302752293578     |



<p align="center">
  <img src="pics/F1_curve.png?raw=true" width="48%" alt="F1 Image" />
  <img src="pics/PR_curve.png?raw=true" width="48%" alt="PR Image"/>
</p>


## Test Results 
<p align="left" float="middle">
<img src="pics/f (1).jpeg?raw=true" width="25.5%" alt="1"/>
<img src="pics/f (2).jpeg?raw=true" height="32.5%" width="25.5%" alt="2"/>
</p>

<p align="left" float="middle">
<img src="pics/f (3).jpeg?raw=true" width="25.5%" alt="1" />
<img src="pics/f (4).jpeg?raw=true" height="32.5%" width="25.5%" alt="2"/>
</p>

<p align="left" float="middle">
<img src="pics/f (5).jpeg?raw=true" width="25.5%" alt="1"/> 
<img src="pics/f (6).jpeg?raw=true" height="32.5%" width="25.5%" alt="2e" /> 
</p> 

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


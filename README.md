
This repository contains Python codes for phishing detection using ML models. A sophisticated framework based on Stacked Generalization has been developed to obtain reliable performance over diverse datasets. The 4 datasets utilized in this study are also provided here. 

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/pypi/v/scikit-learn?label=scikit-learn&color=blue)

![XGBoost](https://img.shields.io/pypi/v/xgboost?label=XGBoost&color=orange)
![LightGBM](https://img.shields.io/pypi/v/lightgbm?label=LightGBM&color=green)


# Paper Title

"A Sophisticated Framework for the Accurate Detection of Phishing Websites"

DOI: https://doi.org/10.48550/arXiv.2403.09735


The paper is currently under review.


## Synopsis

Phishing is an increasingly sophisticated form of cyberattack. Designing an ML framework that can provide generalized performance over a wide variety of datasets is a challenge. 

In this project, a stacking ensemble classifier is constructed which can harness the capabilities of a variety of different ML algorithms and provide generalized performance. A greedy-based selection mechanism is employed to obtain the optimal combination of weak learners while the recursive feature elimination algorithm is employed to extract the most representative features for individual classifiers. Finally, a neural network, capable of learning complex non-linear relationships in the data, was utilized as the meta-learner. 

The performance of the developed system was tested on 4 different phishing datasets. The proposed algorithm outperformed the other existing phishing detection models obtaining accuracy of 97.49%, 98.23%, 97.48%, and 98.20% on the four datasets.

### Performance

![App Screenshot](https://github.com/newaz-aa/Phishing/blob/main/Figures/fig_3.jpg)


### BibTeX Citation
```bibtex
@article{newaz2024sophisticated,
  title={A Sophisticated Framework for the Accurate Detection of Phishing Websites},
  author={Newaz, Asif and Haq, Farhan Shahriyar and Ahmed, Nadim},
  journal={arXiv preprint arXiv:2403.09735},
  year={2024}
}
```

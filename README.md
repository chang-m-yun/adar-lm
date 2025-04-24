# Predicting post-transcriptional ADAR activity using machine learning
**Authors**: Chang M. Yun<sup>1</sup>, Xiaowei Zhang<sup>2</sup> \
<sup>1</sup>Department of Chemical Engineering, Stanford University, <sup>2</sup>Department of Bioengineering, Stanford University

![Figure 1: Schematic of adenosine-to-inosine (A-to-I) modification by ADARs](/docs/figure_2.png)

**Figure 1: Schematic of adenosine-to-inosine (A-to-I) modification by ADARs<sup>1</sup>.** \
<sup>1</sup>Nakahama, T. & Kawahara, Y. Adenosine-to-inosine RNA editing in the immune system: friend or foe? Cell. Mol. Life Sci. 77, 2931–2948 (2020).

## Model 1. Feature engineering and ensemble tree based model:
* Code for merging B2 and mNG dataset: data_merge.ipynb
* Code for feature engineering: features.ipynb
* Code for training with RandomForestRegressor: RandomForrest.ipynb
* Code for training with XGBoost Regressor: XGBoost.ipynb

## Model 2. Transformer-based language model:
* Code for data processing: data_preprocessing.ipynb
* Code for transformer model: Transformer.ipynb

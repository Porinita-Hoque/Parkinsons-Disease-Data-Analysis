# <p align='center'>Parkinsons' Disease : Data Analysis</p>

<p align='justify'>The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages ranging from 33 to 87, at the Department of Neurology in Cerrahpaşa Faculty of Medicine, Istanbul University. The control group comprises 64 healthy individuals (23 men and 41 women) with ages between 41 and 82. During the data collection process, the microphone is set to 44.1 KHz, and following the physician's examination, the sustained phonation of the vowel /a/ was collected from each subject with three repetitions.</p>

### Attribute Information
<p align='justify'>Various speech signal processing algorithms including Time-Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features, and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.</p>

### Dataset Overview
- Data Set Characteristics: Multivariate
- Attribute Characteristics: Integer, Real
- Number of Attributes: 754
- Associated Tasks: Classification
- Missing Values: N/A

### Columns Description
- Baseline Features: Columns 3 to 23
- Intensity Parameters: Columns 24 to 26
- Formant Frequencies: Columns 27 to 30
- Bandwidth Parameters: Columns 31 to 34
- Vocal Fold: Columns 35 to 56
- MFCC: Columns 57 to 140
- Wavelet Features: Columns 141 to 322
- TQWT Features: Columns 323 to 754
- Class: Column 755

### Classification Models Used
- K Nearest Neighbor 
- Logistic Regression 
- Support Vector Machine
- Random Forest Classifier 
- Hist Gradient Boosting Classifier
- Light Gradient Boosting Machine

### Results Overview
| Classifier | Accuracy | Precision | Recall | F1-Score |
|:----------:|:-------:|:---------:|:------:|:-------:|
| KNN        | 83.5526 |  83.9635  | 83.5526| 81.7208 |
| SVM        | 82.8947 |  82.2086  | 82.8947| 81.8672 |
| RFC        | 83.5526 |  85.4221  | 83.5526| 81.1188 |
| LR         | 82.8947 |  82.8548  | 82.8947| 81.1308 |
| HGBC       |   87.5  |  88.6068  |  87.5  | 86.3099 |
| Light-GBM  | 86.8421 |  88.8509  | 86.8421| 85.2636 |

<br>

      Also, designed a Neural Network Model that yielded a Validation Accuracy of 86.78 % 

<hr>
<p align="center">Dataset (Kaggle) Link: https://www.kaggle.com/datasets/porinitahoque/parkinsons-disease-pd-data-analysis</p>
<hr>


<br>
<br>

#### <p align="center"> Copyright © Porinita Hoque (ID : 1711204042) </p>

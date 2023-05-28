# Melanoma_Detection
We present an improved automated system for diagnosing skin cancers (melanoma) using deep learning techniques. 

Abstract:  we present an improved automated system for diagnosing skin cancers (melanoma) using deep learning techniques. We utilize a pre-trained deep CNN model (MobileNet) to extract visual features from dermoscopic images. Our method incorporates boundary localization and cropping to generate more relevant features. Skin lesion classification is performed using a set of classifiers. Validation on the PH2 dataset demonstrates promising performance, outperforming state-of-the-art methods.

Introduction

Melanoma is the most deadly form of skin cancer and has risen rapidly across the globe. Hence, early diagnosis of melanoma is of great significance for timely treatment and healthy living. This disease unexpectedly causes signs on normal skin with a dark mole and an irregular border. Figure  shows sample dermoscopic images from melanoma and non-melanoma categories.

![](figure/sample.jpg)

Proposed Methodology

The structure of the proposed method is depicted in Fig. 2. Our proposed method consists of three major phases: (1) boundary localization, (2) feature extraction, and (3) classification.

![](figure/Proposed_model.png)

Results
To confirm the feasibility of the proposed method, we thoroughly assessed its efficiency on PH2 dataset by employing boundary localization, cropping, and image normalization methods. The performance of MobileNet has been tested with SVM and LDA classifiers separately and the results with and without preprocessing are tabulated in Table 1.
![](figure/results.jpg)

This work is published in 19th International Conference on Artificial Intelligence in Medicine (AIME), Porto, Portugal, Springer,
2021. Link: (https://link.springer.com/chapter/10.1007/978-3-030-77211-6_39)  


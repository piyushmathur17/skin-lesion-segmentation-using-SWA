# skin-lesion-segmentation-using-UNET_SWA
This is code implementation for skin lesion segmentation for detecting melanoma and non melanoma cases. 
#requisites: tensorflow 1.x, keras with tensorflow backend, cv2, numpy, matplotlib.

code based on:

TY  - JOUR
AU  - Tang, Peng
AU  - Liang, Qiaokang
AU  - Xintong, Yan
AU  - Xiang, Shao
AU  - Sun, Wei
AU  - Zhang, Dan
AU  - Coppola, Gianmarc
PY  - 2019/07/01
SP  - 
N2  - Abstract
Background and objective
Efficient segmentation of skin lesion in dermoscopy images can improve the classification accuracy of skin diseases, which provides a powerful approach for the dermatologists in examining pigmented skin lesions. However, the segmentation is challenging due to the low contrast of skin lesions from a captured image, fuzzy and indistinct lesion boundaries, huge variety of interclass variation of melanomas, the existence of artifacts, etc. In this work, an efficient and accurate melanoma region segmentation method is proposed for computer-aided diagnostic systems.

Method
A skin lesion segmentation (SLS) method based on the separable-Unet with stochastic weight averaging is proposed in this work. Specifically, the proposed Separable-Unet framework takes advantage of the separable convolutional block and U-Net architectures, which can extremely capture the context feature channel correlation and higher semantic feature information to enhance the pixel-level discriminative representation capability of fully convolutional networks (FCN). Further, considering that the over-fitting is a local optimum (or sub-optimum) problem, a scheme based on stochastic weight averaging is introduced, which can obtain much broader optimum and better generalization.

Results
The proposed method is evaluated in three publicly available datasets. The experimental results showed that the proposed approach segmented the skin lesions with an average Dice coefficient of 93.03% and Jaccard index of 89.25% for the International Skin Imaging Collaboration (ISIC) 2016 Skin Lesion Challenge (SLC) dataset, 86.93% and 79.26% for the ISIC 2017 SLC, and 94.13% and 89.40% for the PH2 dataset, respectively. The proposed approach is compared with other state-of-the-art methods, and the results demonstrate that the proposed approach outperforms them for SLS on both melanoma and non-melanoma cases. Segmentation of a potential lesion with the proposed approach in a dermoscopy image requires less than 0.05 s of processing time, which is roughly 30 times faster than the second best method (regarding the value of Jaccard index) for the ISIC 2017 dataset with the same hardware configuration.

Conclusions
We concluded that using the separable convolutional block and U-Net architectures with stochastic weight averaging strategy could enable to obtain better pixel-level discriminative representation capability. Moreover, the considerably decreased computation time suggests that the proposed approach has potential for practical computer-aided diagnose systems, besides provides a segmentation for the specific analysis with improved segmentation performance.

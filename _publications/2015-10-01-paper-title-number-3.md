---
title: "Semantic segmentation of low magnification effusion cytology images: A semi-supervised approach"
collection: publications
permalink: #/publication/2015-10-01-paper-title-number-3
excerpt: #'This paper is about the number 3. The number 4 is left for future work.'
date: 2022-11-01
venue: 'Computers in Biology and Medicine'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0010482522008873'
citation: 'Shajahan Aboobacker, Deepu Vijayasenan, Sumam David S., Pooja K. Suresh, Saraswathy Sreeram, Semantic segmentation of low magnification effusion cytology images: A semi-supervised approach, Computers in Biology and Medicine, Volume 150, 2022, 106179, ISSN 0010-4825, https://doi.org/10.1016/j.compbiomed.2022.106179.'
---
Cytopathologists examine microscopic images obtained at various magnifications to identify malignancy in effusions. They locate the malignant cell clusters at a low magnification and then zoom in to investigate cell-level features at a high magnification. This study predicts the malignancy at low magnification levels such as 4X and 10X in effusion cytology images to reduce scanning time. However, the most challenging problem is annotating the low magnification images, particularly the 4X images. This paper extends two semi-supervised learning (SSL) models, MixMatch and FixMatch, for semantic segmentation. The original FixMatch and MixMatch algorithms are designed for classification tasks. While performing image augmentation, the generated pseudo labels are spatially altered. We introduce reverse augmentation to compensate for the effect of the spatial alterations. The extended models are trained using labelled 10X and unlabelled 4X images. The average F-score of benign and malignant pixels on the predictions of 4X images is improved approximately by 9% for both Extended MixMatch and Extended FixMatch respectively compared with the baseline model. In the Extended MixMatch, 62% sub-regions of low magnification images are eliminated from scanning at a higher magnification, thereby saving scanning time.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0010482522008873)

Recommended citation: Shajahan Aboobacker, Deepu Vijayasenan, Sumam David S., Pooja K. Suresh, Saraswathy Sreeram,
Semantic segmentation of low magnification effusion cytology images: A semi-supervised approach,
Computers in Biology and Medicine,
Volume 150,
2022,
106179,
ISSN 0010-4825,
https://doi.org/10.1016/j.compbiomed.2022.106179.

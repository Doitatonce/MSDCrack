# MSDCrack: Dual-encoder pavement concrete crack segmentation network based on multi-stage supervision

Jing Wang, Haizhou Yao, Jinbin Hu, Yafei Ma, Jin Wang

## Overview

# Abstract

Cracks are a prevalent disease on pavement concrete materials. Timely assessment and repair of concrete materials can significantly extend their service life. However, accurate segmentation has always been difficult due to their random distribution, tortuous geometry, and varying degrees of severity. To address these challenges, a Multi-stage Supervised Dual-encoder network for Crack segmentation on pavement concrete (MSDCrack) was proposed based on an encoder–decoder architecture. In this network, attention collapse is mitigated through the addition of self-attention pooling. Furthermore, a feature fusion module was designed to address differences in encoding characteristics across branches. Additionally, a multi-stage supervision strategy was implemented to enhance the network’s predictive performance. Comparative experiments demonstrated that MSDCrack achieved the highest Dice coefficient, F1-score, and IoU on multiple datasets, with F1-score and IoU surpassing other state-of-the-art segmentation networks by over 3.1% and 2.89%, respectively, in generalization performance.
 
# Overall network structure of MSDCrack:

<img width="784" alt="MSDCrack" src="https://github.com/Doitatonce/MSDCrack/blob/main/img/overview%20network.jpg">

## Data availability

The details are shown in our [paper](https://doi.org/10.1016/j.autcon.2024.105884). If you need code for academic research, please contact 2462937589@qq.com, znwj_cs@csust.edu.cn.

DeepCrack dataset is available at https://github.com/yhlleo/DeepCrack.

Crack500 dataset is available at https://github.com/fyangneil/pavement-crack-detection.

FIND dataset is available at https://zenodo.org/records/6383044.

## Reference
If you find MSDCrack useful in your research, please consider giving a star ⭐ and citing using the following BibTeX:
```
@article{WANG2025105884,
title = {Dual-encoder network for pavement concrete crack segmentation with multi-stage supervision},
journal = {Automation in Construction},
volume = {169},
pages = {105884},
year = {2025},
issn = {0926-5805},
doi = {https://doi.org/10.1016/j.autcon.2024.105884},
url = {https://www.sciencedirect.com/science/article/pii/S0926580524006204},
author = {Jing Wang and Haizhou Yao and Jinbin Hu and Yafei Ma and Jin Wang}
}
```

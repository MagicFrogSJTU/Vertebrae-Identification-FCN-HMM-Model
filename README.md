# Vertebrae-Identification-FCN-HMM-Model
## Title 
Vertebrae Identification and Localization Utilizing Fully Convolutional Networks and a Hidden Markov Model  

## Publisher
Published on IEEE transaction on medical imaging: https://ieeexplore.ieee.org/abstract/document/8756197

## Abstract  
Automated identification and localization of vertebrae in spinal computed tomography (CT) imaging is a complicated hybrid task. This task requires detecting and indexing a long sequence in a three-dimensional (3-D) image, and both image feature extraction and sequence modeling are needed to address the problem. In this paper, the powerful fully convolutional neural network (FCN) technique performs both of these tasks simultaneously because FCNs directly encode and decode the spatial interdependence of different components in images. The key module of our proposed framework is a 3-D FCN trained in an end-to-end manner at the spine level to capture the long-range contextual information in CT volumes. The large increase in the calculation due to the full-size image inputs is alleviated by the scale-down of the inputs and the use of an auxiliary FCN to compensate for the loss of details. The composite network pipeline design enables the integration of local image details and global image patterns. Furthermore, explicit spatial and sequential constraints are imposed by the hidden Markov model (HMM) for a higher robustness and a clearer interpretation of network outputs. The proposed framework is quantitatively evaluated on the public dataset from the MICCAI 2014 Computational Challenge on Vertebrae Localization and Identification and demonstrates an identification rate (within 20 mm) of 94.67%, a mean identification rate of 87.97% and a mean error distance of 2.56 mm on the test set, thus achieving the highest performance reported on this dataset.

## PDF of the artical   
can be downloaded at:   [ResearchGate](https://www.researchgate.net/profile/Kang_Li4/publication/334373484_Vertebrae_Identification_and_Localization_Utilizing_Fully_Convolutional_Networks_and_a_Hidden_Markov_Model/links/5d2a29b4a6fdcc2462ddb758/Vertebrae-Identification-and-Localization-Utilizing-Fully-Convolutional-Networks-and-a-Hidden-Markov-Model.pdf)

## Code   
Under preparations for open-access for accademic researches.

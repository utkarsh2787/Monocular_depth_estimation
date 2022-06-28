# Monocular Depth Estimation 

The problem of Monocular Depth Estimation has widespread appliactions in Computer Vision, whether it is Autonoumous Driving, Robotic Surgeries etc. This repository is a collection of an ONGOING RESEARCH aimed at designing new, lightweight and accurate Supervised Learning methods for Monocular Depth Estimation. We have choosen the NYU - depth V2 dataset that has 1449 single still images, collection of indoor and outdoor scenes. 

This Repository currently has 4 previous state-of-the-art models that have been analysed and implemented by us in Google Colaboratory.

**1. Lightweight Monocular Depth Estimation on Edge Devices : Siping Liu, Laurence T. Yang, Xiaohan Tu, Renfa Li and Cheng Xu** [Incomplete]

    This article proposes and Encoder-Decoder based approach and aim at further optimizing the model by using Reinforcment Learning to Prune the model, and finally GPU       overhead Scheduling to reduce GPU latency. The basic model backbone is a MobileNetV2 based encoder and a novice UpSampConv Layer that make up the Deocder. 
    
**2. Monocular Depth Estimation Using Multi Scale Neural Network And Feature Fusion : Abhinav Sagar**

**3. Monocular Depth Estimation with Adaptive Geometric Attention : Taher Naderi, Amir Sadovnik, Jason Haywardy, Hairong Qi**

    This research article is based on the development of a novice Adaptive Geometric Attention Module, based on the concept of Attention, borrowed from the field of         Natural Language Processing. This model is based on an Encoder-Decoder based approach, where the ResNeXt 101 is an Encoder and a custom Decoder based on an               organisation of AGA, DRB (Dilated Residual Blocks) and the ASPP (Atrous Spatial Pyramid Pooling).
    
**4. Decomposition and replacement: Spatial knowledge distillation for monocular depth estimation : Minsoo Song, Wonjun Kim** [Incomplete]

    This model approach is based on the concept of Knowledge Distillation. For the teacher network, ResNeXt 101 (32 X 8d) as an encoder and classic UNET Decoder was used     and trained upon the Rooted Scale Invariant Error. For the Student network, MobileNetV2 was used as an encoder and the same pre trained UNET decoder was used with       special modules such as Replace Block and Laplacian Pyramid based decomposition loss to further improve the Distillation process.     

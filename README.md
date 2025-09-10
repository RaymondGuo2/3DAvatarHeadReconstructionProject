# Repository for Raymond Guo's Individual Project

This is the official repository for Raymond Guo's MSc Computing Individual Project titled "Transforming 2D Images into 3D Child Avatars - Enhancing Self-Attachment Technique with 3D Reconstruction".

This repository represents the collection of all the individual experiments and implementations that were carried out during the project, and is thus structured as the main module to multiple git submodules. More context to the submodules can be discovered by entering the respective repositories, and referencing with the individual project report's methodology and implementation sections. 

To see the project report, you can [click here for the PDF](FinalReport.pdf)

### Overall Reconstruction Demo

Below is a demo of the reconstruction using the [FFHQ-UV-RGB](https://github.com/RaymondGuo2/FFHQ-UV-RGB/tree/b0627f10423925203ed3606506bd3b8e497a7cc1) method.

![Demo GIF](demos/Project%20Demo.gif)

### Expression Change Application

For the expression change application of the 3D head model, you can view the [Unity Frontend](https://github.com/RaymondGuo2/ExpressionChangeUnity/tree/03567a24e11c4982f0a0273b0b0fded5ef72e97d) and the [Flask Backend](https://github.com/RaymondGuo2/FacialExpressionApplication/tree/ac4b5431324366bdb573deb1002fa01e6e3eb8e7) code, with the demo below:

![Demo GIF](demos/Expression%20Change%20Demo.gif)

### Other Approaches

A variety of other deep-learning and computer vision reconstruction approaches were adopted in this project, which can be found by exploring the below repositories:

- [3D-VAE-GAN](https://github.com/RaymondGuo2/Avatar-3D-VAE-GAN/tree/7bb1f266f1b5d1dcbdc7d13b7d704c4e07d9f71a) inspired by Wu et al. (2016) 3D-VAE-GAN and [Bryon Kucharski's](https://github.com/bryonkucharski/Multiview-3D-VAE-GAN) implementation
- [Cascaded Refinement Network for Head Model Completion](https://github.com/RaymondGuo2/Head_Model_PCN/tree/dc5c3d6b9aa5a0591ef7554afd41ba56ecc99f2e) inspired by the Cascaded Refinement Network for PCN - Wang et al. (2021)
- [FLAME Head Model Reproduction](https://github.com/RaymondGuo2/TF_FLAME_Reproduction/tree/dc213a2a7584b037287627502477a3b2393d21cd) - Li et al. (2017)

### Acknowledgements

Many thanks are given to Professor Abbas Edalat and Xinyan Ye for their help and guidance during this project period.

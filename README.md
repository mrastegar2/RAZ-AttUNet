# RAZ-AttUNet
This repository contains the official implementation of the paper: 
Attention-driven framework to segment renal ablation zone in post-treatment CT images: A step towards ablation margin evaluation
> by Maryam Rastegarpoor, Derek W. Cool, and Aaron Fenster
> 
> Submitted to: the Journal of Medical Imaging , 2025
>
> ---

## Overview

We train an advanced deep-learning method using the Attention-based U-Net architecture to segment the Renal Ablation Zone in CT images.  

The pipeline includes:

- Preprocessing by normalization, converting to 2D, and histogram equalization
- Training the 2D Attention-based U-Net model
- Model Evaluations by nested 5-fold cross validation
- Post Processing using Connected Component and Averaging
- Evaluation segmentation metrics including region-based and distance-based metrics



# Deep Homography Estimation-based Heterogeneous Decoupled Channel Precoding Mapping
## Overview
This is a repository for Deep Homography Estimation-based Heterogeneous Decoupled Channel Precoding Mapping, a submitted manuscript to IEEE Wireless Communications Letters. 

#### A. Abstract
The fully decoupled radio access network (FD-RAN) is a potential 6G RAN architecture that is flexible and efficient. However, its decoupling feature presents significant challenges for real-time downlink (DL) channel precoding. In this work, with the insight that mapping within heterogeneous uplink (UL) and DL channels of stationary decoupled UL and DL base stations (BSs) to user equipment (UE) is similar to the homography of static stereo projections of an object, a deep homography estimation-based DL precoding mapping that inherently integrates precoding and localization for heterogenous decoupled channels is derived. The proposed approach demonstrates superiority within a typical FD-RAN scenario with two challenging heterogeneous decoupled channel setups and various training overheads.

#### B. Proposed Modules
Once the manuscript is ready for early access, more details about this work will be provided.

## Requirements
No special requirements
- Python >= 3.7
- For the pytorch version, we used 1.10.2+cu102, yet it is not mandatory.


## Project Details
#### A. Experiment Setup

The efficacy of the proposed progressive-learning-based framework is substantiated through comprehensive experimentation encompassing two UE mobility and CSI processing delay settings under two PN contamination levels. The dataset generation setup is presented in the following table.
<p align="center">
  <img src = "https://github.com/TeleRagingFires/Progressive/blob/8672a90f3384fa7373b9f4b89a13dd5506888e7d/Data.jpg" width="500">
</p>

## Results and Reproduction

#### Evaluation Results
The Table summarizes the overall performance with common prediction quality matrices composing the mean square error (MSE), the mean absolute error (MAE), the structure similarity (SSIM), and the cosine similarity rho.

To further verify the progressive learning-based framework and its impact on the system, a singular value decomposition (SVD) baseband precoding is conducted to simulate the average spectral efficiency R in a given receiver noise power.
![alt text](https://github.com/TeleRagingFires/Progressive/blob/139c7807a5f770da2aab967a940c2844bb750d52/Result.jpg)

## Acknowledgment
Once the manuscript is ready for early access, more details about this work will be provided.

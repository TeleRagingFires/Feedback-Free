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
The proposed homography precoding mapping is evaluated in a challenging typical FD-RAN scenario from the DeepMIMO. The FD-RAN scenario within the UE sampling area with its propagation attributes is illustrated in the following figure.
<p align="center">
  <img src = "https://github.com/TeleRagingFires/Feedback-Free/blob/f0167fb652757af60bcd81380c503ca7125a2608/FD_RAN_Scenario.jpg" width="700">
</p>

Details of the experimental configurations are enumerated in the following table.
<p align="center">
  <img src = "https://github.com/TeleRagingFires/Feedback-Free/blob/d415973cc5824f03f1984d6896193e41a295932f/Data.jpg" width="500">
</p>

## Results and Reproduction

#### Evaluation Results
#### A. UE Localization
Table II summarizes the DL-BS relative UE localization performance from homogeneous UL-BS I and II.
![alt text](https://github.com/TeleRagingFires/Progressive/blob/139c7807a5f770da2aab967a940c2844bb750d52/Result.jpg)

## Acknowledgment
Once the manuscript is ready for early access, more details about this work will be provided.

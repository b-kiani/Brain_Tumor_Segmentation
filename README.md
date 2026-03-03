3D GAN for Brain Tumor Segmentation

Implementation of the experiments from “Segmentation of Brain Tumor Using a 3D Generative Adversarial Network”
Diagnostics, 2023, 13(21), 3344 — doi:10.3390/diagnostics13213344

📌 Overview

This repository contains the code and experimental setup used to reproduce the results from the MDPI Diagnostics paper titled “Segmentation of Brain Tumor Using a 3D Generative Adversarial Network” by Behnam Kiani Kalejahi et al.

The work proposes a 3D Generative Adversarial Network (GAN) architecture designed for automated segmentation of brain tumors in volumetric MRI scans. The GAN model consists of:

A generator that performs dense 3D segmentation of MRI volumes.

A discriminator that enforces realistic boundary and region segmentation through adversarial training.

The model is trained and evaluated on the BraTS 2021 dataset of 3D MRI scans, comparing segmentation performance across different experimental setups.

# DLL16: MONAI Core on SageMaker

## Description

Amazon SageMaker is an end-to-end data science platform to build, train, and run machine learning models. MONAI Core is a PyTorch-based, open-source library for deep learning training of medical imaging models.
In this workshop, we will provide a brief introduction to MONAI and its various components. Researchers and data scientists will learn how MONAI Core running on SageMaker lets them explore more deep neural network architectures, more hyperparameters, and more hypotheses compared to static on-premises infrastructure for medical imaging workloads. We will also feature MONAI Auto3DSeg—a low-code tool that empowers developers to address the complex task of 3D medical image segmentation. Notably, a team of NVIDIA researchers utilized Auto3DSeg to achieve success in several MICCAI 2023 challenges. Participants will engage in hands-on experience by running two MONAI labs within their SageMaker environment as part of their own AWS accounts, which will be provided as part of the course.

## Presenters
* Alex Lemm (Tech BD Medical Imaging Innovation) - [Alex's LinkedIn profile](https://www.linkedin.com/in/alexanderlemm/)
* Andrew Crabb (Sr. Solutions Architect) - [Andrew's LinkedIn profile](https://www.linkedin.com/in/andrewcrabb/)

## Session Date & Time

Wed, 29 Nov 2023, 1:00pm-2:00pm

## Labs

We will run through the following two labs that are part of [the official MONAI Bootcamp GitHub repository](https://github.com/Project-MONAI/monai-bootcamp):

* MONAI End-to-End Workflow - Solution
* Auto3DSeg Hello World

We already presented all labs this year during multi-hour workshops at MIDL 2023 and MICCAI 2023. Based on the 1h time constraint at RSNA 2023, we will focus on two of the nine labs.
During the RSNA 2023 workshop, participants will clone the MONAI Bootcamp repo (`git clone https://github.com/Project-MONAI/monai-bootcamp.git`) to their own SageMaker environments.

# Agenda

* Introduction to MONAI Core and Amazon SageMaker 
* Lab 1: MONAI End-to-End Workflow - Solution
* Demo: Singe node training vs training on (multiple) training clusters
* Introduction to MONAI Auto3DSeg
* Lab 2: Auto3DSeg Hello World
* Wrap-up

## Prerequisites

Participants should be familiar with the following:

* Reading and executing Python code
* Navigating a JupyterLab-based IDE 
* Understanding of the overall data science process 
* Understanding of the basic PyTorch/DL flow 

# Additional resources

If you like to learn more on how to use MONAI and/or FLARE in combination with various AWS services, please have a look at the following resource list that is part of the official MONAI Bootcamp repository: [MONAI on AWS resources](https://github.com/Project-MONAI/monai-bootcamp/blob/main/aws_resources.md)

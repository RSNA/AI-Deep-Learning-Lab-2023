# Building a Segmentation Model: DICOM to Deployment
RSNA Deep Learning Lab 2023
Wednesday November 29, 2:30–3:30 p.m.

Presenters:
* Evan Calabrese
* Jikai Zhang
* Sarthak Pati
* Ujjwal Baid

License: CC-BY

<span style="color:red">**Please bring a laptop computer with internet access and a modern browser (Chrome, Edge, Firefox) to the live session. You do not need a particularly fast CPU or a discrete GPU. An external mouse is recommended by not required.**</span>

<span style="color:yellow">**To prepare for the course, it is recommended that you familiarize yourself with the code, however you do not need to install anything or run any code to participate in the live session.**</span>
# Project Overview
The goal of this project is to start with an idea for a new medical image segmentation task and end with a fully trained, high performing, and easily deployable segmentation model.

## Coming up with a Project Idea
Hopefully you already have an idea for a medical image segmentation task in mind. If not, consider the following:

Is your idea **SMART**?
* Is it **S**PECIFIC? Vague ideas will be difficult to implement.
* Is it **M**EASURABLE? In this context, is there a relevant ground truth?
* Is it **A**CHIEVABLE? Can your idea actually be accomplished?
* Is it **R**ELEVANT? Has this already been done? Would the result be meaningful?
* Is it **T**IME-BOUND? Can this be accomplished in a reasonable timeframe?

## Example Project Idea
For the remainder of this demo, we are going to use the following idea as an example:

### Idea
Automated volumetric segmentation of the globes (eyeballs) on head CT images

### Rationale
In the setting of acute head trauma, open globe injury may be difficult to detect clinically. Most patients treated for head trauma will undergo CT Head, which presents an opportunity to screen for globe pathology.

### Hypothesis
Differences in globe volume (left versus right) may serve as an imaging biomarker for open globe injury.

### Clinical Relevance
Accurate identification of open globe injury would facilitate ophthalmology consultation and could prevent unnecessary vision loss in patients with traumatic globe injury. 

## Identifying a Dataset
One of the most important aspects of developing a medical image segmentation model is defining your initial cohort. This will not be covered in detail here, however, here are some factors to consider:
* What is the target patient demographic?
* What is the target imaging modality?
* Will this be a single-center or multi-center dataset?
* Are there relevant publicly available datasets that could be used?

### Example Dataset
For this project, we will use the publicly available CT Head dataset from Qure.ai. This dataset consists of 500 patients imaged with CT Head with various different pathologies. For more information, please refer to:

http://headctstudy.qure.ai/dataset

We will only use 100 of these cases for this demo.

## Data Splits
It is essential to define your data split BEFORE undertaking any model development work. This data split will allow you to objectively evaluate the performance of your model after it has been developed.

### Defining a Train/Test Split
For this project, we will use the automatic train/validation/test split functionality that is built into GaNDLF (more on this later). If you are not using software that allows automated data splits, then it is essential to define the splits before model training.

# Steps
 <span style="color:red">**These steps are NOT necessary for participating in the live demo at RSNA.**</span> You only need to complete these steps if you want to run the demo on your own. However, it would be helpful to familiarize yourself with the code before the session.
## Step 1 - Initial Setup
### Description
This step will help you install all the software requisites for running this demo on your local computer.
### Notebook
`dicom2deploy-initial-setup.ipynb`
### Instructions
Follow the steps outlined in the relevant notebook.

## Step 2 - Data Preparation
### Description
This step will help you download the Qure.ai CT Head dataset from the internet and do some basic preprocessing for use with deep learning segmentation software.
### Notebook
`dicom2deploy-initial-data-prep.ipynb`
### Instructions
Follow the steps outlined in the relevant notebook.

## Step 3 - MONAILabel Active Learning
## Description
This step will help you modify the MONAILabel `segmentation` app for use with this demo. Specifically, we will modify the app for globe segmentation from head CTs, and set up a MONAILabel server for active learning to facilitate model development.
## Notebook
`dicom2deploy-monailabel.ipynb`
## Instructions
Follow the steps outlined in the relevant notebook.

# Step 4 - Final Model Training and Deployment
## Description
Once we have all the data labeled, we will train a final "production" model, evaluate the model performance, and package the model for deployment.
## Notebook
`dicom2deploy-deployment.ipynb`
## Instructions
Follow the steps outlined in the relevant notebook.

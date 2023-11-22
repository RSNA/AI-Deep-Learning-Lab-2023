# RSNA AI Deep Learning Lab 2023

## Intro

Welcome Deep Learners!  

This document provides all the information you need to participate in the RSNA AI Deep Learning Lab. This set of classes provides a hands-on opportunity to engage with deep learning tools, write basic algorithms, learn how to organize data to implement deep learning and improve your understanding of AI technology. 

The classes will be held in the RSNA AI Deep Learning Lab classroom, which is located in the Lakeside Learning Center, Level 3. Here's the schedule of [classes](#class-schedule). CME credit is available for each session.


## Requirements

All lessons are designed to run in Google Colab, which is a free web-based version of Jupyter hosted by Google. You will need a Google account (eg, gmail) to use Colab. If you don't already have a Google account, please create one in advance at the [account sign-up page](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp). You can [delete the account](https://support.google.com/accounts/answer/32046?hl=en) when you complete the lessons if you wish. 

We recommend that you use a computer with a recent vintage processor running the [Chrome browser](https://www.google.com/chrome/). 


## Class Schedule

| Date / Time | Session Folder | Notebooks |
| --- | --- | --- |
| Sunday, 26 Nov 2023 |
| Sun 10:00-11:00am | [Basics of NLP in Radiology](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/nlp-basics) (_Beginner friendly_) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/nlp-basics/DLL52_Basics_NLP_Radiology.ipynb) |
| Sun 11:00am-12:30pm | [CT Body Part Classification](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/ct-body-part) (_Beginner friendly_) | [Train notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/ct-body-part/train.ipynb), [Inference notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/ct-body-part/inference.ipynb) |
| Sun 2:30-3:30pm | [Data Processing & Curation for Deep Learning](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/data-curation) (_Beginner friendly_) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/data-curation/RSNA23_DLL_Data_Processing_Curation_for_Deep_Learning.ipynb) |
| Monday, 27 Nov 2023 |
| Mon 9:00-10:00am | [DICOM Data Wrangling with Python](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/dicom-wrangling) (_Beginner friendly_) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/dicom-wrangling/DataWrangling2021RSNA16.ipynb) |
| Mon 10:30-11:30am | [NCI Imaging Data Commons: Curated data and Reproducible AI workflows](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/nci-idc) (_Beginner friendly_) | [Notebook](https://github.com/ImagingDataCommons/IDC-Tutorials/blob/master/notebooks/labs/idc_rsna2023.ipynb) |
| Mon 12:00-1:00pm | [ChatCTP: DICOM De-Identification Using ChatGPT](https://github.com/georgezero/rsna23-chatctp-dicom-deid-using-chatgpt/) (_Beginner friendly_) | [Notebook](https://ai.skp.one/rsna23-deid-dll-colab-notebook) |
| Mon 1:30-2:30pm | [NLP: Text Classification with Transformers](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/nlp-text-classification) (_Beginner friendly_) | **See README for pre-course prep**, [Report Classification](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/nlp-text-classification/RSNA23_llama_cpp_report_labeling.ipynb), [Chat with ACR Contrast Manual](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/nlp-text-classification/RSNA23_ACR_contrast_manual_chat.ipynb) |
| Mon 3:00-4:00pm | [Accessing freely available public datasets from The Cancer Imaging Archive (TCIA)](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/tcia) (_Beginner friendly_) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/tcia/TCIA_RSNA_Deep_Learning_Lab_2023.ipynb) |
| Tuesday, 28 Nov 2023 |
| Tues 9:00-10:00am | [Zero-code Implementation of Federated Learning for Radiology]() (_Beginner friendly_) | TBD |
| Tues 10:30-11:30am | [MIDRC: Building & Using AI-Ready Datasets from a Massive Open Data Commons](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/midrc) (_Beginner friendly_) | **See README in session folder** |
| Tues 12:00-1:00pm | [MedNIST Exam Classification with MONAI](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/mednist-monai) (_Beginner friendly_) | TBD |
| Tues 1:30-2:30pm | [Evaluating Fairness of AI Models in Radiology]() | TBD |
| Tues 3:00-4:00 pm | [Best Practices for Model Training: Architectures, Hyperparameters & Optimization](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/best-practices-training) | TBD |
| Wednesday, 29 Nov 2023 |
| Wed 10:00-11:00 am | [Object Detection in Medical Imaging](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/object-detection) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/object-detection/YOLO_RSNA2023.pdf) |
| Wed 11:30am-12:30pm | [Medical Image Generation](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/image-generation) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/image-generation/RSNA2023_DLL_DDPM.ipynb) |
| Wed 1:00-2:00pm | [Accelerate your AI-based medical imaging research with MONAI Core on SageMaker](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/monai-sagemaker) | **See README in session folder** |
| Wed 2:30-3:30pm | [Developing & Implementing a 3D Segmentation Model: From DICOM to Deployment](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/3d-seg) | **Notebooks in session folder:** [see README](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/3d-seg) |
| Thursday, 30 Nov 2023 |
| Thurs 9:00-10:00am | [DICOM In, DICOM Out for Segmentation](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/tree/main/sessions/dicom-seg) | [Notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/dicom-seg/RSNA_2021_DICOM_IN_DICOM_OUT_Segmentation.ipynb) |
| Thurs 10:30-11:30 am | [Deploy Your Own Model in HuggingFace]() | TBD |

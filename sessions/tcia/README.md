# Summary
Access to large, high quality data is essential for researchers to understand disease and precision medicine pathways, especially in cancer. However HIPAA constraints make sharing medical images outside an individual institution a complex process. [The Cancer Imaging Archive (TCIA)](https://www.cancerimagingarchive.net/) TCIA is a public service funded by the National Cancer Institute which addresses this challenge by providing hosting and de-identification services to take major burdens of data sharing off researchers.

TCIA has published over 200 unique data collections containing more than 60 million images. Recognizing that images alone are not enough to conduct meaningful research, most collections are linked to rich supporting data including patient outcomes, treatment information, genomic / proteomic analyses, and expert image analyses (segmentations, annotations, and radiomic / radiogenomic features). **In this course we will address a variety of use cases for identifying TCIA datasets of interest and downloading them via Jupyter Notebooks.**

# Learning Objectives

* Learn how TCIA makes data sharing easier for researchers, and hear a summary of existing datsets that are freely available for download
* Practice utilizing TCIA for data exploration, cohort definition, and downloading of data
* Learn how to access public and restricted access datasets using TCIA's REST APIs and other command line tools via Google Colab
  
# Before you arrive
In some cases, you must specifically request access to TCIA collections before you can download them. 
These are listed as **limited access** on the [Browse Collections](https://www.cancerimagingarchive.net/collections/) page. 
The steps to request access may vary depending on the collection, but will always require that you first 
[create a TCIA user account](https://wiki.cancerimagingarchive.net/x/xgHDAg). 

If you'd like to be able to follow along when we demonstrate functionality related to accessing restricted data, 
please create an account using the link above and then email help@cancerimagingarchive.net to request access to the
[QIN-Breast-02](https://doi.org/10.7937/TCIA.2019.4cfm06rr) collection sometime before the day of the class. 

# A brief introduction to The Cancer Imaging Archive (TCIA)
We'll begin with a very brief [slide presentation](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/raw/main/sessions/tcia/RSNA_DLL_intro_2023-11-15.pptx) to provide an overview of The Cancer Imaging Archive.

# Interactive Notebook
Then we'll walk through [this notebook](https://github.com/RSNA/AI-Deep-Learning-Lab-2023/blob/main/sessions/tcia/TCIA_RSNA_Deep_Learning_Lab_2023.ipynb) together for the hands-on portion of the learning lab.

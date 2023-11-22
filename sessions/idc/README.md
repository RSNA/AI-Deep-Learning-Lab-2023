![image](https://github.com/ImagingDataCommons/IDC-Tutorials/releases/download/rsna2023/2023RSNA-DLL-IDC_header.png)

# **National Cancer Institute Imaging Data Commons (IDC)**: Curated Data and Reproducible AI Workflows

# About

This notebook was prepared for the IDC Deep Learning Lab DLL session at the [Radiological Society of North America (RSNA) 2023 annual meeting](https://reg.meeting.rsna.org/flow/rsna/rsna23/RSNA2023/page/pre-event-landing-page) that took place Nov 26-30 in Chicago, USA. It is part of the RSNA 2023 DLL program and notebook series available in https://github.com/RSNA/AI-Deep-Learning-Lab-2023.

## Presenter
Andrey Fedorov, PhD - Brigham and Women's Hospital / Harvard Medical School

## Session Date & Time
Monday, November 27, 2023 10:30 - 11:30 PM (US Central Time)

To learn more about IDC you are also welcome to visit RSNA'23 *Imaging Informatics Educational Exhibit INEE-45 "NCI Imaging Data Commons: Towards Transparency and Reproducibility in Imaging AI"* at the Learning Center to ask questions and see more IDC demonstrations!

## Pre-course instructions

This session will include a mix of presentation mechanisms, including slide presentations, live demonstrations of the IDC website and related software, and Python notebooks using [Google Colaboratory](https://colab.research.google.com/) (Google Colab).

For the best educational experience, you must bring your own laptop computer, since the components that will be demonstrated are not optimized for tablet or smartphone devices. If you choose to experiment with the Python notebooks, you will also need a Google account (even if temporary) to access Colab.

## About IDC

[NCI Imaging Data Commons (IDC)](https://imaging.datacommons.cancer.gov) is a cloud-based environment containing publicly available cancer imaging data co-located with analysis and exploration tools and resources. IDC is a node within the broader [NCI Cancer Research Data Commons (CRDC)]() infrastructure that provides secure access to a large, comprehensive, and expanding collection of cancer research data.

If this is the first time you hear about IDC, here are some highlights about what it has to offer:

* **45 TB of data**: IDC contains radiology, brightfield (H&E) and fluorescence slide microscopy images, along with image-derived data (annotations, segmentations, quantitative measurements) and accompanying clinical data
* **free**: all of the data in IDC is publicly available: no registration, no access requests, no forms to fill or approval committees
* **cloud-based**: all of the data in IDC is available from both Google and AWS public buckets: fast and free to download, no out-of-cloud egress fees
* **commercial-friendly**: most of the data in IDC is covered by the permissive CC-BY license, which allows commercial reuse (small subset of data is covered by the CC-NC license); each file in IDC is tagged with the license to make it easy for you to understand and follow the rules
* **harmonized**: all of the images and image-derived data in IDC is harmonized into standard DICOM representation

## Tutorial program

### 1. Introduction to IDC 

* [Presentation slides](https://tinyurl.com/idc-rsna23) (slides will be shared publicly following the tutorial)


### 2. Hands-on demonstration of the IDC Portal

* IDC Portal: https://portal.imaging.datacommons.cancer.gov/explore/

### 3. Hands-on demonstration of the 3D Slicer IDC Browser extension

* SlicerIDCBrowser extension: https://github.com/ImagingDataCommons/SlicerIDCBrowser

### 4. Basics of interacting with IDC from Python

* [Getting started with IDC](https://github.com/ImagingDataCommons/IDC-Tutorials/blob/master/notebooks/labs/idc_rsna2023.ipynb) notebook
  * _Our new python package [`idc-index`](https://github.com/ImagingDataCommons/idc-index) makes basic IDC metadata searchable without requiring Google credentials!_

### Other relevant materials to explore on your own

* [IDC User Forum](https://discourse.canceridc.dev) is the place to ask any questions related to IDC, get help from IDC developers, and meet other IDC users!
* [Getting started with IDC](https://github.com/ImagingDataCommons/IDC-Tutorials/tree/master/notebooks/getting_started) tutorial series: unlike the notebook above, these notebooks rely on Google BigQuery; all of the prerequisites are free
* [Advanced topics](https://github.com/ImagingDataCommons/IDC-Tutorials/tree/master/notebooks/advanced_topics) tutorials: here you can learn how to search and combine clinical data with imaging metadata
* [Viewers deployment](https://github.com/ImagingDataCommons/IDC-Tutorials/tree/master/notebooks/viewers_deployment) tutorials: learn how to host your own instances of OHIF and Slim viewers and use them to visualize your own private data in Google Cloud
* [IDC Zenodo community](https://zenodo.org/communities/nci-idc): direct submissions of data to IDC are deposited to Zenodo to archive, provide citation, and generate the DOI to provide visibility and credit to the submitters
* [IDC publications](https://learn.canceridc.dev/publications): curated list of peer-reviewed manuscripts and preprints by the IDC team and external groups that utilized IDC in their research
* [MHub](https://mhub.ai/): a platform for Deep Learning models in medical imaging curated into a standardized and easy-to-use format. MHub-curated models are ready to be applied to the data in IDC in its native DICOM representation, and are accompanied by publicly available sample images. 
   * [How to use MHub with IDC](https://github.com/ImagingDataCommons/IDC-Tutorials/blob/master/notebooks/labs/idc_mhub_miccai23.ipynb) notebook


## Acknowledgments and disclaimers

* This project has been funded in whole or in part with Federal funds from the NCI, NIH, under task order no. HHSN26110071 under contract no. HHSN261201500003l.
* Free cloud hosting and out of cloud egress of IDC data are supported through the partnership with the respective public datasets programs of Google and Amazon Web Services.
* We are grateful to the Advanced Cyberinfrastructure Coordination Ecosystem (ACCESS) for the JetStream2 credits allocation.
* The views presented do not necessarily reflect the views or policies of the Department of Health and Human Services, nor does mention of trade names, commercial products, or organizations imply endorsement by the U.S. Government.


If you use IDC in your research, please give credits to IDC by citing the following publication:

> Fedorov, A., Longabaugh, W. J. R., Pot, D., Clunie, D. A., Pieper, S., Aerts, H. J. W. L., Homeyer, A., Lewis, R., Akbarzadeh, A., Bontempi, D., Clifford, W., Herrmann, M. D., Höfener, H., Octaviano, I., Osborne, C., Paquette, S., Petts, J., Punzo, D., Reyes, M., Schacherer, D. P., Tian, M., White, G., Ziegler, E., Shmulevich, I., Pihl, T., Wagner, U., Farahani, K. & Kikinis, R. NCI Imaging Data Commons. Cancer Res. 81, 4188–4193 (2021). http://dx.doi.org/10.1158/0008-5472.CAN-21-0950

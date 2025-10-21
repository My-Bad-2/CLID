# Comprehensive Lung Cancer Imaging Dataset (CLID)
`Version: 1.0.0 Last Updated: October 21, 2025`

## 1. Description
The Comprehensive Lung Cancer Imaging Dataset (CLID) is a curated collection of medical images designed to facilitate the research and development of machine learning models for lung cancer analysis. This dataset amalgamates computed tomography (CT) scans and histopathological images from several public sources, providing a diverse and robust resource for tasks such as:
* Tumor detection and segmentation from CT scans.
* Cancer subtype classification (e.g., Adenocarcinoma vs. Squamous Cell Carcinoma) from histopathology slides.
* Multimodal data fusion models.
* Survival prediction and cancer grading.

By combining data from different patient cohorts, imaging modalities, and acquisition protocols, CLID aims to promote the development of more generalizable and resilient AI-powered diagnostic tools.

## 2. Data Sources
This dataset is a collection and aggregation of the following public datasets. We extend our sincere gratitude to the original creators and maintainers. Please ensure you cite the original publications if you use this dataset.
1. Lung CT and Histopathological Images Dataset
* Description: The Lung CT and Histopathological Images Dataset contains labeled images for lung cancer detection and classification. It includes CT scans of adenocarcinoma, squamous cell carcinoma, and normal lung tissue, along with histopathological images for adenocarcinoma, squamous cell carcinoma, and benign tissue. This dataset is ideal for training models in multi-class cancer detection and differentiation.
* Content Used: CT scans and Histopathological Images
* Source: [Kaggle](https://www.kaggle.com/api/v1/datasets/download/programmer3/lung-ct-and-histopathological-images-dataset)
* License: "CC0: Public Domain"

## 3. Dataset Structure
The dataset is organized into two main directories for each imaging modality.
```
CLID/
├── CT Scan
│   ├── adenocarcinoma
│   ├── normal
│   └── squamous_cell
├── Histo_Images/
│   ├── adenocarcinoma
│   ├── normal
│   └── squamous_cell
└── README.md
```

## 4. License and User Obligations
This is a derivative dataset. Your use of this data is subject to the licenses and policies of ALL original sources. It is your responsibility to review and comply with them.

### Source License Summary
* **CC0: Public Domain**: Public Domain. The work can be used, copied, modified, distributed, and built upon for any purpose—including commercial—with no conditions or attribution required, although giving credit is still appreciated.

### License for this Derivative Dataset (CLID)
This curated dataset is licensed under [**Open Data Commons Open Database License (ODbL) v1.0**](LICENSE.md).

## 5. Contact
For questions, bug reports, or suggestions, please  open an issue on the dataset's GitHub repository [CLID](https://github.com/My-Bad-2/CLID).
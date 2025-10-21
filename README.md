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
* Source: [Kaggle](https://www.kaggle.com/datasets/programmer3/lung-ct-and-histopathological-images-dataset)
* License: "CC0: Public Domain"
2. Chest CT-Scan images Dataset
* Description: It was a project about chest cancer detection using machine learning and deep leaning (CNN). We classify and diagnose if the patient have cancer or not using AI model. We give them the information about the type of cancer and the way of treatment. we tried to collect all data we need to make the model classify the images easily. So, I had to fetch data from many resources to start the project. I researched a lot to collect all the data from many resources and cleaned it for the CNN.
* Content Used: CT Scans
* Source: [Kaggle](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)
* License: "OBdL v1.0"
3. Lung and Colon Cancer Histopathological Images
* Description: This dataset contains 25,000 histopathological images with 5 classes. All images are 768 x 768 pixels in size and are in jpeg file format.
The images were generated from an original sample of HIPAA compliant and validated sources, consisting of 750 total images of lung tissue (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas) and 500 total images of colon tissue (250 benign colon tissue and 250 colon adenocarcinomas) and augmented to 25,000 using the Augmentor package.
* Content Used: Histopathological Images of Lung cancer
* Source: [Kaggle](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)
* License: "CC BY-SA 4.0"
* Citation: Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019

## 3. Dataset Structure
The dataset is organized into two main directories for each imaging modality.
```
CLID/
├── CT Scan
│   ├── adenocarcinoma
│   ├── large_cell
│   ├── normal
│   └── squamous_cell
├── Histopathological Images/
│   ├── adenocarcinoma
│   ├── normal
│   └── squamous_cell
└── README.md
```

## 4. License and User Obligations
This is a derivative dataset. Your use of this data is subject to the licenses and policies of ALL original sources. It is your responsibility to review and comply with them.

### Source License Summary
* **CC0: Public Domain**: Public Domain. The work can be used, copied, modified, distributed, and built upon for any purpose—including commercial—with no conditions or attribution required, although giving credit is still appreciated.
* **OBdL**: Allows you to freely copy, distribute, and adapt a database for any purpose, including commercial use. In return, you must provide appropriate credit to the original source and share any new or modified versions of the database under the same ODbL license. Files starting with prefix "mohamedhanyyy_" are licensed under OBdL.
* **CC BY-SA 4.0**: allows you to share, adapt, and remix a work for any purpose, even commercially, as long as you provide attribution to the original creator and license any new works under the same CC BY-SA 4.0 license

### License for this Derivative Dataset (CLID)
This curated dataset is licensed under [**Open Data Commons Open Database License (ODbL) v1.0**](LICENSE-1.md) for the image names starting with the prefix "mohamedhanyyy_" and [**CC BY-SA 4.0**](LICENSE-2.md) for the rest of the images.

## 5. Contact
For questions, bug reports, or suggestions, please open an issue on the dataset's GitHub repository [CLID](https://github.com/My-Bad-2/CLID).
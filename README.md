# AVDD-TCMI-dataset

The dataset used in this project is hosted on Hugging Face:[AVDD-TCMI Dataset](https://huggingface.co/datasets/Mar-rill/AVDD-TCMI-dataset)

Due to size limits, the dataset is provided via Hugging Face Hub instead of GitHub.

## Introduction
The **AVDD-TCMI dataset** is a multimodal dataset for depression detection. Our dataset comprises a total of 1,230 valid samples, including 969 non-depressed individuals and 261 depressed individuals. It contains two primary subsets:
- **HDS (Hospital Depression Subset):** HDS is collected from volunteers at West China Hospital of Sichuan University and includes 282 valid samples, comprising 159 non-depressed volunteers (including doctors, nurses, and patients without depression) and 123 clinically diagnosed depressed patients undergoing treatments.
- **SDS (Student Depression Subset):** SDS is collected from a middle school and contains 948 valid samples, including 810 non-depressed and 138 depressed volunteer students.

## Modalities
- **mulitimodal**
- **audio**
- **visual**

## Structure
```
AVDD-TCMI-dataset/
├── HDS/
│ ├── 0/
│ │ ├── 0_tcm/ # regional features extracted based on TCM facial inspection (images)
│ │ ├── 0_acoustic.csv # audio_features
│ │ └── 0_visual.csv # video_features
│ └── ...
├── SDS/
│ └── 0/
│ └── ...
├── HDS_labels.csv # id,label (0=non-depressed,1=depressed),gender (f=female,m=male)
└── SDS_labels.csv
```

## Data Splits
This dataset is not pre-split into train/validation/test. Users should perform their own split.

## Contact
For questions, contact:1224045611@njupt.edu.cn

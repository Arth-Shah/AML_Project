# AML_Project
AML Project of Arth J. Shah (202521004)


![Python(Preferred)](https://img.shields.io/badge/Python-3.12%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Kaggle](https://img.shields.io/badge/Kaggle-Notebook%20Ready-20BEFF)


Time taken to run codes

 1. RawNet2   -  29 min 12 sec
 2. AASIST    -  55 min 32 sec
 3. AASIST3   -  1 hr 43 mins
 4. Rawformer -  1 hr 10 mins


---
## Dataset Structure

This project supports ASVspoof 2019 and ASVspoof 2021 (LA) datasets.

### Required Format

Datasets must be organized as:

```

dataset_root/
├── train/
│   ├── bonafide/
│   └── spoof/
├── dev/
│   ├── bonafide/
│   └── spoof/
└── test/
│   ├── bonafide/
│   └── spoof/

```

Update paths in `config.py` accordingly if using python.

The `Dataset_Formation/` directory provides scripts to automatically organize ASVspoof 2019 and ASVspoof 2021 (LA) datasets into the required format once downloaded zip (from [original ASVSpoof website](https://www.asvspoof.org/database)) and extracted. Users are recommended to use these scripts for consistency.

Preprocessed Datasets zip download (Kaggle.com)
- ASVspoof 2021 (LA):  
  https://www.kaggle.com/datasets/artharking/asv-2021-la-test

- ASVspoof 2019 (AA):  
  https://www.kaggle.com/datasets/artharking/asv-19-aa

These can be used directly without additional preprocessing.

---

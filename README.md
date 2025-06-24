# VersaMammo

## Clone repository
```shell
git clone https://github.com/PiggyJerry/VersaMammo-Downstream.git

cd VersaMammo-Downstream
```

## Prepare classification datasets and segmentation\detection datasets
### Datasets-Links:
Datasets downloading URL:
    
| Dataset Name | Link | Access |
|-----|---------------|--------|
| BMCD | https://zenodo.org/records/5036062 | Open Access |
| CBIS-DDSM | https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset | Open Access |
| CDD-CESM | https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=109379611#109379611bcab02c187174a288dbcbf95d26179e8 | Open Access |
| DMID | https://figshare.com/articles/dataset/_b_Digital_mammography_Dataset_for_Breast_Cancer_Diagnosis_Research_DMID_b_DMID_rar/24522883 | Open Access |
| INbreast | [https://www.physionet.org/content/vindr-spinexr/1.0.0/](https://www.kaggle.com/datasets/tommyngx/inbreast2012) | Open Access |
| MIAS | [https://physionet.org/content/vindr-pcxr/1.0.0/](https://www.kaggle.com/datasets/kmader/mias-mammography) | Open Access |
| CSAW-M | https://figshare.scilifelab.se/articles/dataset/CSAW-M_An_Ordinal_Classification_Dataset_for_Benchmarking_Mammographic_Masking_of_Cancer/14687271 | Credentialed Access |
| KAU-BCMD | https://www.kaggle.com/datasets/asmaasaad/king-abdulaziz-university-mammogram-dataset?select=Birad5 | Open Access |
| VinDr-Mammo | https://www.physionet.org/content/vindr-mammo/1.0.0/ | Credentialed Access |
| RSNA | https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data | Open Access |
| EMBED | [https://physionet.org/content/mimic-cxr/2.0.0](https://registry.opendata.aws/emory-breast-imaging-dataset-embed/) | Credentialed Access |

After downloaded datasets above, you have to use the correspoding processing code for it. Remember to change the dataset link in the code!!!

## Processing Dataset Codes and Files Linking:

| Dataset Name | Process Dataset Code |
|--------------|----------------------|
| BMCD | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/BMCD.ipynb |
| CBIS-DDSM | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/CBIS-DDSM.ipynb |
| CDD-CESM | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/CDD-CESM.ipynb |
| DMID | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/DMID.ipynb |
| INbreast | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/INbreast.ipynb |
| MIAS | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/MIAS.ipynb |
| CSAW-M | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/CSAW-M.ipynb |
| KAU-BCMD | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/KAU-BCMD.ipynb |
| VinDr-Mammo | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/VinDr-Mammo.ipynb |
| RSNA | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/rsna.ipynb |
| EMBED | https://github.com/PiggyJerry/MammoVQA/blob/main/preprocess/EMBED.ipynb |

## Prepare pre-trained weights

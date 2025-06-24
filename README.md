# VersaMammo

## Clone repository
```shell
git clone https://github.com/PiggyJerry/VersaMammo-Downstream.git

cd VersaMammo-Downstream
```

## Download datasets
### Datasets-Links:
Datasets downloading URL:
    
| Dataset Name | Link | Access |
|-----|---------------|--------|
| BMCD | https://zenodo.org/records/5036062 | Open Access |
| CBIS-DDSM | https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset | Open Access |
| CDD-CESM | https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=109379611#109379611bcab02c187174a288dbcbf95d26179e8 | Open Access |
| DMID | https://figshare.com/articles/dataset/_b_Digital_mammography_Dataset_for_Breast_Cancer_Diagnosis_Research_DMID_b_DMID_rar/24522883 | Open Access |
| INbreast | https://www.kaggle.com/datasets/tommyngx/inbreast2012 | Open Access |
| MIAS | https://www.kaggle.com/datasets/kmader/mias-mammography | Open Access |
| CSAW-M | https://figshare.scilifelab.se/articles/dataset/CSAW-M_An_Ordinal_Classification_Dataset_for_Benchmarking_Mammographic_Masking_of_Cancer/14687271 | Credentialed Access |
| KAU-BCMD | https://www.kaggle.com/datasets/asmaasaad/king-abdulaziz-university-mammogram-dataset?select=Birad5 | Open Access |
| VinDr-Mammo | https://www.physionet.org/content/vindr-mammo/1.0.0/ | Credentialed Access |
| RSNA | https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data | Open Access |
| EMBED | https://registry.opendata.aws/emory-breast-imaging-dataset-embed/ | Credentialed Access |
| DBT-Test | http://www.cancerimagingarchive.net/ | Open Access |
| LAMIS | https://github.com/LAMISDMDB/LAMISDMDB_Sample | Credentialed Access |
| MM | https://data.mendeley.com/datasets/fvjhtskg93/1 | Open Access |
| NLBS | https://www.frdr-dfdr.ca/repo/dataset/cb5ddb98-ccdf-455c-886c-c9750a8c34c2 | Open Access |

## Prepare classification datasets
After downloaded datasets above, you have to use the correspoding processing code for it. Remember to change the dataset link in the code!!!

### Processing Dataset Codes and Files Linking:

| Dataset Name | Process Dataset Code |
|--------------|----------------------|

## Prepare segmentation\detection datasets
After downloaded datasets above, you have to use the correspoding processing code for it. Remember to change the dataset link in the code!!!

### Processing Dataset Codes and Files Linking:

| Dataset Name | Process Dataset Code |
|--------------|----------------------|

## Prepare VQA datasets
Please prepare the dataset according to MammoVQA[https://github.com/PiggyJerry/MammoVQA], and put the dataset's json files under /VQA folder.

## Prepare pre-trained weights

## Training
For all the downstream tasks, you can use the following command to train the models (please modify the downstream_task to the corresponding task):
```shell
bash /downstream_task/bash.sh
```

## Testing
For all the downstream tasks, you can use the following command to test the models (please modify the downstream_task to the corresponding task):
```shell
bash /downstream_task/eval.sh
```

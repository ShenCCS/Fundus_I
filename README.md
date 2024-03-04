# Fundus Image for RETFound model and ViT model
# ===================================
### Training data not split by ID
# ===================================
>
## Enviroment
* python 3.7.5 
* conda env : retfound
> link : https://github.com/rmaphoh/RETFound_MAE

## Data Preprocessing _ Row data
> Route: /john/network/RETFound/data/
> 
> Row data(Zip from Keelung) :/john/network/RETFound/data/Zip
> 
> Row data(unzip)_images : /john/network/RETFound/data/dataset
> 
* code: RETFound_data_preprocessing.ipynb (Move file together)

## Data Preprocessing _ Images select ROI
> Image Route : /john/network/RETFound/data/ROI
>
* code: RETFound_data_preprocessing.ipynb (ROI)

## Data Preprocessing _ ID classification
> Files Route : /john/network/RETFound/data/Images_Files
>
* code : RETFound_data_preprocessing.ipynb (ID)
> split Training & validation & Testing data for RETFound model
> 
* code : RETFound_data_preprocessing.ipynb (Training validaion Testing)

# Fundus Image for RETFound model and ViT model
# =====Training data not split by ID=====
>
## Enviroment
* python 3.7.5 
* conda env : retfound & gpu
* Model execution environment : Nvidia A5000
> link : https://github.com/rmaphoh/RETFound_MAE

## Data Preprocessing _ Row data
> Route: /john/network/RETFound/data/
> 
> Raw data(Zip from Keelung) :/john/network/RETFound/data/Zip
> 
> Raw data(unzip)_images : /john/network/RETFound/data/dataset
> 
* code: RETFound_data_preprocessing.ipynb (Move file together)

## Data Preprocessing _ Images select ROI
> Image Route : /john/network/RETFound/data/ROI
>
* code: RETFound_data_preprocessing.ipynb (ROI)

# model(RETFound)
> code File : /john/network/RETFound_MAE-main/Fundus_I/RETFound
* code : Age(2521).ipynb、BMI(2521).ipynb....
* Note : GPU -> A5000

# Captum
> File Route : /john/network/RETFound/RETFound_MAE-main/captum/codes
* code : captumImage.ipynb

# Microcirculation | Leaders of Digital 2022
## Eye Vessel Segmentation Track


**Technologies used:** 

 - PyTorch, 
 - Albumentations, 
 - Scikit-Learn, 
 - Pandas, 
 - Numpy, 
 - Pillow

**Solution Description:**

1. Pretrain U-Net using efficientnet backbone with Third-party Vessel Segmentation Data
2. Train the model on Microcirculation Data on cross-validation
3. Predict Test Data with cross-validaion folds models
4. Weight and average the results obtained
5. Round predictions with some treshold
6. Zip predicted masks

## Bone-Age-Assessment / Group Skeletal Hand
###  ABSTRACT
- Inspired by Chen et al. (2020)’s incorporation of gender information in bone age assessment (BAA), we searched for other possible factors that influence the outcome of BAA and found ethnicity to be key information in the literature. <br>
- We examined whether the addition of an ethnicity feature could improve the original model's performance at bone age prediction. <br>
- We preprocessed the data from Digital Hand Atlas (DHA) to adjust to the original model, and one-hot encoded the ethnicity feature to concatenate it alongside the gender and the image features in the age regression network. <br>
- Using the hyperparameters that yield the optimal performance in the paper, we trained both the DHA dataset and a subsample of the RSNA dataset with the same size and compared the resulting test mean absolute errors (MAE). <br>
- We found that there was no significant improvement with the inclusion of ethnicity in the model, but further research involving hyperparameter tuning is needed to confirm. *(See report and pre for details)*


 

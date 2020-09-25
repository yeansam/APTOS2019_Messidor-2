# Preliminary Study of Diabetic Retinopathy Classification from Fundus Images using Deep Learning Model
# APTOS 2019 Blindness Detection

## Notebooks:
- <b>Data_preprocessing_(FYP 2).ipynb</b>: Image pre-processing  
- <b>APTOS_(FYP_2_best_solution).ipynb</b>: Architecture for data training with APTOS train and test datasets   
- <b>APTOS_(FYP_2_best_solution_Messidor_2).ipynb</b>: Same as APTOS_(FYP_2_best_solution).ipynb, but used Messidor-2 dataset to replace APTOS test dataset and some additional evaluations

## Datasets used:  
- <b>APTOS</b>: Training and Testing  
Link: [APTOS 2019 Blindness Detection Dataset](https://www.kaggle.com/c/aptos2019-blindness-detection/data)
- <b>Messidor-2</b>: Further testing (In order to see how does the prediction model performs on test dataset that is from a different source as well as obtain overall accuracy due to the competition no longer accept submission)   
Link: [Messidor-2 dataset](http://www.adcis.net/en/third-party/messidor2/)

## The results:
- 0.9308 Quadratic Weighted Kappa score 
- Higher than 74% of accuracy on APTOS test dataset (estimated)  
- 65% of accuracy on Messidor-2 dataset

## References (Thanks for the references!):
[mikelkl/APTOS2019](https://github.com/mikelkl/APTOS2019/tree/master/notebooks): Image pre-processing   
[richiebui/APTOS](https://github.com/richiebui/APTOS): Training architecture starter

# MentalAId
----
MentalAId is an Artificial Intelligence model assisting in quick automatic screening of broad-spectrum psychosis on basis of 49 hematoloical tests and two demographic variables (sex & age).

* To assess the risk probability of psychosis based on you own hematological test data, refer to [example_data.csv](https://github.com/LiMuxiBADD/MentalAId/blob/main/MentalAId/example_data.csv)
  * Each row represents a record, columns from 'A/G' to 'WBC' are 49 tests required for prediction
  * column 'dig' denotes the diagnosis label, 'N' for non-psychosis and 'P' for psychosis (not necessary for model prediction) 
  * Note that do not change the order of indicators, as they are organized in a fixed way


MentalAId
----
* To utilize MentalAId, follow the steps:
  1. Run [Data_preprocessing.ipynb](https://github.com/LiMuxiBADD/MentalAId/blob/main/PsychoDNet/Data_preprocessing.ipynb)
  2. Run [PsychoDNet.ipynb](https://github.com/LiMuxiBADD/PsychoDNet/blob/main/MentalAId/PsychoDNet.ipynb)
 * [example_data.csv](https://github.com/LiMuxiBADD/PsychoDNet/blob/main/MentalAId/example_data.csv), [embedding.csv](https://github.com/LiMuxiBADD/MentalAId/blob/main/MentalAId/embedding.csv) and [sum_data.csv](https://github.com/LiMuxiBADD/MentalAId/blob/main/MentalAId/sum_data.csv) are required, while you only need to change *example_data.csv*
 * *data.npy* and *label.npy* are intermediate files generated by *Data_preprocessing.ipynb*

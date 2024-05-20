# Deposition efficiency (DE) prediction in Cold spray (CS) - Overview files

## GUI_DE_prediction _CS.ipynb
This script shows the Python code (in a Jupyter Notebook format) for the GUI, which integrates a machine learning (ML) model used to predict the DE in CS processes for various spray parameters.
The ML model used in the GUI is a neural network (NN) trained with dataset D2 as described in the manuscrip: "Predicting deposition efficiency across diverse cold spray process parameters using machine learning".

Please execute the script in the same folder as the h5, pkl and png files.

## neural_network_model_II_20231011.h5
This file contains the NN model trained with dataset D2 for the prediction of DE in CS.

## scaler_for_NN_II_20231011.pkl
This file contains a trained StandardScaler object for normalizing the input data for the NN prediction model.

## CS_data_Literature_D1_D2.xlsx
This file contains the datasets D1 and D2 with CS spray parameters and corresponding achieved DE-values as reported in published manuscripts.

*Note: The models described in our manuscript were trained using this dataset along with additional data obtained from experiments conducted at Titomic in Melbourne, Australia. The data from these experiments is proprietary and therefore not included here.

## png-files
These files illustrate the prediction error for dataset D2 depending on differnent DE bins. The ipynb.script requires access to these files to function. 

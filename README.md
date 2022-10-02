# LUT CARS Data Analysis 
# Effect of Different NRB types
Paper tittle: "Effect of non-resonant background on the extraction  of Raman signals from CARS spectra using deep neural networks"

By [Rajendhar junjuri](https://scholar.google.co.in/citations?user=BRu_wuAAAAAJ&hl=en)\, [Ali Saghi](https://scholar.google.co.in/citations?view_op=list_works&hl=en&hl=en&user=GcWhnFcAAAAJ),  [Lasse Lensu](https://scholar.google.co.in/citations?user=dk2Ezl0AAAAJ&hl=en&oi=ao), and [Erik M. Vartiainen](https://scholar.google.co.in/citations?user=zbxe2qYAAAAJ&hl=en&oi=ao) 

## About Synthetic test data
These are 300 synthetic test spectra evaluated in the manuscript.

1. First, 100 spectra correspond to ‘Product of two Sigmoid NRB’.

2. Spectra 101-200 account for ‘One sigmoid NRB’.

3. Spectra 201-300 correspond to ‘Polynomial NRB’.

"y_test_300_merge_spectra3.npy"---> referes to the true Raman signal

"x_test_300_merge_spectra3.npy"---> referes to the input CARS data

## About the CNN model code

The model architecture directly adapted from the SpecNet paper (See https://github.com/Valensicv/SpecNet for the full code of the neural net-work model)
Here three different NRB are evaluated 

It can be accessed from the following program.
RSS_Advances_CNN_to_train_with_different_NRBs.py

Testing can be done by using following program.
RSS_Advances_CNN_prediction_on_test_data.py

## About the trained model weights

"One_sigmoid_NRB_model_weights.h5" --->referes wiehts of the model trained with One sigmoid NRB

"Polynomial_NRB_model_weights.h5" --->referes wiehts of the model trained with Polynomial_NRB

"Specnet_weights.h5" --->referes wiehts of the model trained with product of two sigmoids NRB

## About the experimetal CARS data
The experimetal CARS data set used in this investigation can only be provided by upon the request [Erik M. Vartiainen](erik.vartiainen@lut.fi) 

## Getting Started and Requirements 
You can use the Python (TensorFlow 2.7.0) to test the pretrained network. We have tested it in Spyde

## Citation
Formats to cite our paper.

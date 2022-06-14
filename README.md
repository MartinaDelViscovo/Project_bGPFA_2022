# Project_bGPFA_2022

In this repository, we include files used to implement bGPFA, as from Jensen et al 2021, and to use 
the latents X inferred by bGPFA and the firing rates calculated as F=CX as an input for decoding, 
in comparison with the smoothed firing rates (directly calculated from the dataset) and the latents 
found by PCA. We test the performance of bGPFA for four decoders: a linear regressor and a ridge regressor
(working with or without history), an LSTM and a multilayer perceptron (MLP). 


The bGPFA algorithm is developed by Jensen et al, while it is tested on data from Glaser et al 2018. 

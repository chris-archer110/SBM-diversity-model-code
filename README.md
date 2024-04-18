# SBM-diversity-model-code

Source code for the paper "Modeling Diversity Dynamics in Time-Evolving Collaboration Networks" By Christopher Archer and Gireeja Ranade. 
  
  (1) data_parsing.ipynb processes the raw APS publication data into a csv file
  
  (2) data_filtering.ipynb applies all the filters described in the paper on the data
  
  (3) graph_builder.ipynb makes the filtered data into a graph, then fits the model with estimated parameter values

The pipeline for the data processing is data_parsing.ipynb -> data_filtering.ipynb -> graph_builder.ipynb

The APS dataset can be requested with this link: https://journals.aps.org/datasets

The dataset with deduplicated author names (APS_author2DOI.dat) can be found in the resource section of the paper "Quantifying the evolution of individual scientific impact" By Roberta Sinatra et al. (https://www.science.org/doi/10.1126/science.aaf5239)

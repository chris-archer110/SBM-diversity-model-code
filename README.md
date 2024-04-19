# SBM-diversity-model-code

Source code for the paper "Modeling Diversity Dynamics in Time-Evolving Collaboration Networks" By Christopher Archer and Gireeja Ranade. 
  
  (1) _data_parsing.ipynb_ processes the raw APS publication data into a csv file
  
  (2) _data_filtering.ipynb_ applies all the filters described in the paper on the data
  
  (3) _graph_builder.ipynb_ makes the filtered data into a graph, then fits the model with estimated parameter values

  (4) _aps_filtered_data.csv_ is the publication data after the filters in the paper have been applied (after _data_filtering.ipynb_)

  (5) _aps_filtered_data_no_restriction.csv_ is the publication data under the same filters but with no coauthor restrictions (this is used to generate Figure 5 in the paper)

The pipeline for the data processing is data_parsing.ipynb -> data_filtering.ipynb -> graph_builder.ipynb

The full APS dataset can be requested with this link: https://journals.aps.org/datasets

The dataset with deduplicated author names (APS_author2DOI.dat) can be found in the resource section of the paper "Quantifying the evolution of individual scientific impact" By Roberta Sinatra et al. (https://www.science.org/doi/10.1126/science.aaf5239)

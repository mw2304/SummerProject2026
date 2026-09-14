# SummerProject2026
## SUMMER REPORT TITLE: An Investigation of How Neural Networks Can Reconstruct Three-Gamma Annihilation Positions in Positron Emission Tomography 

The aim of the investigation was to compare how different neural networks predict annihilation sites. The focus developed to investigation of three gamma. The datasets used involved data with no Compton Scattering *'ThreeG_NCS'*. A compressed, smaller root file has been uploaded to each folder, so, if needed, it can be executed, *'augmerged.root'*. 

### There are two main folders: 
  **'ARCHIVE NOTEBOOKS':** This is the development models, which is further split into
      - **'CNN Archive'** and **'MLP Archive'**, which are the respective folders for the CNN and MLP neural networks development. 
      Where possible, the code has been edited to use the smaller *'augmerged.root'* file.
      - **'ROOT ARCHIVE'** which were used to get to grips with the simulation data in the beginning stages of the research. 
  **'FINAL MODELS':** These show the combined models for CNN and MLP, compiled into one notebook to allow for evaluation and comparison. 
      the **VAE** and **smeared energy** models are kept in one notebook, indicating what   was changed with # but not separated. This is due to the exploratory nature of these models/notebooks and is mostly used for further discussions.
      the reduced root file, *'augmerged.root'* is in each folder, to execute if needed. 

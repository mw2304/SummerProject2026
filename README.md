# Summer Project 2026

## SUMMER REPORT TITLE: An Investigation of How Neural Networks Can Reconstruct Three-Gamma Annihilation Positions in Positron Emission Tomography

The aim of the investigation was to compare how different neural networks predict annihilation sites. The focus developed to the investigation of three-gamma annihilation. The datasets used involved data with no Compton Scattering, *ThreeG_NCS*. A compressed, smaller ROOT file has been uploaded to each folder, so, if needed, it can be executed using *augmerged.root*.

### There are two main folders:

- **ARCHIVE NOTEBOOKS:** This contains the development models and is further split into:
  - **CNN Archive** – development of the CNN neural networks.
  - **MLP Archive** – development of the MLP neural networks.
  - **ROOT Archive** – ROOT files and notebooks used to get to grips with the simulation data during the beginning stages of the research.

  Where possible, the code has been edited to use the smaller *augmerged.root* file.

- **FINAL MODELS:** This contains the combined final models 
    - **CNN** and **MLP** : compiled into comparative, multi-approach notebooks to allow for evaluation and comparison.
  - *NOTE* **VAE** and **smeared energy**: models are kept in one notebook, with changes indicated using `#` comments rather than being separated into different notebooks. This reflects the exploratory nature of these models and their use for further discussion.
  - The reduced ROOT file, *augmerged.root*, is included in each folder so that the notebooks can be executed if required.

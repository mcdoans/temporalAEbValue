# Temporal Acoustic Emission (AE) _b_-Value Analyses for Spalling Observation in Rock Tunnels using a Scale-Model Test
This repository provides Python codes for performing temporal acoustic emission analyses relevant to the studies by Wibisono and Gutierrez (2026), published in Rock Mechanics Bulletin.

This repository contains several Python Jupyter Notebook files designed as a short (and hopefully helpful) guide for performing temporal _b_-Value analyses for AE monitoring in laboratory testing. The code assess temporal deconstruction in AE monitoring for _b_-values, average frequency / peak amplitude (AF - AMP), and average frequency / rise time amplitude (AF/RA). This work supports studies by Wibisono (2024) and articles by Wibisono and Gutierrez.

## Cite
Please cite this dissertation and/or forthcoming papers if using this work for any purpose.  
- Wibisono (2024), *[Scale-Model Investigation of Brittle Tunnel Failure Using a True-Triaxial Device](https://repository.mines.edu/entities/publication/1c309126-0321-4467-939a-dbd497320013)*.  
- Wibisono and Gutierrez (2026), *[Identifying Acoustic Emission Precursors for Spalling in Rock Tunnels using a Scale-Model Test](https://doi.org/10.1016/j.ijrmms.2025.106247)*.  

## Notebooks
1. **Temporal _b_-values (`bval_GFT-ch3.ipynb`) and (`bval_MAXC-ch3.ipynb`)**
   - These notebooks provides an introductory example in performing temporal deconstruction in AE monitoring from base _b_-values calculation code provided by *[Lapin (2021)](https://doi.org/10.1029/2021JB021910)*. Two methods for estimating the magnitude of the completeness _M<sub>c</sub>_ are provided for comparison, as detailed in the paper:  GFT (goodness-of-fit tests) and MAXC (maximum curvature)

2. **Average Frequency and Peak Amplitude (AF-AMP) 3D Clustering Plot  (`forthcoming`)**

3. **Average Frequency and Rise Time Amplitude (AF/RA) 3D Clustering Plot and Quantification (`forthcoming`)**

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required packages (specified in each notebook), including:
  - `numpy`, `pandas`, and `math` for numerical computations
  - `matplotlib.pyplot` for plotting

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mcdoans/brittle-slip-lines.git

2. Open the notebooks in Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   
4. Locate your source sheet containing time (in second) and Amplitude (in dB) as the input. Adjust parameters as needed, following instructions within each notebook. 
5. Execute each cell sequentially to calculate and generate the Frequency Magnitude Distribution (FMD) and the temporal _b_-value plots.

## License
This project is licensed under the MIT License, allowing for free use, modification, and distribution. Please see the `LICENSE` file for full details.

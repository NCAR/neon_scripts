# Overcoming Barriers to Enable Convergence Research by Integrating Ecological and Climate Sciences

This repository contains scripts/notebooks associated with analyses presented in the paper (Overcoming barriers to enable convergence research by integrating ecological and climate sciences by Lombardozzi et al. 2023.
The purpose of this repository is to provide a resource and learning tool for creating figures and tables in support of this research paper.


## To reproduce these calculations:

1. First, clone the repository:

```
git clone neon_scripts
```

2. Build Conda Python environments:
```
conda env create -f environment.yml
conda activate neon_paper
```

3. Set paths for input data and model data, or alternatively run the preprocessor notebook. 

4. Follow the steps in each notebook to create the plots.

## Citation

If you use these codes or figures in your research, please cite the paper in which they appear. 

## Contents

The repository includes the following notebooks for re-creating plots and tables:

notebooks/fig3_neon_paper_climatology.ipynb : This notebook generates figure 3 wich includes climatology timeseries plots for this paper.                

notebooks/fig4_timeseries_selected.ipynb                    

notebooks/fig5_neon_paper_plots_spatial_maps.ipynb         

notebooks/fig6_neon_paper_diurnal_cycle_lh_components.ipynb

notebooks/fig7_neon_paper_light_use_boxplots.ipynb

notebooks/fig8_abby_smois.ipynb

notebooks/table1_neon_sites.ipynb  

notebooks/table2_neon_sites_characteristics.ipynb

Besides that, this repository include the following scripts for pre-processing files:

notebooks/neon_preprocessor.ipynb

## Contact

If you have any questions or comments, please feel free to create an issue on this github page or contact paper authors. 

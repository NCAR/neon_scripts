# neon_scripts


--------------
To install all required libraries:
```
conda create --name neon -c conda-forge python=3.9 numpy scipy matplotlib pandas netcdf4 jupyter xarray tqdm bokeh jupyterlab
conda activate neon
```

Then intall the utilities:

```bash
cd neon_scripts/notebooks
conda activate neon
pip install -e .
```
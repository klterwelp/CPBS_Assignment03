## Set up environment 
Make sure you have conda active and installed. Then use the following command to create the conda environment from the file in envs. 

```bash
conda env create -f "cpbs7602_environment_assignment03.yml" 
```

If using in Alpine follow these instructions to add kernel of this conda environment
```bash
conda activate cpbs7602_assignment03
conda install -y ipykernel
python -m ipykernel install --user --name cpbs7602_assignment03 --display-name cpbs7602_assignment03
```
Now you can select this kernel environment! 

## Run Code

### Dimension Reduction
01_dimension_reduction.ipynb notebook 

### Ensemble to Predict Tissue
02_ensemble_tissue.ipynb notebook

### Ensemble to Predict Age
03_ensemble_age.ipynb notebook 

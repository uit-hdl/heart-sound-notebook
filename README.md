# heart-sound-notebook

Jupyter notebook exploring heart sound features

## Assets

The sounds in `assets` directory come from https://deepblue.lib.umich.edu/handle/2027.42/120554


## Help

### Starting Jupyter

Run:
- `conda init`
- `conda activate heart-sound-notebook`
- `jupyter notebook` or `jupyter lab`

### Updating packages

- If updating packages with conda, remember to activate the environment first: `conda activate <environment-name>`
- To update the environment file: `conda env export > environment.yml`

### Git-bash for Windows users

- To use Git bash as console, use "<Your path>\Git\bin\bash.exe" --login-i
- In powershell run: `conda init bash`

### Creating a custom kernel in JupyterHub

- Activate the desired conda environment
- Install `ipykernel`: `conda install ipykernel`
- Create the kernel: `python -m ipykernel install --user --name <name> --display-name "<display name>"`
- Open the notebook (.ipynb) and change the kernel and make sure to check "Always start the preferred kernel".  
This change the kernelspec in the metadata. 
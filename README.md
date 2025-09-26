# heart-sound-notebook

Jupyter notebook exploring heart sound features.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/uit-hdl/heart-sound-notebook/HEAD?urlpath=%2Fdoc%2Ftree%2Fbasic_features.ipynb)


## Help

Just click on the badge above to launch to run the notebook in a virtual environment.
Once the container is built and loaded (it may take a few minutes), click on the `Restart the kernel and run all the cells` to generate the plots.

If you prefer to run locally or in JupyterHub, keep reading.

### Starting Jupyter

Run:
- `conda init`
- `conda env create -f environment.yml`
- `conda activate heart-sound-notebook`
- `jupyter notebook` or `jupyter lab`

### Updating packages

- If updating packages with conda, remember to activate the environment first: `conda activate <environment-name>`
- To update the environment file: `conda env export > environment.yml`

### Git-bash for Windows users

- To use Git bash as console in PyCharm, use "<Your path>\Git\bin\bash.exe" --login-i
- In powershell run: `conda init bash`

### Creating a custom kernel in JupyterHub

- Activate the desired conda environment
- Install `ipykernel`: `conda install ipykernel`
- Create the kernel: `python -m ipykernel install --user --name <name> --display-name "<display name>"`
- Open the notebook (.ipynb) and change the kernel and make sure to check "Always start the preferred kernel".  
This change the kernelspec in the metadata. 
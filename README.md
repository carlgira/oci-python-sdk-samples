# oci-python-sdk-samples
Just a few samples on how to use the OCI python sdk

This repository is the code used in this blog entry <TODO>
    
## Run notebook 

To run the notebook you need to install oci and jupyterlab, here are the instructions.
```
# Create your project directory
mkdir oci-python-sdk-samples
cd oci-python-sdk-samples

# Install virtualenv if you don't have it (you can also use conda)
pip install virtualenv

# Create the enviroment
virtualenv .oci-sdk-env

# Activate your env
source .oci-sdk-env/bin/activate

# Install OCI and jupyterlab
pip install oci jupyterlab

# Just in case, activate your env again
source .oci-sdk-env/bin/activate

# Launch jupyterlab
jupyter-lab
```

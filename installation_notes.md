# Tested 
```
# Create an Environment
mamba create -n ENV-NAME python=3.8

# Activate Environment
mamba activate ENV-NAME

# install ipykernel to be able to run Jupyter notebooks
mamba install ipykernel

# clone baby fork from caroline's github
git clone https://github.com/cmalinmayor/baby_fork.git

# go into directory with baby fork
cd baby_fork
pip install -e .

```

# Deprecated
```mamba create -n baby python=3.7
mamba activate baby
mamba install --file requirements.txt

pip install scikit-learn==0.22.2
pip install gaussianprocessderivatives
pip install .
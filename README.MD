# PK modelling quick prototype

## please do not use in production as it contains -very bad-, repetitive and non-pythonic code

### creates Conda environemnt `kp_model_env` from which all code in Jupyter can be executed

### run

```
git clone https://github.com/RhDm/kp_prototype.git
cd kp_prototype
conda env create -f environment.yml
conda activate kp_model_env
jupyter lab
```

### open `model_prototype.ipynb` in Jupyter and run the code

## please ignore sklearn's warnings
### (or disable them https://stackoverflow.com/questions/32612180/eliminating-warnings-from-scikit-learn)

<br>

### delete environment afterwards if not needed:
```
conda remove --name kp_model_env --all
```
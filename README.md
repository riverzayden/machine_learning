## 1. 세팅

```linux
conda create -n git_ml python=3.8
conda activate git_ml

conda install tensorflow-gpu

# jupyter kernel
conda install nb_conda
pip install ipykernel

# nb_extension
conda install -c conda-forge jupyter_contrib_nbextensions
pip install autopep8  ## autopep8 extension사용 위함
pip install jupyterthemes 
```


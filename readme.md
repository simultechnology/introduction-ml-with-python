
## prerequisite
```
python -m venv venv
source venv/bin/activate
```

## to start
```
jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user

jupyter notebook
```

install history

```
pip install --upgrade pip
pip install numpy scipy matplotlib ipython scikit-learn pandas pillow
pip install jupyter ipykernel jupyter-contrib-nbextensions jupyter-nbextensions-configurator
ipython kernel install --user --name=introduction-ml-with-python
```

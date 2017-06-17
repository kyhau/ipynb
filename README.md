# ipynb
Some test/demo code in ipynb.

## Setup local jupyter notebook (old name ipython notebook)

1. Install jupyter

```
pip install jupyter
```

2. Copy config to default config location

```
cp jupyter_notebook_config.py %USERPROFILE%\.jupyter\jupyter_notebook_config.py
```

3. Create Windows shortcut (e.g. Python 2.7 Target)
```
%COMSPEC% /K C:\Python27\Scripts\jupyter.exe notebook
```

## Use nbviewer to view the notebook

http://nbviewer.jupyter.org/

# Home

A basic Mac setup scenario.

* Install *Anaconda*
* Install *RStudio* from *Anaconda-Navigator*
* Create *Python 3.6* virtual environment -
```
conda create -n venv-3.6 python=3.6 anaconda
conda activate venv-3.6
```
* Install *TuriCreate* -
```
pip install -U turicreate
```
* Install *CoreML Tools* -
```
pip install -U coremltools
```
* Install *TF CoreML* -
```
pip install -U tfcoreml
```
* Install *TensorFlow* -
```
pip install -U tensorflow
```


Some *Anaconda* commands -
```
conda info --envs
conda deactivate
conda env remove -n ENV_NAME
```

How to remove *R CRAN* installed otherwise -
https://cran.r-project.org/doc/manuals/r-release/R-admin.html#Uninstalling-under-macOS
```
sudo rm -Rf /Library/Frameworks/R.framework /Applications/R.app \
   /usr/local/bin/R /usr/local/bin/Rscript
```

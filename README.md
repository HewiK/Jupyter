# Jupyter

## Install

### Installing Jupyter using Anaconda
I used this way to install Jupyter, because Anaconda includes Python, Jupyter, and other packages.
First, download Anaconda. We recommend downloading Anaconda’s latest Python 3 version.

* First download and install Anaconda. (Python 3.X recommended) https://www.anaconda.com/distribution/
* Second, install extra package to be able to run the Titanic Demo Notebook.
```
conda install -c anaconda py-xgboost
  ```
### Installing Jupyter with pip
You can install Jupyter with the Python’s package manager (pip) without Anaconda.
* For Python 3:
```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
  ```
* For Python 2:
```
python -m pip install --upgrade pip
python -m pip install jupyter
  ```
I would not recommend this, because you need to install all packages manually that are preinstalled with Anaconda.

## How to run Jupyter Notebook
To run the notebook, you can run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):
* Start Jupyter Notebook:
```
jupyter notebook
  ```
* Open specific Notebook:
```
jupyter notebook notebook.ipynb
  ```
* Open Notebook with specific Port
 ```
jupyter notebook --port 9999
  ```

## Further Documentation
* you can see all commands and more details in the [Documentation](https://jupyter-notebook.readthedocs.io/en/stable/) of Jupyter
* If you want to make your own Notebook to build models you can adapt the Titanic Demo to your needs.

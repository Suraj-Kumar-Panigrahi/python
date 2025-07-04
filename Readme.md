# Steps
## Create an environment
```python
conda create -p venv python==3.12
```

## Activate / deactivate
```python
conda activate / deactivate <path of venv>
```
## Install ipykernel
```python
pip install ipykernel
```

Different ways to create a virtual environment
```python
python -m venv <folder path>

<folder-path>\Scripts\activate
```
```python
pip install virtualenv

virtualenv -p pytho3 virtual_env_name

virtual_env_name\Scrips\activate\
```
```python
# Needs anaconda
conda create -p venv python==<version> -y

```
# ROAD contest

## Dataset

Dataset can be downloaded from [this repo](https://github.com/gurkirt/road-dataset). You can place the dataset wherever you want (maybe on a dedicated drive, since it consists of several GBs). From now on, we assume you have a symlink to the `road` dataset folder:
```bash
ln -s <road dataset>/road dataset
```

## Initialization

Create a virtualenv and install required packages:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip3 install requirements.txt
```


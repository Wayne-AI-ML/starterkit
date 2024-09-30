# Starterkit for AIML

This repo provides environment setup configs for AIML practitioners to quickly setup their new environment. We assume the platform is Linux.

## How to use this

1. Install miniconda

```bash
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm ~/miniconda3/miniconda.sh
```

2. Create conda environment

```bash
conda env create -f conda_env.yml
```

3. Install Python libraries

```bash
pip install -r pip_env.txt
```

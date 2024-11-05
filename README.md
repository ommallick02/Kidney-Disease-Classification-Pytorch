
# Kidney-Disease-Classification-Pytorch

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

## How to run?

### STEP 01 - Clone the repo

```bash
https://github.com/ommallick02/Kidney-Disease-Classification-Pytorch
```
### STEP 02 - Create and activate a conda environment after opening the repository

```bash
conda create -n kidney-pytorch python=3.10 -y
```

```bash
conda activate kidney-pytorch
```

### STEP 03 - Install the requirements

Install CUDA 12.4

```bash
https://developer.nvidia.com/cuda-12-4-0-download-archive
```

Install Pytorch

```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

```bash
pip3 install -r requirements.txt
```

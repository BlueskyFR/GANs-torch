# GANs with PyTorch

## Environment setup

Using conda + mamba:

```bash
mamba create -n torch python=3.10
conda activate torch
pip install --pre light-the-torch
ltt install torch
pip install ipython jupyter pyzmq
pip install torchvision torchaudio torchmetrics torchdata
mamba install -c conda-forge accimage # Not available on pip
python -c "import torch; print('PyTorch is using CUDA version', torch.version.cuda)"
```
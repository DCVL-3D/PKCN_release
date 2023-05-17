## Installation

We have tested the code on Ubuntu 18.04 and Cuda 11.3 with Python 3.9

```python
conda create -n PKCN python=3.9
conda activate PCKN  
conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio==0.10.1 cudatoolkit=11.3 -c pytorch -c conda-forge
```

PyTorch3D library is installed according to the instructions in https://github.com/facebookresearch/pytorch3d/blob/main/INSTALL.md

```python
conda install -c fvcore -c iopath -c conda-forge fvcore iopath
conda install pytorch3d -c pytorch3d
```

 ***requirment.txt file will be released with the entire code***

```python
cd PKCN
pip install -r requirment.txt
```




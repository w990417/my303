# Data 303
DATA303-Advanced Machine Learning: generative AI @ Korea University

1. [Image generation by Gaussian](https://github.com/mlvlab/data303/blob/main/Image_Generation_by_Gaussian.ipynb)
2. [Image generation by VAE](https://github.com/mlvlab/data303/blob/main/Image_Generation_by_VAE.ipynb)



## packages
### pytorch installation

for pytorch installation, refer to https://pytorch.org/get-started/locally/


for windows (RTX 3060 Ti):
```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```

for mac (M1):
```bash
conda install pytorch torchvision torchaudio -c pytorch
```

### reqirements.txt
requirements.txt lists imported python packages for each platform (windows, mac)
note that it does not list all the packages in the environment, but only the packages that are imported in the notebooks.
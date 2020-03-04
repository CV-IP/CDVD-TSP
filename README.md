# CDVD-TSP
#### [Paper](https://github.com/csbhr/CDVD-TSP) | [Project Page](https://github.com/csbhr/CDVD-TSP)
### Cascaded Deep Video Deblurring Using Temporal Sharpness Prior
By [[Jinshan Pan](https://jspan.github.io/)], [[Haoran Bai](https://csbhr.github.io/)], [Jinhui Tang]

### Updates
[2020-03-04] Testing codes are available!

## Dependencies

- Linux (Tested on Ubuntu 18.04)
- Python 3 (Recommend to use [Anaconda](https://www.anaconda.com/download/#linux))
- [PyTorch 0.4.1](https://pytorch.org/): `conda install pytorch=0.4.1 torchvision cudatoolkit=9.2 -c pytorch`
- numpy: `conda install numpy`
- matplotlib: `conda install matplotlib`
- opencv: `conda install opencv`
- imageio: `conda install imageio`
- skimage: `conda install scikit-image`
- tqdm: `conda install tqdm`
- cupy: `conda install -c anaconda cupy`

## Get Started
### Download
- Pretrained models and Datasets can be downloaded from [Here](https://pan.baidu.com/s/1aVfLcPWpaqt8ljqXGJXRig).
- If you have to download pretrained models，please put them to './pretrain_models'.
- If you have to download datasets，please put them to './dataset'.

### Testing
#### Quick test
1. Download the pre-trained models.
2. Download the testing datasts.
3. Run `python ./code/inference.py --default_data DVD`
  - Argument default_data: the dataset you want to test, optional: DVD, GOPRO
4. The deblured result will be in './infer_results'.
#### Test your own data
1. Download the pre-trained models.
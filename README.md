# ISIE-Net

## Code for the paper "Dual Supervised Network Based on irrelevant information suppression and critical information enhancement for Image Forgery Detection"
<div align="center">
  <img src="https://github.com/ginwins/ISIE-Net/blob/master/images/ISIE-Net.jpg">
</div>

# Environment
- Ubuntu18.04
- Python 3.8
- PyTorch  1.9.0 + Cuda  11.1
- Detail python librarys can found in [requirements.txt](./requirements.txt)

# Dataset
An example of the dataset index file is given as  [data/Casisv1.txt](./data/Casiav1.txt), where each line contains:

`img_path mask_path label`  
- 0 represents the authentic and 1 represents the manipulated.
- For an authentic image, the mask_path is "None".
- For wild images without mask groundtruth, the index should at least contain "img_path" per line.

## Training sets
[CASIAv2](./data/mydata.txt)

## Test sets
[CASIAv1](./data/Casiav1.txt)
[Columbia](./data/Columbia.txt)
[COVERAGE](./data/COVERAGE.txt)
[nist16](./data/nist16.txt)

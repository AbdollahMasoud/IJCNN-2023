# Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbdollahMasoud/IJCNN-2023/blob/main/IJCNN_2023.ipynb) [![IEEE Xplore](https://img.shields.io/badge/IEEE_Xplore-blue)](https://ieeexplore.ieee.org/document/10191163) [![arXiv](https://img.shields.io/badge/arXiv-2304.12729-b31b1b.svg?style=flat)](https://arxiv.org/abs/2304.12729)

This repository contains the dataset and code used in the paper "**Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods**". The peer-reviewed paper was presented at The 2023 International Joint Conference on Neural Networks (IJCNN) and published on [IEEE Xplore](https://ieeexplore.ieee.org/document/10191163). 

## Code
The code was developed using Google Colaboratory. A Google account is needed to execute it. Alternatively, you may follow the structure of the provided [IJCNN_2023.ipynb](https://github.com/AbdollahMasoud/IJCNN-2023/blob/main/IJCNN_2023.ipynb) to write your own code and run it using an offline compiler.

## Dataset
This dataset contains a selection of radio sources from the [Best–Heckman sample](https://academic.oup.com/mnras/article/421/2/1569/1141939), manually labeled by [Ma *et al*](https://iopscience.iop.org/article/10.3847/1538-4365/aaf9a2/meta). The radio images were taken from the FIRST and NVSS surveys. The dataset includes three classes: FRI, FRII, and FR0 (compact sources). The images were converted from their original FITS format to grey-scale images in JPG format to allow easier data handling. The only preprocessing step applied to the dataset (as it appears in the repo), for each image, was to set pixels with a magnitude under $\mu+3\sigma$ to zero.

## References
More information can be found in [the paper](https://ieeexplore.ieee.org/document/10191163) or [the preprint](https://arxiv.org/abs/2304.12729).  
For questions and suggestions feel free to email me at: adarya@sharjah.ac.ae

### Citation
Please cite this work as follows:

```
@inproceedings{darya2023morphological,  
  title={Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods},  
  author={Darya, Abdollah Masoud and Fernini, Ilias and Vellasco, Marley and Hussain, Abir},  
  booktitle={2023 International Joint Conference on Neural Networks (IJCNN)},   
  year={2023},  
  volume={},  
  number={},  
  pages={1-8},  
  doi={10.1109/IJCNN54540.2023.10191163}  
}
```

# Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods

This Repo contains the dataset and code used in the paper "**Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods**". The paper was peer-reviewed and accepted for presentation at The 2023 International Joint Conference on Neural Networks (IJCNN). 

## Code
The code was developed using Google Colaboratory [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbdollahMasoud/IJCNN-2023/blob/main/IJCNN_2023.ipynb).   
A Google account is needed to execute it. Alternatively, you may follow the structure of the provided [IJCNN_2023.ipynb](https://github.com/AbdollahMasoud/IJCNN-2023/blob/main/IJCNN_2023.ipynb) to write your own code and run it using an offline compiler.

## Dataset
This dataset contains a selection of radio sources from the Best–Heckman sample, manually labeled by [Ma *et al*](https://iopscience.iop.org/article/10.3847/1538-4365/aaf9a2/meta). The radio images were taken from the FIRST and NVSS surveys. The dataset includes three classes: FRI, FRII, and FR0 (compact sources). The images were converted from their original FITS format to grey-scale images in JPG format to allow for easier data handling. The only preprocessing step applied to the dataset (as it appears in the repo) was to set pixels with a magnitude under $\mu+3\sigma$ to zero, for each image.

## References
More information can be found from [the preprint](https://arxiv.org/abs/2304.12729).  
For questions and suggestions feel free to email me at: adarya@sharjah.ac.ae

### Citation
Please cite this work as follows:

@misc{darya2023morphological,  
      title={Morphological Classification of Extragalactic Radio Sources Using Gradient Boosting Methods},  
      author={Abdollah Masoud Darya and Ilias Fernini and Marley Vellasco and Abir Hussain},  
      year={2023},  
      eprint={2304.12729},  
      archivePrefix={arXiv},  
      primaryClass={astro-ph.IM}  
}  

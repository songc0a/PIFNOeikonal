# PIFNOeikonal
This repository will release the codes related to the paper "Seismic traveltime simulation for variable velocity models using physics-informed Fourier neural operator" submitted to IEEE TGRS.

# Software requirement
Python Version: 3.8.16

Pytorch Version: 2.0.0+cu117

# Code explanation

PIFNO_eikonal_example.ipynb: Solving the eikonal equation using PIFNO for various models from OpenFWI.

FMM_T_T0.ipynb: Generate reference traveltimes and background traveltimes using FMM.

# Overview

We have developed an innovative multi-source seismic traveltime simulation method adaptable to various velocity models, employing an advanced deep-learning technique known as the physics-informed Fourier neural operator (PIFNO).
![curvelet50_train_T](https://github.com/user-attachments/assets/5848bd23-cda4-431a-8746-320893c8191a)
Training data from the CurveVel-A family: velocity models (first column), numerical traveltime from FMM (second column), predicted traveltime from PIFNO (third column), and traveltime difference (fourth column) for a source in the middle.


# Citation information

If you find our codes and publications helpful, please kindly cite the following publications.

@article{song2024pinnpstomo,

  title={Seismic traveltime simulation for variable velocity models using physics-informed Fourier neural operator},
  
  author={Song, Chao and Zhao, Tianshuo and Waheed, Umair bin and Liu, Cai},
  
  journal={arXiv preprint arXiv:2311.03751},
  
  year={2023}
  
  year={2024}
}

# contact information
If there are any problems, don't hesitate to get in touch with me through my emails: chao.song@kaust.edu.sa;chaosong@jlu.edu.cn

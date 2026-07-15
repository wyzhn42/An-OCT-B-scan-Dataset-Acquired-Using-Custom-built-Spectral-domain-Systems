# An Optical Coherence Tomography (OCT) B-scan Dataset Acquired Using Custom-built Spectral-domain Systems [sample]

**This is a sample repository. For the full dataset, please go to: [10.57760/sciencedb.43262](https://doi.org/10.57760/sciencedb.43262) for dataset files and [10.3788/AI.2025.10026](https://doi.org/10.3788/AI.2025.10026) for more information.**

## Overview

This repository contains our self-acquired optical coherence tomography (OCT) B-scan datasets supporting the study:

> Weiyi Zhang, Haoran Zhang, Qi Lan, Chang Liu, Zheng Li, Chengfu Gu, and Jianlong Yang,
> *Self-supervised PSF-informed deep learning enables real-time deconvolution for optical coherence tomography*,
> Advanced Imaging, 2025. https://doi.org/10.3788/AI.2025.10026

The datasets were collected using our custom-built spectral-domain OCT systems under multiple imaging conditions and were used for the development and evaluation of a self-supervised deep-learning framework for real-time OCT image deconvolution.

---

# Relationship to the Associated Publication

To maximize data availability and facilitate future research, this repository includes not only the image subsets used in the published experiments but also additional acquisitions collected under the same imaging protocols. Some commercial prototype data mentioned in the original paper are excluded because of confidentiality agreements with the equipment provider. Public datasets referenced in our publication are available from their original repositories and are therefore not redistributed in this repository. 

| Object                           | Waveband (nm) | Imaging Optics | Acquisition Condition | Repository Status                       |
| -------------------------------- | ------------- | -------------- | --------------------- | --------------------------------------- |
| Gold nanoparticles               | 840           | Free-space     | Ex vivo               | Released                                |
| Laser viewing card               | 840           | Free-space     | Ex vivo               | Released                                |
| Human eye                        | 1060          | Free-space     | In vivo               | Not released                            |
| Orange slice                     | 840           | Free-space     | Ex vivo               | Released                                |
| Organoid                         | 840           | Free-space     | Ex vivo               | Released                                |
| Swine artery                     | 1310          | Endoscopic     | In vivo               | Available from the original publication |
| Swine artery (commercial system) | 1310          | Endoscopic     | In vivo               | Available from the original publication |
| Human retina (OCTA-500)          | 840           | Free-space     | In vivo               | Available from the original publication |
| Rabbit retina                    | 840           | Free-space     | In vivo               | Released                                |

---


# Folder Structure

```
Dataset/
│
├── 1_gold_nanoparticle/
│
├── 2_laser_viewing_card/
│
├── 4_orange_slice/
│
├── 5_organoid/
│
└── 9_rabbitretina/
```

Unless otherwise specified,

- Image type: OCT B-scan
- Image format: png
- Grayscale
- Original acquisition resolution

No preprocessing, denoising, deconvolution, or annotation has been applied to the released images unless explicitly stated.

---

# Citation

If you use this dataset in your research, please cite both this dataset and the associated publication.

> Weiyi Zhang, Haoran Zhang, Qi Lan, Chang Liu, Zheng Li, Chengfu Gu, Jianlong Yang. Self-supervised PSF-informed deep learning enables real-time deconvolution for optical coherence tomography[J]. Advanced Imaging, 2025, 2(2): 021001

```
@article{zhang2025self,
  title={Self-supervised PSF-informed deep learning enables real-time deconvolution for optical coherence tomography},
  author={Zhang, Weiyi and Zhang, Haoran and Lan, Qi and Liu, Chang and Li, Zheng and Gu, Chengfu and Yang, Jianlong},
  journal={Advanced Imaging},
  volume={2},
  number={2},
  pages={021001}
}
```

---

# License

Please use this dataset only for research and educational purposes.

Commercial use is prohibited unless prior permission is obtained from the copyright holders.

---

# Contact

Corresponding author:

Jianlong Yang

School of Biomedical Engineering

Shanghai Jiao Tong University

Email:
jyangoptics@gmail.com

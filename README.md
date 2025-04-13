# Data-Science-Project
Project Ownership
Nawfal Khan Basheer Mohamed
Student ID: 23025098
University of Hertfordshire

# Derivative Acknowledgment
This project is a derivative work based on open-source projects and academic research listed above.
There are no additional contributors; all development, adaptation, and experimentation were done independently.

##  Paper References

1. **Mehta, S. et al. (2022)**  
   *Simple and Efficient Architectures for Semantic Segmentation*  
   [CVPRW 2022 Paper (PDF)](https://openaccess.thecvf.com/content/CVPR2022W/ECV/papers/Mehta_Simple_and_Efficient_Architectures_for_Semantic_Segmentation_CVPRW_2022_paper.pdf)

2. **Arulananth, T. S. et al. (2024)**  
   *Semantic Segmentation of Urban Environments: Leveraging U-Net Deep Learning Model for Cityscape Image Analysis*  
   [PLOS ONE Article](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0300767)

3. **Anonymous (2023)**  
   *Urban Scene Semantic Segmentation Using the U-Net Model*  
   [Conference Paper (PDF)](https://annals-csis.org/proceedings/2023/drp/pdf/3686.pdf)

4. **Anonymous (2024)**  
   *On the Effect of Image Resolution on Semantic Segmentation*  
   [arXiv Preprint](https://arxiv.org/html/2402.05398v1)

5. **Anonymous (2025)**  
   *Enhanced UNet Algorithm with Attention Mechanism and Deformable Convolution for Semantic Segmentation*  
   [PMC Article](https://pmc.ncbi.nlm.nih.gov/articles/PMC11737789/)

6. **Papers With Code**  
   *Semantic Segmentation on Cityscapes*  
   [Cityscapes Benchmark](https://paperswithcode.com/sota/semantic-segmentation-on-cityscapes)


## Code References

- **kerrgarr / SemanticSegmentationCityscapes**  
  [GitHub Repository](https://github.com/kerrgarr/SemanticSegmentationCityscapes.git)  
  Referenced for dataset preprocessing and baseline segmentation framework setup.

- **deepmancer / unet-semantic-segmentation**  
  [GitHub Repository](https://github.com/deepmancer/unet-semantic-segmentation.git)  
  Used as reference for U-Net architecture and training loop structure.

- **akyadav26 / Semantic-Segmentation-on-CityScapes-Dataset**  
  [GitHub Repository](https://github.com/akyadav26/Semantic-Segmentation-on-CityScapes-Dataset.git)  
  Referenced for evaluation techniques and implementation guidance on Cityscapes.

- **meng1994412 / ResNet_from_scratch**  
  [GitHub Repository](https://github.com/meng1994412/ResNet_from_scratch.git)  
  Used for constructing ResNet blocks from scratch for integration into U-Net.

# ResNet vs. U-Net Image Segmentation on the Cityscapes Dataset

This repository presents a project built from scratch to compare segmentation models for road segmentation on urban scenes using the Cityscapes dataset. The project evaluates **ResNet-based U-Net** and **U-Net** using key performance metrics—specifically, Intersection over Union (IoU).

---

## Introduction

Segmentation is a crucial task in the fields of autonomous driving and urban scene analysis. In this project, two segmentation architectures are evaluated:

- **U-Net:** An encoder-decoder architecture with skip connections that preserves spatial details while incorporating global context.
- **ResNet-based U-Net:** An enhanced version of U-Net that replaces the standard encoder with a ResNet, utilizing residual learning to improve feature extraction and training stability.

The goal is to determine which architectural design better suits road segmentation tasks under real-world conditions.

---

## Research Question

**How do the segmentation performance metrics (IoU, etc.) of ResNet-based U-Net, U-Net, and other segmentation models compare when applied to road segmentation using the Cityscapes dataset?**

---

## Dataset

The project employs the [Cityscapes dataset](https://www.cityscapes-dataset.com/), known for:
- **High-resolution images** of urban environments.
- **Pixel-level annotations** suitable for semantic segmentation tasks.
- **Predefined training, validation, and test splits** for standardized.
## Models

### U-Net
An encoder-decoder model with skip connections that helps recover fine-grained spatial details while learning high-level features.

### ResNet-based U-Net
A variant of U-Net where the encoder is replaced by a ResNet backbone, leveraging residual connections to enhance feature learning.


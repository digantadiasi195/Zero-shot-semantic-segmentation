# Zero-Shot Semantic Segmentation (ZS3)

## Team
- **Tarun Kumar**
- **Diganta Diasi**
- **Major Vaibhav Mishra**
- **Anjali Jaiswal**
- **Aman Kumar Prasad Gond**

## Abstract
This project aims to develop a novel model for Zero-Shot Semantic Segmentation (ZS3), focusing on segmenting objects in images into categories without prior training on those specific classes. By leveraging both visual and auxiliary information, our model addresses limitations of existing approaches, providing applications in fields where labeled data is scarce or costly.

## Introduction
**Zero-Shot Learning (ZSL):** A technique where models classify data into unseen classes using auxiliary information like attributes or semantic embeddings.

**Semantic Segmentation:** The process of classifying each pixel in an image into a class, offering precise object detection by pixel-level classification.

**Zero-Shot Semantic Segmentation (ZS3):** Involves segmenting objects without prior training on specific categories, using external information or embeddings to bridge the gap between seen and unseen classes.

## Related Works
1. **Shape-Aware Zero-Shot Segmentation (SAZS):** Uses vision-language alignment and Laplacian matrix eigenvectors for segmenting images.
2. **Context-aware Feature Generation (CaGNet):** Utilizes semantic word embeddings and pixel-wise contextual information for zero-shot segmentation.
3. **Decoupling Zero-Shot Semantic Segmentation (ZegFormer):** Employs class-agnostic grouping and segment-level zero-shot classification.
4. **ZS3Net:** Combines visual segmentation with semantic word embeddings for classifying objects based on textual descriptions.
5. **ZegCLIP:** Extends CLIP’s zero-shot capability to pixel-level classification with modifications like Deep Prompt Tuning and Relationship Descriptor.

## Proposed Work
We propose a method integrating visual encoding, shape delineation, and spectral decomposition using Singular Value Decomposition (SVD). Our approach uses CLIP to unify visual and spectral features, followed by a Multi-Layer Perceptron (MLP) for zero-shot segmentation.

## Experimental Details
**Datasets:**
- Pascal-VOC 2012: 1,464 training images with 20 object classes.
- Pascal-Context: 4,998 training and 5,105 validation images with 59 classes.

**Training Details:**
- Focused on ZS3Net and ZegCLIP models with adaptation for Pascal-VOC dataset.
- Challenges include outdated library compatibility and dataset limitations.

## Results
**Performance Metrics:**
- Evaluated on pixel accuracy (PA), mean accuracy (MA), and mean intersection-over-union (mIoU).

**Preliminary Findings:**
- ZS3Net showed promising results despite dataset and compatibility issues.
- ZegCLIP faced challenges with outdated libraries, affecting full implementation.

## Conclusion
Our approach demonstrates a sophisticated pipeline for zero-shot segmentation, integrating visual, shape, and spectral data. Despite implementation challenges, the project is ongoing with promising results and potential for future advancements.

---

Feel free to adjust or expand on any section as needed!

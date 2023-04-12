---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

* **Surgical Visual Question Answering on large-scale surgical video dataset** \| Jul 2022 – Mar 2023
  * The existing datasets on Laparoscopic Cholecystectomy are used to create a VQA dataset which contains
questions that deal with detection, counting, localization, spatial relationship and surgical action in an image of
Cholecystectomy procedure.
  * The developed method involves developing a DeepLabv3-based segmentation model, and a Yolov5-based tool
detection model to generate surgical scene graphs, which is ingested by a Question Generation engine to generate
question-anwer pairs.
  * Classification-based VQA model is trained on VisualBERT-based architecture.

* **Weakly-supervised Cell detection for Cytotoxicity Standardization** \| [Code](https://github.com/manasikattel/SISSI) \| [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16852-9_10) \| Mar 2022 – Jul 2022
  * Best Paper award at the Domain Adaptation and Representation Transfer Workshop, MICCAI 2022.
  * Image-level weak labels are used to perform the cell-type detection required for ISO 10993-5 standard reactivity of
Cytotoxicity. The statistical measures of extracted cells reveal the sought reactivity.
  * Our approach involves a Faster-RCNN architecture which is trained using the pseudo-labels obtained from
handcrafted methods along with the image examples of living, dead, and inhibited cells.

* **Skin lesion classification** \| [Code](https://github.com/manasikattel/skin-lesion-cad) \| [Presentation](/files/CAD_presentation.pdf) \| Sep 2022 - Jan 2023
  * This project(also a challenge) deals with the classification of skin lesions into 1. Nevus vs. other (Binary problem) 2. Basal cell vs. Squamous cell vs. Melanoma using both classical image processing techniques and deep learning techniques. 
  * Classical image preprocessing involves hair removal. Morphological Segmentation pipeline is defined to segment the lesions. Colour, Shape, and Bag-of-words features were engineered and different machine learning classifiers were experimented with.
  * For the Deep learning challenge, RegNet and Swin Transformers were trained and tuned for skin lesion classification. Experiments conducted include several augmentation strategies, model sizes, balanced sampling, loss functions, and pretext learning with eight classes present in the binary challenge dataset.
  * Winner in the binary classification problem for both classical approach and deep learning based solution.
  * Supervised by Prof. Xavier Lladó Bardera at the University of Girona, Spain

* **Brain Tissue Segmentation on IBSR dataset** \| [Code](https://github.com/manasikattel/misa)\| Sep 2022 -- Jan 2023
* Data augmentation and registration driven experiments with an ensemble-based nn-UNet model to segment tissues in Brain MRI images.
* A mix of original, preprocessed, and registered images are utilized to incorporate global data variance and spatial information of the three tissue models in the training set. 
* Ranked second on a private leaderboard for course Medical Image Segmentation.
* Supervised by Prof. Arnau Oliver at the University of Girona, Spain.

* **Chest CT Registration between inhale and exhale breathing phases** \|  [Code](https://github.com/manasikattel/chest_ct_registration) \| Sep 2022 -- Jan 2023
* Experimented with different aspects of the registration framework: similarity metric, geometric transformation, interpolation and resolutions, and the impact of preprocessing and segmentation.
 * Supervised by Prof. Robert Martí at the University of Girona, Spain.


* **Morphologically Consistent Eye Vessel Segmentation** \| [Code](https://github.com/manasikattel/Eye-Vessel-Segmentation) \| Sep 2021 – Dec 2021
  * Performed eye vessel segmentation on retinopathy images to extract vessels’ morphology which plays a vital role
in detecting many diseases including Diabetes, Glaucoma, and Hypertension.
  * Developed a method that involved two sequential steps: (i) morphological image processing for local shape priors;
and (ii) matched filter based global shape prior between a known template and the input morphological structure.

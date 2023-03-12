---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

* Surgical Visual Question Answering on large-scale surgical video dataset || Python Jul 2022 – Mar 2023
  * The existing datasets on Laparoscopic Cholecystectomy are used to create a VQA dataset which contains
questions that deal with detection, counting, localization, spatial relationship and surgical action in an image of
Cholecystectomy procedure.
  * The developed method involves developing a DeepLabv3-based segmentation model, and a Yolov5-based tool
detection model to generate surgical scene graphs, which is ingested by a Question Generation engine to generate
question-anwer pairs.
  * Classification-based VQA model is trained on VisualBERT-based architecture.
  * Supervised by Prof. Nicolas Padoy at the CAMMA Lab, University of Strasbourg, France.

* [Weakly-supervised Cell detection for Cytotoxicity Standardization](https://github.com/manasikattel/SISSI) || Python Mar 2022 – Jul 2022
  * Best Paper award at the Domain Adaptation and Representation Transfer Workshop, MICCAI 2022.
  * Image-level weak labels are used to perform the cell-type detection required for ISO 10993-5 standard reactivity of
Cytotoxicity. The statistical measures of extracted cells reveal the sought reactivity.
  * Our approach involves a Faster-RCNN architecture which is trained using the pseudo-labels obtained from
handcrafted methods along with the image examples of living, dead, and inhibited cells.
  * Supervised by Prof. Alessandro Bria and Prof. Claudio Marrocco at the University of Cassino, Italy.

* [Skin lesion classification](https://github.com/manasikattel/skin-lesion-cad) || Python Sep 2022 - Jan 2023
  * This project(also a challenge) deals with the classification of skin lesions into 1. Nevus vs. other (Binary problem) 2. Basal cell vs. Squamous cell vs. Melanoma using both classical image processing techniques and deep learning techniques. 
  * Winner in the binary classification problem for both classical algorithm and deep learning based solution.


* [Morphologically Consistent Eye Vessel Segmentation](https://github.com/manasikattel/Eye-Vessel-Segmentation) || Matlab Sep 2021 – Dec 2021
  * Performed eye vessel segmentation on retinopathy images to extract vessels’ morphology which plays a vital role
in detecting many diseases including Diabetes, Glaucoma, and Hypertension.
  * Developed a method that involved two sequential steps: (i) morphological image processing for local shape priors;
and (ii) matched filter based global shape prior between a known template and the input morphological structure.
  * Supervised by Prof. Fabrice Meriaudeau at the University of Burgungy, France.
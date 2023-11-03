# **nrsc510atubemap**

Welcome to the NRSC510A Tubemap repository! This repository is dedicated to a research project focused on understanding the impact of low-density lipoproteins (LDL) on vascular pathologies in Alzheimer's Disease (AD) mouse models. This README provides an overview of the project, its significance, research question, and work plan.

## Background

It is well-established that elevated low-density lipoproteins (LDL), commonly referred to as "bad cholesterol," are causally related to cardiovascular diseases, including atherosclerosis, stroke, hypertension, and coronary artery disease (1). Successful management of cardiovascular risk factors, including LDL-lowering therapies, is associated with a reduced risk of dementia (2-4). On the other hand, higher LDL-cholesterol levels are linked to an increased risk of Alzheimer's Disease (AD) (5). Most AD patients have evidence of cerebrovascular pathologies upon autopsy (3, 6). Understanding how these cardiovascular risk factors affect vascular contributions to cognitive impairment and dementia (VCID) and AD pathology is of utmost importance.

Studying these effects in vivo is challenging, as commonly used AD research mice are naturally deficient in the cholesteryl ester transfer protein (CETP) and have a high-density lipoproteins (HDL) to LDL ratio unlike humans. Therefore, to better understand the impact of LDL in AD, this project crosses commercially available CETP transgenic mice with mice that have five familial AD mutations (5xFAD mice).

## Research Question

How does reconstitution of CETP expression affect vascular pathologies in AD mouse models?

## Significance

This project aims to increase the translational value of AD mouse model studies by utilizing commercially available CETP transgenic mice, which have a higher LDL to HDL ratio. The goal is to gain insights into how LDL affects vascular pathology in AD, ultimately contributing to a better understanding of the disease.
Work Plan

Our work involves using light sheet microscopy of cleared brains to preserve native tissue morphology and facilitate 3D mapping of cerebrovasculature. To analyze this 3D data effectively, we use the TubeMap processing pipeline, which addresses imaging artifacts, the multi-scale nature, and the hollow tube structure of the vasculature (7). TubeMap is written in Python and utilizes several libraries, including graph-tool, pyopengl, natsort, tifffile, opencv, pyqtgraph, cython, matplotlib, scipy, scikit-image, scikit-learn, pytorch, and pandas.

## Project Milestones

Running the Tubemap pipeline with the tutorial data from the original manuscript deposited at the OSF. It contains raw 3D scans and autofluorescence data from two C57Bl6 mice hemispheres. Vessels were immunolabeled against podocalyxin, cluster of differentiation 31, and actin alpha 2.

We are excited about the potential insights this research will provide and look forward to sharing our findings and progress through this repository.

If you have any questions, suggestions, or are interested in collaborating, please feel free to reach out to us. Thank you for your interest in our research project!

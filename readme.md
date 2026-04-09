# MMAI (6.S985) Spring 2026 

This repository is a collection of the coursework for Multimodal AI (Prof. Paul Liang, MIT 6.S985, Sp26).

In general we seek to identify a multimodal architecture that allows understanding and prediction of atmospheric/oceanic flows, i.e. an ocean foundation model. We focus on simplified 2D quasigeostrophic flows.

In particular we consider a VLM style model that integrates diffusion models for 2D fluid flow and LLM-based text encoders for PDE conditioning (and output).
Most project code can be found the in the main project repository ![](https://github.com/akhilsadam/autoencoders) and the scientific domain code repository (currently includes PDE encoders as well) ![](https://github.com/akhilsadam/qg).

A short description of the assignments follow:
- hw1: We generate three sample flows and try to identify local PCA features with a TSNE transformation
- hw2: We investigate fusion and alignment between high and low-resolution fields, and local vs global representations in a diffusion model for one of the flows.
- hw3: We investigate finetuning a Qwen VLM to find the simulation time of the PDE and intrinsic dimension, or roughly where it is located in the low-dimensional manifold.
CAS Diffusion Acceleration (Course Project)

This repository contains my implementation and experiments for a course project focused on accelerating diffusion model inference. The project is based on an existing open-source repository, with modifications made for experimentation and evaluation.

Original Repository

This work is based on the following open-source project:

AdaptiveDiffusion
https://github.com/InternScience/AdaptiveDiffusion

Most of the implementation in this repository originates from the above project. Full credit for the original implementation belongs to the original authors.

This repository is not intended to claim authorship of the original work, but instead documents the modifications made for academic experimentation.

Files Modified

For the purpose of this course project, I modified specific files in the original repository.

1. sparse_pipeline.py / cas_sparse_pipeline.py

Location:

AdaptiveDiffusion/examples/AdaptiveDiffusion/acceleration/sparse_pipeline.py

Modifications include:

Implementing changes related to the CAS acceleration idea

Modifying the diffusion inference pipeline

Adjusting step skipping / reuse behavior for faster generation

Integrating the modified pipeline with the generation script

Experiments

The experiments performed in this project include:

Text-to-image generation using Stable Diffusion v1.5

Comparison between:

Baseline method:

DDIM sampling

Proposed method:

CAS-based accelerated diffusion pipeline

Evaluation metrics:

FID (Fréchet Inception Distance)

Image generation time

The evaluation is conducted by generating images from text prompts (e.g., COCO captions).

Purpose of This Repository

This repository is provided for course project submission and reproducibility.
It demonstrates how the original implementation was adapted and modified to evaluate diffusion acceleration methods.

Disclaimer

The original implementation belongs to the authors of the AdaptiveDiffusion repository.
My contribution in this repository is limited to the modifications described above.

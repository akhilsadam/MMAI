# hw3
 We investigate finetuning a Qwen VLM to find the simulation time of the PDE and intrinsic dimension, or roughly where it is located in the low-dimensional manifold.

We find that in general it performs quite poorly, even with instruction-based finetuning, fewshot prompting and more tricks. Poor performance is possibly because the Qwen VLM is designed for natural images with less fine-scale structure, and doesn't include a diffusion model.
See the notebook for details.
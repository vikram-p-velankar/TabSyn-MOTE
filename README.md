# TableDiffusion

This is the supporting code for the paper [Enhancing Classification of Imbalanced Data using Diffusion Process.]([https://www.techrxiv.org/users/757062/articles/729160-enhancing-classification-of-imbalanced-data-using-diffusion-process]).

The goal of the TabSyn-MOTE project is to provide generative models for sensitive tabular data that are differentially-private. Enabling data synthesis that preserves the original dataset's statistical characteristics while protecting individual privacy and balancing the data for deep learning models is the aim.

The most notable model from this work is `TabSyn-MOTE`, the first differentially-private diffusion model for tabular data. See [tablediffusion/models/table_diffusion.py](tablediffusion/models/table_diffusion.py)

> :warning: **Disclaimer**: This the source code is meant for research purposes only and is not ready for production use. Because of seed and sampler settings that are inappropriate for a production context, the current implementation might not maintain privacy assurances.


## Citing this work

Truda, Gianluca. "Generating tabular datasets under differential privacy." arXiv preprint arXiv:2308.14784 (2023).

```
@article{truda2023generating,
  title={Generating tabular datasets under differential privacy},
  author={Truda, Gianluca},
  journal={arXiv preprint arXiv:2308.14784},
  year={2023}
@article{truda2023generating,
  title={Mixed-Type Tabular Data Synthesis with Score-based Diffusion in Latent Space},
  author={Hengrui Zhang, Jiani Zhang, Balasubramaniam Srinivasan, Zhengyuan Shen, Xiao Qin, Christos Faloutsos, Huzefa Rangwala, George Karypis},
  journal={arXiv preprint arXiv:2310.09656},
  year={2024}
}
```

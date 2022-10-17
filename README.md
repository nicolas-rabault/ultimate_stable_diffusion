# Ultimate stable diffusion notebook
My custom notebook environment for stable diffusion

If you are looking for the `Beat_stable_diffusion notebook` please switch to the [beat branch](https://github.com/nicolas-rabault/ultimate_stable_diffusion/tree/beat)

## Requirements
A suitable [conda](https://conda.io/) environment named `usd` can be created
and activated with:

```
conda env create -f environment.yaml
conda activate ldm
```

You can also update an existing [latent diffusion](https://github.com/CompVis/latent-diffusion) environment by running

```
conda install pytorch torchvision -c pytorch
pip install transformers==4.19.2 diffusers invisible-watermark
pip install -e .
```

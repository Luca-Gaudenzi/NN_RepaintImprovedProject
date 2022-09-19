# improved-diffusion

This repository was created by Giulia Neccia e Luca Gaudenzi for the Neural Networks exam. This git was cloned from https://github.com/openai/improved-diffusion.



## Installation

Clone this repository and navigate to it in your terminal. Then run:

```
pip install -e .
```

This should install the `improved_diffusion` python package that the scripts depend on.
### 4. Run example
```bash
python ./scripts/test.py --conf_path confs/imagenet64_uncond_100M_1500K.yml
```
Find the output in `./log/example`

**Details on performed tests**
In the directory ./log/results there are configuration files for some tests that have been performed (in particular that on our paper) and the output images for these tests.


# Acknowledgement



This repository is based on [RePaint](https://github.com/andreas128/RePaint) and [Improved-Diffusion](https://github.com/openai/improved-diffusion).





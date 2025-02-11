# image2image-nwp2cfd-piri
This is an adapted code from [`pix2pix: Image-to-image translation with a conditional GAN`](https://www.tensorflow.org/tutorials/generative/pix2pix) tutorial.
In `casoTemplate` one can found the OpenFOAM folder used to run CFD cases.

## Paper

This is the code used for the work:
[`An image-to-image adversarial network to generate high resolution wind data over complex terrains from weather predictions`](https://doi.org/10.1016/j.engappai.2024.109533)

## Usage

Install the conda env with the `requirements.txt` file.
```
$ conda create --name MY_ENV_NAME --file requirements.txt
```

Download the data used from: [Link text Here](www.google.es);
Place it in your specified `data_folder` path.

Set up `checkpoint_dir`, `log_dir` and `res_dir` within the begining of the code.

Finally, run the code from a jupyter-notebook server instance or from command line:
```
$ ipython run.ipynb
```

## Citation

If you found this code useful please cite our work as:

```
@article{MILLAVAL2025109533,
title = {An image-to-image adversarial network to generate high resolution wind data over complex terrains from weather predictions},
journal = {Engineering Applications of Artificial Intelligence},
volume = {139},
pages = {109533},
year = {2025},
issn = {0952-1976},
doi = {https://doi.org/10.1016/j.engappai.2024.109533},
author = {Jaime Milla-Val and Carlos Montañés and Norberto Fueyo},
keywords = {Microscale wind prediction, Computational fluid dynamic, Numerical weather prediction, Image-to-image, Deep learning, conditional Generative Adversarial Network}
}
``` 

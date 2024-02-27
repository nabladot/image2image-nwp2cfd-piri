# image2image-nwp2cfd-piri
This is an adapted code from [`pix2pix: Image-to-image translation with a conditional GAN`](https://www.tensorflow.org/tutorials/generative/pix2pix) tutorial.

## Paper

This is the code used for the work:
`Deep learning image-to-image cGAN model to generate CFD-like data from NWP input over complex terrains`

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
@article{

}
``` 

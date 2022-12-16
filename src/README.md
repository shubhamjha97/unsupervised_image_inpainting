# Modified CoModGAN for Image Inpainting

## Setup the environment

```
conda env create -f environment.yml
```

## Download pretrained models
```
bash download_models.sh
```

## Run inference
```
python infer.py -i <input_dir_with_masks> -o <output_images> -d FFHQ
```

and repeat this for other datasets ["Places", "ImageNet", "WikiArt"].

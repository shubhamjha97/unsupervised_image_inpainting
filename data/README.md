# Download Datasets for Inpainting

If kaggle CLI API is not set up then:
```
pip install kaggle
```
Follow the instructions here to do the authentication: [Link](https://www.kaggle.com/docs/api#getting-started-installation-&-authentication)

## FFHQ

- Repo: https://github.com/NVlabs/ffhq-dataset
- Kaggle command: `kaggle datasets download -d rahulbhalley/ffhq-1024x1024`

## Places2

- Webpage: http://places2.csail.mit.edu
- Download Train: http://data.csail.mit.edu/places/places365/train_large_places365challenge.tar

## ImageNet

- Webpage: https://www.image-net.org/challenges/LSVRC/2012/index.php#
- Kaggle link: https://www.kaggle.com/c/imagenet-object-localization-challenge/data?select=imagenet_object_localization_patched2019.tar.gz
- Kaggle command: `kaggle competitions download -c imagenet-object-localization-challenge`

## WikiArt

- Kaggle: https://www.kaggle.com/c/painter-by-numbers/data
- Kaggle command: `kaggle competitions download -c painter-by-numbers` (It requires `pip install kaggle==1.5.3`)

## Validation set of all datasets with pre generated masks for evaluation purposes:

```
wget https://polybox.ethz.ch/index.php/s/nBta4VE0uBjG65D/download
```

Ground Truths for each of the images:

```
wget https://polybox.ethz.ch/index.php/s/ishe5ocVOOvdiC3/download
```
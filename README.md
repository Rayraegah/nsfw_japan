# NSFW Japan

dataset

## Description

Repository contains lists of URLs that will help you download NSFW images, this set can be used in building big enough dataset to train robust NSFM classification model.

This work inspired by [nsfw_data_scrapper](https://github.com/alexkimxyz/nsfw_data_scrapper) and for downloading images suggested to use scripts from the scrapper.

## NOTE

1. After downloading is highly suggested to clean your dataset, for example:
    - delete duplicates
    - remove images that was banned/deleted (they have a special image placeholder)
    - find out corrupted data and remove it also
    - etc
2. Pay attention to noise, some resources provide highly mixed data of NSFW and neutral images
3. This repository helps in retrieving NSFW images and there's no special URLs for neutral content

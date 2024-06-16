# Art Style Transfer Research Project

This repository contains the research work done to better understand the statistical value of aesthetics, specifically in landscape paintings. The purpose of this README is to provide a starting point for another student to continue the research from where it was left off.

## Dataset

I scraped and formatted two datasets

1. PNAS Landscapes:
  https://www.dropbox.com/scl/fo/0ok5hlub8b3c8urcd58oa/h?rlkey=ppggiqypqe1kg5v0c8am8g9w1&st=juzm13xm&dl=0

2. WGA Landscapes:
  https://www.dropbox.com/scl/fo/vbmn41qyv4yrcxbs7mhzj/h?rlkey=4trr0wltjqo30pityq21q673q&st=towqrjj0&dl=0

Creating new datasets for new painitng types {Still life, Portrait, Religous} should be easy, just modify the notebooks in the scraping directory.
## pkl Snapshots

Here: https://www.dropbox.com/scl/fo/drkyu5t01uixo46s0qj39/ANikebXDDLPOmZeEcKA1K08?rlkey=i5iiovpn6wx6ciawymdd27oo3&st=4m5t8i13&dl=0

## Finetuning

The `finetuning` folder contains the code for resuming the training process from any `.pkl` file. However, the best results have been achieved using the `wikiart1024.pkl` file, which is included in the `data` folder.

## Results

A sample result image demonstrating the current progress of the art style transfer model:

![StyleGAN3 Generated Image](data/results/fakes000360 (1).png)



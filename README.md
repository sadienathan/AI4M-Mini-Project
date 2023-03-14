# AI4M-Mini-Project
 
 This folder contains the inputs, outputs, and code used in my AI for Media mini project. As some of the notebooks I used to train and generate were on google colab I've included links to those. I used a self-collected dataset of images for this project with the aim of generating new images

This repo contains:

-3 Jupyter notebooks
    
To see the outcomes, follow this link: https://artslondon-my.sharepoint.com/:u:/g/personal/s_nathan0620221_arts_ac_uk/EUtUh67HS-BDrAfr1Tpvn5kB7tUveTPDbpaNjg-8G7t-MA?e=foqdkh

-Output folder, containing imagesS
    
-A Book in the form of a pdf

PLEASE NOTE: I had issues with uploading my files to the sharepoint so I had to greatly reduce the examples of the outcomes in these files so that I could upload it. The outputs that remain are representative of hundreds of images that couldn't be uploaded

# Data Collection

To collect the data in this project I used Pin down to scrape images off of pinterest, this github repo ( https://github.com/dixudx/tumblr-crawler ) to scrape several tumblr blogs and this internet archive scraper ( https://github.com/terrybroad/internet-archive-downloader ). This resulted in collecting 10,728 images
Data Organisation

To standardise my images I used this repo ( https://github.com/dvschultz/dataset-tools ) to make the images the correct size and format for training. I also went through my data, removing examples that weren't relevant for training which reduced the dataset down to 7662 images.

# Training and Generation

For this project I started off using the GAN jupyter notebooks from which I got extremely useless results and so moved on to using the google colab notebooks ( https://colab.research.google.com/github/dvschultz/stylegan2-ada-pytorch/blob/main/SG2_ADA_PyTorch.ipynb ), the repo is ( https://github.com/dvschultz/stylegan2-ada-pytorch ) and the stylegan3 notebook ( https://colab.research.google.com/github/dvschultz/stylegan3/blob/main/SG3.ipynb ), though I had much less success with stylegan 3 than stylegan 2. Due to the nature of colabs limitations of how long you can use a premium GPU I was limited in how long I could train my data for, leading to les polished outcomes. As I didn't change the code except for altering truncation and interpolation inputs I have not included the notebooks themselves.
    
Another limitation was my filesizes were so large, due to the number of images, that my googledoc was struggling to have the space to generate new outputs so I used much smaller number of images for different trainings so that I could have the input dataset with enough space for generating outputs, this worked in my favour anyway as I was able to tailor my results but breaking up my larger dataset into more specific categories. 
    
# Project Consolidation

I'm happy with the outcomes of my project given the issues I had with training, I made a small example book PDF which can be found in the book folder to help visualise a format that these outcomes could exist in, with the hopes to bind this into a real book form. 

# Mega-COV
This repository includes information about *Mega-COV*, the dataset introduced in a recent paper we published on [ArXiv](https://arxiv.org/pdf/2005.06012.pdf). Mega-COV is a billion-scale dataset from Twitter for studying COVID-19. The dataset is diverse (covers 234 countries), longitudinal (goes as back as 2007), multilingual (comes in 65 languages), and has a significant number of location-tagged tweets (~32M tweets). We release tweet IDs from the dataset, hoping it will be useful for studying various phenomena related to the ongoing pandemic and accelerating viable solutions to associated problems.

# World map coverage of Mega-COV *V0.1*
![World map coverage of Mega-COV](megacov.jpg)
**(a) Left: Cities.** Each dot is a city. Contiguous cities of the same color belong to the same country. **(b) Right: Point co-ordinates**. Each dot is a point co-ordinate (longitude and Latitude) from which at least one tweet was posted.

# Word clouds for hashtags of Mega-COV *V0.1*
Word clouds for hashtags in tweets from the top 10 languages in the data. We note that tweets in non-English can still carry English hashtags or employ Latin script.
![World cloudf Mega-COV](megacov2.jpg)

# Download the Data

## Data Usage Agreement
- **Mega-COV** is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using the dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s Terms of Service, and cite related [paper](https://arxiv.org/pdf/2005.06012.pdf). (Please see citation section in the end of this README).

## Download
- **Mega-COV** *V0.1* comprises ~ 566M tweet IDs
- You can donwload *MegaCOV_v0.1.tar.gz* from [Google Drive](https://drive.google.com/drive/folders/1t3xZVi7iRBLJWm3xkXTZj-JDGD_opr55?usp=sharing). Please be aware that the compressed files make up a total of ~ 4GB.


# Ethical Considerations
We collect **Mega-COV** from the public domain (Twitter). In compliance with Twitter policy, we do not publish hydrated tweet content. Rather, we only publish publicly available tweet IDs. All Twitter policies, including respect and protection of user privacy, apply. We encourage all researchers who decide to use **Mega-COV** to review Twitter policy at [Twitter policy](https://developer.twitter.com/en/developer-terms/policy) before they start working with the data. 

# Inquiries?
- If you have any questions about this dataset please contact us @ *muhammad.mageeed[at]ubc[dot]ca*.

# Citation
```
@inproceedings{AbdulMageed2020MegaCOVAB,
  title={Mega-COV: A Billion-Scale Dataset of 65 Languages For COVID-19},
  author={Muhammad Abdul-Mageed and AbdelRahim Elmadany and Dinesh Pabbi and Kunal Verma and Rannie Lin},
  year={2020}
}
```

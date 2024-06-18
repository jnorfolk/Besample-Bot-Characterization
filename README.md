# Besample-Bot-Characterization
This was my second TripleTen Externship, where I worked on a data analysis project for Besample, attempting to offer them insights into the behavior of bots vs real human users. 

# How to Use
You can view my notebook (Besample-EDA.ipynb) where I conducted EDA and feature engineering on Besample's user datasets. I ultimately trained machine learning models, examining feature importance to reveal the most significant indicators of bots. Features like using a public IP, or moving through questions too quickly, ended up being very important, while features like using a proxy, or Captcha scores, were surprisingly unimportant.

# A Key Result
Features toward the top (with a longer bar) are the most important features. Not all of the features are intuitively represented - such is the case with proprietary data.
![image](https://github.com/jnorfolk/Besample-Bot-Characterization/assets/117448822/32ca9f7b-b841-4a2c-b8a1-611233bc2e65)

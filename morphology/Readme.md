# Morphology of SDSS galaxies

The goal of this exercice is to test on the same problem a "classical" machine learning and a deep learning approach (CNNs) to separate SDSS galaxies between ellitpicals (early-type) and spirals (late-type). 
- The training set is made of the detailed visual classifications of [Nair&Abraham2010](http://adsabs.harvard.edu/abs/2010ApJS..186..427N) of ~14.000 SDSS galaxies. 

The TType column gives the visual classification as follows:
-5--> E
-3 to -2 --> S0
0 --> S0/a
1 --> Sa
2 --> Sab
3 --> Sb
4 --> Sbc
5 --> Sc
7 --> Sd
> 8 --> Im etc..

- For the "shallow" approach we will use measurements from the [catalog provided](https://github.com/mhuertascompany/deeplearning4astronomy/blob/master/morphology/Nair_Abraham_cat.fit). It includes for every galaxy, strucutural parameters (sizes etc..), colors , SFRs and other indicators.

- For the "deep" approach, the input will be the jpeg images. The jpeg images can be donwnloaded [here](https://drive.google.com/drive/folders/1ufj6ATroZ3emBbSQfQhcL_6W87EPgTaS?usp=sharing). The name is  matched to the ID in the catalog. Donwloand the folder with the images and put it in the same folder where the jupyter notebooks are

- A [jupyter notebook] (https://github.com/mhuertascompany/deeplearning4astronomy/blob/master/morphology/shallow/morph_classical_ML.ipynb) for the shallow approach is provided. I used RFs and ANNs.

- A jupyter notebook for the deep approach.


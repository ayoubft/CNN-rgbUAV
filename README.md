# CNN-rgbUAV

Using CNN (convolutional neural networks) to map forest tree species in high resolution UAV-based RGB-imagery.

Used data from [here](https://zenodo.org/record/4054338#.YIuz1BGRXCI), to create train and test data. The portion that will be used for training will be cropped to `256x256` and augmented then used.

## Expirement 1: Binary classifier using CNN U-Net

Jump to the [notebook](https://github.com/ayoubft/CNN-rgbUAV/blob/main/tree3Classifier-v2.ipynb).

---

### DATA:
Nguyen, Ha Trang, Diez, Yago, Lopez Caceres, Maximo Larry, Kentsch, Sarah, Moritake, Koma, & Shu, Hase. (2020). Dataset of Individual Sick Fir Detection using Computer Vision and Deep Learning. 

https://doi.org/10.5281/zenodo.4054338

### Architecture of CNN U-Net Credits:

**Mapping forest tree species in high resolution UAV-based RGB-imagery by means of convolutional neural networks**;
Felix Schiefer, Teja Kattenborn, Annett Frick, Julian Frey, Peter Schall, Barbara Koch, Sebastian Schmidtlein;
ISPRS Journal of Photogrammetry and Remote Sensing, Volume 170, 2020, Pages 205-215, ISSN 0924-2716;
[Link](https://doi.org/10.1016/j.isprsjprs.2020.10.015)

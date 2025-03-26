# How do Cells Respond to Different Drug Treatments?

In the ipynb file 'projectcode', you will find our analysis of 2.8K cell images treated with a variety of around 300 drugs. We walk through our analysis, starting from the segmentation of the images using Cellpose, to feature extraction from the segmented images, to dimension reduction and clustering methods, and finally to the training of two classification models (multinomial logistic regression and random forest classifier).

The original images can be found [here](https://drive.google.com/drive/folders/11ZoNN19_mOWqsxEUjTFNVEuqMJhrPRYe?usp=share_link).

The masks we outputted can be found [here](https://drive.google.com/drive/folders/1-B7AsFDT5foG9tlrjKLMO_4n4uLiLCn7?usp=sharing).

If you are interested in running this code yourself, you can access the [extracted features](https://drive.google.com/file/d/1NAWyeY4_VN49INudfCrh3iWvUtPNB163/view?usp=share_link) and accompanying [treatment labels](https://drive.google.com/file/d/1Vnw7hz7L9Cit8-9T0LcpNUToYx_6ILwg/view?usp=share_link) and save them to your device locally. Once you save the files locally, you can skip the Image Segmentation, Data Augmentation, and Feature Extraction sections in the Jupyter Notebook file.

## References

Cimini B.A. Goodale A. et al. Chandrasekaran, S.N. Three million images and morphological profiles of cells treated with matched chemical and genetic perturbations. Nature Methods, 2024.

Israel A. Huaman, Fares D. E. Ghorabe, Sofya S. Chumakova, Alexandra A. Pisarenko, Alexey E. Dudaev, Tatiana G. Volova, Galina A. Ryltseva, Sviatlana A. Ulasevich, Ekaterina I. Shishatskaya, Ekaterina V. Skorb, and Pavel S. Zun. Cellpose+, a morphological analysis tool for feature extraction of stained cell images, 2024.

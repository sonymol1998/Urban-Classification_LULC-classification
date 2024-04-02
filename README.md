# Urban-Classification_LULC-classification

![eurosat_overview_small](https://github.com/sonymol1998/Urban-Classification_LULC-classification/assets/133326396/38933d6d-2c82-4b8c-8ae3-c91cd11a6c6d)


Description:
This repository contains code for implementing image classification models on the Eurosat dataset using various deep learning architectures such as Random Forest, ResNet versions 1 and 2, and Wide ResNet. The Eurosat dataset consists of satellite images covering 10 different land use and land cover classes in Europe, making it a valuable resource for remote sensing and environmental monitoring applications.

Models Included:

Random Forest: Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

ResNet v1 and v2: ResNet, short for Residual Network, is a deep learning model architecture introduced by Microsoft Research. ResNet v1 and v2 differ in their architecture designs, with v2 introducing tweaks such as pre-activation blocks and incorporating weight normalization.

Wide ResNet: Wide ResNet is an extension of the ResNet architecture that focuses on increasing model width rather than depth, resulting in improved performance and efficiency, especially for image classification tasks.

Dataset:

The Eurosat dataset comprises 27,000 labeled Sentinel-2 satellite images of different land use and land cover categories, including urban, agriculture, forest, etc. Each image has a resolution of 64x64 pixels and is categorized into one of the 10 classes.

Dataset Download Link:RGB= https://madm.dfki.de/files/sentinel/EuroSAT.zip
MS= https://madm.dfki.de/files/sentinel/EuroSATallBands.zip

Contents:

Data Preprocessing: Code for loading, preprocessing, and augmenting the Eurosat dataset to prepare it for model training and evaluation.

Model Implementations: Python scripts containing the implementations of Random Forest, ResNet v1, v2, and Wide ResNet models using popular deep learning frameworks such as TensorFlow or PyTorch.

Training and Evaluation: Scripts for training the models on the Eurosat dataset and evaluating their performance using metrics such as accuracy, precision, recall, and F1-score.

Results Analysis: Jupyter notebooks or Python scripts for visualizing and analyzing the results obtained from different models, including confusion matrices, class-wise accuracy, and feature importance (for Random Forest).

Usage:

To use this repository, clone it to your local machine and follow the instructions provided in the README.md file. Make sure to download the Eurosat dataset from the provided link and place it in the appropriate directory.

Contributions and feedback are welcome! Feel free to open issues or submit pull requests for any improvements or additional features.


Eurosat: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification. Patrick Helber, Benjamin Bischke, Andreas Dengel, Damian Borth. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2019.

ResNet: Deep Residual Learning for Image Recognition. Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.

Wide Residual Networks. Sergey Zagoruyko, Nikos Komodakis. British Machine Vision Conference (BMVC), 2016.

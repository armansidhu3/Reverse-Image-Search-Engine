# Reverse Image Search Engine

Like Google Reverse Image Search, we use embedding, a spatial representation of an image to find related images. We explore various methods and algorithms to automate this on a scale, from thousands to several million images, and make them searchable in microseconds. 

## Code

1. [1-feature-extraction.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/1_feature_extraction.ipynb): We will extract features from pretrained models like VGG-16, VGG-19, ResNet-50, InceptionV3 and MobileNet and benchmark them using the Caltech101 dataset.

2. [2-similarity-search-level-1.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/2_similarity_search_level_1.ipynb): We write an indexer to index features and search for most similar features using various nearest neighbor algorithms, and explore various methods of visualizing plots.

3. [2-similarity-search-level-2.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/2_similarity_search_level_2.ipynb): We benchmark the algorithms based on the time it takes to index images and locate the most similar image based on its features using the Caltech-101 dataset. We also experiment with t-SNE and PCA.

4. [2-similarity-search-level-3.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/2_similarity_search_level_3.ipynb): So far we experimented with different visualization techniques on the results, t-SNE and PCA on the results. Now we will calculate the accuracies of the features obtained from the pretrained and finetuned models.

5. [3-reduce-feature-length-with-pca.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/3_reduce_feature_length_with_pca.ipynb): We will experiment with PCA and figure out what is the optimum length of the features to use in our experiments.

6. [4-improving-accuracy-with-fine-tuning.ipynb](https://github.com/armansidhu3/Reverse-Image-Search-Engine/blob/master/4_improving_accuracy_with_fine_tuning.ipynb): Many of the pre-trained models were trained on the ImageNet dataset. Therefore, they provide an incredible starting point for similarity computations in most situations. If we tune these models to adapt to our specific problem, they would perform even more accurately for finding similar images.

## Data

We will be using the [Caltech101 dataset](http://www.vision.caltech.edu/Image_Datasets/Caltech101/101_ObjectCategories.tar.gz).

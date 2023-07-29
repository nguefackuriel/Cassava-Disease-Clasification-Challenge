Team name: The Hunters

# Cassava-Disease-Clasification-Challenge
In this project, we design multiples models to classify cassava leaf disease

As the 2nd largest provider of carbohydrates in Africa, cassava is a key food security crop grown by small-holder farmers because it can withstand harsh conditions. At least 80% of small-holder farmer households in Sub-Saharan Africa grow cassava and viral diseases are major sources of poor yields.

In this competition, we introduce a dataset of 5 fine-grained cassava leaf disease categories with 9,436 labeled images collected during a regular survey in Uganda, mostly crowdsourced from farmers taking images of their gardens, and annotated by experts at the National Crops Resources Research Institute (NaCRRI) in collaboration with the AI lab in Makarere University, Kampala.

The dataset consists of leaf images of the cassava plant, with 9,436 annotated images and 12,595 unlabeled images of cassava leaves. Participants can choose to use the unlabeled images as additional training data. The goal is to learn a model to classify a given image into these 4 disease categories or a 5th category indicating a healthy leaf, using the images in the training data (participants can choose to use the unlabeled images in their training data). This competition is part of the fine-grained visual-categorization workshop (FGVC6 workshop) at CVPR 2019.


We started with a simple CNN model, before moving to pretrained models including: ResNet50, ResNet101, ResNeXt101, ViT, EfficientNet to name a few and also use Test time augmentation technique to improve our model.

We obtained an accuracy of 91.34% on the private leaderboard and occupied the 2nd position.

The project was done in collaboration with [Binta Sow](https://github.com/BintaSOW1)

This [link](https://www.kaggle.com/competitions/ammi-2023-convnets/overview) brings you to the Hackathon website on kaggle.

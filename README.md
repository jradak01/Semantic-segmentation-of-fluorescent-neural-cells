# Semantic segmentation of fluorescent neural cells

The project focuses on semantic segmentation of cross-sectional images of the mouse brain, where neurons are stained using fluorescent microscopy. The dataset consists of 283 images and their corresponding cross-sectional masks, which allows for detailed analysis and identification of neurons in the brain.

The project begins with data loading, where images and their masks are prepared for further processing. Afterward, data visualization is performed to gain insight into their nature and ensure quality before training the model.

The model used for semantic segmentation is U-net, known for its flexibility and ability to accurately segment objects in images. During the training phase, various parameters are tested to achieve optimal model performance.

Finally, the trained models are evaluated on a separate test dataset to assess their ability to recognize and segment neurons.

Through this project, the goal is to develop precise and reliable models for semantic segmentation of neurons in mouse brain images, which could significantly contribute to the understanding of neural structure and function in the brain.

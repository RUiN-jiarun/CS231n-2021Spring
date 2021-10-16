### Goals

In this assignment, you will implement language networks and apply them to image captioning on the COCO dataset. Then you will explore methods for visualizing the features of a pretrained model on ImageNet and train a Generative Adversarial Network to generate images that look like a training dataset. Finally, you will be introduced to self-supervised learning to automatically learn the visual representations of an unlabeled dataset.

The goals of this assignment are as follows:

- Understand and implement RNN and Transformer networks. Combine them with CNN networks for image captioning.
- Explore various applications of image gradients, including saliency maps, fooling images, class visualizations.
- Understand how to train and implement a Generative Adversarial Network (GAN) to produce images that resemble samples from a dataset.
- Understand how to leverage self-supervised learning techniques to help with image classification tasks.

**You will use PyTorch for the majority of this homework.**

### Q1: Image Captioning with Vanilla RNNs (30 points)

The notebook `RNN_Captioning.ipynb` will walk you through the implementation of vanilla recurrent neural networks and apply them to image captioning on COCO.

### Q2: Image Captioning with Transformers (20 points)

The notebook `Transformer_Captioning.ipynb` will walk you through the implementation of a Transformer model and apply it to image captioning on COCO.

### Q3: Network Visualization: Saliency Maps, Class Visualization, and Fooling Images (15 points)

The notebook `Network_Visualization.ipynb` will introduce the pretrained SqueezeNet model, compute gradients with respect to images, and use them to produce saliency maps and fooling images.

### Q4: Generative Adversarial Networks (15 points)

In the notebook `Generative_Adversarial_Networks.ipynb` you will learn how to generate images that match a training dataset and use these models to improve classifier performance when training on a large amount of unlabeled data and a small amount of labeled data. **When first opening the notebook, go to `Runtime > Change runtime type` and set `Hardware accelerator` to `GPU`.**

### Q5: Self-Supervised Learning for Image Classification (20 points)

In the notebook `Self_Supervised_Learning.ipynb`, you will learn how to leverage self-supervised pretraining to obtain better performance on image classification tasks. **When first opening the notebook, go to `Runtime > Change runtime type` and set `Hardware accelerator` to `GPU`.**

### Extra Credit: Image Captioning with LSTMs (5 points)

The notebook `LSTM_Captioning.ipynb` will walk you through the implementation of Long-Short Term Memory (LSTM) RNNs and apply them to image captioning on COCO.
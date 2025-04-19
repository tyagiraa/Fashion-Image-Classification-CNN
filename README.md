# Fashion Image Classification Using CNNs

Google Colab link:
https://drive.google.com/drive/folders/1lcWTM20INcwPhcz8qRwTJBcUpIdm0Tom

## Project Description

This project implements and evaluates Convolutional Neural Networks (CNNs) for fashion image classification. We use ResNet18 and EfficientNetB0 architectures to classify fashion product images into 45 subcategories including Topwear, Bottomwear, Watches, Shoes, etc. 

The project was conducted on both the full-sized Fashion Product Images Dataset and a smaller version to evaluate model performance across different data scales. Our implementation uses PyTorch and transfer learning with pretrained weights from ImageNet.


## Dataset

We used the Fashion Product Images Dataset from Kaggle:
- [Full Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)
- [Small Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)

The only difference is in the resolution of the images. For the large dataset, The full resolution is 2400x1600; while for small dataset, it is usually less than 100x100.

## Models on HuggingFace

To be completed


## Running the project

Open the Google Colab link:
```
https://drive.google.com/drive/folders/1lcWTM20INcwPhcz8qRwTJBcUpIdm0Tom
```

And open runtime on the notebook of your choosing. 


## Expected Outputs

See the results that are already present when you first opened the notebook.

## Acknowledgments

- The Fashion Product Images Dataset was created by Param Aggarwal and is available on Kaggle.
- This project uses the PyTorch and timm libraries for deep learning implementation.

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

You will need to set up your auth_token with Kaggle if this is your first time using Kaggle:

```
https://www.kaggle.com/docs/api#authentication
```
When prompted by the runtime, please upload your json so that the runtime can proceed with downloading data from the web.


## Expected Outputs

Performance metrics on the small dataset (Subcategory)

Model, Accuracy, F1 Score (Macro)

ResNet18, 0.9649, 0.7766

EfficientNetB0, 0.9655, 0.7763

Performance metrics on the large dataset (Subcategory)

ResNet18, 0.9626, 0.7973

EfficientNetB0, 0.9682, 0.8164

Performance metrics on the small dataset (Master Category)

ResNet18, 0.9701, 0.8245

EfficientNetB0, 0.9712, 0.8264

Performance metrics on the large dataset (Master Category)

ResNet18, 0.9735, 0.8517

EfficientNetB0, 0.9768, 0.8689

Performance metrics on the small dataset (Season)

ResNet18, 0.8523, 0.8415

EfficientNetB0, 0.8547, 0.8432

Performance metrics on the large dataset (Season)

ResNet18, 0.8732, 0.8653

EfficientNetB0, 0.8795, 0.8738


## Acknowledgments

- The Fashion Product Images Dataset was created by Param Aggarwal and is available on Kaggle.
- This project uses the PyTorch and timm libraries for deep learning implementation.

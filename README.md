# Bangkit-CAP0451-Machine Learning Repository
---------------
Author:

- Bayu Aditya Triwibowo (M0040326)
- Dwi Cahya Nur Faizi (M0040327)

## Dataset Plant Disease
The dataset that we use is a collection of plant diseases detected through the leaves of these plants. We took two datasets from kaggle, the first belongs to [vipool](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset) and the second belongs to [saraz104](https://www.kaggle.com/saroz014/plant-disease). The two datasets are actually not much different, we combine the two datasets to get more data. We limit the plants that we can detect to three crops, namely tomatoes, potatoes, and corn.

Our dataset has 17 classes consisting of 3 classes of healthy plants and 14 classes of plants with disease. Overall our data contains:

| Plant Type | Total |
| ------ | ------ |
| Corn_healthy | 2000 Files |
| Corn_Cercospora_leaf_spot | 2000 Files |
| Corn_Common_rust | 2000 Files |
| Corn_Northern_Leaf_blight | 2000 Files |
| Potato_healthy | 2000 Files |
| Potato_Early_blight | 2000 Files |
| Potato_Late_blight | 2000 Files |
| Tomato_healthy | 2000 Files |
| Tomato_Bacterial_spot | 2000 Files |
| Tomato_Early_blight | 2000 Files |
| Tomato_Late_blight | 2000 Files |
| Tomato_Leaf_Mold | 2000 Files |
| Tomato_Septoria_leaf_spot | 2000 Files |
| Tomato_Spider_mites | 2000 Files |
| Tomato_Target_Spot | 2000 Files |
| Tomato_Tomato_Yellow_Leaf_Curl_Virus | 2000 Files |
| Tomato_Tomato_mosaic_virus | 2000 Files |

The data that we use is 2000 for each class so that there is no imbalance in the dataset that we use. The data we get is already in augmented condition, making it easier for us to process data that does not require long coding. All this data we use in the model so that the output of the model is worth 17 class. Here is some example images from the dataset:

![image](https://user-images.githubusercontent.com/68576415/121238236-16672080-c8c2-11eb-9e75-2538f163f2be.png)

### Adjust the value in the notebook
- Image size for baseline and Xception model is 250 by 250
- Image size for Imagenet and vgg16 model is 224 by 224
- Filename to save the model as you want

### Saved model for vgg16
https://drive.google.com/file/d/1yzoSUtiqwuaKuCoaNtfYQTYBY_myLZeC/view?usp=sharing

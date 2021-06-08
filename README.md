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
| Corn_healthy | 1859 Files |
| Corn_Cercospora_leaf_spot | 1642 Files |
| Corn_Common_rust | 1907 Files |
| Corn_Northern_Leaf_blight | 1908 Files |
| Potato_healthy | 1824 Files |
| Potato_Early_blight | 1939 Files |
| Potato_Late_blight | 1939 Files |
| Tomato_healthy | 1926 Files |
| Tomato_Bacterial_spot | 1702 Files |
| Tomato_Early_blight | 1920 Files |
| Tomato_Late_blight | 1851 Files |
| Tomato_Leaf_Mold | 1882 Files |
| Tomato_Septoria_leaf_spot | 1745 Files |
| Tomato_Spider_mites | 1741 Files |
| Tomato_Target_Spot | 1827 Files |
| Tomato_Tomato_Yellow_Leaf_Curl_Virus | 1961 Files |
| Tomato_Tomato_mosaic_virus | 1790 Files |

The data we get is already in augmented condition, making it easier for us to process data that does not require long coding. All this data we use in the model so that the output of the model is worth 17 class. Here is some example images from the dataset:]

![image](https://user-images.githubusercontent.com/68576415/121238236-16672080-c8c2-11eb-9e75-2538f163f2be.png)

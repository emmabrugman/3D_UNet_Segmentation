# 277B_final

Group members: Emma Brugman, Lucia Lopez, Sabrina Temesghen, Julian Dolan


Our dataset comes from [Brain Tumor Segmentation(BraTS2020)](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data?resource=download) , we download this dataset using the code given to us by Kaggle, as seen below. 

```python
import kagglehub
# Download latest version
path = kagglehub.dataset_download("awsaf49/brats2020-training-data")
print("Path to dataset files:", path)
```


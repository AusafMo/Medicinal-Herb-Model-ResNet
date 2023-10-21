🙋‍♂️ **The Training notebook(s) used to train/FineTune ResNet50 on Mendley Medicinal leaf dataset** 
## What is this? :
- The Project aims to solve the problem of identification of medicinal herbs.
- The Machine Learning Model uses ResNet, with a validation accuracy of 98% and testing accuracy of 96%.
- The training and testing dataset contains over 1500 images across 50 medicinal herb species.
- The model is capable of classifying the user-given image into 30 species.

## Tech Stack Used :
  * Python 3
  * Pandas
  * Numpy
  * Pillow
  * PyTorch
  * Tensorflow
  * FineTuned ResNet50 model trained on Mendeley Medicinal Leaf Dataset
  * Dataset:
        <a href = "https://data.mendeley.com/datasets/nnytj2v3n5/1">
                  ```
                  S, Roopashree; J, Anitha (2020),
                  “Medicinal Leaf Dataset”,
                  Mendeley Data, V1, doi: 10.17632/nnytj2v3n5.1
                  ```     
        </a>

## Training, Validation and Test Accuracies for 54 Epochs (Early Stoping):
  - **Training Accuracy** : 97.55%
  - **Validation Accuracy** : 98.64%
  - **Top 1 Testing Accuracy** : 96.43%
  - **Top 5 Testing Accuracy** : 99.07%
  
### Training Vs Validation Accuracy :
  ![download](https://github.com/AusafMo/NoteBook-Medicinal-Herb-Model-ResNet/assets/75237046/7ed54432-6b9b-4682-a163-cc974b70a434)

### Sample Predictions :
  ![download](https://github.com/AusafMo/NoteBook-Medicinal-Herb-Model-ResNet/assets/75237046/26662297-7d08-47e5-8018-0d74d926ca42)


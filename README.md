***DINO Image Dataset Splitting and Bounding Box Visualization***

Project Overview

This project demonstrates how to leverage the DINO repository to split a dataset of images and visualize the associated bounding boxes. We'll utilize Python code to achieve this functionality.

First we have downloaded the dataset from the given link

``
https://drive.google.com/drive/folders/1DCpmo919b7OrAng9clEbiMHjO3D0hyoa?usp=sharing
``

Then we split the data as 160 images of training images and 40 for validation purpose using Scikit-learn train_test Split method as below.

```python
train_filenames, test_filenames = train_test_split(image_filenames, test_size=0.2, random_state=42)
```

Then we analyzed the data by using Border Box Method
Random image 1 from dataset.  ![Screenshot from 2024-09-24 13-47-00](https://github.com/user-attachments/assets/7cc623f3-f6d9-4e9c-8d52-c7199d31daae)
)

Random image 2 from dataset.  ![Screenshot from 2024-09-24 13-46-51](https://github.com/user-attachments/assets/94573f5b-4eda-4ac7-93d4-b950015b2e78)

Random image 3 from dataset. ![Screenshot from 2024-09-24 13-46-43](https://github.com/user-attachments/assets/6055b777-9cfb-495f-9fec-b10b43c58a8c)

Random image 4 from dataset. ![Screenshot from 2024-09-24 13-36-59](https://github.com/user-attachments/assets/a79083c3-5759-4db8-b5c2-185b0bfe25d0)

Now then we have to clone the DINO repository and download the pre-trained DINO-4scale model with the ResNet-50 (R50) backbone from the provided link in the repository.

As I dont have the Cuda in my System i was unable to run the further code.





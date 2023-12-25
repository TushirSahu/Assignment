# Resume Classifier using the transfer learning architecture
## Dataset: 
The RVL-CDIP dataset consists of scanned document images belonging to 16 classes such as letter, form, email, resume, memo, etc. The dataset has 320,000 training, 40,000 validation and 40,000 test images. But then rearranged this dataset into two classes resume and non-resume. The corrupted images were also removed while rearranging the data.
## Data Augmentation: 
Applied image data augmentation techniques during training, including rotation, width and height shifts, zooming, and horizontal flips. These augmentations enhance the model's ability to generalize and improve its performance on diverse document images.
## Model Selection:
Used the Transfer learning method as it is one of the efficient methods for image classification tasks. Here I have used VGG-16 architecture because of its lightweight nature as compared to other state-of-art architectures (DenseNet121,Resnet50 etc).
## Fine-Tuning: 
Leveraged fine-tuning with the VGG-16 architecture to efficiently adapt the pre-trained model to the specific document image classification task. The lightweight design of VGG-16 facilitates quick and effective fine-tuning, making it a suitable choice for resource-conscious applications.





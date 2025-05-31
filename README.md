# Design-and-Implementation-of-an-Object-Detection-Model

####  Files Included:

1. BIPOLAR_FACTORY_ASSIGNMENT.ipynb

   This is the main notebook. It contains all the code for training and testing the object detection model using Faster R-CNN on the Pascal VOC 2007 dataset.

2. fasterrcnn_voc.pth

   This is the trained model weights file. It was saved after training for 10 epochs.

3. Evaluation Metrics Report.pdf

   This file shows the evaluation results like mAP, precision, and recall after testing the model.

4. Demo on Test Images.png

   This is a screenshot showing how the model detects objects on test images.

5. Experience Report.docx

   This is a personal report that explains my experience during this assignment. It includes the challenges I faced, how I used AI help, and what I learned.

---

####  How to Run the Notebook:

1. Requirements:

   Python 3.8 or higher  
   PyTorch  
   Torchvision  
   Matplotlib  
   Pascal VOC dataset (automatically downloaded)

2. Steps:

   Open the BIPOLAR_FACTORY_ASSIGNMENT.ipynb file in Jupyter Notebook or Google Colab.  
   Run the code cells one by one.  
   The notebook will train the model and show results.  
   You can also load the trained model (fasterrcnn_voc.pth) for faster testing.


####  What This Project Does:

Loads the VOC 2007 dataset.  
Prepares data and annotations for object detection.  
Uses a pre-trained Faster R-CNN model and fine-tunes it on the dataset.  
Trains the model and evaluates it using standard metrics.  
Shows visual results on test images.

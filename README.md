# ANPR-using-Tesseract
This model focuses on Detection and Recognition of Number Plate.Detection is done using OpenCV using contour detection and Recognition is done using Tesseract and CNN model . The test is mostly done on Indian Number Plates and rear view image of the car is taken for testing.

Two different models are used to check the difference and accuracy of both the models on the same dataset and to chcek the pros and cons of both the models.

**Functions of the .py files given above**

The number_plate_detection_cnn.py file is used to detect the number plate of the car and the output of this model is given to the number_plate_rec_cnn.py model for recognition using CNN.
These two .py files are used while using the CNN model.
For Tesseract OCR model run the Tesseract_OCR.py file the detection and recognition is combined and put in this .py file all together ,no need to run any other file for Tesseract model.
The number_recognition.py file is a basic file which just recognises number and is trained on mnist dataset.



## The whole Report on the above two models is attached Above.

**Run the .py files on Google Colab**

Number Plate Detection For CNN:
![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()

# License-Plate-Detection-using-OpenCV-and-Haar-Cascade-Classifier

## AIM
To develop a Python program using OpenCV that detects a vehicle’s license plate from an image by applying a Haar Cascade classifier, drawing bounding boxes, and extracting the plate region.

## ALGORITHM
1.Start

2.Load the input image using cv2.imread().

3.Convert the image to grayscale to simplify computation.

4.Apply preprocessing:

  • Gaussian Blur to reduce noise
  • Histogram Equalization to enhance contrast
  • Load the Haar Cascade file: haarcascade_russian_plate_number.xml

5.Apply detectMultiScale() on the preprocessed image to detect license plates.

6.For each detected plate:

7.Draw a bounding box on the original image
  • Crop the plate region
  • Save the cropped plate as an image
  
8.Display:

  • Original image
  • Preprocessed images
  • Detection output
9.End

## RESULT: 
The license plate of the vehicle was successfully detected using Haar Cascade, and the detected region was extracted and saved.

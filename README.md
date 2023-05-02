# AIL_blur_license_plates

- This repository contains a python script <b>License_plates_blurring</b>that is used to load path to images from a csv file, the YoLo4 algorithm for car detection is applied 
  to the images. Next, the model <b>haarcascade_russian_plate_number.xml</b> is applied to recognize identification numbers and easyocr to read the text on the image.
- Before executing the code, it is necessary to download weights for the YoLo4 model from following link:
- https://github.com/AlexeyAB/darknet#yolo-v4-v3-and-v2-for-windows-and-linux
- Download file <b>yolov4.weights</b>.
- The images should be stored in <b>img</b> folder.
- The CSV file should be stored in <b>data</b> folder.

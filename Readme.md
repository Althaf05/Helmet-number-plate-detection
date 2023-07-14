# Helmet Detection and License Plate Extraction using YOLOv5
This project is designed to detect if a rider is wearing a helmet and extract the license plate number of the bike if the rider is not wearing a helmet. The project uses YOLOv5 deep learning algorithm for object detection. The image or video is fed to the model using a user-friendly GUI which then displays the results.
## How it Works
The project uses computer vision techniques to detect the presence of a helmet on a rider's head and the license plate on the bike. The YOLOv5 model is trained on a dataset of images that contain different types of helmets and license plates.<br/>
When an image is fed into the model, it scans the image and identifies any helmets or license plates that are present in the image. If the model detects that the rider is not wearing a helmet, it will extract the license plate number and store it in a file.<br/>
The license plates of the bike will be cropped and saved into two seperate folders "number_plates" and "number_plates_text". The 'number_plates' will contain the images of the number plates while the 'number_plates_text' will contain text file which has the number plate.They are also stored into a csv according to their timestamp so that the user will know when the person didn't wear the helmet.



## Installation
 1. git clone https://github.com/Althaf05/Helmet-number-plate-detection.git<br/>
 2. pip install -r requirements.txt
 3. train the model using the dataset chosen
 4. integrate it with the GUI

# Mini-project-2
Traffic control and the identification of vehicle owners have become a major problem in all countries. Sometimes it becomes difficult to identify a vehicle owner who is breaking the rules of the road and breaking into private properties.

Therefore, it is not possible to catch and punish such kind of people because the police might not be able to retrieve the vehicle number of the moving vehicle due to the speed of the vehicle.

In order keep track of the vehicles entered places like educational institutions and private properties we can use this model.

So, to solve these types of problems Number Plate Detection System can be used.
 
 # Block diagram
 ![image](https://user-images.githubusercontent.com/72657448/156212560-cb9a7005-1c84-4084-8fc5-20f6bc501520.png)
 
Image acquisition: Capturing the image of the vehicle which contains the numberplate.

Preprocessing: Removal of noise and adjustment of brightness and contrast, Greyscale conversion to reduce memory usage and complexity.

License Plate Extraction: Applying Edge detection to the image and finding contours in the image and identifying the numberplate. Mask the entire image except the license plate and cropping the number plate image

Character recognition: Application of OCR on the cropped image of the number plate and identifying the text on the number plate.

Data Saving: Saving the data on the number plate in a CSV file.



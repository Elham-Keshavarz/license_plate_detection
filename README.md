# license_plate_detection

The project developed using [YOLOv5](https://github.com/ultralytics/yolov5#readme) to detect the License Plate from a vehicle and uses the [Wandb](https://github.com/wandb/wandb)  to demonstrate the result.

![image](https://user-images.githubusercontent.com/42807143/198024944-4e59f913-613b-4486-b885-192429d220ec.png)


## Data Labelling
In this project I use [Label Studio](https://labelstud.io/) in order to label 215 images in order to make a dataset . Each image has a text file including class id of the object and object coordinates . There are other tools like [roboflow](https://app.roboflow.com) to augment more data . 

![image](https://user-images.githubusercontent.com/42807143/198024461-f358dc66-8ffc-489d-b2e3-76bf239be3c3.png)


## Using YOLOv5
In this project I use three main models for training . Small , Medium and Large YOLO v5 models are used , each of these models including epoch =100 and  two different batch sizes . The best result was detected in Medium model with epoch =100 , batch_size = 32.

<img src="https://user-images.githubusercontent.com/42807143/198022522-ae1361e2-e158-4573-a3ad-c2aebc28783c.png" width="400" height="400">

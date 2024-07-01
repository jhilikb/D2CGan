# D2CGan

# THaze dataset

We introduced a real-world hazy dataset,that we have collected  using different hazy and clean videos (both from the same  location) to show climate and road condition variations. Hazy videos, each around 3 minutes long, were collected in the month of December. In contrast, clean videos were recorded during the month of May. These hazy and clean recorded videos are transformed into corresponding sequences while maintaining a frame rate of one image per second. Currently, 8600 hazy and 4000 clean images collected under different haze levels are available. This dataset includes a wide range of vehicle categories, such as buses, cars, e-rickshaws, motorbikes, etc., that will support future research in various domains, such as autonomous vehicles, traffic monitoring, etc. Some sample hazy and clean image can be viewed from the Images folder.


You can download the images from https://drive.google.com/drive/folders/1-dmO59uuVjJ9jP7B0S1KpPhfa-7isQ75?usp=sharing

# Raindrop dataset

We have also annotated the raindrop dataset[1] for the class "car". The Raindrop dataset's training set consists of 861 images, with 199 images belonging to the car class. Our annotated folder contains 199 text files with bounding box dimensions in 'xmin, ymin, xmax, ymax' format. This can be downloaded from https://drive.google.com/drive/folders/1qjGzm0WMf0dLAZFdNrQDEdv40Jhvf5db?usp=drive_link .This will allow testing of the dataset for object detection performance. 

Object detection scores.

| Dataset      |           | mAP  |
| ------------- |:-------------:| -----:|
|Raindrop     | clean | 79.95 |
|       | rainy      |   77.23 |
|  | D2CGAN_OD      |   77.37 |


[1]  Rui Qian, Robby T Tan, Wenhan Yang, Jiajun Su, and Jiay ing Liu. Attentive generative adversarial network for rain drop removal from a single image. In CVPR, pages 2482-2491, 2018

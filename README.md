# Welcome to OpenCV Tutorial


## Inspiration

OpenCV is a widely used , most popular computer vision library , that finds
day to day application.From Object Detection , Facial Recogonition , Autonomous Navigation
and a ton a lot ...

You can explore various other examples and techniques as a follow up to the tutorials
from [Offical Docs](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_table_of_contents_imgproc/py_table_of_contents_imgproc.html)


## Installation

You can experiment with OpenCV either in [Google Colab](https://colab.research.google.com/) or any of your faviourite IDE.
As a recommendation for offline usage, you can try [PyCharm](https://www.jetbrains.com/pycharm/) along with [Kite](https://www.kite.com/) to make coding much easier and flexible.

```sh
pip install opencv-python
```
# More Examples


### Duck

<img src="images/duck_original.jpeg" width="300" height="300">

```sh
img = cv2.imread("duck_original.jpeg")
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)
mask = cv2.inRange(hsv, (0, 0, 0), (220, 145,255))
```


<img src="images/duck_inrange.jpeg" width="300" height="300">

### Rubix Cube
<img src="images/rubic_original.jpeg" width="300" height="300">


```sh
img = cv2.imread("rubic_original.jpeg")
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)
mask = cv2.inRange(hsv, (0, 0, 0), (211, 182,187))
```


<img src="images/rubic_inrange.jpeg" width="300" height="300">

### Hand
<img src="images/hand_original.jpeg" width="300" height="300">


```sh
img = cv2.imread("hand_original.jpeg")
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)
mask = cv2.inRange(hsv, (2, 33, 90), (23, 216,255))
```


<img src="images/hand_inrange.jpeg" width="300" height="300">


### Pink cup


<img src="images/cup_original.jpeg" width="300" height="300">


```sh
img = cv2.imread("cup_original.jpeg")
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)
mask = cv2.inRange(hsv, (0, 154, 0), (255, 255,255))
```


<img src="images/cup_inrange.jpeg" width="300" height="300">



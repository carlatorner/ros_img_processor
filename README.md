## ros_img_processor
Just a simple template node receivng an image and doing something. Links to OpenCV and ROS wrapped.

## How to run the code
In a terminal window, type:
```sh
$ roslaunch ros_img_processor ros_img_processor.launch
```

## Tip
Check your webcam encodings (yuyv,mjpeg,...) and set them accordingly at file launch/usb_camera.launch


## Modificaciones
Se ha añadido al codigo la detección de circulos utilizado anteriormente, y se ha calculado la dirección del vector (ray direction), multiplicando la inversa de la matriz K y el centro del circulo.

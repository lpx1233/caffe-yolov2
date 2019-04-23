# caffe-yolov2-aur

Specialized aur version for arch/manjaro installation with opencv4

## Reference

> YOLO9000: Better, Faster, Stronger

> http://pjreddie.com/yolo9000/

> https://github.com/yeahkun/caffe-yolo

> https://github.com/hustzxd/z0

> https://github.com/hustzxd/z1

> https://github.com/weiliu89/caffe.git

> https://github.com/gklz1982/caffe-yolov2

## modifications

1. add reorg_layer

2. convert yolo weights to caffemodel

3. add detection output layer

4. add detection evaluate layer

## Usage

### convert model

`cd examples/indoor/convert`

1. convert yolo.cfg to yolo.prototxt
2. convert yolo weights to caffemodel

`python convert_weights_to_caffemodel.py yolo.prototxt yolo.weights yolo.caffemodel`


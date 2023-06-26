The YOLOv4-tiny source code used in this study was obtained from https://github.com/AlexeyAB/darknet; the same website also provided pretrained weights. The following command trains a model for a feature using configuration files in this repository.

darknet.exe detector train _feature_name\\custom.data_ _configuration_file_ yolov4-tiny.conv.29 -map

yolov4-tiny.conv.29 is the pretrained weights files and can be download from https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.conv.29

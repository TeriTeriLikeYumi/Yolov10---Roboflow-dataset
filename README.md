# Yolov10---Roboflow-dataset

## How to run the model
```python
  yolo predict model=jameslahm/yolov10{n/s/m/b/l/x}
```
from ultralytics import YOLOv10

model = YOLOv10.from_pretrained('jameslahm/yolov10{n/s/m/b/l/x}')
# or
```python
# wget https://github.com/THU-MIG/yolov10/releases/download/v1.1/yolov10{n/s/m/b/l/x}.pt
model = YOLOv10('yolov10{n/s/m/b/l/x}.pt')
model.predict()
```

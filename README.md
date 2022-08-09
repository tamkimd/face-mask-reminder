# face-mask-reminder
Detect and remind to wear a face mask
# Data
* <a href="https://drive.google.com/file/d/17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb/view?usp=sharing" target="_blank">data.zip</a>
* !gdown --id 17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb
*  classes : with_mask , no_mask
* Data has been converted to yolo txt format from https://www.kaggle.com/datasets/andrewmvd/face-mask-detection
# Train
     face_mask.pt 4Mb  mAP@0.5 0.982
Result after 100 epochs
    
# Run
      python yolov5/detect.py --source 0 --weights face_mask.pt  --view-img --lang vi --time-remind 4
* --lang vi or en: Audio reminder in Vietnamese or English language
* --time-remind: time between 2 reminders
### Reference

* [YOLOv5](https://github.com/ultralytics/yolov5)

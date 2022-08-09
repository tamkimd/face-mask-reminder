# face-mask-reminder
detect and remind to wear a face mask
# Data
* <a href="https://drive.google.com/file/d/17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb/view?usp=sharing" target="_blank">data.zip</a>
* !gdown --id 17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb
*  classes : with_mask , no_mask
* Data has been converted to yolo txt format from https://www.kaggle.com/datasets/andrewmvd/face-mask-detection
# Run
      python yolov5/detect.py --source 0 --weights yolov5/best.pt  --view-img --lang vi --time-remind 4
* --lang vi or en: Audio reminder in Vietnamese or English language
* --time-remind: time between 2 reminders

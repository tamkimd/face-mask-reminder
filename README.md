# face-mask-reminder
detect and remind to wear face mask
# Data
* <a href="https://drive.google.com/file/d/17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb/view?usp=sharing" target="_blank">data.zip</a>
* !gdown --id 17EjaIIj3YGiemA9cJD2so2i9ZdMIJ5Vb
*  classes : with_mask , no_mask
* Data has been converted to yolo txt format from https://www.kaggle.com/datasets/andrewmvd/face-mask-detection
# run
      python yolov5/detect.py --source 0 --weights yolov5/best.pt  --view-img --lang vi
      
 he

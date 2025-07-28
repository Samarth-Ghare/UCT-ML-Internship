# Project 5: Crop and Weed Detection

**Company**: Uniconverge tech. Pvt. Ltd.  
**Domain**: Agriculture / Computer Vision  
**Tech Stack**: Python, YOLOv5, PyTorch, Google Colab

## 📌 Problem Statement
To detect and classify crops and weeds in agricultural fields using a custom-trained YOLOv5 object detection model. This helps enable smart, selective pesticide spraying to improve efficiency and reduce environmental damage.

## 📁 Dataset
- 1300 labeled images of sesame crops and weeds
- YOLOv5 annotation format (`.txt` labels)
- Resized to 512x512 using data augmentation

## 🚀 Model Details
- Model used: YOLOv5s
- Trained on Google Colab with Tesla T4 GPU
- Image size: 512x512
- Epochs: 50
- Best Precision: 0.83 | Recall: 0.78 | mAP@50: 0.86

## 📊 Results
| Class | Precision | Recall | mAP@50 |
|-------|-----------|--------|--------|
| Crop  | 0.76      | 0.77   | 0.82   |
| Weed  | 0.91      | 0.80   | 0.89   |
| **All** | **0.83** | **0.78** | **0.86** |

## 📂 Outputs
- Trained weights: `best.pt`
- Detection results saved in `runs/detect/exp/`

## 📌 Usage
To detect weeds in new images:
```bash
!python detect.py --weights best.pt --img 512 --conf 0.25 --source path/to/images
```

## 👨‍💻 Author
Samarth Ghare  
Intern at Uniconverge tech. Pvt. Ltd.

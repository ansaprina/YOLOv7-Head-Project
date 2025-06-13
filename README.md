#  Head Detection with YOLOv7

This project uses the YOLOv7 object detection framework to detect human heads in images and videos. It includes both training and inference pipelines implemented in Jupyter notebooks

##  Project Structure

- `YOLOv7.ipynb` — general YOLOv7 detection pipeline 
- `YOLOv7_head.ipynb` — head-specific detection workflow with custom dataset

##  Features

-  Training on custom head detection dataset
-  Inference on images
-  Use of pretrained YOLOv7 weights for fine-tuning
-  Visualization of bounding boxes
-  Export results and measure FPS

##  Quick Start

### 1. Clone YOLOv7 repository

```bash
git clone https://github.com/WongKinYiu/yolov7
cd yolov7
pip install -r requirements.txt
```

### 2. Add notebooks and data

Place `YOLOv7_head.ipynb` and your dataset (`images/`, `labels/`, `data.yaml`) into the repo folder.

### 3. Run the notebook

Use Jupyter or Google Colab:

```bash
jupyter notebook YOLOv7_head.ipynb
```

Modify training paths, batch size, and number of epochs as needed.

##  Sample Results

- FPS: ~xx (on GPU)
- mAP@0.5: ~xx% after fine-tuning



##  Dependencies

- Python 3.8+
- PyTorch
- OpenCV
- Jupyter
- YOLOv7 (official repo)

##  Credits

Based on the [YOLOv7](https://github.com/WongKinYiu/yolov7) repository by Wong Kin Yiu.

---

Made for academic purposes.

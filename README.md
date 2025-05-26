
# 🧠 YOLO Real-Time Object Detection with Webcam

This Python project uses the **Ultralytics YOLO model** to perform **real-time object detection** using your **webcam**. It's based on the powerful and fast `YOLOv5` model (`yolov5su.pt`).

---

## 🚀 Features

- Real-time object detection from your webcam.
- Displays bounding boxes, class names, and confidence scores.
- Lightweight and easy to modify for your custom use cases.

---

## 📦 Requirements

Install the required dependencies using:


```bash
pip install ultralytics opencv-python
````

---

## 🧠 Model

This project uses the `yolov5su.pt` model. Make sure it's in the same folder or replace it with any other YOLOv8 model like:

```python
model = YOLO('yolov8n.pt')
```

You can download models from [Ultralytics GitHub](https://github.com/ultralytics/ultralytics).

---

## 🖥️ How to Run

```bash
python text.py
```

Press **`q`** to exit the detection window.

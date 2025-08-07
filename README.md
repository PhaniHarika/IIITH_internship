This repository documents my internship project, where I developed a complete computer vision pipeline to detect and segment surgical instruments in live surgery videos using the **YOLOv8 framework**.

The project was completed over 5 structured tasks, each focusing on a specific stage of the pipeline — from image/frame segmentation to model training and video reconstruction.

---

## 📌 Project Goals

- Learn and apply YOLOv8 for object detection and segmentation
- Handle real-world medical data (images & videos)
- Build modular, reusable steps for video-based detection
- Train a custom YOLO model on annotated surgical data
- Prepare a research-grade project workflow

---

## 🧠 Tasks Overview

| Task No. | Title                                   | Description |
|----------|-----------------------------------------|-------------|
| **Task 1** | [Segment Local Images](./Task1_Segmentation_Local_Images) | Performed YOLOv8 segmentation on a folder of static local images |
| **Task 2** | [Download & Split Video into Frames](./Task2_Video_Download_and_Frame_Split) | Downloaded or used surgical video, and extracted frames using FFmpeg |
| **Task 3** | [Frame-wise Segmentation](./Task3_Framewise_Segmentation) | Applied segmentation model on each extracted frame |
| **Task 4** | [Reconstruct Segmented Video](./Task4_Reconstruct_Segmented_Video) | Combined segmented frames back into a single output video |
| **Task 5** | [Train Custom YOLOv8 Model](./Task5_Model_Training_Surgical_Instrument_Detection) | Trained YOLOv8n on Roboflow dataset of annotated surgical instruments |

---

## 🧪 Technologies Used

- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- Python
- OpenCV
- FFmpeg
- Google Colab
- Roboflow (for dataset)
- Git & GitHub

If results.ipynb doesn’t render on GitHub, download or open it in Colab for full view
▶️ [View Results Notebook in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Task5_Results.ipynb)

---

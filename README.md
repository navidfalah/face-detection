# Face Detection with Detectron2 🖼️👤

This project performs **face detection** using the **Detectron2** library, a state-of-the-art object detection framework by Facebook AI Research. The goal is to detect faces in images and visualize the results with bounding boxes. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **Detectron2** for face detection in images. 🤖📸
- Downloads and processes images from a dataset containing face annotations. 🕸️📥
- Visualizes detected faces with bounding boxes using Detectron2's visualizer tools. 📊🖼️

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install pyyaml==5.1
!git clone 'https://github.com/facebookresearch/detectron2'
!python -m pip install -e detectron2
!pip install torch torchvision
!pip install opencv-python tqdm pandas requests
```

---

## Usage 🖥️

1. **Download Dataset**: The script downloads images from a dataset containing face annotations.
2. **Preprocess Data**: Images are saved locally, and annotations are processed for Detectron2.
3. **Train/Test Model**: A pre-trained Detectron2 model is used for face detection.
4. **Visualize Results**: Detected faces are visualized with bounding boxes.

---

## Code Structure 🗂️

- **Data Collection**:
  - Downloads images and annotations from a dataset.
  - Saves images locally and processes annotations for Detectron2.

- **Face Detection**:
  - Uses a pre-trained Detectron2 model for face detection.
  - Visualizes detected faces with bounding boxes.

- **Visualization**:
  - Displays images with detected faces and bounding boxes.

---

## Results 📊

- **Detected Faces**: The model detects faces in images and draws bounding boxes around them.
- **Visualization**: Images with detected faces are displayed for analysis.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model detecting faces in an image:

```plaintext
Image: face_0.jpg
Detected Faces: 2
```

---

## Dependencies 📦

- `detectron2`
- `torch`
- `torchvision`
- `opencv-python`
- `tqdm`
- `pandas`
- `requests`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝

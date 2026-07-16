# Real-Time vehicle Detection & Real-Time Person Detection 

A computer vision project combining **YOLOv8** (person detection)  analyze people in a live webcam feed in real time.

## What it does

1. Detects vehicle in a static test image using YOLOv8 as a sanity check
2. Detects people in a live webcam feed and draws bounding boxes around them

## Setup

```bash
pip install -r requirements.txt
```

Place a test image in `assets/` and update the path in the notebook, or use your own.

## Run

Open `person-detection-vehicle-recognition.ipynb` in Jupyter. Sections 1–2 (static image) run anywhere. **Sections 3–4 require a local webcam** and will not run in a hosted/cloud notebook environment (Colab, Kaggle, etc.) — run them with a local Jupyter install.

## Notes

This project analyzes live webcam footage for learning purposes only, it isn't deployed against footage of other people, and DeepFace's predictions are statistical estimates rather than ground truth about any individual.

## Tech Stack

`Python` · `OpenCV` · `Ultralytics YOLOv8` · `DeepFace` · `Matplotlib`

## Lets Connect :
- Gamil : sandipsubedi012@gmail.com
- Instagram : sandipsubedi0

# Vision Object Detection

Python FastAPI computer-vision API for object detection with bounding boxes.

Runs Ultralytics YOLOv8 Nano locally, returns class labels, confidence scores, and coordinates, and can overlay detections for the demo UI.

## Stack

- **Backend:** Python 3.11+, FastAPI, Uvicorn
- **AI / CV:** Ultralytics YOLOv8 Nano, OpenCV, Pillow
- **Frontend (optional demo UI):** React + Vite

## Features

- Image upload or sample scene detection
- Bounding boxes with class counts
- Local inference (weights download on first run)

## Quick start

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8006
```

API docs: http://localhost:8006/docs

```bash
cd frontend
npm install
npm run dev
```

## Author

Pooja Sharma — [Pooja101117](https://github.com/Pooja101117)

# Object Detector (COCO YOLOv8n)

Ready-to-deploy browser-based object detector.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g., `yolo-detector`)
2. Clone it locally
3. Copy all files from this folder into the repo root
4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Add YOLO detector"
   git push origin main
   ```
5. Go to **Settings > Pages > Source: Deploy from branch (main, / root)**
6. Wait 1-2 min, then open: **https://<your-username>.github.io/<repo-name>/**
7. On your phone:
   - Allow camera access
   - Point at objects → see detections in real-time!

## Controls

- **Confidence Slider**: Min confidence threshold (0.10 - 0.95)
- **IoU Slider**: Non-Maximum Suppression threshold (0.20 - 0.95)
- Higher confidence = fewer false positives, maybe miss small objects
- Higher IoU = keep more overlapping boxes

## What it detects

80 COCO classes: person, car, dog, cat, bicycle, bus, truck, phone, laptop, etc.

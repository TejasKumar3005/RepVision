# Zen-style Exercise Rep Counter — Vision ML (IIT Delhi COP290)

Count exercise repetitions **live from a camera** using pose-estimation keypoints. Design-course project (COP290) built around PoseNet-style models.

## What it does

- Detects body keypoints frame-by-frame
- Tracks joint angles / trajectories for common movements
- Increments a **rep counter** when a full movement cycle is recognized
- Aimed at a clean fitness-demo UX (see also the related Zenfit website repo)

## Stack

- Python demo path (`run.py`) with PoseNet conversion utilities
- Browser / TF.js lineage for on-device pose models
- OpenCV-style camera loop for the live counter

## Run

```bash
pip install -r requirements.txt
python run.py
```

## Course

**COP290 — Design Practices**, IIT Delhi

## License

Coursework / educational use. Upstream PoseNet bits retain their original licenses.

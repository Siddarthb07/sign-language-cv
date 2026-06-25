# sign-language-cv

OpenCV + MediaPipe pipeline for **real-time hand landmark extraction** from webcam video. Train a small classifier on **your own** labelled gesture clips.

## Status

**Early scaffold — no implementation code yet.** This repo documents intent and setup steps. Code lands in a future push.

Planned layout:

```
sign-language-cv/
├── scripts/capture.py      webcam frame + landmark export
├── scripts/train.py        sklearn classifier on saved landmarks
├── data/                   user-collected labelled clips (gitignored)
└── demo/                   inference + optional GIF export
```

## Quick start (verify deps)

```bash
python -m venv .venv
.\.venv\Scripts\activate   # Windows
pip install opencv-python mediapipe numpy scikit-learn joblib
python -c "import mediapipe as mp; print('ok')"
```

Roadmap: fingerspelling A–Z first, then word-level gestures.

## Related work

Archived gesture demos: [cv2-volume-control](https://github.com/Siddarthb07/cv2-volume-control) (system volume via hand gestures).

## License

MIT · Siddarth Boggarapu

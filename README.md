# sign-language-cv

OpenCV + MediaPipe pipeline for **real-time hand landmark extraction** from webcam video. Train a small classifier on **your own** labelled gesture clips.

## Status

Scaffold — collect samples, train (`scripts/train.py` once added), export a demo GIF. Resume CV project listed on my dossier.

## Quick start (landmarks only)

```bash
python -m venv .venv
.\.venv\Scripts\activate   # Windows
pip install opencv-python mediapipe numpy scikit-learn joblib
python -c "import mediapipe as mp; print('ok')"
```

Roadmap: fingerspelling A–Z first, then word-level gestures.

## License

MIT · Siddarth Boggarapu

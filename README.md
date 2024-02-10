# pyannote-3.1-offline
This makes the raw pytorch `.bin` models offline, but it still does require the `pyannote-audio==3.1.1` library.

From inside a `venv`:
```
pip install pyannote-audio==3.1.1
```

Then, in the diarization Python script:
```
pipeline = Pipeline.from_pretrained("/home/e6quisitory/pyannote-3.1-offline/config.yaml")
```

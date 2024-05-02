# STT_Whisper
A quick implementation of voice recording through a microphone for OpenAI Whisper

# Installation
1) Install Python dependencies
```sh
pip install -r requirements.txt
```

2) Install ffmpeg

# Usage (CLI)
```sh
python3 main.py
```

OTHER ARGUMENTS:
`--model` -> The name of the Whisper model to use (default base)

# Usage (Library)
Clone STT_Whisper into your project

```python3
from STT_whisper.main import whisper_microphone_transcribe

result = whisper_microphone_transcribe() # Decoded text at result.text
```

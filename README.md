# realtime-voice-transcription
Display a rolling view of parsed text as it comes in from a a microphone.

Create a virtual enviornment and enter it

Windows:
```
python -m venv venv
./venv/Scripts/activate
```
Linux:
```
python3 -m venv venv
source venv/bin/activate
```

Install dependencies
```
pip install -r requirements.txt
```

Note that pyaudio is very hardware specific so may require further steps (installing portaudio for example)
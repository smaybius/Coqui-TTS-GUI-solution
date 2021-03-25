# Coqui TTS GUI solution
Graphical user interface by AceOfSpadesProduc100 for using TTS and vocoder models in the form of a text editor, made using Tkinter.
This is an addon for TTS 0.0.10, as it should hopefully already be part of the version after it.
![Preview](./Screenshot_2021-03-22_173624.png)

## How to use
- Download or clone from this repository: https://github.com/coqui-ai/TTS
- Copy gui.py and synthesize.py into TTS/bin, overwriting the existing synthesize.py
- (Linux users) Install the following:
```bash
sudo apt install python3-tk
sudo apt-get install -y python3-dev libasound2-dev
```
- Install from source as explained in the repository's readme: 
```bash
pip install -e .
```
- Install simpleaudio:
```bash
pip install simpleaudio
```
- Run the following command:
```bash
tts --start_gui
```

## Major TODOs
- Solve all Linter errors in the pull request for TTS

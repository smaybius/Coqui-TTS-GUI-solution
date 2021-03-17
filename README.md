# Coqui TTS GUI solution
Graphical user interface by AceOfSpadesProduc100 for using TTS and vocoder models in the form of a text editor, made using Tkinter.
![Preview](./Screenshot_2021-03-13_185326.png)

## How to install
- Download or clone from this repository: https://github.com/coqui-ai/TTS
- Run the following under "Install TTS" in the repostory's readme, and then run the following below:
```bash
pip install playsound
```
- Copy coqui_tts_gui.py into the TTS/bin folder.
## How to use
WARNING: DO NOT run this from IDLE or directly in Python such as double-clicking the file, it will be stuck loading. To be safe, run the following:
```bash
python coqui_tts_gui.py
```
## Major TODOs
- Consist the models comboboxes of what's read from models.json instead of hardcoding them
- Solve all Linter errors in the pull request for TTS

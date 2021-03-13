# Mozilla TTS GUI solution
Graphical user interface by AceOfSpadesProduc100 for using TTS and vocoder models in the form of a text editor, made using Tkinter.
![Preview](./Screenshot_2021-03-13_155111.png)

## How to install
- Download or clone from this repository: https://github.com/mozilla/TTS
- Run the following under "Install TTS" in the repostory's readme, and then run the following below:
```bash
pip install playsound
```
- Copy mozilla-tts-gui.py into the TTS repository's folder
## How to use
WARNING: DO NOT run this from IDLE or directly in Python such as double-clicking the file, it will be stuck loading. To be safe:
```bash
python mozilla-tts-gui.py
```
To add new models to the GUI, run `TTS --list_models` and compare the output to the lists in the dropdown boxes, and add what's missing in the latter:
```python
ttsmodelbox['values'] = ('en/ljspeech/glow-tts',  
                          'en/ljspeech/tacotron2-DCA', 
                          'en/ljspeech/speedy-speech-wn', 
                          'es/mai/tacotron2-DDC', 
                          'fr/mai/tacotron2-DDC') 
                          
vocodermodelbox['values'] = ('universal/libri-tts/wavegrad',  
                          'universal/libri-tts/fullband-melgan', 
                          'en/ljspeech/multiband-melgan')
```

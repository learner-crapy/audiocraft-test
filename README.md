# audiocraft-test

https://github.com/facebookresearch/audiocraft

```
conda create -n audiocraft python==3.10 -y

conda activate audiocraft

git clone https://github.com/facebookresearch/audiocraft.git 

cd audiocraft

pip install -e .

conda install "ffmpeg<5" -c conda-forge

python -m demos.musicgen_app
```

```
# with public link
python -m demos.musicgen_app --share
```






## The errors and solutions

**AttributeError: module 'gradio' has no attribute 'make_waveform'**

import gradio
gradio.__version__
'5.13.1'

`pip install gradio==4.44.1`



ERROR: Failed building wheel for pesq

windows

conda install -c conda-forge pesq



OSError: Can't load tokenizer for 't5-base'.

server

models--t5-base

models--facebook--encodec_32khz

## device

**2080ti**


https://4bb0a5d62b8fc10486.gradio.live



| model                                 | download | level | run  |
| ------------------------------------- | -------- | ----- | ---- |
| facebook/musicgen-melody              | F        |       | T    |
| facebook/musicgen-medium              | T        | 7/10  | T    |
| facebook/musicgen-small               | T        | 5/10  | T    |
| facebook/musicgen-large               | T        |       | T    |
| facebook/musicgen-melody-large        | T        |       | T    |
| facebook/musicgen-stereo-small        | T        |       | T    |
| facebook/musicgen-stereo-medium       | T        | 5/10  | T    |
| facebook/musicgen-stereo-melody       | T        |       | T    |
| facebook/musicgen-stereo-large        | T        |       | T    |
| facebook/musicgen-stereo-melody-large | T        |       | T    |



4090



https://7be9c1fa2211d86cfc.gradio.live



| model                                 | download | level | run  |
| ------------------------------------- | -------- | ----- | ---- |
| facebook/musicgen-melody              | F        |       | T    |
| facebook/musicgen-medium              | T        | 7/10  | t    |
| facebook/musicgen-small               | T        | 5/10  | T    |
| facebook/musicgen-large               | T        |       | F    |
| facebook/musicgen-melody-large        | T        |       | F    |
| facebook/musicgen-stereo-small        | T        |       | F    |
| facebook/musicgen-stereo-medium       | T        | 5/10  | T    |
| facebook/musicgen-stereo-melody       | T        |       |      |
| facebook/musicgen-stereo-large        | T        |       | F    |
| facebook/musicgen-stereo-melody-large | T        |       | F    |



unlv server 

https://autohealth.ngrok.dev/


## others
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

```
ffmpeg -i audio.mp3 -ss 10 -to 40 -c copy output.mp3
```

## Fine-tuning
### dataset
https://drive.google.com/drive/folders/1bA4D2y_LsLiOI18EX9NMkuVstg8Z1NES?usp=sharing

path: My Drive/MU/train




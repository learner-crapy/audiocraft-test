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





https://74c5b432ff1e2fcf3a.gradio.live



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







4090



https://6c15d5254f010b4488.gradio.live/



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

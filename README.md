# STSA: Spatial-Temporal Semantic Alignment for Facial Visual Dubbing

Pytorch implementation for our ICME2025 submission "STSA: Spatial-Temporal Semantic Alignment for Facial Visual Dubbing".

<!-- <img src='./pbf.png' width=900> -->

## Demo:
### Long Video Generation Compared with SOTA Methods
Ours:
<video width="600" controls>
  <source src="https://github.com/user-attachments/assets/b7fb5bfd-7a15-4f73-a7e2-83916165c54c" type="video/mp4">
</video>


---
## Inference:
### Requirements
- Python 3.8.7
- torch 1.12.1
- torchvision 0.12.1
- librosa 0.9.2
- ffmpeg

### Prepare Environment
First create conda environment:
```
conda create -n stsa python=3.8
conda activate stsa
```
[Pytorch](https://pytorch.org/)  1.12.1 is used, other requirements are listed in "requirements.txt". Please run:
```
pip install -r requirements.txt
```
### Quick Start
Run the following command:
```
python inference.py --video_path "demo_templates/video/speakerine.mp4" --audio_path "demo_templates/audio/education.wav"
```
You can specify the `--video_path` and `--audio_path` option to inference other videos.

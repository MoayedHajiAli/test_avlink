# AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation
[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://snap-research.github.io/AVLink/)
[![arXiv](https://img.shields.io/badge/arXiv-2311.18822-b31b1b)](#TODO)


<div>
https://private-user-images.githubusercontent.com/52598644/396864167-f5114207-c098-4f00-864e-3a4eb24fa08a.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQ1MTc5NTQsIm5iZiI6MTczNDUxNzY1NCwicGF0aCI6Ii81MjU5ODY0NC8zOTY4NjQxNjctZjUxMTQyMDctYzA5OC00ZjAwLTg2NGUtM2E0ZWIyNGZhMDhhLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjE4VDEwMjczNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM4MWZmNTJiMGNiZGFkZWQ0NmY4MDE4M2EyNGQzZmIwZTI4ZTAzMzI5YjRmNzQxZjFlNzk4NGRjOTE3MzQzM2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.6RWEjQtObTEklwxg3Q8T4KbSIgyGVmghEshPJkYWIEc
</div>

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1040336513?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="teaser"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


# AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation
<div align="justify">
<b>Abstract</b>: We propose AV-Link, a unified framework for Video-to-Audio and Audio-to-Video generation that leverages the activations of frozen video and audio diffusion models for temporally-aligned cross-modal conditioning. The key to our framework is a Fusion Block that enables bidirectional
information exchange between our backbone video and audio diffusion models through a temporally-aligned self attention operation. Unlike prior work that uses feature extractors pretrained for other tasks for the conditioning signal, AV-Link can directly leverage features obtained by the
complementary modality in a single framework i.e. video features to generate audio, or audio features to generate
video. We extensively evaluate our design choices and demonstrate the ability of our method to achieve synchronized and high-quality audiovisual content, showcasing its potential for applications in immersive media generation. For more details, please visit our <a href='https://snap-research.github.io/AVLink/'>project webpage</a> or read our 
<a href='#TODO'>paper</a>.
</div> 
<br>


# Issues
If you have any questions about AV-Link, please open an issue in this GitHub page or send your questions to `mh155@rice.edu`

# Project Page Template
a template of our project page can be found under `docs` directory

## Citation
If you find this paper useful in your research, please consider citing:
```
TODO
```
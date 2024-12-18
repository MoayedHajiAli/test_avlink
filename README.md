# AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation
[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://snap-research.github.io/AVLink/)
[![arXiv](https://img.shields.io/badge/arXiv-2311.18822-b31b1b)](#TODO)


Results:
<table class='center'>
<tr>
  <td>

https://github-production-user-asset-6210df.s3.amazonaws.com/134203169/342309262-d7c89984-c567-4ca7-8e2d-8f49d84bda4a.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240624%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240624T122032Z&X-Amz-Expires=300&X-Amz-Signature=5b13f216056dedca2705233038dbb22f73023d2c1deaf3b03972d7b91c1bbab5&X-Amz-SignedHeaders=host&actor_id=134203169&key_id=0&repo_id=812946188

 </td>

</table>



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
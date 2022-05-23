# <center> Text-to-sound Synthesis </center>

<center> Dongchao Yang<sup>1</sup>, Jianwei Yu<sup>2</sup>, Chao Weng<sup>2</sup>, Yuexian Zou<sup>1</sup> </center> 
 
<center> 1 Peking University </center>

<center> 2 Tencent AI Lab</center>

## Introduction
This is a [demo](https://github.com/yangdongchao/text-to-sound-synthesis-demo/) for our paper **_Text-to-sound Synthesis_**. In the following, we will show some generated samples by our proposed method.

## Examples

### The comprarison betwween generated and real audios

| <center>Text description</center> | <center>generated samples</center> | <center>Original samples</center> |
| :--- | :--- | :--- |
|A man speaks as crickets sing|<audio src="samples1/YryFDPxgDOGc_mel_sample_0.wav" controls preload></audio>|<audio src="samples1/YryFDPxgDOGc.wav" controls preload></audio>|
|Corresponding Mel-spectrograms|<img src="Pic/YryFDPxgDOGc_g0.png"/>|<img src="Pic/YryFDPxgDOGc_org.png"/>|
|A person is snoring while sleeping|<audio src="samples1/YsLkeqCDJIyw_mel_sample_1.wav" controls preload></audio>|<audio src="samples1/YsLkeqCDJIyw.wav" controls preload></audio>|
|Corresponding Mel-spectrograms|<img src="Pic/YsLkeqCDJIyw_g1.png"/>|<img src="Pic/YsLkeqCDJIyw_org.png"/>|
|Birds and insects make noise during the daytime
|<audio src="samples1/Yvms5XGTDVQc_mel_sample_1.wav" controls preload></audio>|<audio src="samples1/Yvms5XGTDVQc.wav" controls preload></audio>|
|Corresponding Mel-spectrograms|<img src="Pic/Yvms5XGTDVQc_g1.png"/>|<img src="Pic/Yvms5XGTDVQc_orf.png"/>|
|A dog barks and whimpers|<audio src="samples1/YsShpyu2l4YQ_mel_sample_9.wav" controls preload></audio>|<audio src="samples1/YsShpyu2l4YQ.wav" controls preload></audio>|
|Corresponding Mel-spectrograms|<img src="Pic/YsShpyu2l4YQ_g1.png"/>|<img src="Pic/YsShpyu2l4YQ_org.png"/>|

### Other generated samples
* **Sample 1**
    * **Text input**
    _An engine idles consistently before sputtering some_
    * **Generated sound**
    <audio src="demo1/YrwT__ERCUno_mel_sample_0.wav" controls="controls">ERROR</audio>
---
* **Sample 2**
    * **Text input**
    _A man talks followed by a woman shouting_
    * **Generated sound**
    <audio src="demo1/Ys3cT_DAj31g_mel_sample_0.wav" controls="controls">ERROR</audio>
---
### Links

[[Paper](https://arxiv.org/abs/2204.01355)] [[Bibtex](bib.txt)] [[Demo GitHub](https://github.com/ZhaZhaFon/demo-confusion)]

### References

[1] Delcroix M, Ochiai T, Zmolikova K, et al. Improving speaker discrimination of target speech extraction with time-domain speakerbeam[C]//ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020: 691-695.  
[2] Cosentino J, Pariente M, Cornell S, et al. Librimix: An open-source dataset for generalizable speech separation[J]. arXiv preprint arXiv:2005.11262, 2020.
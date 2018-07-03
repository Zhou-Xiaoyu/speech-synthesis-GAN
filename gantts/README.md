# Results of TTS and Voice Conversion using GAN

Two folders in the `results` directory: `tts` for TTS and `vc` for Voice Conversion. 
In each experiment, 5 sentences are used as the test set.

Directory structure:

`tts`:
* groundtruth
* baseline
* gan  

gives the ground truth, the synthesized speeches with a traditional method and the results with GAN, respectively.

`vc`:
- source
- target
- baseline
- gan

gives the audios from the source speaker, the target speaker, the converted with a traditional method, and the converted with GAN, respectively.

**For more details, please check the [notebook](http://nbviewer.jupyter.org/github/Zhou-Xiaoyu/speech-synthesis-GAN/blob/master/gantts/notebooks/gantss_results.ipynb).**




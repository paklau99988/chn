# chn

**Speech-Transformer

https://github.com/kaituoxu/Speech-Transformer/issues/2
Does not compile, depents on python 2.7, numerous issues with running the scripts 
Requires Kaldi for feature extraction 

**Python 2.7, trained on both aishell (150 hours) and baidu (1200 hours) 

https://github.com/CynthiaSuwi/ASR-for-Chinese-Pipeline


**Aishell-2 corpus 

https://www.groundai.com/project/aishell-2-transforming-mandarin-asr-research-into-industrial-scale/1


http://www.openslr.org/18/


**ESPNet 

https://zhuanlan.zhihu.com/p/112804998



**DeepSpeech in Mandarin:

https://github.com/PaddlePaddle/DeepSpeech#running-in-docker-container

https://deepspeech.bj.bcebos.com/zh_lm/zh_giga.no_cna_cmn.prune01244.klm
https://nero-mirror.stanford.edu/pypi/web/simple/paddlepaddle-gpu/
Update the lib:
https://nero-mirror.stanford.edu/pypi/web/packages/5f/b0/769cd78f5fdc9de41d760512750e70ace87caea54502882d0818e4b3ce1d/paddlepaddle_gpu-1.6.2.post107-cp27-cp27mu-manylinux1_x86_64.whl#sha256=e09b0ccf009c14984676ea535b94e5bc1b05e6ce3f80c332c464fcd1474a6067

2020-06-17 05:32:48,777-INFO: begin to initialize the external scorer for decoding
2020-06-17 05:32:48,873-INFO: language model: is_character_based = 1, max_order = 5, dict_size = 0
2020-06-17 05:32:48,873-INFO: end initializing scorer
2020-06-17 05:32:48,873-INFO: start inference ...
W0617 05:33:02.716257   374 device_context.cc:236] Please NOTE: device: 0, CUDA Capability: 60, Driver API Version: 10.1, Runtime API Version: 10.0
W0617 05:33:02.719714   374 device_context.cc:244] device: 0, cuDNN Version: 7.5.
W0617 05:33:02.719738   374 device_context.cc:270] WARNING: device: 0. The installed Paddle is compiled with CUDNN 7.6, but CUDNN version in your machine is 7               .5, which may cause serious incompatible bug. Please recompile or reinstall Paddle with compatible CUDNN version.

{"audio_filepath": "/data_aishell/wav/test/S0765/BAC009S0765W0371.wav", "duration": 5.118875, "text": "中国的冬季运动还处于半起步阶段"}

Reporting real CER
http://cs230.stanford.edu/projects_winter_2020/reports/32618697.pdf

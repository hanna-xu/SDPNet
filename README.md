# SDPNet
A Deep Network for Pan-sharpening with Enhanced Information Representation
<div align=center><img src="https://github.com/hanna-xu/SDPNet/blob/master/ex.png" width="980" height="250"/></div><br>

## To test with the pretrained model:
run test.py

## To train:
* Step 1: download the [h5 file]() or create your own h5 file according to [it](https://github.com/hanna-xu/utils).
* Step 2: run P2MS_main.py and MS2P_main.py for P2MS and MS2P models
* Step 3: run spec_main.py and spat_main.py for spatial and spectral encoder and decoders 
* Step 4: run spec_diff.py and spat_diff.py for unique channels
* Step 5: run main.py for training (2 GPUs are needed)

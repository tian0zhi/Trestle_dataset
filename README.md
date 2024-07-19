# Trestle_dataset 栈桥数据集
Trestle_dataset （acoustic signal） of 《Modulation Recognition of Underwater Acoustic Signals Using Deep Hybrid Neural Networks》 & 《One2ThreeNet: An automatic microscale-based modulation recognition method for underwater acoustic communication systems》.

文章《Modulation Recognition of Underwater Acoustic Signals Using Deep Hybrid Neural Networks》与《One2ThreeNet: An automatic microscale-based modulation recognition method for underwater acoustic communication systems》所使用的栈桥数据集。

[This goole drive_link](https://drive.google.com/drive/folders/1GAYwajIOMRHBeA9ZHiVn9o6GGMKWwOlL)


## Introduction：
The Trestle underwater acoustic signal dataset was collected on August 13, 2020, in the shallow coastal area of the Trestle scenic spot in the Shinan District, Qingdao City, Shandong Province, China. 

Modulation types：
OFDM, 2PSK, 4PSK, 2FSK, 4FSK, 16QAM, 64QAM

Sample size:	
200 signals for each type of modulation, 1400 signals in total.

Carrier frequency:
14000Hz

Symbol rate:
560sps

You can use "signal_preproc.m" to preprocess the dataset!

## Citation

If you publish work that uses dataset, please cite paper as follows:

```bibtex
@ARTICLE{9694507,
  author={Zhang, Weilong and Yang, Xinghai and Leng, Changli and Wang, Jingjing and Mao, Shiwen},
  journal={IEEE Transactions on Wireless Communications}, 
  title={Modulation Recognition of Underwater Acoustic Signals Using Deep Hybrid Neural Networks}, 
  year={2022},
  volume={21},
  number={8},
  pages={5977-5988},
  keywords={Feature extraction;Modulation;Underwater acoustics;Convolutional neural networks;Convolution;Wireless communication;Recurrent neural networks;Underwater acoustic signal;modulation recognition;deep hybrid neural network;R&CNN},
  doi={10.1109/TWC.2022.3144608}}

@ARTICLE{10461997,
  author={Wang, Jingjing and Huang, Zihao and Shi, Wei and Mao, Shiwen},
  journal={IEEE Transactions on Wireless Communications}, 
  title={One2ThreeNet: An automatic microscale-based modulation recognition method for underwater acoustic communication systems}, 
  year={2024},
  volume={},
  number={},
  pages={1-1},
  keywords={Feature extraction;Underwater acoustics;Modulation;Symbols;Convolutional neural networks;Communication systems;Receivers;Automatic modulation recognition;convolutional neural network;data augmentation;deep learning;One2ThreeNet},
  doi={10.1109/TWC.2024.3371226}}


```

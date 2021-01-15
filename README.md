# Crowd counting with machine learning techniques

This is the official repository of the seminar paper *Crowd counting with machine learning techniques*, which is part of the IBB master's course at University of Ljubljana, Slovenia. You can read the report [here](https://github.com/tersekmatija/crowd-counting-cnns/blob/master/tersekmatija_kljunmasa.pdf).

In the paper we analyzed 5 CNN models for crowd counting and combined two to make our improvement. We provide the code of the improved model in a separate repository and we link the official implementations and papers of other models.

This repository contains the paper, links to the used models, and link to the datasets.

## Used models
In our paper we analyze:
- CSRNet ([paper](https://arxiv.org/pdf/1802.10062.pdf), [official implementation](https://github.com/leeyeehoo/CSRNet-pytorch))
- Bayesian Crowd Counting ([paper](https://arxiv.org/pdf/1908.03684.pdf), [official implementation](https://github.com/ZhihengCV/Bayesian-Crowd-Counting))
- DM-Count ([paper](https://arxiv.org/pdf/2009.13077.pdf), [official implementation](https://github.com/cvlab-stonybrook/DM-Count))
- SFA-Net ([paper](https://arxiv.org/pdf/1902.01115.pdf), [official implementation](https://github.com/pxq0312/SFANet-crowd-counting))
- SGANet ([paper](https://arxiv.org/pdf/1911.07990.pdf), [official implementation](https://github.com/hellowangqian/sganet-crowd-counting))

Our improvement of the CSRNet:

- Bayesian CSRNet ([implementation](https://github.com/tersekmatija/Bayesian-CSRNet))

We provide the pretrained weights for the mentioned models on [Google drive](https://drive.google.com/drive/folders/1EDdVykHX-rc9IaaOCIGXjiRQJbsgJcdA?usp=sharing), so you can test and evaluate them yourself. Note that you might have to fix some data paths in the official implementations.

## Datasets
In this paper we evaluate the models on ShanghaiTech part A and part B datasets ([download](https://drive.google.com/file/d/17W7sOlXA_RtlDhrMcod8NF8A7-LwdQaw/view?usp=sharing)), as well as UCF-QNRF dataset ([download](https://www.crcv.ucf.edu/data/ucf-qnrf/)).

## Demo
We also provide an online interactive demo on [Heroku](https://ibb-crowd-count.herokuapp.com/). Please bear in mind that the demo uses CPU for evaluation, and due to the Heroku limitations can't process large images.

## Citation
If you use our model or any of the models described in our paper, or the mentioned datasets, please cite them accordingly.
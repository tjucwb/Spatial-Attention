# SA
This is the code about the arxiv paper "parameter-free spatial attention network for Person Re-Identification"

Our code is mainly based on [PCB](https://github.com/syfafterzy/PCB_RPP_for_reID)
## Network
![](https://github.com/schizop/SA/blob/master/network/network.png) 

# Preparation
Prerequisite: Python 2.7 and Pytorch 0.4.0(we run the code under version 0.4.0, maybe versions <= 0.4.0 also work.)
## Dataset
[Market-1501](https://pan.baidu.com/s/1qlCJEdEY7UueGL-VdhH6xw)  提取码: 1ri5
  
# Training
if you are going to train on the dataset of market-1501, run:

```
python2 main.py -d market -b 48 -j 4 --epochs 100 --log logs/market/ --combine-trainval --step-size 40 --data-dir Market-1501
```
also, you can just download a trained [weight file](https://pan.baidu.com/s/1mQkjrJMa1KQmaHax1kAjsw) from BaiduPan 提取码: wwjv

# Results
![](https://github.com/schizop/SA/blob/master/results/result.jpg) 

# Citiaion

Please cite these papers in your publications if it helps your research:
@misc{1811.12150,
Author = {Haoran Wang and Yue Fan and Zexin Wang and Licheng Jiao and Bernt Schiele},
Title = {Parameter-Free Spatial Attention Network for Person Re-Identification},
Year = {2018},
Eprint = {arXiv:1811.12150},
}

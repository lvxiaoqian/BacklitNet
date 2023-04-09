# BacklitNet
Official implement of [BacklitNet: A dataset and network for backlit image enhancement](https://www.sciencedirect.com/science/article/abs/pii/S1077314222000340)

## Abstract
Backlit images are usually taken when the light source is opposite to the camera. The uneven exposure (e.g., underexposure on the foreground and overexposure on the background) makes the backlit images more challenging than general image enhancement tasks that only need to increase or decrease the exposure on the whole images. Compared to traditional approaches, Convolutional Neural Networks perform well in enhancing images due to the abilities of exploiting contextual features. However, the lack of large benchmark datasets and specially designed models impedes the development of backlit image enhancement. In this paper, we build the first large-scale BAcklit Image Dataset (BAID), which contains 3000 backlit images and the corresponding ground truth manually adjusted by trained photographers. It covers a broad range of categories under different backlit conditions in both indoor and outdoor scenes. Furthermore, we propose a saliency guided backlit image enhancement network, namely BacklitNet, for robust and natural restoration of backlit images. In particular, our model innovatively combines a nested U-structure with bilateral grids, which enables fully extracting multiscale saliency information and rapidly enhancing arbitrary resolution images. Moreover, a carefully designed loss function based on prior knowledge of brightness distribution of backlit images is proposed to enforce the network to focus more on backlit regions during the training phase. We evaluate the proposed method on the BAID dataset and two public small-scale backlit image datasets. Experimental results demonstrate that our method performs favorably against the state-of-the-art approaches.

## TODO

- [x] BAID Dataset
- [ ] Test code
- [ ] Training code

## Code 

Coming Soon!


## Dataset
Please refer to: 
* Google Drive: [BAID Dataset](https://drive.google.com/drive/folders/1-M7s5YJSIM7TgcMRwXWGK3GmoMniUoov?usp=sharing)

or

* BaiduYun: [BAID Dataset](https://pan.baidu.com/s/1bc8XozwC2VU8ZLLtpQNpUg), passward: q0qh



## Citation

```
@article{lv2022backlitnet,
  title={BacklitNet: A dataset and network for backlit image enhancement},
  author={Lv, Xiaoqian and Zhang, Shengping and Liu, Qinglin and Xie, Haozhe and Zhong, Bineng and Zhou, Huiyu},
  journal={Computer Vision and Image Understanding},
  volume={218},
  pages={103403},
  year={2022},
  publisher={Elsevier}
}
```

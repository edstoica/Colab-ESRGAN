# Colab-ESRGAN [[Enhanced SRGAN Paper]](https://arxiv.org/abs/1809.00219)
## Simply download `Colab-ESRGAN-(new&old-arch).ipynb` and open it inside your Google Drive or click [here](https://colab.research.google.com/github/styler00dollar/Colab-ESRGAN/blob/master/Colab-ESRGAN-(new&old-arch).ipynb) and copy the file with "File > Save a copy to Drive..." into your Google Drive. 
### 

### Credits
Enhanced Super-Resolution Generative Adversarial Networks by Xintao Wang, [Ke Yu](https://yuke93.github.io/), Shixiang Wu, [Jinjin Gu](http://www.jasongt.com/), Yihao Liu, [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=en), [Yu Qiao](http://mmlab.siat.ac.cn/yuqiao/), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/)

Original Colab file created by shahidul56 can be found [here](https://github.com/xinntao/ESRGAN/pull/22) and [here](https://colab.research.google.com/github/shahidul56/ESRGAN/blob/master/ESRGAN.ipynb). This notebook is a modification by styler00dollar.

Also thanks to [ata4](https://github.com/ata4) for creating [esrgan-launcher](https://github.com/ata4/esrgan-launcher) and [Joey](https://github.com/JoeyBallentine) for further improving that repo. 

#### Important information

- If you can't open `Colab-ESRGAN.ipynb` inside your Google Drive, try this [colab link](https://colab.research.google.com/github/styler00dollar/Colab-ESRGAN/blob/master/Colab-ESRGAN.ipynb) and save it to your Google Drive. The "open in Colab"-button can be missing in Google Drive, if that person never used Colab.
- ESRGAN tutorials and custom models can be found in this [wiki page](https://upscale.wiki/wiki/Main_Page).
- Google Colab does assign a random GPU. It depends on luck.
- The Google Colab VM does have a maximum session length of 12 hours. Additionally there is a 30 minute timeout if you leave colab. The VM will be deleted after these timeouts.

#### BibTeX
<!--
    @article{wang2018esrgan,
        author={Wang, Xintao and Yu, Ke and Wu, Shixiang and Gu, Jinjin and Liu, Yihao and Dong, Chao and Loy, Chen Change and Qiao, Yu and Tang, Xiaoou},
        title={ESRGAN: Enhanced super-resolution generative adversarial networks},
        journal={arXiv preprint arXiv:1809.00219},
        year={2018}
    }
-->    
    @InProceedings{wang2018esrgan,
        author = {Wang, Xintao and Yu, Ke and Wu, Shixiang and Gu, Jinjin and Liu, Yihao and Dong, Chao and Qiao, Yu and Loy, Chen Change},
        title = {ESRGAN: Enhanced super-resolution generative adversarial networks},
        booktitle = {The European Conference on Computer Vision Workshops (ECCVW)},
        month = {September},
        year = {2018}
    }
## Qualitative Results
PSNR (evaluated on the Y channel) and the perceptual index used in the PIRM-SR challenge are also provided for reference.

<p align="center">
  <img src="figures/qualitative_cmp_01.jpg">
</p>
<p align="center">
  <img src="figures/qualitative_cmp_02.jpg">
</p>
<p align="center">
  <img src="figures/qualitative_cmp_03.jpg">
</p>
<p align="center">
  <img src="figures/qualitative_cmp_04.jpg">
</p>


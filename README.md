This is the MXNet version of CDL used in the KDD 2016 hands-on tutorial for MXNet. Note that the code is a simplified version of CDL and is used for demonstration only (you can also find the corresponding IPython notebook). We do not use pretrain and sigmoid activation (as used in the matlab/C++ code for CDL) in this version of code, which may harm the performance.

To run the code, please type in (after installing MXNet):
python cdl.py
in the command line.

More details on the work and some direct extensions can be found at http://wanghao.in/CDL.htm.

Matlab version for full CDL: https://github.com/js05212/CDL.

Data: https://www.wanghao.in/data/ctrsr_datasets.rar.

Slides: http://wanghao.in/slides/CDL_slides.pdf and http://wanghao.in/slides/CDL_slides_long.pdf.

Other implementations (third-party):

[Tensorflow code](https://github.com/gtshs2/Collaborative_Deep_Learning) by [gtshs2](https://github.com/gtshs2).

[Keras code](https://github.com/zoujun123/Keras-CDL) by [zoujun123](https://github.com/zoujun123).

[Python code](https://github.com/xiaoouzhang/Collaborative-Deep-Learning-for-Recommender-Systems) by [xiaoouzhang](https://github.com/xiaoouzhang).

#### Reference:
[Collaborative Deep Learning for Recommender Systems](http://wanghao.in/paper/KDD15_CDL.pdf)
```
@inproceedings{DBLP:conf/kdd/WangWY15,
  author    = {Hao Wang and
               Naiyan Wang and
               Dit{-}Yan Yeung},
  title     = {Collaborative Deep Learning for Recommender Systems},
  booktitle = {SIGKDD},
  pages     = {1235--1244},
  year      = {2015}
}

```
<br>
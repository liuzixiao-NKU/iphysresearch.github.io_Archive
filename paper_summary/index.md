---
title: Paper Summary
date: 2018-08-22
---

[返回到首页](../index.html)

---

![](https://i.loli.net/2018/08/24/5b7fffecd8d1d.png)




> **Please note that these posts are for my future self to review the materials on these papers without reading them all over again.** 
>
> Therefore, the list of contents is only collected due to my own interests.



[TOC]







---



# :rainbow: GW Astronomy

- Rotation-invariant convolutional neural networks for galaxy morphology prediction



# :cloud_with_rain: Denoising & Noise Modeling

> **Collection of popular and reproducible image denoising works**【最新可复现图像去噪算法汇总】
>
> - by Bihan Wen
> - by Wenhan Yang

- [Paper Summary] K He, J Sun, X Tang. "**Single image haze removal using dark channel prior**" (2009)(**CVPR best paper**)([pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.672.3815&rep=rep1&type=pdf))(**何凯明！**)
- [Paper Summary] Olaf Ronneberger, Philipp Fischer, and Thomas Brox "**U-Net: Convolutional Networks for Biomedical Image Segmentation**" arXiv:1505.04597 (2015) **(U-Net)** ([Website](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)) ([code](https://github.com/xuyuting45/DSB2018-mx-unet)) ([code](https://github.com/chinakook/U-Net))
- [Paper Summary] Xiao-Jiao Mao, Chunhua Shen, Yu-Bin Yang. "**Image Restoration Using Convolutional Auto-encoders with Symmetric Skip Connections**" arXiv:1606.08921 (2016) **(Skip connections)** ([code](https://github.com/7wik/convolutional-auto-encoders-with-skip-connections))
- [Paper Summary] F Zhu, G Chen, PA Heng. "**From Noise Modeling to Blind Image Denoising**" CVPR (2016) ([Website](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Zhu_From_Noise_Modeling_CVPR_2016_paper.html))

- [Paper Summary] Fu, X., Huang, J., Ding, X., Liao, Y., Paisley. J "**Clearing the skies: A deep network architecture for single-image rain removal**" arXiv:1609.02087 (2017) (**DerainNet**)
- [Paper Summary] Zhang, H., Sindagi, V., Patel. "**Image de-raining using a conditional generative adversarial network.**" arXiv:1701.05957 (2017) (去雨) (**ID-CGAN**)
- [Paper Summary] R Qian, R T. Tan, W Yang, J Su, J Liu. "**Attentive Generative Adversarial Network for Raindrop Removal from a Single Image**." arXiv:1711.10098 (2017) **(单图去雨)** ([code](http://t.cn/RDfhFhN)) (attentive GAN)
- [Paper Summary] Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky. "**Deep Image Prior**" arXiv:1711.10925 (2017) ([Website](https://dmitryulyanov.github.io/deep_image_prior))
- [Paper Summary] Li, R., Cheong, L.F., Tan, "**Single image deraining using scale-aware multi-stage recurrent network.**" arXiv:1712.06830 (2017)
- [Paper Summary] Jaakko Lehtinen, Jacob Munkberg, Jon Hasselgren, Samuli Laine, Tero Karras, Miika Aittala, Timo Aila "**Noise2Noise: Learning Image Restoration without Clean Data**" arXiv:1803.04189 (2018) (ICML 2018) ([机器之心](https://mp.weixin.qq.com/s/JZaWJzVHXShgTQUuiJlDVA)) ([nvidia](https://news.developer.nvidia.com/ai-can-now-fix-your-grainy-photos-by-only-looking-at-grainy-photos/))
- [Paper Summary] C Chen, Q Chen, J Xu, V Koltun. "**Learning to See in the Dark**" arXiv:1805.01934 (CVPR)(2018)([YouRube](https://www.youtube.com/watch?v=qWKUFK7MWvg&feature=youtu.be))
- [Paper Summary] D Stoller, S Ewert, S Dixon. "**Wave-U-Net: A Multi-Scale Neural Network for End-to-End Audio Source Separation**" arXiv:1806.03185 (**Wave-U-Net**)([code](https://github.com/f90/Wave-U-Net))([code](https://github.com/ShichengChen/WaveUNet))
- [Paper Summary] Jingwen Chen, Jiawei Chen, Hongyang Chao, Ming Yang. "**Image Blind Denoising With Generative Adversarial Network Based Noise Modeling**" CVPR (2018) **(GAN盲降噪)**([Website](http://openaccess.thecvf.com/content_cvpr_2018/html/Chen_Image_Blind_Denoising_CVPR_2018_paper.html))([将门创投](https://mp.weixin.qq.com/s/Vb0sIXC7s0yMRfhZFeC-wg))
- [Paper Summary] S Guo, Z Yan, K Zhang, W Zuo, L Zhang. "**Toward Convolutional Blind Denoising of Real Photographs**" arXiv:1807.04686 (2018) **(CBDNet)** ([code](http://t.cn/Rgrv2Lr ))
- [Paper Summary] Xia Li, Jianlong Wu, Zhouchen Lin, Hong Liu1, and Hongbin Zha. "**Recurrent Squeeze-and-Excitation Context Aggregation Net for Single Image Deraining**." arXiv:1807.05698 (2018) **(单图去雨)** ([code](https://github.com/XiaLiPKU/RESCAN))(RESCAN)





# ---

# :surfer: Survey & Review

- [Paper Summary] LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. "**Deep learning**." **(Three Giants' Survey)**

# :running_man: ImageNet Evolution

> Deep Learning broke out from here

- [[Paper Summary](./ImageNet Classification with Deep Convolutional Neural Networks.html)] Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "**Imagenet classification with deep convolutional neural networks**." (2012). **(AlexNet, Deep Learning Breakthrough!)**
- [Paper Summary] Pierre Sermanet, David Eigen, Xiang Zhang, Michael Mathieu, Rob Fergus, Yann LeCun. "**OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks**" (2013). **(winner of the localization task of ILSVRC2013)**
- [Paper Summary] Simonyan, Karen, and Andrew Zisserman. "**Very deep convolutional networks for large-scale image recognition**." (2014).**(VGGNet,Neural Networks become very deep!)**
- [Paper Summary] Szegedy, Christian, et al. "**Going deeper with convolutions**." (2015).**(GoogLeNet)**
- [Paper Summary] He, Kaiming, et al. "**Deep residual learning for image recognition**." (2015).**(ResNet, Very very deep networks, CVPR best paper)**

# :goal_net: Model Configurations

- [Paper Summary] Hinton, Geoffrey E., et al. "**Improving neural networks by preventing co-adaptation of feature detectors**." (2012). **(Dropout)**
- [Paper Summary] Maas, Andrew L, Hannun, Awni Y, and Ng, Andrew Y. "**Rectifier nonlinearities improve neural network acoustic models.**" Proc. ICML, 30, (2013). **(Leaky ReLU)**
- [Paper Summary] Goodfellow, Ian J., Warde-Farley, David, Mirza, Mehdi, Courville, Aaron C., and Bengio, Yoshua.
  "**Maxout networks.**" In Proceedings of the 30th International Conference on Machine Learning, ICML (2013) **(Maxout "Neuron")**
- [Paper Summary] Graham, Ben. "**Spatially-sparse convolutional neural networks.**" ArXiv e-prints, September 2014c. **(very leaky ReLU)**
- [Paper Summary] Srivastava, Nitish, et al. "**Dropout: a simple way to prevent neural networks from overfitting**." (2014)
- [Paper Summary] X Glorot, Y Bengio. "**Understanding the difficulty of training deep feedforward neural networks**" Proceedings of the thirteenth international conference on artificial intelligence and statistics. (2010) **(Xavier initialization)** 
- [Paper Summary] K He, X Zhang, S Ren, J Sun. "**Delving deep into rectifiers: Surpassing human-level performance on imagenet classification**" Proceedings of the IEEE international conference on computer vision. (2015) **(Leaky ReLU & Xavier initialization with additional factor)**
- [Paper Summary] Ioffe, Sergey, and Christian Szegedy. "**Batch normalization: Accelerating deep network training by reducing internal covariate shift**." (2015).**(An outstanding Work in 2015)**
- [Paper Summary] DA Clevert, T Unterthiner, S Hochreiter. "**Fast and accurate deep network learning by exponential linear units (elus)**" arXiv:1511.07289 (2015)
- [Paper Summary] Ba, Jimmy Lei, Jamie Ryan Kiros, and Geoffrey E. Hinton. "**Layer normalization**." (2016).**(Update of Batch Normalization)**
- [Paper Summary] Courbariaux, Matthieu, et al. "**Binarized Neural Networks: Training Neural Networks with Weights and Activations Constrained to+ 1 or−1**." **(New Model,Fast)**
- [Paper Summary] Jaderberg, Max, et al. "**Decoupled neural interfaces using synthetic gradients**." (2016). **(Innovation of Training Method,Amazing Work)**
- [Paper Summary] Chen, Tianqi, Ian Goodfellow, and Jonathon Shlens. "Net2net: Accelerating learning via knowledge transfer."(2015).**(Modify previously trained network to reduce training epochs)**
- [Paper Summary] Wei, Tao, et al. "**Network Morphism.**" (2016). **(Modify previously trained network to reduce training epochs)**



# :skier: Optimization

- [Paper Summary] J Bergstra, Y Bengio. "**Random search for hyper-parameter optimization**" Journal of Machine Learning Research, (2012) **(Hyperparameter Optimization: Random search)**

- [Paper Summary] Sutskever, Ilya, et al. "**On the importance of initialization and momentum in deep learning**." (2013) **(Momentum optimizer)**
- [Paper Summary] Kingma, Diederik, and Jimmy Ba. "**Adam: A method for stochastic optimization**." (2014). **(Maybe used most often currently)**
- [Paper Summary] Andrychowicz, Marcin, et al. "**Learning to learn by gradient descent by gradient descent**." (2016).**(Neural Optimizer,Amazing Work)**
- [Paper Summary] Han, Song, Huizi Mao, and William J. Dally. "**Deep compression: Compressing deep neural network with pruning, trained quantization and huffman coding**." (2015). **(ICLR best paper, new direction to make NN running fast,DeePhi Tech Startup)**
- [Paper Summary] Iandola, Forrest N., et al. "**SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and< 1MB model size**." (2016).**(Also a new direction to optimize NN,DeePhi Tech Startup)**



# :tv: Understanding / Generalization / Transfer

- **Distilling the knowledge in a neural network** (2015), G. Hinton et al. [[pdf\]](http://arxiv.org/pdf/1503.02531)
- **Deep neural networks are easily fooled: High confidence predictions for unrecognizable images** (2015), A. Nguyen et al. [[pdf\]](http://arxiv.org/pdf/1412.1897)
- **How transferable are features in deep neural networks?** (2014), J. Yosinski et al. [[pdf\]](http://papers.nips.cc/paper/5347-how-transferable-are-features-in-deep-neural-networks.pdf)
- **CNN features off-the-Shelf: An astounding baseline for recognition** (2014), A. Razavian et al. [[pdf\]](http://www.cv-foundation.org//openaccess/content_cvpr_workshops_2014/W15/papers/Razavian_CNN_Features_Off-the-Shelf_2014_CVPR_paper.pdf)
- **Learning and transferring mid-Level image representations using convolutional neural networks** (2014), M. Oquab et al. [[pdf\]](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Oquab_Learning_and_Transferring_2014_CVPR_paper.pdf)
- **Visualizing and understanding convolutional networks** (2014), M. Zeiler and R. Fergus [[pdf\]](http://arxiv.org/pdf/1311.2901)
- **Decaf: A deep convolutional activation feature for generic visual recognition** (2014), J. Donahue et al. [[pdf\]](http://arxiv.org/pdf/1310.1531)



# :beginner: Weight Initialization

- **Understanding the difficulty of training deep feedforward neural networks** by Glorot and Bengio, 2010 [[PDF](http://www.jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf?hc_location=ufi)]
- **Exact solutions to the nonlinear dynamics of learning in deep linear neural networks** by Saxe et al, 2013 [[PDF](https://arxiv.org/pdf/1312.6120)]
- **Random walk initialization for training very deep feedforward networks** by Sussillo and Abbott, 2014 [[PDF](https://arxiv.org/pdf/1412.6558)]
- **Delving deep into rectifiers: Surpassing human-level performance on ImageNet classification** by He et al., 2015 [[PDF](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf)]
- **Data-dependent Initializations of Convolutional Neural Networks** by Krähenbühl et al., 2015 [[PDF](https://arxiv.org/pdf/1511.06856)]
- **All you need is a good init**, Mishkin and Matas, 2015 [[PDF](https://arxiv.org/pdf/1511.06422)]





# How to comment

> With use of the [hypothes.is](https://hypothes.is/) extension (right-sided), you can highlight, annote any comments and discuss these notes inline*at any pages*and *posts*.
>
> *Please Feel Free* to Let Me Know and *Share* it Here.





---

[返回到首页](../index.html) | [返回到顶部](./index.html)

---
<br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
<br>
<script type="application/json" class="js-hypothesis-config">
  {
    "openSidebar": false,
    "showHighlights": true,
    "theme": classic,
    "enableExperimentalNewNoteButton": true
  }
</script>
<script async src="https://hypothes.is/embed.js"></script>
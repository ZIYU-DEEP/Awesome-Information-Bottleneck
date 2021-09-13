# Awesome Information Bottleneck [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

*In memory of Professor Naftali Tishby.*
<br>



## 0. Introduction
**To learn, you must forget**. This may probably be one of the most intuitive lessons we have from Naftali Tishby's Information Bottleneck (IB) methods, which grew out of the fundamental tradeoff (rate *v.s.* distortion) from Claude Shannon's information theory.

It has been four years since the dazzling talk on [Opening the Black Box of Deep Neural Networks](https://www.youtube.com/watch?v=FSfN2K3tnJU). It is time for us to take a look back, to celebrate what has been established, and to prepare for a future.

This repository is summarized as follows:
- [Classics (must-read ones)](##1-classics)
- [Theories](##1.-classics)
- [Models](##1.-classics)
- [Applications](##1.-classics)
- [Other Information Theory Driven Work](##1.-classics)


## 1. Classics
**The information bottleneck method** [[link](https://arxiv.org/abs/physics/0004057)] \
Naftali Tishby, Fernando C. Pereira, William Bialek\
*Preprint, 2000*
<br>

**The information bottleneck: Theory and applications** [[link](http://www.yaroslavvb.com/papers/slonim-information.pdf)] \
Noam Slonim\
*PhD Thesis, 2002*
<br>

**Opening the Black Box of Deep Neural Networks via Information** [[link](https://arxiv.org/abs/1703.00810)] \
Ravid Shwartz-Ziv, Naftali Tishby\
*ICRI, 2017*
<br>

**Deep Variational Information Bottleneck** [[link](https://openreview.net/forum?id=HyxQzBceg)] \
Alexander A. Alemi, Ian Fischer, Joshua V. Dillon, Kevin Murphy\
*ICLR, 2017*
<br>

## 2. Theories
**Caveats for information bottleneck in deterministic scenarios** [[link](https://arxiv.org/abs/1808.07593)] \
Artemy Kolchinsky, Brendan D. Tracey, Steven Van Kuyk\
*UAI, 2018*
<br>

**On the Information Bottleneck Theory of Deep Learning** [[link](https://openreview.net/forum?id=ry_WPG-A-)] \
Andrew Michael Saxe, Yamini Bansal, Joel Dapello, Madhu Advani, Artemy Kolchinsky, Brendan Daniel Tracey, David Daniel Cox\
*ICLR, 2018*
<br>

**The Dual Information Bottleneck** [[link](https://arxiv.org/abs/2006.04641v1)] \
Zoe Piran, Ravid Shwartz-Ziv, Naftali Tishby\
*Preprint, 2019*
<br>

**Learnability for the Information Bottleneck** [[link](https://arxiv.org/abs/1907.07331)] [[slides](https://docs.google.com/presentation/d/1sBYA6V-mL6cwYxEWxA5oMDOKYEq1FIjvZ3jOoXDlVD8/edit?usp=sharing)] [[poster](https://docs.google.com/presentation/d/1jkMxI7j8YXTxtUdy9PAtRfYRaLvFdT7hI1qP9m-qDbE/edit?usp=sharing)] [[journal version](https://www.mdpi.com/1099-4300/21/10/924)] [[workshop version](https://openreview.net/forum?id=SJePKo5HdV)] \
Tailin Wu, Ian Fischer, Isaac L. Chuang, Max Tegmark\
*UAI, 2019*
<br>

**Phase Transitions for the Information Bottleneck in Representation Learning** [[link](https://openreview.net/forum?id=HJloElBYvB)] [[video](https://media.mis.mpg.de/mml/2021-02-04)] \
Tailin Wu, Ian Fischer\
*ICLR, 2020*
<br>

## 3. Models
**The Deterministic Information Bottleneck** [[link]()] \
DJ Strouse, David J. Schwab\
*Neural Computation, 2017*
> This replaces the mutual information term with entropy in the original IB objective.

<br>

**Variational Discriminator Bottleneck** [[link](https://openreview.net/forum?id=HyxPx3R9tm)] \
Xue Bin Peng, Angjoo Kanazawa, Sam Toyer, Pieter Abbeel, Sergey Levine\
*ICLR, 2019*
<br>

**Nonlinear Information Bottleneck** [[link](https://www.mdpi.com/1099-4300/21/12/1181)] \
Artemy Kolchinsky, Brendan Tracey, David Wolpert\
*Entropy, 2019*
> This formuation shows better performance than VIB.

<br>

**Graph Information Bottleneck** [[link](https://arxiv.org/abs/2010.12811)] [[code](https://github.com/snap-stanford/GIB)] [[slides](https://docs.google.com/presentation/d/1yGs6kfaFHKlZdu0REuSpZTN4Pqt7b0bAnh2y8lvYm3A/edit)] \
Tailin Wu, Hongyu Ren, Pan Li, Jure Leskovec,\
*NeurIPS, 2020*
<br>

**Concept Bottleneck Models** [[link](https://arxiv.org/abs/2007.04612v3)] \
Pang Wei Koh, Thao Nguyen, Yew Siang Tang, Stephen Mussmann, Emma Pierson, Been Kim, Percy Liang\
*ICML, 2020*
<br>

**Disentangled Representations for Sequence Data using Information Bottleneck Principle** [[link](http://proceedings.mlr.press/v129/yamada20a.html)] [[talk](https://papertalk.org/papertalks/13911)] \
Masanori Yamada, Heecheol Kim, Kosuke Miyoshi, Tomoharu Iwata, Hiroshi Yamakawa\
*ICML, 2020*
<br>

**Disentangled Information Bottleneck** [[link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjhjduUk_vyAhVZ6XMBHQlpBPoQFnoECAQQAQ&url=https%3A%2F%2Fojs.aaai.org%2Findex.php%2FAAAI%2Farticle%2Fview%2F17120%2F16927&usg=AOvVaw1yu4FBl7RBV1xGUgh21VmY)] [[code](https://github.com/PanZiqiAI/disentangled-information-bottleneck)] \
Ziqi Pan, Li Niu, Jianfu Zhang, Liqing Zhang\
*AAAI, 2021*
<br>

**IB-GAN: Disentangled Representation Learning** [[link](https://ojs.aaai.org/index.php/AAAI/article/view/16967)] [[code](https://github.com/insuj3on/IB-GAN)][[talk](https://papertalk.org/papertalks/30379)]\
Insu Jeon, Wonkwang Lee, Myeongjang Pyeon, Gunhee Kim\
*AAAI, 2021*
> This model add additional IB constraint based on InfoGAN.

<br>


**Deciding What to Learn: A Rate-Distortion Approach** [[link](https://arxiv.org/abs/2101.06197v3)] \
Dilip Arumugam, Benjamin Van Roy\
*ICML, 2021*
<br>

## 4. Applications
**Past-future information bottleneck in dynamical systems** [[link](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.79.041925)] \
Felix Creutzig, Amir Globerson, Naftali Tishby\
*Physical Review, 2009*
<br>

**InfoBot: Transfer and Exploration via the Information Bottleneck** [[link](https://openreview.net/forum?id=rJg8yhAqKm)] \
Anirudh Goyal, Riashat Islam, DJ Strouse, Zafarali Ahmed, Hugo Larochelle, Matthew Botvinick, Yoshua Bengio, Sergey Levine\
*ICLR, 2018*
<br>

**Compressing Neural Networks using the Variational Information Bottleneck** [[link](http://proceedings.mlr.press/v80/dai18d.html)] \
Bin Dai, Chen Zhu, Baining Guo, David Wipf \
*ICML, 2018*
<br>

**Inserting Information Bottlenecks for Attribution in Transformers** [[link](https://arxiv.org/abs/2012.13838v2)] \
Zhiying Jiang, Raphael Tang, Ji Xin, Jimmy Lin\
*EMNLP, 2020*
<br>

**Information Bottleneck Disentanglement for Identity Swapping** [[link](https://openaccess.thecvf.com/content/CVPR2021/html/Gao_Information_Bottleneck_Disentanglement_for_Identity_Swapping_CVPR_2021_paper.html)] \
Gege Gao, Huaibo Huang, Chaoyou Fu, Zhaoyang Li, Ran He\
*CVPR, 2021*
<br>

## 5. Surveys and Other Information Theory Driven Work
**On the Information Bottleneck Problems: Models, Connections, Applications and Information Theoretic Views** [[link](https://www.mdpi.com/1099-4300/22/2/151)] \
Abdellatif Zaidi, Iñaki Estella-Aguerri, Shlomo Shamai\
*Entropy, 2020*
<br>

**ReduNet: A White-box Deep Network from the Principle of Maximizing Rate Reduction** [[link](https://arxiv.org/abs/2105.10446)] [[code](https://github.com/ryanchankh/ReduNet)] \
Kwan Ho Ryan Chan, Yaodong Yu, Chong You, Haozhi Qi, John Wright, Yi Ma\
*Preprint, 2021*
<br>

**Intelligence, physics and information -- the tradeoff between accuracy and simplicity in machine learning** [[link](https://arxiv.org/abs/2001.03780)] \
Tailin Wu\
*PhD Thesis, 2021*
<br>

**Where is the Information in a Deep Neural Network?** [[link](https://arxiv.org/abs/1905.12213)] \
Alessandro Achille, Giovanni Paolini, Stefano Soatto\
*Preprint, 2020*
<br>















<!--
**** [[link]()] \
\
**
<br>

**** [[link]()] \
\
**
<br>

**** [[link]()] \
\
**
<br>

**** [[link]()] \
\
**
<br>

**** [[link]()] \
\
**
<br> -->


<!--

**** [[link]()] \
\
**
<br> -->

<!--

**** [[link]()] \
\
**
<br> -->

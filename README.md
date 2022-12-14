
TODO:

Sanya
- Improve architecture design -> **done**
- Prepare video visualization -> **in progress**

Vlad
- Prepare how to run readme. 
- Make project page as in reference
- Add description and tables with figures onweb page


General
- add pwc paper + sota
- twitter + linked in 
- thread preparation


<p align="center">

  <h1 align="center">FingerFlex: Inferring Finger Trajectories from ECoG signals</h1>
  <p align="center">
    <a href="https://rainbowrui.github.io/">Vladislav Lomtev</a>
    ·
    <a href="https://github.com/kovalalvi">Alexander Kovalev</a>
    ·
    <a href="">Alex Timchenko</a>

  </p>
  <h3 align="center"><a href="https://arxiv.org/abs/2211.01960">Paper</a> | <a href="https://ustc3dv.github.io/ndr/">Project Page</a> | Some text </h3>
  <div align="center"></div>
</p>

<p align="center">
We propose FingerFlex, a new state of the art model for prediction finger movements from brain activity(ECoG).
</p>
<br>

## Abstract 
Motor brain-computer interface (BCI) development relies critically on neural time series decoding algorithms. Recent advances in deep learning architectures allow for automatic feature selection to approximate higher-order dependencies in data. This article presents the FingerFlex model - a convolutional encoder-decoder architecture adapted for finger movement regression on electrocorticographic (ECoG) brain data. State-of-the-art performance was achieved on a publicly available BCI competition IV dataset 4 with a correlation coefficient between true and predicted trajectories up to 0.74. The presented method provides the opportunity for developing fully-functional high-precision cortical motor brain-computer interfaces.

## Model 

<p align="center">
 <img src="https://user-images.githubusercontent.com/55140479/202727963-ee8dfcda-2ca1-496d-ac5b-ae1c5d4e82eb.png" alt="drawing"  width="800" />
</p>

<!-- ![fingerflex-Page-2 drawio (7)]() -->


Model architecture 

## Results 

We test our FingerFlex on multiple datasets BCI Competition IV and Stanfore which covers various subjects and different ECoG positions.



https://user-images.githubusercontent.com/30879198/200183717-b6c30904-bcec-4eff-a9f3-201f2ab79bb3.mp4





## How to check

## Citation

```
@article{fingerflex2022,
  title={FingerFlex: Inferring Finger Trajectories from ECoG signals},
  author={Lomtev, Vladislav and Kovalev, Alexander and Timchenko, Alexey},
  journal={arXiv preprint arXiv:2211.01960},
  year={2022}
}
```

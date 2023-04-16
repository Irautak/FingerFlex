<p align="center">

  <h1 align="center">FingerFlex: Inferring Finger Trajectories from ECoG signals</h1>
  <p align="center">
    <a href="https://rainbowrui.github.io/">Vladislav Lomtev</a>
    ·
    <a href="https://github.com/kovalalvi">Alexander Kovalev</a>
    ·
    <a href="">Alex Timchenko</a>

  </p>
  <h3 align="center"><a href="https://arxiv.org/abs/2211.01960">Paper</a> </h3>
  <div align="center"></div>
</p>

<p align="center">
We propose FingerFlex, a new state of the art model for prediction finger movements from brain activity (ECoG).
</p>
<br>

## Abstract 
Motor brain-computer interface (BCI) development relies critically on neural time series decoding algorithms. Recent advances in deep learning architectures allow for automatic feature selection to approximate higher-order dependencies in data. This article presents the FingerFlex model - a convolutional encoder-decoder architecture adapted for finger movement regression on electrocorticographic (ECoG) brain data. State-of-the-art performance was achieved on a publicly available BCI competition IV dataset 4 with a correlation coefficient between true and predicted trajectories up to 0.74. The presented method provides the opportunity for developing fully-functional high-precision cortical motor brain-computer interfaces.

## Model 

<p align="center">
 <img src="https://user-images.githubusercontent.com/55140479/202727963-ee8dfcda-2ca1-496d-ac5b-ae1c5d4e82eb.png" alt="drawing"  width="800" />
</p>

<!-- ![fingerflex-Page-2 drawio (7)]() -->


Figure 1. Model architecture. The proposed model is designed in the same way as the convolutional autoencoder. It allows to capture local and global features from brain signals.  Our model is fully convolutional so we can use different time window during real time prediction and tune this parameter for reducing temporal delay.



## Results 

We test our FingerFlex on multiple datasets BCI Competition IV and Stanford which covers various subjects and different ECoG positions.

Video.

https://user-images.githubusercontent.com/55140479/232328031-6746d5ce-e807-4c70-aa1d-b128d5dec89d.mp4


Plot.
<p align="center">
 <img src="https://user-images.githubusercontent.com/55140479/232242216-def29c1e-f220-439f-a9c9-a50d8654a30c.png" alt="drawing"  width="600" />
</p>



### Metrics


![image](https://user-images.githubusercontent.com/55140479/232328224-4e12494b-7b6b-43c3-9e75-eb311b7053c1.png)

Performance comparison on works solving BCI Competition IV dataset 4 finger trajectory decoding task


An example of true and decoded finger trajectories time series on BCI Competition IV dataset. 


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

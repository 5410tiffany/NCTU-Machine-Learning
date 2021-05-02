
[TOC]
## Environment Setting
* python `3.7.7`
* matplotlib  `3.1.3`
*  numpy `1.18.1`
*  pandas `1.0.3`


## 1. Gaussian Process

### Dataset
* `dataset` contains two files:
    * `gp_x.csv` is the input
    * `gp_t.csv` is the output

### Run the code
* run `hw2_309706005_GP.ipynb`

### Results
* The fitting results using different hyperparameters(thetas)

![](https://i.imgur.com/1fzIMWg.png)

![](https://i.imgur.com/sgwckIj.png)

![](https://i.imgur.com/TlZVj40.png)

![](https://i.imgur.com/RUXrxu7.png)

* The fitting results using ARD to tune the hyperparameters(thetas)

![](https://i.imgur.com/UtU0qwp.png)

* The learning process of ARD

![](https://i.imgur.com/hfEmqkq.png)



## 2. Support Vector Machine(SVM)

### Dataset
* `dataset` contains two files:
    * `x_train.csv` is the input
    * `t_train.csv` is the output
    
### Run the code
* run `hw2_309706005_SVM.ipynb`

### Result
* The results with different 
    * kernels: polynomial and linear 
    * decision functions: ovo and ovr

![](https://i.imgur.com/gpeDZzz.png)

## 3. EM algorithm and K-means

### Dataset
* `dataset` contains the original figure `imghw3.jpg`

![image](https://user-images.githubusercontent.com/37042357/116810504-aead0f80-ab76-11eb-8dfe-a424c4ec8082.png)

    
### Run the code
* run `hw2_309706005.ipynb`

### Result
* K-means where `K = 3, 5, 7, 10`

![](https://i.imgur.com/bZg7X60.png)

* EM algorithm where `K = 3, 5, 7, 10`

![](https://i.imgur.com/yqyx7IW.png)

* The training process of different `K` in Gaussian Mixture Model

![](https://i.imgur.com/j2iboL3.png)




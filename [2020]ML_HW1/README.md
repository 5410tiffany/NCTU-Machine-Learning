# NCTU-Machine-Learning

## Dataset
* `dataset_X.csv` in `Dataset` constains 7 different features for related to chance of admission (input) 
* `dataset_X.csv` in `Dataset` contains the chance of admission for college application(target)
## Environment Setting
* python `3.7.7`
* matplotlib  `3.1.3`
*  numpy `1.18.1`
*  pandas `1.0.3`

## Run the code
* run `hw1_run.ipynb`
## Results
* the RMS of each feature and the target using polynomial function(m=1) as the basis function:
![](https://i.imgur.com/xVPb6sk.png)
* RMS of different basis functions:
    * Gaussian
    * Sigmodial

![](https://i.imgur.com/jA3CfTc.png)
* different Lambda vs their train & validation RMS using Maximum a posterior approach(MAP)
![](https://i.imgur.com/sMjvGgd.png)

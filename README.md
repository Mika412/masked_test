# masked_test

## Installation
```bash
# create a separate conda env
conda create -n masked_test python=3.7

# activate it 
conda activate masked_test

# this installs the right pip and dependencies for the fresh python
conda install ipython pip

# get pytorch and torchvision
conda install pytorch=1.4 torchvision=0.5 cudatoolkit=10.0 -c pytorch

# more dependencies
conda install tqdm=4.42.1 pandas=1.0.1 matplotlib=3.1.3 pyyaml=5.3 scipy=1.4.1
conda install -c conda-forge yacs=0.1.6

# to monitor GPU usage on a cluster
pip install gpustat==0.6.0

# to view train logs in visdom
pip install visdom==0.1.8.9

# siamese dependencies
pip install numpy==1.14.1 cython scikit_image==0.13.1 keras==2.1.6 h5py imgaug opencv_python
```

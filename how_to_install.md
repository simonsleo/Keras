# IBM power8 machine
ssh lgm2

```
virtualenv /path/to/install
```

miniconda2 to install the package of H5df
```
pip install theano 
pip install keras
```
specify the path of cuda in the configuration file of theano ``

```
export PATH=$PATH:/usr/local/cuda/
```
check via 
``` 
which nvcc
```

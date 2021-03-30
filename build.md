# Env
    Tensor RT constraint about verion Ubuntu with cuda.
    
    Current Tensor RT supports till Ubuntu 18.04.
    https://forums.developer.nvidia.com/t/is-it-possible-to-install-tensorrt-7-2-2-on-ubuntu-20-04/164245/7
    
    If Ubuntu 20.04 and cuda 10.1 will error.
    ERROR: tensorrt-6.0.1.5-cp36-none-linux_ppc64le.whl is not a supported wheel on this platform.

## 1. Tensor RT
    https://docs.nvidia.com/deeplearning/tensorrt/install-guide/index.html#installing-pip
    
    pip install nvidia-pyindex
    pip install nvidia-tensorrt
    
    sudo apt-get install -y --no-install-recommends libnvinfer6=6.0.1-1+cuda10.1     libnvinfer-dev=6.0.1-1+cuda10.1     libnvinfer-plugin6=6.0.1-1+cuda10.1

## 2. Pycuda
    pip install pycuda
    
## Retina face

[tensorRT] (https://github.com/wang-xinyu/tensorrtx)

```mkdir build
   cd build
   cmake ..
   make
   sudo ./retina_r50 -s
   
   Test:
   sudo ./retina_r50 -d
    ```
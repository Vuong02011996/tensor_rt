# Env
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
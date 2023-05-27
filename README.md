TensorRT 8 C++ (almost) minimal examples

> This is a fork from <https://github.com/agrechnev/trt-cpp-min>

This repo provides a minimal example for TensorRT on Windows Platform.

## Version

- TensorRT: 8.6.1.6
- Cuda: 11.7
- CUDNN: 8.9.1.23

## Installation

- TensorRT: <https://developer.nvidia.com/nvidia-tensorrt-8x-download>
- Cuda: <https://developer.nvidia.com/cuda-11-7-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exe_local>
- CUDNN: <https://developer.nvidia.com/rdp/cudnn-download>

## Configuration

- Include directories:
  - D:\TensorRT-8.6.1.6\include;
  - C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\include;
  - C:\Program Files\NVIDIA\CUDNN\v8.x\include;
- Link directories
  - C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\lib\x64;
  - D:\TensorRT-8.6.1.6\lib;
  - C:\Program Files\NVIDIA\CUDNN\v8.x\lib;
- Link libs
  - nvinfer.lib;
  - nvonnxparser.lib;
  - cudart_static.lib;
  - cudnn.lib;

### Paths

- CUDA_PATH: C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7
- TensorRT Lib: D:\TensorRT-8.6.1.6\lib
- zlib: D:\TensorRT-8.6.1.6\zlib123dllx64\dll_x64
- CUDNN Bin: C:\Program Files\NVIDIA\CUDNN\v8.x\bin

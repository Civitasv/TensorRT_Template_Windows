# TensorRT

TF-TRT: TensorFlow integration

## Steps

1. Conversion: TF-TRT; ONNX; python/C++(manually constructing a network)
2. Deployment: TensorFlow; TensorRT(python/C++ Runtime Engine); Triton Inference Server

## Latency vs Throughput

Generally speaking, at inference, we pick a small batch size when we want to prioritize latency and a larger batch size when we want to prioritize throughput. Larger batches take longer to process but reduce the average time spent on each sample.

## TensorRT vs Pytorch

TensorRT 专注于优化和加速已经训练好的深度学习模型的推理过程。

Pytorch 主要用于定义和训练模型。

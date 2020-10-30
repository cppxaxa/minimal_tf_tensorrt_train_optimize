## Introduction

* A minimal example of a full flow - Train a model, save a model, optimize the saved model with TensorRT
* Tensorflow 1.14
* CUDA 9.0
* TensorRT 7.0
* Python 3.7.9
* Ubuntu 16.04
* NVIDIA Driver 396.54

## Readme

To run tensorboard and see the model
> tensorboard --logdir xor_010

To run inference
1. Run the cells in note_010_load_signature.ipynb

To run TensorRT optimization and inference
1. Run the cells in tensorrt_inference.ipynb

To re-run the model training from scratch
Run the cells at note_010_save_signature.ipynb

## Steps sequence

* note_010_save_signature.ipynb
* note_010_load_signature.ipynb    // Benchmark without optimization
* tensorrt_inference.ipynb  	 // Benchmark with optimization

## Credits and references
* https://stackoverflow.com/questions/33997823/tensorflow-mlp-not-training-xor
* https://stackoverflow.com/a/47235448/6484802

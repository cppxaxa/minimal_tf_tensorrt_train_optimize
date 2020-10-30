## Introduction

A minimal example of a full flow - Train a model, save a model, optimize the saved model with TensorRT

## Readme

To run tensorboard and see the model
    tensorboard --logdir xor_010

To run inference
1. Extract the xor_010_ck
2. Run the cells in note_010_load_signature.ipynb


To re-run the model training from scratch
Run the cells at note_010_save_signature.ipynb

## Steps sequence

note_010_save_signature.ipynb
note_010_load_signature.ipynb    // Benchmark without optimization
tensorrt_inference.ipynb  	 // Benchmark with optimization

# Pipeline_ResMLP_On_Edge_TPU  
## Introduction
We try to pipeline the resmlp model on the multiple coral edge TPU USB accelerator,     
because the tensor size of mlp model is too large to fit in the hardware architecture of [coral edge TPU USB accelerator](https://coral.ai/products/accelerator/) 
## Environment  
Rasberry Pi 4B、coral edge TPU USB accelerator  
## Reference
[Keras_mlp](https://github.com/leondgarse/keras_mlp#resmlp)  
[Pycoral](https://github.com/google-coral/pycoral/tree/master/examples)  

<h3 align=center><img src='https://symbols.getvecta.com/stencil_92/77_pytorch-icon.1c19d88dac.svg' height=150px width=150px ></h3>

<div>
<details open="open">
<summary>Table of Contents</summary>


- [About](#About)    
- [Torch](#torch)
  - [Tensors](#tensors)
  - [AutoGrad](#autograd---pytorch-automatic-diffrentiation-engine)    
- [Suggestions](#suggestions)
</details>

</div>

# About
This repo is contains collection for internal concepts of Pytorch in short. Also some notes for CUDA programming as I learnt along the way. 

# Torch
>Pytorch is an open source is an open source machine learning framework that accerlates path from reserach prototyping to production deployment.

Pytorch has many Deep Learning primitives, Neural Networks, Activation and Loss Functions, optimizers and also associated libraries for Computer Vision and NLP together with the support of Hardware accerlertion through GPU(CUDA).

Since Pytorch is open source it is very developed and is used in many big companies such as Microsoft, FastAI, etc.

## Tensors 
Tensors are multidimesional array that support
very fast mathematical calculations and has over 300 operations.

It is access through python API and is compiled through C++ which is optimized through CPU and GPU.

## AutoGrad - PyTorch Automatic Diffrentiation Engine 
Diffrentation is needed in optimizing gradient based function.
There are mainly two ways to compute diffrentation of a derivative.
-[Symbolic derivatives](https://www.sympy.org/en/index.html) - It is what used in mathematics. It requires full symbolic function. It is precise but rigid.
-Numerical derivatives - It uses the method of finite diffrences to compute differentation. It requires a black-box function. It is imprecise but rigid.




<br>

# Suggestions
Suggestions are Valuable while making this repo.

Feel free to suggest errors and other things along by creating an issue and making a pull request for the same.

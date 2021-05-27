# Attention-Augmented-Convolutional-Networks
This is a pytorch implementation of the paper [Attention Augmented Convolutional Networks](https://arxiv.org/abs/1904.09925 "Attention Augmented Convolutional Networks") by Irwan Bello, Barret Zoph, Ashish Vaswani, Jonathon Shlens and Quoc V. Le.

## Method
The paper implements the attention mechanism into different ResNet architectures. Convolutional and attentional feature maps are concatenated in a choosen ratio.

*     v = <sup>d<sub>v</sub></sup> / <sub>F<sub>out</sub></sub></span> is the ratio of attentional channels to number of original output filters

*     k = <sup>d<sub>k</sub></sup> / <sub>F<sub>out</sub></sub></span> is the ratio of key depth to number of original output filters


## Example
```python 

```
## Requirements
- pytorch
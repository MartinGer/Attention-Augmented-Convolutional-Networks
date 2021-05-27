# Attention-Augmented-Convolutional-Networks
This is a pytorch implementation of the paper [Attention Augmented Convolutional Networks](https://arxiv.org/abs/1904.09925 "Attention Augmented Convolutional Networks") by Irwan Bello, Barret Zoph, Ashish Vaswani, Jonathon Shlens and Quoc V. Le.

## Method
The paper implements the attention mechanism into different ResNet architectures. Convolutional and attentional feature maps are concatenated in a choosen ratio.

![aacn_image](https://user-images.githubusercontent.com/19909320/119885192-cd15e900-bf31-11eb-985b-be4e09ac9a4c.png)

*  ![v](https://user-images.githubusercontent.com/19909320/119885127-b40d3800-bf31-11eb-8165-1b12a739179f.png) 
is the ratio of attentional channels to number of original output filters

* ![k](https://user-images.githubusercontent.com/19909320/119885316-f9316a00-bf31-11eb-96e4-97134fc0dfb1.png) 
is the ratio of key depth to number of original output filters


## Example
```python 

```
## Requirements
- pytorch

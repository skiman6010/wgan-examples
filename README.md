## Implementation of Wasserstein GAN

This is a small, simple implementation I wrote for running WGAN on a dataset. 
There are better tools, this was just for learning.

## How to use
Please do not use this.
### Example
`python wgan.py --data mnist --model mlp --gpus 0`

## Thoughts
It trains extremely slowly, but that is to be expected with such a low cost function. 

Overall, I like it. It works well and is a good update over normal GAN. I want to implement the gradient penalty method next.

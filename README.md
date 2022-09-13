# Biweekly Report #2
# Grant Norman
## loss_landscapes.ipynb
In this [notebook](./loss_landscapes.ipynb), I create my own Convolutional Neural Network, tracking all of the dimensions for the layers / operations. I then train this model on the classic MNIST dataset. I then do a brief exploration of a dimensionality reduction method to visualize a high-dimensional loss landscape.

## gpu_vs_cpu.ipynb
Inspired by the novel use of GPUs in Alex Net, this [notebook](./gpu_vs_cpu.ipynb), provides a brief overview of using GPUs. I overview PyTorch's implementation methods and briefly dive into some lower level details, and then I compare the performance of matrix-vector multiplication, between my GPU and my CPU. This notebook shows that PyTorch makes using GPUs easy (although with some complications still), and that GPUs offer a massive performance boost.

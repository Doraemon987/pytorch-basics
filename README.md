# PyTorch Basics

This repository documents my journey of learning PyTorch from scratch toward becoming an AI Research Scientist.

## Goal

- Learn PyTorch fundamentals
- Implement research papers
- Understand Transformer architectures
- Build AI research projects

## Progress

### Day 1

- Created first tensor
- Learned tensor shape
- Learned tensor dtype
- Learned tensor device

### Day 2

- Tensor reshape
- Tensor indexing
- Tensor slicing

### Day 3

- Learned tensor arithmetic
- Performed element-wise operations
- Used matrix multiplication
- Practiced tensor broadcasting

### Day 4

- Learned tensor reshaping
- Used reshape() and view()
- Practiced indexing and slicing
- Understood tensor dimensions and shapes

### Day 5

- Learned Autograd basics
- Used requires_grad
- Calculated gradients with backward()

### Day6

- Built a linear regression model using `nn.Module`
- Defined linear layers with `nn.Linear`
- Calculated loss using `nn.MSELoss`
- Optimized parameters with `torch.optim.SGD`
- Implemented a complete training loop (forward, backward, step)
- Performed model inference using `torch.no_grad()
- Experienced with different learning rates and visualized loss convergence

### Day 7

- Paired feature tensors and label tensors using `TensorDataset`
- Configured mini-batch creation and dataset shuffling with `DataLoader`
- Practiced tensor dimension reduction using `.squeeze()` and data conversion with `.tolist()`
- Trained a linear model using mini-batch gradient descent (MBGD)
- Implemented epoch-level loss aggregation and verified parameter convergence
- Performed inference on unobserved input data using `torch.no_grad()`

# PyTorch Basics Tutorial

This workspace contains a single Jupyter notebook, `DL.ipynb`, that walks through core PyTorch concepts from tensors to basic neural network building blocks.

## What the notebook covers

- Creating tensors from Python data
- Inspecting tensor shape and dtype
- Matrix multiplication with tensors
- Defining linear layers with `torch.nn`
- Understanding layer weights, biases, and parameter counts
- Building simple `nn.Sequential` models
- Adding activation functions such as `Sigmoid` and `Softmax`
- One-hot encoding with `torch.nn.functional.one_hot`
- Computing cross-entropy loss
- Introductory notes on convex vs. non-convex functions
- Backpropagation as the basis for training

## Requirements

- Python 3.9+ recommended
- Jupyter Notebook or VS Code with notebook support
- PyTorch

The notebook includes a CPU-only install command for PyTorch:

```python
!pip install torch --index-url https://download.pytorch.org/whl/cpu
```

## How to run

1. Open `DL.ipynb` in VS Code or Jupyter.
2. Run the installation cell if PyTorch is not already available.
3. Execute the cells from top to bottom to follow the tutorial in order.

## Notes

- The notebook is educational and intentionally uses small, easy-to-follow examples.
- Some later cells build on variables defined earlier, so running the notebook sequentially is recommended.

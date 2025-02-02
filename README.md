# Concepts
This repository i am using to learn basic of ML.Here in this directory i will be documenting key files 

1. What is a Tensor?
A tensor is a multi-dimensional array used for storing data in deep learning. It’s similar to matrices but can have more than two dimensions. Tensors are the basic building blocks in deep learning frameworks like TensorFlow and PyTorch.

Example of Tensors:
Concept	Example	Shape
Scalar (0D Tensor)	5	()
Vector (1D Tensor)	[1, 2, 3]	(3,)
Matrix (2D Tensor)	[[1, 2], [3, 4]]	(2,2)
3D Tensor	[[[1, 2], [3, 4]], [[5, 6], [7, 8]]]	(2,2,2)

Tensors can go up to n dimensions, making them ideal for handling images, videos, and text data.

2. What is TensorFlow?
🟢 TensorFlow is an open-source deep learning framework developed by Google. It is widely used for building and training deep learning models, including image recognition, NLP (natural language processing), and more.

Key Features of TensorFlow:
Efficient for large-scale ML models ✅
Supports GPUs/TPUs for fast training 🚀
Works well for production and mobile deployment 📱
Example Code (TensorFlow Tensor Creation):

When to Use TensorFlow?
✅ If you're working with enterprise-level applications, large datasets, or production-ready deep learning models.

3. What is PyTorch?
🟠 PyTorch is an open-source deep learning framework developed by Facebook (Meta). It is widely used in research and AI model development because of its flexibility and ease of debugging.

Key Features of PyTorch:
More Pythonic (Easier to write and debug code) 🐍
Great for research and experimentation 🧪
Dynamic computation graphs (easier to modify models on the fly) 🛠

When to Use PyTorch?
✅ If you're doing AI research, working with custom neural networks, or want a more intuitive deep learning framework.

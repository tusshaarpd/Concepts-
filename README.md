# Concepts
This repository i am using to learn basic of ML.Here in this directory i will be documenting key information

Key Differences
1️⃣ Parallel Processing 🏎️
CPU: Executes one or a few tasks very quickly (good for logic-based operations).
GPU: Handles thousands of small tasks at the same time, making it ideal for graphics and AI.
2️⃣ Core Count & Speed 💡
CPU: Has a few powerful cores (e.g., Intel i7 has 8–12 cores).
GPU: Has thousands of small cores optimized for massive calculations (e.g., NVIDIA RTX 4090 has 16,384 CUDA cores).
3️⃣ Memory & Bandwidth 🔄
CPU: Uses fast cache and RAM, but has lower memory bandwidth.
GPU: Uses high-bandwidth memory (HBM or GDDR6X), ideal for large data sets in deep learning.
4️⃣ Best Uses 🎯
✅ Use CPU for general computing: web browsing, Word, coding, and running an OS.
✅ Use GPU for AI, deep learning, gaming, and 3D rendering.

Simple Analogy
Think of a CPU as a smart manager 🧑‍💼 and a GPU as a large team of workers 🏭.

CPU (Manager): Makes important decisions and handles complex tasks one at a time.
GPU (Workers): Performs many repetitive tasks simultaneously, making things faster for large workloads.


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

4. face_recognition
This library helps in detecting and recognizing faces in images or videos.
It is built on dlib (a machine-learning library) and uses deep learning to find and compare faces.
You can use it to:
Detect faces in a photo.
Compare faces to see if they match.
Identify known people from a database of face images.

5. Pillow (PIL Fork)
Pillow is a library for working with images in Python.
It allows you to open, edit, and save images in different formats like JPEG, PNG, BMP, etc.
It is a fork (improved version) of an older library called PIL (Python Imaging Library).

6. numpy
NumPy is a library for working with numbers and arrays in Python.
It is very fast and is often used for mathematical operations and image processing.
In face recognition, images are treated as arrays of numbers, and NumPy helps manipulate them easily.

7. opencv-python (OpenCV)
OpenCV (Open Source Computer Vision) is a library for image processing and computer vision.
It is used for:
Face and object detection
Video processing
Applying filters and transformations to images
It works well with face_recognition for real-time face detection.

# Project Title: Image Processing with NumPy & Matplotlib
This project is a hands-on exploration of Image Processing using NumPy for matrix manipulation and Matplotlib for data visualization. Instead of using high-level libraries like OpenCV, I have developed this project to understand how digital images work at the pixel level by treating them as multi-dimensional arrays.

Key Features & Logic Implemented:
Array Representation: Loading and converting real images into 3D NumPy arrays (Height, Width, RGB Channels).
Grayscale Conversion: Implemented the mathematical logic of averaging pixel intensities across the color axis (np.mean on axis=2).
Channel Manipulation: Isolating and removing specific color channels (e.g., removing Blue to create a 'Warm' filter) using Array Slicing.
Brightness Control: Using NumPy Broadcasting and np.clip to adjust pixel values without exceeding the 8-bit limit (0-255).
Geometric Transformations: Implementing Image Flipping and Cropping using Python’s advanced Slicing and Indexing techniques.
Random Noise Generation: Creating synthetic digital noise using np.random.randint to simulate "Old TV static" effects.

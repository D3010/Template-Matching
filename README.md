🧠 Template Matching in Computer Vision
A Python implementation using SAD and NCC with support for multi-scale template matching.

📌 Overview
This project presents a hands-on demonstration of template matching, a classical approach in computer vision for finding the presence and location of a template image within a larger image. The implementation showcases two popular similarity measures:

Sum of Absolute Differences (SAD)

Normalized Cross-Correlation (NCC)

The project is implemented using Python, with OpenCV, NumPy, and Matplotlib, and includes detailed image visualization and multi-scale detection capabilities.

🧪 Objective
The main goal is to:

Understand the core mechanics behind template matching techniques.

Compare and visualize how SAD and NCC work in detecting patterns.

Extend basic template matching to multi-scale template matching, making the solution more robust to object size variations.

🔍 Methods Used
1. Sum of Absolute Differences (SAD)
SAD compares a template with a region of the image by computing the sum of the absolute pixel-wise differences. A lower SAD value indicates a closer match.

2. Normalized Cross-Correlation (NCC)
NCC is a robust statistical approach that measures similarity while accounting for lighting and contrast variations. A higher NCC score suggests a better match.

🔧 Features
✅ Custom implementation of 2D Convolution
✅ Dynamically generated Gaussian Kernel for image smoothing
✅ Single and Multi-scale Template Matching
✅ Matches visualized with bounding boxes
✅ Visualization handled using matplotlib for clarity
✅ Zero-padding support in convolution

📁 Project Structure
bash
Copy
Edit
📂 template-matching/
├── Template_Matching.ipynb                # Full notebook with code and visuals
├── Template_Matching_Documentation.pdf    # Detailed write-up of the methodology
├── Template_Matching.ipynb - Colab.pdf    # Colab-rendered version of the notebook
├── README.md                              # You’re here!
🧰 Dependencies
Python 3.x

OpenCV

NumPy

Matplotlib

🎯 Results
The project includes:

Matching templates on grayscale images using SAD and NCC.

Visualization of the best-matched region(s) with bounding boxes.

An advanced demonstration of multi-scale matching using Gaussian filtering and template resizing to handle objects at various resolutions.

🎓 Learning Outcomes
Developed a deeper understanding of how template matching works under the hood.

Learned the limitations and strengths of SAD vs. NCC.

Gained insight into image convolution, kernel design, and multi-scale detection.

Strengthened skills in visual debugging and interpreting correlation scores.

📸 Visual Examples
The final output visually highlights the matched regions across different template scales:

🟩 Green: Small-scale template match

🔵 Blue: Medium-scale match

🔴 Red: Large-scale match

📖 Documentation
For complete theoretical explanations, equations, and breakdowns of each method, refer to the Template_Matching_Documentation.pdf included in this repository. It includes:

Mathematical background

Function-by-function breakdown

Use case scenarios

Visual representations of the process

💡 Future Improvements
Implement GPU-accelerated versions using libraries like CuPy or TensorFlow.

Add rotation- and scale-invariant matching capabilities.

Explore feature-based alternatives like ORB, SIFT, or template matching with edge maps.

📬 Contact
If you have any questions or suggestions, feel free to reach out at:
📧 dshah30.us@gmail.com


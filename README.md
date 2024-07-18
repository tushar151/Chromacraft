# Chromacraft

https://drive.google.com/drive/folders/1yQVO6heiji_Gwbbs5pMP0SIesCkDgYeg?usp=sharing

**Overview**:
This project focuses on colorizing black and white images using a deep learning model implemented in OpenCV and deploying the solution using Streamlit, an open-source app framework. The model used for colorization is based on a pre-trained Caffe model that performs colorization by rebalancing the distribution of colors in the LAB color space.

**Key Features**:
- **Deep Learning Model**: Utilizes a pre-trained deep learning model to predict the color distribution for grayscale images.
- **Streamlit Integration**: Provides an interactive web interface for users to upload and colorize their images.
- **Customization**: Includes custom CSS for styling the Streamlit app.

**Directory Structure**:
- `main.py`: The main script that runs the Streamlit app and handles image uploads, model loading, and image colorization.
- `colorization_deploy_v2.prototxt`: The configuration file for the Caffe model.
- `pts_in_hull.npy`: Numpy file containing cluster centers for ab channel quantization.
- `colorization_release_v2.caffemodel`: The pre-trained Caffe model file.

**Usage**:
1. **Upload Image**: Users can upload their black and white images in JPG, PNG, or JPEG formats.
2. **Colorization**: The uploaded image is processed and colorized using the deep learning model.
3. **Display**: The original and colorized images are displayed side by side for comparison.

**Future Improvements**:
- Enhance the user interface with more customization options.
- Add support for batch processing of images.
- Integrate more advanced models for improved colorization results.

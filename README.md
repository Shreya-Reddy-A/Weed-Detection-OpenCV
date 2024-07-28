
# Weed Detection Using OpenCV

This project implements a weed detection system using computer vision techniques with OpenCV, presented through a Streamlit web application. It aims to identify and locate weeds in agricultural fields, helping farmers optimize their crop management practices.

# UI:

![Screenshot (262)](https://github.com/user-attachments/assets/9f04a9b1-257e-4cbc-bd1c-8917dcf7751c)
![Screenshot (263)](https://github.com/user-attachments/assets/3a9e18b1-9598-4871-a5d5-9f580a1cb91f)
![Screenshot (264)](https://github.com/user-attachments/assets/d99138e5-7173-4da1-a03a-c5c72bcb86bd)

# Features

- Image preprocessing for optimal weed detection
- Color-based segmentation to distinguish weeds from crops
- Shape analysis for weed identification
- Model training using K-Nearest Neighbors classifier
- Visualization of detected weeds on input images
- Interactive web interface using Streamlit and result display

# Getting Started
To get started follow these steps:

1. **Clone the Repository**:
   
   - Clone this repository to your local machine.
     ```
     git clone https://github.com/Shreya-Reddy-A/Weed-Detection-OpenCV.git
     ```
3. **Install Dependencies**:
   
   - Navigate into the cloned directory and install the necessary dependencies.
     ```
     cd Weed-Detection-OpenCV
     pip install -r requirements.txt
     ```
3. **Dataset**:
- Ensure you have your image dataset and annotations in the correct folders:
  - Images should be in the `images` folder in .jpeg format.
   
5. **Streamlit app**:
 
     - To run the Weed and Crop Detection Streamlit app
        ```
        streamlit run app.py
        ```
   - Open your web browser and navigate to the URL provided by Streamlit (typically `http://localhost:8501`).
   - Use the web interface to view weed detection results.

# Requirements

- Python 3.7+
- OpenCV 4.5+
- NumPy
- Matplotlib (for visualization)
- Streamlit









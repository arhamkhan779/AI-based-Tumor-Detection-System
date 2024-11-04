Here’s the updated README with the video link properly embedded:

---

# AI-Based Brain MRI Tumor Detection System

## Demo Video

Watch the demo of the application here:  
[![Watch the demo](https://img.youtube.com/vi/Pdjc3235Dqg/0.jpg)](https://youtu.be/Pdjc3235Dqg)

## Overview

The AI-Based Brain MRI Tumor Detection System is a web application developed using Streamlit that enables users to upload MRI images and detect potential tumors using advanced machine learning techniques. The application employs the YOLOv8 model for object detection, providing visual feedback with bounding boxes around detected tumors.

## Project Structure

```
.
├── .gitignore
├── LICENSE
├── README.md
├── Requirements.txt
├── best.pt
├── code.ipynb
├── l.mp4
└── mainapplication.py
```

## Getting Started

### Prerequisites

- Python 3.x
- pip
- [Anaconda](https://www.anaconda.com/products/distribution) (recommended for package management)

### Required Libraries

To run this project, you will need to install the following libraries:

- Streamlit
- NumPy
- OpenCV-Python
- Pillow
- ultralytics

You can install these libraries using pip:

```bash
pip install streamlit numpy opencv-python pillow ultralytics
```

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/brain-mri-tumor-detection.git
   cd brain-mri-tumor-detection
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env_name
   source env_name/bin/activate  # On Windows use `env_name\Scripts\activate`
   ```

3. **Install Required Libraries**:  
   Use the command provided above to install the required libraries.

### Running the Application

1. **Start the Streamlit Application**:
   Run the following command to start the Streamlit application:
   ```bash
   streamlit run mainapplication.py
   ```

## Workflow

1. **Image Upload**:
   - Users can upload MRI images (JPEG or PNG) through the web interface.

2. **Image Prediction**:
   - The application processes the uploaded image using the YOLOv8 model to detect tumors.

3. **Display Results**:
   - The original and processed images are displayed side by side, with bounding boxes indicating detected tumors.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and libraries that facilitated the project, especially the YOLO model for object detection.

---

Let me know if there are any other changes you’d like to make!

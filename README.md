
# Image Classification with Gradio

## Overview
This project demonstrates how to deploy a pre-trained image classification model using TensorFlow and Gradio. The model is based on MobileNetV2, which is a lightweight deep neural network for image classification tasks. The Gradio interface provides an easy-to-use web interface for classifying images.

## Setup Instructions
Follow these instructions to set up and run the project locally.

### Prerequisites
- Python 3.x
- TensorFlow
- TensorFlow Hub
- Gradio
- NumPy
- Pillow (PIL)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/saadkhannust/image-classification-with-gradio.git
   cd image-classification-with-gradio                                                        
   ```

2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```

3. Install the required dependencies:
   ```sh
   pip install tensorflow tensorflow-hub gradio numpy pillow
   ```
Running the Project
1. Run the Gradio interface script:
   ```sh
   python app.py
   ```

2. Open the provided URL in your web browser to access the Gradio interface.
Project Structure
- `app.py`: Main script to run the Gradio interface.
- `saved_model/my_model`: Directory containing the saved TensorFlow model.
- `ImageNetLabels.txt`: Text file containing the labels for the ImageNet dataset.
Usage
Upload an image through the Gradio interface, and the model will classify the image and display the predicted label along with the confidence score.
Example
Upload an image of a dog, and the model will classify it as a 'dog' with a certain confidence score.

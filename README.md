# Waste Classification using Deep Learning

Overview

This project is a waste classification system built using Deep Learning. The model can classify images of waste into Organic or Recyclable categories, helping in efficient waste management. It was developed as part of the Solution Challenge to promote environmental sustainability.

Dataset

Dataset Used: Waste Classification Dataset - Kaggle

The dataset consists of images categorized into Organic and Recyclable waste.

# Technologies Used:

  Python

  TensorFlow & Keras (for model training)

  NumPy & Pandas (for data handling)

  Matplotlib (for data visualization)

  Streamlit (for web deployment)

  OpenCV & Pillow (for image processing)

  Model Architecture

  Pretrained Model: MobileNetV2 (Transfer Learning)

  Image Input Size: 224x224

  Activation Function: Softmax

  Optimizer: Adam

  Loss Function: Categorical Crossentropy

# How to Use the Model

  Upload an image of waste.

The model predicts whether the waste is Organic or Recyclable.

Displays the result along with the uploaded image.

Deployment

This project is deployed as a web application using Streamlit. You can run it on your local machine or deploy it on cloud platforms like Streamlit Sharing or Render.

Running the Project Locally

# Clone the repository

git clone https://github.com/your-github-username/waste-classification.git
cd waste-classification

# Install dependencies

pip install -r requirements.txt

# Run the Streamlit app

streamlit run app.py

# Future Improvements

  Expand dataset for better accuracy

  Deploy as a mobile application

  Integrate with IoT for real-world waste classification

# Contribution

  Feel free to contribute by creating issues or submitting pull requests.



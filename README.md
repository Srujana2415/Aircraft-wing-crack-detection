✈️ Aircraft Outer Body Crack Detection using Deep Learning

📖 Overview -
Aircraft maintenance requires regular inspection of the aircraft's outer body to detect cracks before they become major structural failures. Manual inspection is time-consuming, expensive, and may lead to human errors.
This project uses Deep Learning (Convolutional Neural Network - CNN) and Computer Vision techniques to automatically detect cracks from aircraft surface images. The model classifies images into Cracked and Uncracked categories, helping improve inspection efficiency and aircraft safety.

🎯 Objectives -
- Detect cracks automatically from aircraft surface images.
- Reduce manual inspection time and human errors.
- Improve aircraft safety through early crack detection.
- Assist maintenance teams with faster inspections.

🛠️ Technologies Used -
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

📂 Project Structure -
Aircraft-Crack-Detection/
│
├── dataset/
│   ├── cracked/
│   └── uncracked/
│
├── crack_detection.py
├── requirements.txt
├── README.md
└── sample_images/

⚙️ Project Workflow -
Aircraft Surface Images
          │
          ▼
Image Preprocessing
      (OpenCV)
          │
          ▼
Image Normalization
          │
          ▼
CNN Model Training
          │
          ▼
      Prediction
(Cracked / Uncracked)
          │
          ▼
Performance Evaluation
(Confusion Matrix & ROC Curve)

🧠 CNN Model Architecture -
- Conv2D (32 Filters, ReLU)
- MaxPooling2D
- Conv2D (64 Filters, ReLU)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 Neurons, ReLU)
- Output Layer (Sigmoid)

📊 Features -
- Image preprocessing using OpenCV
- CNN-based crack detection
- Binary image classification
- Automatic model training
- Train-Test split
- Confusion Matrix generation
- ROC Curve visualization
- Prediction on test images

📦 Requirements -
numpy
opencv-python
tensorflow
matplotlib
scikit-learn
seaborn

📈 Output -

The project provides:
- Crack / Uncracked Prediction
- Model Accuracy
- Confusion Matrix
- ROC Curve
- AUC Score
- Test Image Predictions

🎯 Applications -

- Aircraft Maintenance
- Aerospace Industry
- Automated Visual Inspection
- Structural Health Monitoring
- Predictive Maintenance

🔮 Future Enhancements -
- Detect multiple aircraft defects (cracks, dents, corrosion)
- Real-time detection using drones or cameras
- Transfer Learning using ResNet50 or EfficientNet
- Deploy as a Web Application using Flask or Streamlit
- Mobile application for field inspection

👩‍💻 Author -
Usha Srujana
Computer Science Engineering Graduate
Domain: Artificial Intelligence | Deep Learning | Computer Vision


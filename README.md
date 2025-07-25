# Molar-Age-Predictor
# 🦷 Molar Age Predictor
MolarAge estimates age groups from OPG images by analyzing third molars. The dataset from Jamia Millia Islamia was segmented using LabelMe and EfficientSAM. 
Models like VGG16, ResNet101, and transformers were tested, with transformers achieving the best results. Open to contributions!

A lightweight and efficient web app that predicts the **age of a person using molar teeth X-ray images**, powered by deep learning and Streamlit. Built with a focus on dental forensics and medical AI research.


---

##  Features

-  Trained CNN model on preprocessed molar X-ray dataset
-  Image upload support for inference
-  Real-time predictions with Streamlit UI
-  Lightweight and deployable (Streamlit Cloud, HuggingFace Spaces, etc.)
-  Visualization of model confidence (coming soon)

---

##  Tech Stack

| Technology      | Description                            |
|----------------|----------------------------------------|
| **Python**      | Core programming language              |
| **TensorFlow/Keras** | Deep learning model (CNN)           |
| **OpenCV**      | Image processing & preprocessing       |
| **Streamlit**   | Web UI for uploading and predicting    |
| **Pandas & NumPy** | Data processing libraries            |

---



# 🌿 Plant Disease Detection from Leaf Images

This project classifies tomato plant leaf diseases using a Convolutional Neural Network (CNN).

## 🔧 Tools Used
- Python
- TensorFlow + Keras
- OpenCV
- Streamlit
- PlantVillage Dataset (5 Tomato classes)

## 🚀 How to Run

1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Train the model:
```bash
python train_model.py
```

3. Launch web app:
```bash
streamlit run streamlit_app.py
```

## 📁 Dataset
Place 5 tomato disease folders under `/dataset/`:
- Tomato_Early_blight
- Tomato_Late_blight
- Tomato_Leaf_Mold
- Tomato_Septoria_leaf_spot
- Tomato_healthy

## 📦 Deliverables
- Trained CNN model
- Streamlit Web App
- Sample Dataset
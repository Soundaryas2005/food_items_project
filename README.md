Food Recognition and Calorie Estimation

This machine learning project uses image classification and regression techniques to identify food items from images and estimate their calorie content. Developed as part of my internship application for **Prodigy Infotech**.

---

#Objective

Enable users to track dietary intake by simply uploading a food image — the model will:
- Classify the food (e.g., Pizza, Apple, Burger)
- Estimate its calorie value (in kcal)

---

#Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- EfficientNetB0 (Transfer Learning)
- Scikit-learn

---
Project Structure

```bash
food_items_project/
├── food_model.py         # Model architecture
├── train.py              # Train model on food images + calorie labels
├── predict.py            # Predict food item and calories from image
├── dataset/
│   ├── labels.csv        # Contains image_name, food_label, calories
│   └── images/           # Folder of food images
└── requirements.txt      # Dependencies

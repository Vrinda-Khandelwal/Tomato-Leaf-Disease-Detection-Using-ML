#  Tomato Leaf Disease Detection System

This project is a web-based application for detecting diseases in tomato plant leaves using deep learning (CNN) and guiding users with a built-in multilingual chatbot (English & Hindi).

---

##  Features

- Upload tomato leaf images and predict disease with 90%+ accuracy.
- Audio input support in chatbot interface.
- Built using **TensorFlow**, **Flask**, and **HTML/CSS/JS**.
- Trained on a **Kaggle dataset** of tomato leaf diseases.

---

##  Project Structure

```

├── tomato/                       # Project folder
│   ├── train/                   # Training dataset
│   ├── val/                     # Validation dataset
│   ├── uploads/                 # Uploaded images folder
│   ├── static/
│       └── styles.css           # Static assets (CSS/JS/images)
│       └── images		  # Upload images present in images folder 
│   ├── template/
│       └── index.html           # Frontend HTML interface
├── tomato\_disease\_model.h5    # Trained CNN model(select any one model from models folder)
├── app.py                       # Flask backend with chatbot
├── requirements.txt             # Required Python libraries
├── README.md                    # This file
└── report.pdf                   # Project report (for submission)

````

---

##  How to Run (Locally or via Google Colab)

###  1. Install Requirements

```bash
pip install -r requirements.txt
````

Or manually install:

```bash
pip install Flask tensorflow numpy Pillow pyngrok
```

---

###  2. Run the App

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser or use the **ngrok URL** if running from Google Colab.

---

###  3. Features Demo

* Upload an image and get the prediction.
* Switch language to "hi" for Hindi replies.

---

##  Diseases Handled by Model

1. Tomato Bacterial Spot
2. Tomato Early Blight
3. Tomato Late Blight
4. Tomato Leaf Mold
5. Tomato Septoria Leaf Spot
6. Tomato Spider Mites
7. Tomato Target Spot
8. Tomato Yellow Leaf Curl Virus
9. Tomato Mosaic Virus
10. Healthy

---

##  Dataset

**Source:** [Kaggle - Tomato Leaf Dataset](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf)
**Classes:** 10 tomato leaf disease categories

---

##  Technologies Used

* Python, TensorFlow, Keras
* Flask Web Framework
* HTML, CSS, JavaScript
* Ngrok (for public link in Colab)

---

##  Authors

* Your Name: VRINDA KHANDELWAL
	     TUSHAR RATHORE
	     VISHWAS SAXENA
	     YASH KUMAR SAHU
* Email: vrindakhandelwal2002@gmail.com
* Institution/College Name: Shri Ram Murti Smarak College of Engineering & Technology 

---

##  License

This project is for educational purposes only. Model and UI may be extended for real-world agricultural applications.

```

---

Let me know if you'd like:
- A downloadable `.md` or `.txt` file version.
- A sample UI screenshot to include.
- A `logo.png` or icon to go with the project.
```

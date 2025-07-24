# 🧠 DermAI Assistant – Smart Dermatology Diagnostic Tool

DermAI Assistant is an intelligent, AI-powered dermatology tool that helps users identify skin conditions through image analysis. Using deep learning and image processing, it offers **accurate skin condition diagnosis**, **personalized treatment recommendations**, and **preventive advice** — all through an easy-to-use web interface.

---

## 🚀 Features

- 🔬 **AI-Powered Skin Disease Detection** using Convolutional Neural Networks (CNN)
- 📷 **Image Upload & Capture** support for affected skin areas
- 📊 **Personalized Treatment & Prevention Recommendations**
- 🧠 **Offline-Ready Model** – No external API dependencies
- 🔐 **User Privacy Focused** – Local processing only
- 🌐 **Mobile-Responsive Web UI**
- 🛠️ **Lightweight & Real-World Ready**

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **ML/DL:** TensorFlow / Keras, OpenCV
- **Model:** Custom-trained CNN for multi-class skin condition classification
- **Storage (optional):** SQLite or Local JSON

---

## 📷 How It Works

1. User uploads or captures a photo of the skin condition.
2. Image is preprocessed and passed into the trained CNN model.
3. Model returns the predicted skin condition.
4. Based on prediction, treatment & prevention steps are displayed.

---

## 🧪 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Lokesh-Kukudala/DermAI.git
cd DermAI-Assistant
````

### 2. Set Up Virtual Environment

```bash
python -m venv venv
# Activate:
source venv/bin/activate         # For Linux/Mac
venv\Scripts\activate            # For Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
python app.py
```

### 5. Open in Browser

Go to: [http://localhost:5000](http://localhost:5000)

---

## 📁 Project Structure

```
DermAI-Assistant/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   └── result.html
├── model/
│   └── trained_skin_model.h5
├── app.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## 🧠 Model Details

* **Type:** CNN (Convolutional Neural Network)
* **Classes:** Acne, Eczema, Psoriasis, Melanoma, etc.
* **Training Dataset:** Open-source dermatology datasets
* **Accuracy:** \~90% on validation data

---

## 🔐 Data Privacy

* No images or user data is stored or sent externally.
* All processing happens locally within your browser and backend.
* Built with data security and ethical healthcare in mind.

---

## 🔧 Future Enhancements

* 🤖 Improved multi-class classification model
* 📱 Android/iOS support via PWA or React Native
* 🌍 Multilingual interface
* 🧾 Admin dashboard for diagnosis history (optional)

---

## 📌 Limitations

* **Disclaimer:** This tool is for educational and informational purposes only.
  It is **not a substitute** for professional medical advice, diagnosis, or treatment.
* Results depend on image clarity and lighting.
* Accuracy may vary across different skin tones and rare conditions.


## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome!

### To contribute:

```bash
1. Fork this repository
2. Create a new branch (git checkout -b feature-name)
3. Commit your changes (git commit -m "Add feature")
4. Push to the branch (git push origin feature-name)
5. Create a Pull Request
```

---

## 📬 Contact

**Developer:** Lokesh Kukudala
📧 Email: [kukudalalokesh09@gmail.com](mailto:kukudalalokesh09@gmail.com)
🔗 GitHub: [Lokesh-Kukudala](https://github.com/Lokesh-kukudala)

---

> 🧠 Built with deep learning, dermatology, and a passion for helping people.
>
> ❤️ Made with care for a healthier world.

```

#  Real-Time Accident Detection Using CNN & VGG16

This project detects road accidents in real-time using deep learning (VGG16) and sends automatic alerts using Twilio.

---

##  Model File
The trained model (`Accident.keras` ~294 MB) is available on Google Drive:
 [Download Model from Google Drive] -> https://drive.google.com/drive/folders/1uBZmwaYFAZXK2nZiW1WOVpW-U5O1VcJJ?usp=sharing

---

## Files in this Repository
- `main_acc.ipynb` – Main code for accident detection  
- `mapping.csv` – Image–class mapping file  
- `test/` – Test images  
- `Accident.keras` – (linked to Google Drive due to 100 MB limit)

---

##  Technologies Used
- **Deep Learning:** CNN, VGG16 (Keras, TensorFlow)  
- **Alert System:** Twilio API (SMS notifications)  
- **Libraries:** OpenCV, Pandas, NumPy, Matplotlib, scikit-learn, geopy  

---

## How to Run

1. Clone this repository:
```bash
git clone https://github.com/vimal-kumar-3/accident-detection.git
```

2. Open the Jupyter Notebook:
```bash
jupyter notebook main_acc.ipynb
```

3. Make sure you have all dependencies installed:
```bash
pip install -r requirements.txt
```

4. Download the trained model (Accident.keras) from the Google Drive link
   and place it in the project folder.

## Hardware Used

Traffic Camera (Video Source)

Ultrasonic Sensor

Infrared Sensor

Raspberry Pi


 

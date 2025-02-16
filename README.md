## **Face Recognition System using OpenCV**

This project implements a real-time face recognition system using OpenCV and the LBPH (Local Binary Patterns Histograms) face recognizer. It includes three main components: face data collection, model training, and real-time recognition.

### **Features**
✅ Collects face images using a webcam  
✅ Trains a face recognition model using OpenCV's LBPH algorithm  
✅ Performs real-time face recognition with confidence levels  
✅ Displays a lock/unlock status based on recognition confidence  

---

## **Project Structure**
```
📂 Face-Recognition-Project
├── 📂 faces/               # Directory to store collected face images
├── 📄 Data Collection Code.ipynb  # Notebook for face data collection
├── 📄 Model Training Code.ipynb   # Notebook for training the face recognition model
├── 📄 Final Face Recognition Code.ipynb  # Notebook for real-time recognition
├── 📄 README.md            # Project documentation
```

---

## **Installation & Setup**
### **1️⃣ Install Dependencies**
Ensure you have Python and OpenCV installed:
```bash
pip install opencv-python opencv-contrib-python numpy
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/vaibhav208/Face-Recognition-Project.git
cd Face-Recognition-Project
```

### **3️⃣ Run Face Data Collection**
Run the script to capture 100 face samples:
```bash
python "Data Collection Code.ipynb"
```

### **4️⃣ Train the Face Recognition Model**
```bash
python "Model Training Code.ipynb"
```

### **5️⃣ Run Face Recognition**
```bash
python "Final Face Recognition Code.ipynb"
```

---

## **Usage**
1. The system will start capturing face data from your webcam.
2. It will train an LBPH-based model for recognition.
3. When running the recognition script, the system will:
   - Detect faces in real-time.
   - Display the confidence level of recognition.
   - Unlock if confidence > 75%, otherwise show "No face found".

---

## **Troubleshooting**
- **Webcam not opening?** Ensure your camera is accessible and not used by another application.
- **Face not detected?** Make sure you're in a well-lit environment.
- **Model not recognizing?** Recollect data and retrain the model.

---

## **Contributing**
Feel free to fork this repository and make improvements. Pull requests are welcome!

---

## **License**
📜 This project is open-source and available under the **MIT License**.

---

### 🔥 Happy Coding! 🚀  

---

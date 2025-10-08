# 💤 Drowsiness Detection (Basic)  
A **mini real-time driver drowsiness detection system** built with 🧠 **OpenCV**, 🧩 **dlib**, and 📏 **Eye Aspect Ratio (EAR)** logic.  

---

## ⚙️ Features
✅ Detects when eyes are closed for too long using EAR  
✅ Uses facial landmarks from dlib for accuracy  
✅ Displays **visual alert** when drowsiness is detected  
✅ Lightweight and simple — perfect for demos or small projects  

---

## 📸 Output Previews

| Alert Screenshots |  |
|--------------------|----------------|
| ![Output1](Screenshot%20of%20output1.png) | ![Output2](Screenshot%20of%20output2.png) |
| ![Output3](Screenshot%20of%20output3.png) |  |

---

## 🧠 How It Works
1. Detects face using   
2. Identifies eye landmarks with   
3. Computes **Eye Aspect Ratio (EAR)**  
4. If EAR remains below threshold → triggers alert 🚨  

---

## 🚀 How to Run

### 🧩 Install dependencies
```bash
pip install opencv-python dlib imutils scipy
```

### 📁 Run the program
```bash
python Drowsiness_Detection_basic.py
```

Make sure your  model file path is correct inside the script.

---

## 📂 Files Included
- **Drowsiness_Detection_basic.py** — main script  
- **Screenshot of output1/2/3.png** — proof of working output  

---

## 👤 Author
**Ashapr100**  
💻 GitHub: [Ashapr100](https://github.com/Ashapr100)


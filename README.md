# StegoEmbed
🔒 Secure Data Hiding in Images Using Steganography – A Python-based tool that embeds secret messages in images using pixel manipulation. Uses LSB encoding for minimal distortion. Supports encoding, decoding, and optional passcode protection. Fast, efficient, and cross-platform. 🚀 

# 🔒 Image Steganography GUI  

A Python-based steganography tool that lets you **hide and extract secret messages** within images using a **graphical user interface (GUI)** built with **Tkinter**.  

---

## 🚀 Features  
- **LSB-Based Image Steganography** – Uses Least Significant Bit (LSB) encoding.  
- **Secure Message Hiding** – Hide text messages inside image pixels.  
- **GUI-Based** – Easy-to-use interface built with Tkinter.  
- **Password Protection** – Prevents unauthorized message extraction.  
- **Image Selection & Preview** – Load, encode, and decode images smoothly.  
- **Text File Import** – Load messages directly from a text file.  

---

## 📥 Installation  

1️⃣ **Clone the repository:**

```bash

git clone https://github.com/ankan-debug/StegoEmbed.git
cd StegoEmbed
```
2️⃣ **Install dependencies:**  
```bash
pip install -r requirements.txt
```
3️⃣ **Run the application:**  
```bash
python StegoEmbed.py
```

### **🔹 Steps to Run on Kali Linux**
#### **1️⃣ Open the Terminal**  
Press **`Ctrl + Alt + T`** or search for **"Terminal"** in the Kali menu.

#### **2️⃣ Check if Python is Installed**  
Run:  
```bash
python3 --version
```
If Python is not installed, install it using:  
```bash
sudo apt update && sudo apt install python3 python3-pip -y
```

#### **3️⃣ Install Required Dependencies**  
Your tool uses **Tkinter and OpenCV**, so install them with:  
```bash
sudo apt install python3-tk -y  # Install Tkinter for GUI
pip3 install opencv-python
```

#### **4️⃣ Clone Your GitHub Repository**  
```bash
git clone https://github.com/ankan-debug/StegoEmbed.git
cd StegoEmbed
```

#### **5️⃣ Install the Required Python Libraries**  
```bash
pip3 install -r requirements.txt
```
If `requirements.txt` is missing, install dependencies manually:  
```bash
pip3 install opencv-python tkinter
```

#### **6️⃣ Run the Application**  
```bash
python3 StegoEmbed.py
```
🚀 **Your GUI-based steganography tool should now open!**

---

### **🔹 Troubleshooting Common Issues**
✅ **Problem:** `ModuleNotFoundError: No module named 'tkinter'`  
**Solution:** Install Tkinter using:  
```bash
sudo apt install python3-tk -y
```

✅ **Problem:** `ImportError: No module named cv2`  
**Solution:** Install OpenCV using:  
```bash
pip3 install opencv-python
```

✅ **Problem:** App doesn’t open  
**Solution:** Ensure all dependencies are installed and try running:  
```bash
python3 StegoEmbed.py
```

---

### **💡 Next Steps**
Try encoding and decoding messages in images and let me know if you face any issues! 🚀😊


## 🎯 Usage  

### 🔹 Encoding a message  
1. Click **"Select Image"** to choose an image.  
2. Enter the **secret message** in the text box or load a message from a file.  
3. Set a **password** for extra security.  
4. Click **"Encode Message"** – the tool will generate a new image with the hidden message.  

### 🔹 Decoding a message  
1. Click **"Select Image"** to load the stego-image.  
2. Enter the correct **password**.  
3. Click **"Decode Message"** – the tool will extract and display the hidden message.  

---

## 🛠 Technologies Used  
- **Python** – Main programming language  
- **Tkinter** – GUI framework  
- **OpenCV** – Image processing  
- **File Dialog & MessageBox** – File handling and user prompts  

---

## 📜 License  
This project is licensed under the **MIT License** – feel free to use, modify, and share!  

---

## 🤝 Contributing  
Contributions are welcome! Fork the repository, improve the code, and submit a pull request.  

---

## 📧 Contact  
For any questions or suggestions, feel free to open an issue or reach out!  
sahaankan628@gmail.com


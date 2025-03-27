# Remove Background via AI

A simple web-based application that removes image backgrounds using AI. It utilizes TensorFlow.js and a pre-trained **U-2-Net** deep learning model to process images directly in the browser.  

### 🔗 Live Demo  
Try it here: [GhostCut AI](https://www.ravzzy.com/app/remove-background/home.html)  

<img width="1278" alt="Screenshot 2025-03-25 at 9 09 53 PM" src="https://github.com/user-attachments/assets/b610948f-143c-498c-a77a-04e952b2a3a5" />

### 🚀 Features  
- Drag-and-drop or file upload support  
- AI-powered background removal using **U-2-Net**  
- Downloadable processed image  
- Responsive UI with progress indicators  

### 🧠 AI Model  
This project is built on top of the **U-2-Net** model by [xuebinqin](https://github.com/xuebinqin/U-2-Net), which provides high-quality image segmentation for background removal. The model is converted for TensorFlow.js and runs entirely in the browser.  

### 📂 Installation & Local Testing  
To run this locally, you can use Python’s built-in HTTP server:  

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/yourusername/background-remover.git
   cd background-remover
   ```  

2. **Start a Local Server**  
   - Using Python 3:  
     ```sh
     python -m http.server 8000
     ```  
   - Using Python 2:  
     ```sh
     python -m SimpleHTTPServer 8000
     ```  

3. **Open in Browser**  
   Navigate to:  
   ```
   http://localhost:8000
   ```

### 📌 Notes  
- Ensure `models/model.json` and related files are in the correct path for AI processing.  
- Works best in modern browsers with WebGL support.  

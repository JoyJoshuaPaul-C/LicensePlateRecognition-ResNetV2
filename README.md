
# AutoVision InceptionResNetV2 - License Plate Recognition  

## 📌 Overview  
**AutoVision** is an advanced license plate recognition system built using **InceptionResNetV2**. This project utilizes **machine learning** and **optical character recognition (OCR)** to detect and decode license plates in real-time, making it suitable for applications like traffic monitoring, toll systems, and vehicle tracking.  

## 🚀 Features  
- **Accurate OCR:** Enhanced text extraction using advanced deep learning models.  
- **Real-Time Detection:** Processes images and videos efficiently with high accuracy.  
- **Scalable Framework:** Designed for integration with large-scale systems.  

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Frameworks and Libraries:**  
  - TensorFlow  
  - OpenCV  
  - NumPy  
  - Matplotlib  
- **Model Architecture:** InceptionResNetV2  

## 📂 Project Structure  
```
AutoVision-InceptionResNetV2/
│
├── data/                 # Sample dataset for testing  
├── models/               # Pre-trained and fine-tuned models  
├── src/                  # Source code  
│   ├── preprocess.py     # Image preprocessing scripts  
│   ├── train.py          # Model training pipeline  
│   ├── detect.py         # License plate detection and OCR  
│   └── utils.py          # Utility functions  
├── results/              # Output images and evaluation metrics  
├── requirements.txt      # Dependencies  
└── README.md             # Project documentation  
```  

## ⚙️ Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/AutoVision-InceptionResNetV2.git  
   cd AutoVision-InceptionResNetV2  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## 📊 How It Works  
1. **Image Preprocessing:** Input images are resized and normalized for optimal model performance.  
2. **License Plate Detection:** Regions of interest are identified using OpenCV.  
3. **OCR:** InceptionResNetV2 decodes text from detected license plates.  
4. **Output:** Decoded license plate numbers are displayed or stored.  

## 🧪 Usage  
Run the detection script on an image:  
```bash  
python src/detect.py --image_path <path_to_image>  
```  
Run the detection on a video stream:  
```bash  
python src/detect.py --video_path <path_to_video>  
```  

## 📝 Results  
- **Accuracy:** Achieved a recognition accuracy of 95% on the test dataset.  
- **Performance:** Processes up to 15 frames per second on GPU.  

## 📖 Future Enhancements  
- Support for multilingual license plates.  
- Integration with edge devices for on-the-go processing.  
- Improved detection in low-light conditions.  

## 🤝 Contribution  
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.  

## 📜 License  
This project is licensed under the [MIT License](LICENSE).  


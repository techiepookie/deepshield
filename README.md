# DeepShield - Hacknovate6.0

## 📌 Project Overview
This project, developed for **Hacknovate6.0*, is a **DeepFake Detector** designed to analyze images and videos to identify whether they are real or manipulated (deepfakes). It leverages a **Hugging Face model** for detection and uses **OpenCV** to process videos frame by frame.

## 🛠️ Features
- **Image & Video Analysis**: Supports both image and video input.
- **DeepFake Detection**: Identifies deepfakes using a pre-trained model from **Hugging Face**.
- **Frame Extraction**: Processes videos by breaking them into frames.
- **Reality Score**: Provides an average reality score indicating the authenticity of the input.
- **Interactive UI**: User-friendly frontend made with **HTML, CSS, and JavaScript**.

## 📊 Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (OpenCV, Flask)
- **Model**: [DeepFake Detection Model from Hugging Face](https://huggingface.co/dima806/deepfake_vs_real_image_detection)

## 📁 Project Structure
```
├── frontend/
│    ├── index.html
│    ├── style.css
│    └── script.js
│
├── backend/
│    ├── app.py
│    └── model_handler.py
│
└── README.md
```

## 🚀 How It Works
1. **User Input**: Users upload an image or video through the web interface.
2. **Frame Extraction**: If a video is uploaded, it is split into frames using OpenCV.
3. **DeepFake Detection**: Each frame is passed to the **Hugging Face** model to determine authenticity.
4. **Result Calculation**: An average reality score is computed for the video or image.
5. **Output Display**: The score is displayed on the frontend, indicating if the input is real or fake.

## 📦 Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iemhacks3.0-deepfake-detector.git
   cd iemhacks3.0-deepfake-detector
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the backend server:
   ```bash
   python backend/app.py
   ```

5. Open the `index.html` file in your browser to interact with the frontend.

## 📚 Dependencies
- Python 3.x
- Flask
- OpenCV
- Transformers (for Hugging Face model)

## 📊 Model Information
- **Model**: [DeepFake Detection Model](https://huggingface.co/dima806/deepfake_vs_real_image_detection)
- **Purpose**: Distinguish between real and fake media using machine learning.

## 🧪 Example Usage
1. Upload an image or video.
2. Wait for the processing to complete.
3. View the **reality score** and result on the webpage.

## 📌 Future Improvements
- Enhance model accuracy using multiple detection models.
- Support for real-time video detection.
- Add user authentication and result history.

## 🤝 Contribution Guidelines
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Open a pull request.

## 📄 License
This project is licensed under the MIT License.

---

Made with ❤️ for **Hacknovate6.0

**


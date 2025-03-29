# Visual Questions Answers - Simpsons Family

## 📌 Introduction
The **Visual Questions Answers (VQA) - Simpsons Family** project aims to recognize characters, objects, and accessories appearing in videos of The Simpsons family. Additionally, the system supports natural language processing (NLP) to answer user queries related to video content.

## 🚀 Key Features
- **Character Recognition**: Identify characters in the video, such as Homer, Marge, Bart, Lisa, and Maggie.
- **Object & Accessory Detection**: Detect objects such as cars, tables, chairs, clothes, hats, etc.
- **NLP for Question & Answer Processing**:
  - Example: "What color is Homer's shirt?" ➝ "Homer is wearing a white shirt."
  - Example: "Is Homer wearing a hat?" ➝ "No, Homer is not wearing a hat."

## 🛠️ Technologies Used
- **Computer Vision**: Uses Python and OpenCV for video processing.
- **Object Detection**: YOLO (You Only Look Once) for detecting characters and objects.
- **Deep Learning (DL) & Machine Learning (ML)**: Deep learning models to enhance detection accuracy.
- **Natural Language Processing (NLP)**: AI models to process user questions.
- **AI & Neural Networks**: Neural network applications for image analysis and question semantics.
- **Backend**: Python (Flask/FastAPI) for API management.
- **Database**: MongoDB for storing recognition data.
- **Docker**: For packaging and deploying the application.

## ⚙️ Installation
### 1. Clone the repository
```bash
  git clone https://github.com/your_username/Visual_Questions_Answers_Simpsons_Family.git
  cd Visual_Questions_Answers_Simpsons_Family
```

### 2. Install dependencies
```bash
  pip install -r requirements.txt  # Install required libraries
```

### 3. Run the application
#### Run the backend (Flask/FastAPI)
```bash
  python app.py  # Or uvicorn main:app --reload for FastAPI
```
#### Run YOLO detection
```bash
  python detect.py --source path_to_video.mp4
```
#### Run the NLP model
```bash
  python nlp_model.py
```

## 📌 Usage Guide
1. Upload your video to the system.
2. Wait for the system to process and recognize characters/objects.
3. Enter a question related to the video (e.g., "Is Homer wearing glasses?").
4. Receive an AI-generated answer.

## 🤝 Contributions
If you want to contribute to this project, fork the repository and submit a pull request. All contributions are welcome!

## 📜 License
This project is released under the MIT License.

---
🔥 **Contact**: If you have any questions, feel free to reach out via email at hoabinh105.work@gmail.com or create an issue on GitHub.


# Train_Wagons
MultiDisciplinary Vision AI application over real time insights with trigger event.
This is Railway Wagon Inspection Project.
https://youtu.be/RtpJCx-Iiwk?si=bY263t-Eig-v8Hhv





🌟 Description
This repository hosts a comprehensive solution for real-time object detection and alerting system for train wagons using YOLOv5, OpenCV, and EasyOCR. The project integrates machine learning and Telegram bot communication for user-friendly monitoring and alerting.

🔒 Features
1️⃣ Object Detection
Identifies key wagon components such as closed doors, opened doors, wagon numbers, and train.
Powered by the YOLOv5 model for accurate and efficient detection.
2️⃣ Alert System
Sends instant alerts via Telegram when an opened door is detected.
Captures and sends images of detected anomalies for user verification.
3️⃣ Wagon Number Recognition
Extracts wagon numbers using EasyOCR for real-time text recognition.
Stores detected wagon numbers in an Excel file for further processing.
⚙️ Installation
Follow these steps to set up the project locally:

Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/wagons-object-detection.git
Navigate to the project directory:
bash
Copy
Edit
cd wagons-object-detection
Install the required dependencies:
bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is unavailable, manually install:

bash
Copy
Edit
pip install streamlit opencv-python telepot torch torchvision numpy easyocr pandas
🚀 Usage
Start the video feed:

bash
Copy
Edit
python app.py
For Streamlit Interface:
Launch the Streamlit app for a user-friendly interface:

bash
Copy
Edit
streamlit run app.py
View real-time object detection and alerts in your browser or Telegram.

💡 Contributing
We welcome contributions to improve the project!

Fork this repository.
Create a new branch for your feature or bug fix.
Submit a pull request with clear descriptions of changes.
🎉 Get Started Today

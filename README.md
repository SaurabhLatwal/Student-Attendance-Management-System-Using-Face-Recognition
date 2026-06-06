Student Attendance Management System Using Face Recognition

A Python-based desktop application that automates student attendance using **Face Recognition Technology**. The system captures student facial images, trains a recognition model, and marks attendance automatically through real-time face detection.

This project aims to reduce manual effort, improve attendance accuracy, and provide a contactless attendance solution for educational institutions.

---

Features

-  Student Registration System
-  Face Image Capture using Webcam
-  Face Detection using Haar Cascade Classifier
-  Face Recognition using LBPH Algorithm
-  Automatic Attendance Marking
-  Manual Attendance Entry Option
-  Attendance Report Generation
-  Subject-wise Attendance Management
-  User-Friendly GUI using Tkinter
-  Voice Feedback using Text-to-Speech

---

Technologies Used

- Python
- OpenCV
- Tkinter
- NumPy
- Pandas
- Pillow
- OpenPyXL
- Pyttsx3

---

Project Structure

```
Student-Attendance-System/
│
├── Attendance/
├── StudentDetails/
├── TrainingImage/
├── TrainingImageLabel/
├── UI_Image/
│
├── attendance.py
├── automaticAttedance.py
├── takeImage.py
├── trainImage.py
├── show_attendance.py
├── takemanually.py
├── test.py
│
├── haarcascade_frontalface_default.xml
├── haarcascade_frontalface_alt.xml
├── requirements.txt
└── README.md
```

---

Installation

1. Clone the Repository

```bash
git clone https://github.com/your-username/student-attendance-system.git
cd student-attendance-system
```

2. Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

3. Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy opencv-python opencv-contrib-python pandas pillow openpyxl pyttsx3
```

---

How to Run

Run the main application:

```bash
python attendance.py
```

---

Working Procedure

Step 1: Register Student

- Enter Enrollment Number.
- Enter Student Name.
- Capture face images through webcam.

Step 2: Train the Model

- Click on **Train Images**.
- The system creates a trained model using collected facial datasets.

Step 3: Mark Attendance

- Enter Subject Name.
- Start automatic attendance.
- The webcam detects and recognizes registered students.
- Attendance is stored automatically with date and time.

Step 4: View Attendance

- Open attendance records.
- Check subject-wise attendance reports.

---

Output

Student Registration
- Capture approximately 50 facial samples per student.

Face Recognition
- Detects faces in real-time using webcam input.

Attendance Report
- Generates attendance sheets in CSV format.

---

Requirements

```text
numpy
opencv-python
opencv-contrib-python
openpyxl
pandas
pillow
pyttsx3
```

---

Future Improvements

- Integration with a database (MySQL/MongoDB)
- Cloud-based attendance storage
- Web application version
- Email notifications for attendance reports
- Anti-spoofing techniques for enhanced security

---

Contributing

Contributions are welcome!

Feel free to fork this repository and submit pull requests to improve the project.

---

License

This project is developed for educational purposes. You may modify and use it according to your requirements.

---

Author

Saurabh Latwal
 
If you found this project useful, consider giving it a ⭐ on GitHub.

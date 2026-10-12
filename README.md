# 📸 Smart Attendance System Using Face Recognition

A Python-based attendance management application built with Streamlit and face recognition technology. The system identifies students from a group photograph, marks attendance, and generates downloadable CSV reports.

## 🚀 Features

- Train a face recognition model using student photographs.
- Recognize registered students in group photographs.
- Automatically mark students as Present or Absent.
- Display attendance statistics and percentages.
- Download attendance records in CSV format.
- View previously generated attendance records.

## 🛠️ Technologies Used

- Python
- Streamlit
- OpenCV
- face-recognition
- NumPy
- Pandas
- Pillow

## 📁 Project Structure

```text
SMART-ATTENDANCE-SYS/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/KHYATIRAJ03/SMART-ATTENDANCE-SYS.git
cd SMART-ATTENDANCE-SYS
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application should open in your browser.

## 📋 How to Use

1. Open the application.
2. Select **Train Model** and upload student photographs.
3. Train the model.
4. Select **Take Attendance** and upload a group photograph.
5. Review the recognized faces and attendance statistics.
6. Download the attendance report as a CSV file.
7. Use **View Attendance Records** to review saved reports.

## 🔒 Privacy Notice

Use student photographs only with appropriate permission. Protect biometric data and attendance records, and avoid uploading personal photographs, trained models, or private attendance CSV files to a public repository.

## ⚠️ Notes

- Clear, front-facing photographs generally produce better recognition results.
- Install compatible versions of Python and the required dependencies.
- Face recognition can make mistakes. Verify attendance records before using them officially.

## 👨‍💻 Author

GitHub: [KHYATIRAJ03](https://github.com/KHYATIRAJ03)


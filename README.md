
# Face based attendance system using python

# 🎓 Face Recognition Attendance System

A Python-based automatic attendance system that uses **face recognition** to mark student attendance. The system captures face images, trains a model, and automatically identifies students via webcam to fill attendance — saving results in subject-wise `.csv` files.

---

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `OpenCV (cv2)` | Camera access & face detection |
| `NumPy` | Numerical operations for image data |
| `Pandas` | Attendance data management |
| `CSV` | Reading & writing attendance files |
| `Datetime` | Recording date & time of attendance |



## 📊 Attendance CSV Format

Each subject creates a separate CSV file with the following format:

| ID | Name | Date | Time |
|---|---|---|---|
| 101 | John Doe | 2024-04-03 | 09:15:32 |
| 102 | Jane Smith | 2024-04-03 | 09:16:05 |

---

## 📦 Requirements

Install all dependencies using:
```bash
pip install -r requirements.txt
```

Key packages:
```
opencv-python
numpy
pandas
```




# Face Recognition Attendance System

**Version: v1.0**

This is the first version of the AI-powered Face Recognition Attendance System. It captures faces in real-time, matches them with stored identities, and marks attendance automatically in an Excel file.

## Features  
- ✅ Real-time face detection using OpenCV  
- ✅ Face recognition with high accuracy  
- ✅ Automatic attendance marking in an Excel file  

## Important Points  
- **Visual Studio C++ Build Tools**: Required for installing `dlib`, which is essential for face recognition.  
- **Conda Environment**: The setup is done using a Conda environment with Python installed(Python 3.11.11).

## Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/Raghulskr12/Smart-Face-Attendance.git  
cd Smart-Face-Attendance  
```

### Step 2: Set Up a Conda Environment
It is recommended to use a virtual environment to manage dependencies.

```bash
# Create and activate a new Conda environment
conda create --name face-attendance python=3.9 -y  
conda activate face-attendance  
```

### Step 3: Install Dependencies
All required dependencies are listed in the `requirements` file. Install them using:

```bash
pip install -r requirements/requirements.txt  
```

## How to Use

### Add Photos for Training:
- Place training images inside the `Training_images` folder.
- Each image should be named after the person's identity (e.g., `Raghul.jpg`).
- The more images you add, the better the accuracy.

### Run the Face Recognition System:
```bash
python main.py
```

### Adjust Threshold for Better Accuracy:
- Modify the face distance threshold in the script (`main.py`) as needed.
- Lower values increase strictness, while higher values make recognition more flexible.

### Attendance Output:
- The system will detect and recognize faces, marking attendance in `attendance.xlsx`.

## Contribute & Support
Feel free to fork this repository, contribute, and suggest new features.

If you find this project useful, consider giving it a ⭐ on GitHub.


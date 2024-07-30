# Face Recognition-Based Attendance System

This project implements a face recognition-based attendance system using OpenCV and Tkinter in Python. The system captures images, trains the model, and marks attendance by recognizing faces.

## Features

- **Face Detection and Capture:** Captures images of individuals and stores them.
- **Training:** Trains a model using the captured images.
- **Face Recognition:** Recognizes faces from the camera and marks attendance automatically.
- **GUI:** User-friendly interface using Tkinter.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Vishalbhalkar/Face-Recognition-Based-Attendace-System.git
    cd Face-Recognition-Based-Attendace-System
    ```

2. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Download Haarcascades:**
    Ensure `haarcascade_frontalface_default.xml` is in the project directory.

## Usage

1. **Run the main application:**
    ```sh
    python Layout_and_code.py
    ```

2. **Using the Application:**
    - **Enter ID and Name** and click on 'Upload Image' to capture images.
    - Click on 'Trainer' to train the model with the captured images.
    - Click on 'Mark Your Attendance' to recognize faces and mark attendance.

3. **View Attendance:**
    Attendance records are saved as CSV files in the `Attendance` directory.

## Project Structure

Face-Recognition-Based-Attendance-System/
│
├── Attendance/ # Attendance records
├── ImagesUnknown/ # Unknown face images
├── StudentDetails/ # CSV file with student details
├── TrainingImageLabel/ # Trained model file
├── TrainingImages/ # Captured training images
├── Layout_and_code.py # Main application code
├── haarcascade_frontalface_default.xml # Haarcascade for face detection
├── README.md # Project documentation
├── requirements.txt # List of dependencies
└── Untitled5.ipynb # Jupyter notebook for testing

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

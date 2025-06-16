# 🖐️ Gesture-Controlled Virtual Mouse

This project allows users to control mouse actions using hand gestures captured via webcam, using Python, OpenCV, MediaPipe, and PyAutoGUI.

It was developed as part of a Minor Project at SRM Institute of Science and Technology by Dhruv Dhar and Syed Faizan Haidar under the guidance of Dr. D. Shiny Irene.

---

## 🎥 Demo Video

📁 The demo video is included in the repository.  
👉 [Click here to download or view](demo-video.mp4)

> ⚠️ GitHub **does not play** MP4s inline. Viewers must download or open in a new tab.



---

## 🧠 Features
- Real-time gesture recognition using webcam
- Perform mouse **left click**, **right click**, and **scrolling** using hand gestures
- Built with **OpenCV**, **MediaPipe**, and **PyAutoGUI**
- Enhances accessibility for users with mobility impairments
- Does not require any specialized hardware

---

## 🧰 Technologies Used

| Tech         | Purpose                           |
|--------------|------------------------------------|
| Python       | Programming language               |
| OpenCV       | Webcam and image processing        |
| MediaPipe    | Hand landmark detection            |
| PyAutoGUI    | Mouse control (click, scroll, move)|

---

## 🚀 How to Run

### Step 1: Install dependencies

Install the required libraries using pip:

```bash
pip install -r requirements.txt
Step 2: Run the application
bash
Copy
Edit
python virtual_mouse.py
Use gestures:

✌️ Peace sign → Right Click

👍 Thumb Up → Left Click

✊ Fist → Scroll

📁 Project Structure
csharp
Copy
Edit
gesture-virtual-mouse/
├── virtual_mouse.py          # Python code
├── requirements.txt          # Dependency list
├── README.md                 # This file
├── docs/                     # Reports and presentation
│   ├── Research_Paper.pdf
│   ├── Project_Report.docx
│   ├── Implementation.docx
│   └── Presentation.pptx
# Real-Time-Drowsiness-Detection-System

Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. The objective of this project is to build a drowsiness detection system that will detect drowsiness through the implementation of computer vision system that automatically detects drowsiness in real-time from a live video stream and then alert the user with an alarm notification.

**#TECHSTACK I USE**

* [OpenCV Library](https://opencv.org/) - Most used computer vision library. Highly efficient. Facilitates real-time image processing.
* [imutils library](https://github.com/jrosebr1/imutils) -  A collection of helper functions and utilities to make working with OpenCV easier.
* [Dlib library](http://dlib.net/) - Implementations of state-of-the-art CV and ML algorithms (including face recognition).
* [scikit-learn library](https://scikit-learn.org/stable/) - Machine learning in Python. Simple. Efficient. Beautiful, easy to use API.
* [Numpy](http://www.numpy.org/) - NumPy is the fundamental package for scientific computing with Python. 
🚗 Drowsiness & Yawn Detection System

A real-time Computer Vision application that detects driver drowsiness and yawning using a webcam. The system analyzes facial landmarks, monitors eye closure using the Eye Aspect Ratio (EAR), and measures mouth opening to identify yawns. Whenever signs of fatigue are detected, an audio alert is triggered to help prevent accidents caused by driver inattention.

✨ Features
Real-time face detection using OpenCV
Eye Aspect Ratio (EAR) based drowsiness detection
Yawn detection using lip distance analysis
Instant audio alerts for fatigue detection
Lightweight and runs on a standard webcam
No GPU required

🛠️ Tech Stack
Python
OpenCV
Dlib
NumPy
SciPy
Imutils
Playsound

**🚀 How It Works**
Detects the driver's face from the webcam feed.
Extracts 68 facial landmarks using Dlib.
Calculates the Eye Aspect Ratio (EAR) to monitor eye closure.
Measures mouth opening to detect yawning.
Triggers an alarm when drowsiness or yawning exceeds predefined thresholds.

📦 Installation
git clone https://github.com/your-username/Drowsiness-Detection-System.git
cd Drowsiness-Detection-System

pip install -r requirements.txt
▶️ Run
python drowsiness_yawn.py

Or use a specific webcam:

python drowsiness_yawn.py --webcam 0
🎯 Applications
Driver Safety Systems
Fleet Monitoring
Smart Transportation
Workplace Fatigue Detection
📌 Future Improvements
Deep Learning-based fatigue detection
Mobile app integration
Head pose estimation
Cloud-based monitoring dashboard


📌 Eye-Controlled Mouse using MediaPipe & Python
This project lets you control your mouse pointer using eye movement and blink detection using a webcam.

🔧 Requirements
Python 3.10 (recommended)

OpenCV

MediaPipe ==0.10.14

PyAutoGUI

✅ Setup Instructions
bash
Copy
Edit
# Step 1: Clone the repo
git clone https://github.com/your-username/eye-controlled-mouse.git
cd eye-controlled-mouse



# Step 2: Create and activate a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # macOS/Linux



# Step 3: Install dependencies
pip install -r requirements.txt



# Step 4: Run the script
python eye_cursor.py
🧠 How It Works
Uses MediaPipe Face Mesh to track eye and iris position.


Moves the cursor based on iris movement.

Detects a blink (distance between 2 landmarks) to simulate a mouse click.

🛑 Quit
Press q to exit the window.












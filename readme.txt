__________________Sirajul_Islam__________________
All command must write in Command prompt, other wise it causes ERROR.

Steep 1:
Install Python 3.10 or 3.9
https://filehippo.com/download_python/3.10.0/


Steep 2: 
Initialize tailwindcss in cli mode
https://tailwindcss.com/docs/installation/tailwind-cli


Steep 3:
Change Directory to sign_env
cd sign_env


Steep 4:
Create Python virtual environment by typing command
py -3.10 -m venv venv


Steep 5:
Activate environment script by typing command 
venv\Scripts\activate


Steep 6:
Install necessary libraries by typing commands
pip install --upgrade pip
pip install mediapipe==0.10.9
pip install opencv-python
pip install numpy
pip install scikit-learn
pip install flask flask-cors


Steep 7:
Now check the environment are ready or not by typing
python -c "import cv2, mediapipe; print('OK')"
(If console output OK, then you are in right environment other wise install libraries again from Steep 6:)


Steep 8:
run the app by typing
python app.py


Steep 9:
Open index.html from 'src' folder by live server
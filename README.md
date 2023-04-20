# Emotion_Detection_Using_Python

To use this code, you will need to have the following libraries installed:

cv2
tensorflow
numpy
winsound
twilio
To run the code, follow these steps:

1] Clone the repository or download the code files.

2] Open the terminal or command prompt and navigate to the directory where the code files are located.

3] Create a virtual environment and activate it. You can do this using the following commands:
python -m venv myenv
myenv\Scripts\activate (Windows)
source myenv/bin/activate (macOS/Linux)

4] Install the required libraries by running the following command:
pip install -r requirements.txt

5] Run the code using the following command:
python main.py

6] The code will capture video from the default camera and detect faces in real-time. It will then predict the emotion of each face and draw a rectangle around the face with a label showing the predicted emotion.

If the percentage of attentive faces is below a certain threshold, the code will play a sound and send a message using the Twilio API.

Note: You will need to set up a Twilio account and obtain an account SID, auth token, and phone numbers to use the messaging feature.

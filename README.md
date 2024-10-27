# SOS-Gesture-Recognition
The code as is built to recognise the signal for help in a video stream. When the code recognises a succession of open hand - palm to the camera and tuck thumb, followed by a closed fist - trap thumb, it prints out a message.

## How to Test 
Navigate to  [MediaPipe Studio](https://mediapipe-studio.webapps.google.com/studio/demo/gesture_recognizer) and import 'sos_hand_gestures.task' as a Model (in the Model Selections section).
Slowly perform the SOS hand movements and see if they are recognised. You will not see an alert here, but the model will react to your gestures.


## How to Develop Further
### Step 1
Unzpiz 'SOSproject-20241027T134417Z-001.zip' and save it into your local Google Drive

### Step 2
Open 'SOS_AndroidML_HandGestureRecognitionModelTraining.ipynb' in Google Colab and perform the following changes
- mount your Google Drive to the project
- make sure all the paths to the images you are using are working - if you have issues with this, check my comments in the project or check the below resources

## Resources
**Coding:**
[Rock-Paper-Scissors](https://github.com/google-ai-edge/mediapipe-samples/blob/main/tutorials/gesture_recognizer/WiMLS_2022_MediaPipe_Gesture_Recognizer_Walkthrough.ipynb)

[Model training with MediaPipe Model Maker - ML on Android with MediaPipe Series](https://www.youtube.com/watch?app=desktop&v=vODSFXEP-XY&ab_channel=GoogleforDevelopers)
 [Colab - get image from Drive:](https://medium.com/data-arena/how-to-load-files-insert-images-in-google-colabatory-c5d1365d60d4)

**Image Inspiration:**
[TBWA](https://tbwa.com/work/signal-for-help/)
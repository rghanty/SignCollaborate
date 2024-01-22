# SignCollaborate
### An ASL translation application built for nwHacks 2024.

An easy-to-use, lightweight and AI-driven application that allows you to communicate with people with speaking or hearing disabilities, while not understanding ASL.

It uses the cv2 library and your device's front camera to capture frames from a live video feed.
This application has three different functionalities:
1. ASL to text/speech: The trained machine learning model converts the ASL sign shown on the screen and predicts what English alphabet it could be. The prediction is shown as Alph text.![image](https://github.com/rghanty/SignCollaborate/assets/99227180/e73e11b8-8428-43de-bbab-6da1662491de)
2. Speech to text: We use the speech_recognition library for this functionality. Meant for people to communicate back with people with hearing disabilities without knowing ASL.
3. A system checker that checks if your system has the required dependencies to use the application and prompts you to install them if not.

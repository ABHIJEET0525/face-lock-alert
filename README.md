# face-lock-alert
Face-Lock-Alert is a python based machine learning project to provide robust user authentication and has breach detection ability by combining facial recognition algorithm and secure authentication protocol.


Author - Abhijeet


Face-Lock-Alert
Face-Lock-Alert is an advanced Python-based security application that utilizes machine learning techniques for facial recognition to ensure robust user authentication and breach detection capabilities. The project integrates various libraries including Twilio, datetime, os, geocoder, smtplib, OpenCV (cv2), getpass, NumPy, and subprocess for seamless functionality.


Features
User Signup: Register users by capturing basic details and facial images for authentication.
Facial Recognition Login: Authenticate users during login using a trained machine learning model to compare captured faces with stored facial features.
Breach Detection: Detect unauthorized access attempts and promptly notify administrators via email and SMS using machine learning-based facial recognition.
Alert Mechanisms: Utilize Twilio for SMS notifications, SMTP for email alerts, and OpenCV for facial recognition to identify and alert administrators of security breaches, attaching images of unauthorized persons for further action.
Security Measures: Implement robust security practices including password hashing, data encryption, and secure transmission protocols.

Clone the repository:
https://github.com/ABHIJEET0525/face-lock-alert.git

Usage
Run the main Python script to start the application:
python home.py

Project Structure
The project directory structure is as follows:

alert_sms.py: Module for generating SMS alerts.
alert_email.py: Module for sending email alerts.
device_location.py: Module to fetch the current location of the device.
facelockalertdata.py: Contains email addresses and passwords.
home.py: Main module for displaying login, signup, and exit options and navigating between them.
signup.py: Module for user signup and capturing images for model training.
login.py: Module for user login, breach detection, and alerting via email, SMS, and images.
image_attachment.py: Module for attaching captured threat images to email notifications.
twiliokeys.py: Configuration file for Twilio attributes.
Additional folders: images, passwords, temp, threat_images, trained_models, users.


Acknowledgements
This project utilizes the power of machine learning through the following open-source libraries:
Twilio - For SMS notifications.
OpenCV - For facial recognition.
NumPy - For numerical computation

DATA FLOW STRUCTURE:
![image](https://github.com/thesumeetsingh/face-lock-alert/assets/148633096/ff0f0b3e-7ae7-4bb6-8ee2-b49b720875d0)


SIGNUP
![image](https://github.com/thesumeetsingh/face-lock-alert/assets/148633096/3dc3d5d1-9954-4132-92bc-c08cd283f4fa)

BREACH DETECTION ON LOGIN
![image](https://github.com/thesumeetsingh/face-lock-alert/assets/148633096/957a62b1-391f-40f1-8e9a-33c9b77e3198)

RECIEVED EMAIL OF THREAT PERSON
![image](https://github.com/thesumeetsingh/face-lock-alert/assets/148633096/183b037f-109d-44fc-af35-812d8c9294b5)

ALERT SMS
![image](https://github.com/thesumeetsingh/face-lock-alert/assets/148633096/4a6737fc-8733-4b69-a03b-8a45491a3698)

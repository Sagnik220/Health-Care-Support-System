###  Health Care Support System

The idea behind the project is to help hospital workers monitor and relay information about a patient's condition to respective authorities in charge in as little time as possible.
Here I have built a **python based auto-messaging application along with a signaling board to determine the patient’s current condition and relay the message to the authority**. I have made it very user-friendly so that anybody and everybody can use it. 
In this way we can also maximize the potential of the hospital workforce. Due to the advancement in technology, it plays a major role in the healthcare industry. Health care is an industry where most businesses are engaged and is in high demand. 


### THEORETICAL STUDY
The idea of the project is to help the patient’s needs inside a hospital, using **Mediapipe, OpenCV and Arduino UNO.** We have taken the idea of hand-tracking using the Mediapipe Library to count the number of fingers to light up the LEDs.
Suppose a patient is not in a condition to communicate with the doctor about his/her needs at that moment or needs some supplies but cannot call the doctor. Then the camera monitoring the patient will track the number of fingers put up by him/her. Accordingly, the light will glow at the place where all the patients are monitored.
```
We have encoded the count of fingers as :- 
• 1 fingers → Green Light → The patient is okay but needs supplies like food and water or some daily medicines 
• 2 fingers → Yellow Light → The patient needs to go to the bathroom for urination or excretion 
• 3 fingers → Red Light → The patient is facing severe problems and needs instant medical attention
```


#### 1. 	Mediapipe
**MediaPipe is a cross-platform framework for building multimodal applied machine learning pipelines. MediaPipe is a framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) applied ML pipelines**.

#### 2. 	OpenCV
**OpenCV (Open Source Computer Vision Library)** is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.


#### 3. 	WhatsApp Message Integration
**Pywhatkit is a Python library for sending WhatsApp messages at a certain time**.
Pywhatkit module utilizes the WhatsApp webpage to automate messages sending to any number on WhatsApp. But make sure that you are logged into your WhatsApp in your browser.


**Syntax : pywhatkit.sendmsg(“receiver mobile number” , ”message” , hours , minutes)**


**Parameters :**


##### Receiver mobile number: The Receiver’s mobile number must be in string format and the country code must be mentioned before the mobile number.
##### Message: Message to be sent (Must be in string format).
##### Hours: This module follows the 24 hrs time format.
##### Minutes: Mention minutes of the scheduled time for the message (00-59)



#### 4. 	Email Service Integration
**Simple Mail Transfer Protocol (SMTP) is a protocol, which handles sending email and routing e-mail between mail servers.** 
Python provides a smtplib module, which defines an SMTP client session object that can be used to send mail to any Internet machine with an SMTP or ESMTP listener daemon.
				
<img src="images\smtp.jpg" width="900" height="600">



#### 5. 	High Level Design of the Application


<img src="images\SystemDesign.jpg" width="1000" height="600">




### How to set up locally?

- Check if your system has python installed in it before!

- Fork the repository

- Git clone your forked repository

- Create virtual environment
```
- pip install --user virtualenv
- python -m venv env
- source env/bin/activate (Linux)
- env\Scripts\activate (Windows)
```

- Install dependencies
```
- pip install -r requirements.txt
```  

- Check dependencies
```
- pip list
```  

### Software Used:

- Language
```
- Python
```
- Libraries
```
- OpenCV
- Mediapipe
- pyfirmata
- controller
```

### Hardware Used:

```
- Arduino UNO
- Jumper Wires
- Breadboard
- LED light's Red,Green,Yellow

```

### Setup Picture:

<img src="images\setup.jpg"  width="900" height="600">



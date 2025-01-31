# diabetic_retinopathy
# Diabetic_Retinopathy
Title: Diagnosis of Diabetic Retinopathy Using Deep Learning Algorithms.
Description: 
1. Detect the presence of diabetic retinopathy and classify its severity level at the Early Stage. 
2. Contacting Specialised doctors and getting feedback, and guidance for affected persons.
3. Communicating with patients in remote/rural areas through SMS alerts with doctor descriptions for prevention.

METHODOLOGY:      
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/7abd071a-a691-4aa4-8b68-70f43bb37c00)

The following details the many steps used as part of the suggested technique.
• Using a fundus camera to capture the patient's retinal picture, uploading via a website that connects DL models kept in the cloud with a technician's assistance at a system or computer for processing.
• The trained DL is illustrated below in the training model. The cloud-based model receives the raw input image and goes through various fundamental processes, such as pre-processing, to produce the needed image. Predictions and a thorough report will be produced.
• For rural areas which have small dispensaries and can afford a fundus camera, but don't have expert medical professionals available. A device that enables clinicians to rank instances according to the seriousness of the condition. For anyone who wants to make healthcare affordable and accurate in remote areas.
• The findings from the DL model are kept and results are forwarded to a specialist doctor, who does a comprehensive study of the model predictions and provides feedback to the patient and technician to explain the situation.
• The same feedback and description are sent through SMS alerts to patients.

IMPLEMENTATION:
The implementation phase is divided into two parts shown below.
PART-A: DL PREDICTION MODEL:
i. Web Page Prediction Model:
Python's model.py file from the Flask application framework can be used to add deep learning models for prediction. The model.py file can accept input data from users or external sources. After any necessary preprocessing, the data should be fed into a trained deep-learning model for inference.
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/d838b274-da77-4a5a-b2eb-cbf631df78c2)

PART-B: WEB INTERFACE
In a healthcare context, an interface that links admin and doctors can help to improve interactions and exchanges of data between these two groups. This interface may provide features like appointment scheduling, patient data management, and secure messaging, allowing administrators and doctors to work more efficiently together when providing patient care and monitoring patients.
Web interface involves the following pages.
• Home Page
• About Page
• Contact Page
• Login Page
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/3af3b175-2492-4653-b7fb-47c8b5a41cd3)

i. Admin Page:
The admin can administer many components of the system from the Admin Home Page, which acts as a central center. A wide range of options are available, including managing patientrecords, updating doctor information, and sending SMS messages.
STEP 1: Utilize the New Registration Form on this page to register a new patient. The DR database will be stored with all information.
STEP 2: The patient retinal picture upload webpage in the second step enables the admin to upload results of model predictions of their patients with the Registration number to the website.
STEP 3: The My Registrations homepage shows a patient's name, age, registration number, medical history, and any feedback given by their doctor, in addition to other basic information. Patients can quickly access and review their medical records, monitor their progress.
STEP 4: Using the website's SMS Sending Page, administrators can send SMS messages to patients.
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/d8ad8fd4-dcb3-48b4-8a70-20765cfb8fd8)

ii. Doctors Page:
Doctors can check patient registrations and make certain updates to their personal information on the Doctors Home Page. Doctors can manage their patient load and maintain their information updated on this page simply and safely. Doctors need the View Registration and Feedback Updating Page to successfully manage patient care. Additionally, the page enables physicians to comment on a patient's condition, and the feedback is updated in the patient's record on the My Registrations page so that admin can see it.
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/e3a236a6-e24b-4665-a706-d3dd283af4df)
![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/7ee83e96-e892-40a9-862e-8d82786b3b18)

RESULT AND DISCUSSION
We combined a dataset from Kaggle's APTOS 2019 blindness detection with ResNet-152 to train our suggested model, and the outcome has an accuracy of 0.984. A variety of machine learning methods, including K-Nearest Neighbour (KNN), Support Vector Machine (SVM), Decision Tree (DT), and Regression approach, were compared to the suggested approach. Table 1 below provides a summary of the findings along with the accuracy ratings for each model.

![image](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/16221986-cd9c-456c-a48d-bef74254b415)
![SMS ALERTS to patients](https://github.com/ngyadav/diabetic_retinopathy/assets/118537866/47a5b95c-7c89-41b7-a2b6-0f494e43bf55)


INNOVATION IN OUR PROJECT
Based on the survey conducted, numerous methods have been devised to predict different stages of diabetic retinopathy. However, this project proposes a unique approach that utilizes Deep Learning Algorithms to detect the various stages of diabetic retinopathy at an early phase. The system not only provides automatic diagnosis but also facilitates web-based interaction with specialists. In addition, the feedback and description provided by the doctors are transmitted to the patients via SMS alerts on their mobile devices. This integrated approach aims to enhance the efficiency of diabetic retinopathy diagnosis, enable timely interventions, and ensure effective communication between healthcare providers and patients, ultimately improving the overall management of the condition.

Contact Details:
Members: BHAVANI SHANKAR[1JB19CS050] DEPT OF CCE, NANDAGANESH[1JB19EC058]DEPT OF eCE. STUDENTS OF SJBIT, SJBIT, BANGALORE.
Ph No: +919100585589 
E-mail: gampabhavanishankar@gmail.com

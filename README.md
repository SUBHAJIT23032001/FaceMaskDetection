# FACE MASK DETECTION WITH COVID GLOBAL UPDATES
This is a ‘Mask Detection System’ based on real world AI and ML applications. The software detects if people are wearing masks or not. It also has a global notification section of covid cases throughout the world. This software is made with Python. Some modules are Tkinter, Pillow, Beautifulsoup, Plyer, Opencv, Pandas, Requests, Itertools etc. A dataset has been used for training and testing data as images of people wearing masks and without masks with mask. We have selected this idea to make project remembering the present covid situation, importance of masks and also the uprising trend of using AI and ML in many real-world practices. Our project ‘MASK DETECTION SYSTEM’ along with ‘COVID UPDATES’ works based on machine learning concepts. There is a GUI canvas which contains background image changing with time. There are three buttons for different functions. The title of the first button is ‘LIVE DETECTION’. Opening it we get a computer vision using web camera and a bounding rect locating the area. Coming in front of webcam we can see the result. The system detects if we are wearing masks or not. It shows accuracy percentage as per prediction and also the number of people before webcam. The system has been cross checked many times with similar things with mask but in each case, we get 99% correct result. To exit the live detection function we have to pree ‘q’ on our keyboard. The next button in the main GUI is ‘COVID UPDATES’. By clicking on this we get a window where we have to write country name and type of covid case. We can select type of cases related Covid-19 like total deaths, total cases, new cases, new deaths, total recovered, all cases. Then we can to click on the show notification button to get a notification pop up in pc. We can also download json or csv format files as record. We have fetched the global updates from worldometer website. The image detection portion is used to chose a image and then count number of people and then for detecting who are wearing masks and who are not. The third button on the main GUI is EXIT which is used to exit the program.

# PURPOSE
The main goal of our project is to implement ‘MASK DETECTION SYSTEM’ and ‘COVID UPDATES’ using deep learning concept. For making it user friendly our target is to build a ‘GUI’ with buttons integrated on it for using the system. For the live detection idea, we have to detect faces and also detect the accuracy or wearing or not wearing mask. Based on that we have to produce a decision as the output. We also have to work on image data for training model. For Covid Updates section we have to make a GUI and pop notification as per user’s chosen country and type of covid case. We have to also keep an option to download databases of covid cases. To make correct result and get correct and updated data is also our concern. There should be image detection portion that should detect if people are wearing mask from image and there should be also a count of number of people.

# Applications
* In the ‘Live Detection’ part we can place our face before web-cam of our pc and then it will detect that we are wearing mask or not. The number of people will be shown. More than one person can be detected.
* The prediction accuracy of with mask or without mask will be shown. We can clearly get an idea that the person is wearing mask or not. So, in this global Covid-19 pandemic situation this system can be used for safety measures.
* his system can be used in offices, schools, colleges, railway station, airport, hospitals, shopping malls and any other places to check that people are wearing masks or not.
* In the ‘Global Updates’ part we have to write the name of the country. We can select type of cases related Covid-19 like total deaths, total cases, new cases, new deaths, total recovered, all cases. Then we have to click on the show notification part to see the result. * We can also download json or csv format files as record. The records fetched from the worldometer website is accurate.
* The notification system can be also used anywhere for database analysis of Covid Cases. Students, researchers, officers or anyone can use this for database and research purpose. This will also help for statistical analysis of records.
* The image detection portion counts number of peoples from an chosen image from device and shows who are wearing mask and who are not. This system can be also used as attendance system along with following covid guidelines.

# FUTURE SCOPES
* This ‘Face Mask Detection’ system can be deployed in any public place or densely populated areas in checking area before entry for Covid-19 safety measures. It will increase awareness of the global pandemic situation and everyone will know the importance of wearing mask.
* This system will make people follow the guidelines related Covid-19 and it will also make the situation better by decreasing the number of affected people.
* Many important exams which are getting postponed affecting students’ careers. In future using this system many exams and other important tasks can be conducted avoiding any losses.
* The global notification idea can be added in other systems and shown in public places through tv or computer to keep people updated and make them alert for their health.
* The development ideas, AIML concepts and other knowledges, the global notification or database part will encourage students or researchers to increase their knowledges.
* This system can be deployed and more updated to make a attendance system following covid guidelines.

# FOLDER STRUCTURE
     ├── .idea
     ├── _pycache_  
     ├── dataset
     |      ├── with_mask
     |      └── without_mask
     ├── face_detector
     ├── CoronaGlobalUpdatesGUI.py
     ├── CovidUpdates.py
     ├── Detection.py
     ├── Training.py
     ├── detectMask_image.py
     ├── mask_detection_gui.py
     ├── mask_detector.model
     └── icons, background images, gifs, sounds etc.
     

# MADE BY SUBHAJIT PATI

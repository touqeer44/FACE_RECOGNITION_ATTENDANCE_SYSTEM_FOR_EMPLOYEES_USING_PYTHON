# FACE_RECOGNITION_ATTENDANCE_SYSTEM_FOR_EMPLOYEES_USING_PYTHON







FACE RECOGNITION ATTENDANCE SYSTEM FOR EMPLOYEES USING PYTHON



Final Year Project Proposal

Submitted by:
Fahad Touqeer

Supervised by:
Dr. Rana Nazeer Ahmad

Department of Information Technology
The Islamia University of Bahawalpur

Session      2022–2026
 
Certificate

This is to certify that the  project  report  titled  “Face Recognition Attendance System for Employees using Python” is the original work carried out by Fahad Touqeer under the supervision of Dr. Rana Nazeer Ahmad in partial fulfillment of the requirements for the degree of Bachelor of Science in Information Technology at The Islamia University of  Bahawalpur, 2022–2026.




_____________________________
Dr. Rana Nazeer Ahmad
Supervisor
 
Acknowledgement

I would like to express my sincere gratitude to my supervisor, Dr. Rana Nazeer Ahmad, for his guidance, support, and encouragement throughout this project. I am also thankful to the Department of Information Technology, The Islamia University of Bahawalpur, for providing me with the resources and knowledge necessary to complete this work. Finally, I would like to thank my family and friends for their motivation and moral support.
 
Abstract
This project aims to design and implement a Face Recognition Attendance System for employees using Python. The system automates the attendance marking process through facial recognition, reducing human intervention and ensuring accuracy. It uses machine learning and image processing techniques through libraries like OpenCV, Dlib, and Face Recognition, and is developed using Django and MySQL. The project provides a web-based interface where employees can register, log in, and view attendance records, while the admin can manage user data and attendance logs.
 
1: Introduction
1.1 Background
Attendance management is a crucial aspect of any organization. Traditional attendance systems often rely on manual entry or biometric devices that require physical contact. The Face Recognition Attendance System leverages image processing and machine learning to automate attendance tracking, making it efficient, accurate, and contactless.
1.2 Problem Statement
Manual attendance systems are time-consuming, error-prone, and prone to manipulation. This project addresses these limitations by developing an automated attendance system based on facial recognition technology.
1.3 Objectives
• To design and develop an automated face recognition system for attendance.
• To integrate Python and Django for real-time face detection and data management.
• To reduce human effort and enhance accuracy in attendance tracking.
• To provide an easy-to-use web interface for employees and administrators.
1.4 Scope
This system is intended for organizations and institutions where employee attendance tracking is essential. It can be extended to educational institutions or other organizations requiring identity verification.
 
 2: Literature Review
Various researchers have contributed to the development of face recognition-based attendance systems. According to IRJET (2020), the integration of OpenCV and machine learning has made facial detection more accurate. Studies from ResearchGate (2021) also highlight the importance of Dlib and CNN-based facial encodings in achieving high recognition accuracy. These studies guided the methodology adopted in this project.
 
 3: System Analysis and Design
3.1 System Requirements
Hardware Requirements:
• Laptop or PC with at least i3 processor, 4GB RAM, and webcam.

Software Requirements:
• Windows 7 or higher, Python, Django, MySQL, XAMPP Server, Sublime Text or VS Code.
3.2 System Architecture
The architecture consists of three main layers: the frontend (HTML/CSS/JS), backend (Python/Django), and database (MySQL). The webcam captures facial data, which is processed by OpenCV and Dlib for recognition, and attendance is logged in the database.
System Architecture














3.3 Data Flow Diagram (DFD)
Level 0 DFD illustrating main processes and external entities.
DFD Level 0 – Data Flow Diagram




















3.4 Use Case Diagram
Simplified use-case showing primary interactions between employee and admin.



            


Employee




                                                                                                      
                                                                              Admin









3.5 ER Diagram
Simplified ER diagram showing key entities and relationships.

	                                                                                                                                           ER Diagram (Simplified)
	
                                                                                                                                      


	



Records                                   
                                            
                                             Views/Updates Status




 
3.6 Process Flowchart of Daily Attendance Marking Process
 
4: Implementation

The system is implemented  using  Python’s  Django framework  for  the backend and OpenCV for facial detection. Employees register their profiles and facial data through the interface. The webcam detects and compares the face with stored encodings, marking attendance automatically upon recognition. The admin panel allows management of users and attendance records.

 
Flowchart Process of Employee Registration 
 
Flowchart Process of Admin Viewing Attendance Records
 
5: Testing and Results

Testing was carried out to ensure system functionality, accuracy, and usability. Unit testing verified individual modules, while integration testing ensured smooth data flow. The system achieved an average face detection accuracy of 95% in well-lit environments. Poor lighting conditions slightly reduced performance.
6: Conclusion and Future Work
This project successfully developed an automated face recognition attendance system that minimizes human intervention and ensures accuracy. In the future, the system can be enhanced by integrating mask detection, liveness detection to prevent spoofing, and cloud-based storage for scalability.
References
1) https://www.irjet.net/archives/V7/i12/IRJET-V7I12377.pdf
2) https://www.questjournals.org/jses/papers/Vol5-issue-2/D05021829.pdf
3)https://www.researchgate.net/publication/341870242_Smart_Attendance_System_using_OPENCV_based_on_Facial_Recognition
4)https://www.researchgate.net/publication/352393875_Attendance_Management_System_using_Face-Recognition
 
 
 


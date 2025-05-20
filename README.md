# smart_attendance_system
This project offers a cutting-edge solution for attendance tracking, combining the power of Django and deep learning to deliver a secure and accurate experience. Leveraging MTCNN (Multi-Task Cascaded Convolutional Networks) for face detection and the InceptionResnetV1 model for face encoding, the system automatically recognizes faces in real-time and logs attendance seamlessly.

Key Features:
Real-Time Face Recognition: Utilizes MTCNN and InceptionResnetV1 for precise face detection and encoding.

Multi-Camera Support: Configurable to work with both IP and local cameras for enhanced flexibility.

Automated Attendance Logging: Automatically records check-ins and check-outs, reducing manual intervention.

Admin Dashboard: Provides easy access to student databases, attendance records, and customizable settings.

Alert Sound on Successful Recognition: Plays a sound via Pygame when a face is successfully recognized.

Secure Login and Access: Ensures data security by restricting admin access for viewing, editing, and authorizing users.

Download Procedure
1.Download zipfile and extract in a folder named (smart_attendance_system)
2.open cmd in that folder
3.insert that commands in that cmd
4.pip install -r requirements.txt
5.python manage.py migrate
6.python manage.py runserver
7. after all the above installation
8. put this ip on browswer (http://127.0.0.1:8000/)
9. project is running now

# Smart-Attendance-System
# Combined mini project 


Face recognition systems are popular for their contactless and non-invasive nature, despite lower accuracy compared to iris or fingerprint recognition. They streamline attendance by automating the process, reducing proxy risks, and improving efficiency. The growing demand for secure systems makes this technology highly beneficial across sectors.

Manual attendance in schools and colleges is time-consuming and prone to proxy issues. Many institutes have adopted biometric methods like fingerprint recognition, but face recognition offers a faster, non-intrusive solution. By comparing student faces with a database, this system automates attendance, improving efficiency over traditional methods.

Manual attendance is time-consuming and prone to errors, including proxy attendance. RFID systems reduce errors but require physical interaction and can cause queues. Fingerprint recognition also faces delays due to queueing and requires physical contact with scanners, making it less ideal for large groups. Both methods have limitations.

**Limitations**  
- Time-Consuming  
- Error-Prone  
- Proxy Attendance  
- Queue-Based Delays  
- Intrusiveness

This Python script creates a face recognition-based attendance system with a graphical user interface (GUI). OpenCV captures images from the webcam, while Pillow converts them for real-time display in tkinter, which builds the GUI. Tkinter handles user interaction for logging in, logging out, and registering. Pickle serializes and stores face data for future recognition. The os module manages file paths, and face_recognition processes webcam images to generate and compare face encodings with stored data for accurate recognition. A custom util module simplifies tkinter operations by creating buttons, labels, and message boxes, keeping the code modular.

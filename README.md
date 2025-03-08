# Object_Oriented_Programming_Project

GROUP DOMAIN:
Cubers

GROUP MEMBERS:
Ramsey Foster
Nicolas Escobedo
Luca Ficano Latimer

1. Rubik's Cube Solver Application
Description
This application utilizes a webcam to capture images of a Rubik’s Cube, process the cube’s current state, and provide step-by-step solutions for solving it. The system applies computer vision techniques to detect cube colors and a solving algorithm to generate optimal moves.

2. Key Features
Webcam Integration

Capture real-time images of the Rubik’s Cube.
Process images using OpenCV for color detection.
Handle lighting and angle variations for accurate cube state recognition.
Cube State Processing

Convert the detected cube state into a structured format.
Validate cube states to ensure solvability.
Solving Algorithm

Implement a Rubik’s Cube solving algorithm (e.g., Kociemba’s Algorithm or Beginner’s Method).
Display step-by-step visual and textual instructions to solve the cube.
User Interface (GUI)

Intuitive JavaFX interface to guide users through capturing the cube.
Visual representation of cube faces and solution steps.
User Authentication (Optional)

Secure login system for saving cube solving history.
Role-based access if an admin panel is included.
History & Reporting

Store previous cube states and solutions in a database for analysis.
Generate reports on solving times and accuracy.

3. OOP Principles Applied
Encapsulation

Secure handling of image data and cube state processing.
Use private attributes for cube state storage and controlled access via methods.
Inheritance

Base Class: CubeSolver (Defines common solving methods).
Derived Classes:
BeginnerSolver (Basic solving method).
AdvancedSolver (Optimized solving method using Kociemba’s Algorithm).
Polymorphism

Implement different solving strategies based on user selection.
Overloaded methods for different cube input formats (image-based, manual input).
Abstraction

Define an interface CubeSolverInterface to allow different solving strategies.
Abstract class CameraProcessor for handling image capture and processing.

4. Technologies & Tools
Programming Language: Java
GUI Framework: JavaFX for an interactive and user-friendly interface.
Computer Vision: OpenCV (JavaCV bindings) for image processing and cube detection.
Database Management: MySQL for storing user data, cube history, and solving stats.
Security & Authentication:
Secure login using hashed passwords (BCrypt).
Role-based access for users and admins (if applicable).
Development Tools:
IDE: IntelliJ IDEA or Eclipse
Version Control: Git, GitHub

5. Expected Outcomes
A fully functional Rubik’s Cube Solver Application that captures cube states and provides an optimal solving sequence.
Efficient, modular, and scalable design following OOP best practices.
Accurate color detection and state validation using OpenCV.
Intuitive UI that helps users solve their cube step by step.
Data storage capabilities for tracking solving performance and history.

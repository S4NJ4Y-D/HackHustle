# HackHustle
AI-Driven Boolean Query Generator for Healthcare


Table of Contents
Introduction
Requirements.txt
Features
Technologies Used
Project Structure
Setup Instructions
Usage
Future Enhancements
Contributing
License

Introduction
AI-Driven Boolean Query Generator for Healthcare is a machine learning-powered web application designed to help healthcare professionals analyze medical scans, detect conditions (e.g., cancer), and generate Boolean queries to support research, diagnostics, and clinical decision-making. The project provides a streamlined interface for users to upload medical scans and receive Boolean-based analysis results, such as whether a specific condition is detected.
This project was developed as part of a 24-hour hackathon to showcase the potential of AI in enhancing medical database search capabilities and delivering accurate results.

Requirements.txt
flask
flask-cors
flask-restful
tensorflow
opencv-python
numpy
pandas
scikit-learn
pillow

To install all packages listed in the requirements.txt file in a new environment, use:

    pip install -r requirements.txt


Features
Medical Scan Upload: Allows users to upload medical scans directly through the website.
Condition Detection: Analyzes uploaded scans to detect specified conditions (e.g., lung cancer).
Boolean Query Generation: Automatically generates Boolean queries based on analysis results, providing a structured output for efficient database searches.
Frontend and Backend Integration: A user-friendly frontend with HTML, CSS, and JavaScript, and a backend in Flask to handle analysis.
Modular Design: Organized code structure for easy scalability and maintenance.

Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Python, Flask
Machine Learning: Model trained to detect conditions in medical scans (e.g., cancer detection)
Image Processing: PIL, imagehash for image comparison (if applicable)
Tools and Libraries: Flask, Pillow, imagehash, and any additional ML libraries (e.g., TensorFlow, CNN) if applicable

Project Structure
project_folder/
|-- app.py                    # Main Flask application
|-- dataset/                  # Folder containing dataset images for comparison
|   |-- image1.jpg
|   |-- image2.jpg
|-- templates/                # HTML template files
|   |-- upload.html           # Upload page
|   |-- result.html           # Result display page
|-- static/                   # Static files (CSS, JS, images)
|-- README.md                 # Project documentation
|-- requirements.txt          # Required libraries for the project

Setup Instructions
To set up the project locally:
1.Clone the repository:

    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name

2.Install Dependencies: Make sure Python is installed, then install the required libraries:

    pip install -r requirements.txt

3.Run the Flask App: Start the server by running:

    python app.py

4.Access the Application: Open a browser and go to http://127.0.0.1:5000 to access the application.

Usage
1.Navigate to the Home page and click Get Started.
2.Select a medical scan type (e.g., Lung Cancer Detection).
3.Upload the scan on the upload page and click Analyze.
4.View the generated Boolean query and results on the results page.

Future Enhancements
1.Enhanced Detection Capabilities: Extend support for multiple medical conditions.
2.Real-time Analysis: Integrate real-time detection for live scans.
3.Expanded Boolean Queries: Generate complex Boolean queries to assist in broader clinical queries.
4.Database Integration: Allow saving and querying results for future reference.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request if you would like to contribute to the project.
1.Fork the Project
2.Create your Feature Branch (git checkout -b feature/YourFeature)
3.Commit your Changes (git commit -m 'Add new feature')
4.Push to the Branch (git push origin feature/YourFeature)
5.Open a Pull Request


License
This project is licensed under the MIT License. See LICENSE for more information.

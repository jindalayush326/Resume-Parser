# Resume Parsing & Auto Form Filling

## Description

The Auto Resume Parsing & Auto Form Filling LLM Application is an intelligent tool designed to streamline the resume uploading and parsing process. It utilizes AI-driven models to extract essential details from resumes in PDF format and automatically fill out corresponding fields on the user interface. This system is powered by technologies such as Flask, PyPDF2, Google Generative AI, and Python. The application is ideal for users seeking to simplify the resume review process while ensuring that key information is accurately captured and displayed.

## Demo of the app
A demo showcasing the Auto Resume Parsing & Auto Form Filling LLM Application in action can be viewed at the link below:  
https://resume-pareser.onrender.com/


<img src="https://github.com/jindalayush326/Resume-Parser/blob/main/images/Screenshot%20(6076).png"/>
<img src="https://github.com/jindalayush326/Resume-Parser/blob/main/images/Screenshot%20(6077).png"/>
<img src="https://github.com/jindalayush326/Resume-Parser/blob/main/images/Screenshot%20(6078).png"/>

## Installation

To run this project, follow these steps:

1. Clone this repository to your local machine.
   ```bash
   git clone [https://github.com/jindalayush326/Resume-Parser.git]
   ```

2. Navigate to the project directory.
   ```bash
   cd Resume-Parser
   ```

3. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

Set up API keys:

4. Create a .env file in the root directory and add your API keys for Google Gemini Flash 1.5 and SerperAPI as follows:
   GOOGLE_API_KEY=<your-google-api-key>

## Usage

1. Ensure you have installed all dependencies as instructed above.

2. Run the Flask app.
   ```bash
   python ex.py
   ```

3. Access the app through your browser at http://localhost:5000

4. Interact with the app:

   Upload your resume in PDF format.
   View the extracted details displayed on the interface.

## Key Features
1. Resume Uploading: Users can upload their resumes in PDF format for parsing.
2. Auto Parsing: The application automatically extracts critical details such as name, contact information, education, skills, and work experience from the uploaded resume.
3. User-Friendly Interface: Built with Flask and HTML, providing a clean and intuitive interface for users to interact with.
4. Real-Time Feedback: Extracted information is displayed instantly on the same page for user review.

## Technologies Used
1. Flask: A web framework for building the application.
2. PyPDF2: A library to extract text from PDF files.
3. Google Generative AI: A powerful model for processing and extracting structured information from unstructured text.
4. Python: The programming language used to develop the core functionality.
5. HTML/CSS: Used for the front-end of the application to create a responsive and user-friendly interface.

## Credits
Flask
PyPDF2
Google Generative AI
Python

## License

This project is licensed under the [MIT License](LICENSE).
```

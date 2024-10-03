# ChatGPT-based Customer Support System

This is a simple customer support system using a Flask web application that interacts with OpenAI's GPT-3.5-turbo model to answer customer queries.

## Table of Contents
1. [Set up the environment](#set-up-the-environment)
2. [Download programs and related documentation](#download-programs-and-related-documentation)
3. [Process of program execution](#process-of-program-execution)
4. [Screenshot of execution results](#screenshot-of-execution-results)
5. [File Structure](#file-structure)
6. [License](#license)

## Set up the environment

To set up the environment, follow these steps:

### 1. Clone the Repository
First, clone the repository from GitHub:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Python3 and pip (Ubuntu)
Make sure you have Python 3 and pip installed. If not, run the following commands:
```bash
sudo apt update
sudo apt install python3 python3-pip python3-venv
```

### 3. Set up a Virtual Environment
It's recommended to set up a virtual environment to manage dependencies:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies
Install all required packages using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 5. Add OpenAI API Key
Create a `.env` file in the project root and add your OpenAI API key:
```
OPENAI_API_KEY=your-openai-api-key-here
```

Alternatively, export the environment variable directly (for temporary use):
```bash
export OPENAI_API_KEY=your-openai-api-key-here
```

## Download programs and related documentation

The main components of this project are:

1. **Flask** – Python web framework used to create the web app.
2. **OpenAI API** – Provides the ChatGPT model to answer user queries.
3. **HTML/CSS/JS** – Front-end design to interact with the user.

Refer to the following documentation for more details:
- [Flask Documentation](https://flask.palletsprojects.com/)
- [OpenAI GPT-3 API Documentation](https://beta.openai.com/docs/)

## Process of program execution

### 1. Running the Flask App
To start the Flask application, ensure your virtual environment is activated and run the following command:
```bash
python3 app.py
```
The app will be accessible at `http://127.0.0.1:5000/` in your browser.

### 2. Using the Customer Support System
- Open the app in your browser.
- Enter your question in the input box and click the **Send** button.
- ChatGPT will respond with an answer in the chat box.

### 3. Stopping the Server
To stop the Flask server, press `Ctrl + C` in your terminal.

## Screenshot of execution results

Add a screenshot here showing the execution of the app, displaying the interaction between the user and ChatGPT.

## File Structure

```plaintext
/project-folder
|-- app.py                  # Main Flask application
|-- templates/
|   |-- index.html           # Frontend HTML template
|-- static/                  # Static files (if any)
|-- requirements.txt         # Python dependencies
|-- README.md                # Project documentation
|-- .gitignore               # Files to ignore in Git
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Appendix
(Google Slide)[https://docs.google.com/presentation/d/1mcfiuwxxV6Ystplep2WQRNZoF3aNHshuFCRu5qqmF_k/edit#slide=id.p]
(Pdf reference with screenshots)[https://github.com/ASD-Are/GenAI/blob/main/Web%20Based%20Chatbot/Detailed%20Screenshot%20Guide%20with%20Errors%20Handled.pdf]

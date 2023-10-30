# Chatbot-Using-Python

This project is a Python-based chatbot application using Flask and TensorFlow. It uses a dataset to train a model that generates responses to user queries.

## Project Structure

The project consists of three main files:

- `app.py`: This is the main Python script that contains the Flask application and the chatbot logic.
- `templates/index.html`: This is the frontend of the web application.
- `dialogs.txt`: This is the dataset used to train the chatbot model.
- `NMphase5.ipynb`: Complete documentation of the project with executed codes and outputs.

## Dependencies

To run this project, you need to install the following dependencies:

- Python 3.9.0+
- Flask
- TensorFlow
- Numpy
- Pandas
- Scikit-learn
- NLTK

You can install these dependencies using pip:


pip install flask tensorflow numpy pandas scikit-learn nltk



## Running the Project

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the `app.py` script using Python.


python app.py


This will start the Flask application. You can access the web application by opening a web browser and navigating to `http://localhost:5000`.

## Usage
- Access the web application at `http://localhost:5000`.
- Enter your query in the input field and click "Send."
- The chatbot will process your query and provide a response based on the pre-trained model.

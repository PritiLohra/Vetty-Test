# Vetty-Test

this is a simple web application that allows users to view the contents of text files through a web interface. It provides the ability to specify file names, as well as optional start and end line numbers.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/vettytest.git
   
##Create and activate a virtual environment:

'''bash
cd vettytest
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

##Install dependencies:
pip install -r requirements.txt

##Usage
Run the Flask application:

'''bash

python app.py

Visit: http://localhost:5000 in your web browser.

##Endpoints
/: Displays the contents of the default file (file1.txt).
/<filename>: Displays the contents of the specified file.
/?start_line=<start>&end_line=<end>: Displays a specific range of lines if start and end parameters are provided.
Example: http://localhost:5000/file2.txt?start_line=5&end_line=10

##Exception Handling
If an exception occurs, an error page will be displayed with details about the exception.

##Deployment
Ensure you have fulfilled the installation steps.
Deploy the application according to your hosting environment.

##Contributing
Feel free to contribute to this project. Create a fork and submit a pull request.

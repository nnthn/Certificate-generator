# Certificate Generator

This project generates PDF certificates from a list of participants provided in a CSV file. 

## Instructions

Follow the steps below to set up and run the project:

### 1. Prepare the Project Directory

Ensure your project directory includes the following files:
- `index.html` (your HTML file)
- `response.csv` (your CSV file with participant data)
- `styles.css` (your CSS file)
- `certificate.svg` (your SVG file)

### 2. Create `response.csv`

Create a CSV file named `response.csv` with the following format (as an example):

```csv
idno,name
001,John Doe
002,Jane Smith

3. Install Python

Make sure Python is installed on your system. You can download it from python.org.
4. Start a Simple HTTP Server

Open a terminal or command prompt, navigate to the directory containing your project files, and run the following command:
For Python 3.x:

sh

python -m http.server 8000

For Python 2.x:

sh

python -m SimpleHTTPServer 8000

This command starts a local web server on port 8000.
5. Open the HTML File in a Browser

Open a web browser and go to:

sh

http://localhost:8000/index.html

This will load your HTML file and execute the JavaScript code, generating the PDFs for each entry in response.csv.
Example Directory Structure

recept
├── index.html
├── response.csv
├── styles.css
└── certificate.svg


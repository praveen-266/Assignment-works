### Task Overview:
This Python script extracts questions, options, and solutions from a text file and saves the data in JSON format. 

### Requirements:

   - Python 3.x
   - `re` 
   - `json`

Install the required packages by running the following command in your terminal or command prompt:          
    - **`pip install re json`**

### How it Works
- The script first imports the necessary libraries: re for regular expressions and json for JSON manipulation.
- The extract_text function is defined to handle the extraction of questions, options, and solutions from the input text.
- The function reads the input file Task.txt and processes each line of the text.
- It identifies the question ID, question text, options, correct answers, and solution text, and stores them in a dictionary.
- The extracted questions are appended to a list, and the final list is returned by the extract_text function.
- The script then converts the list of questions to a JSON string using the json.dumps function and saves the output to the Final_output.json file.

### How to Run 
  1. **Clone the Repository:** First, you need to clone the repository to your local machine. You can do this by running the following command in your terminal or command prompt:
     - `git clone https://github.com/praveen-266/MathonGo-Assignment.git`
  2. **Navigate to the Project Directory:** Once the repository is cloned, change your current directory to the project directory:
     - `cd Question-Solution-Extractor`
  3. **Run the code:** After installing the dependencies, you can run the code. The specific command to run the code will depend on the project structure and the programming language used.
     - `python Assignment_Code.py`
 

### Sample Input
- The content of the "Task.txt" file is used as input for the script.

### Sample Output
- The extracted data is formatted and stored in the "Final_output.json" file.

# Email Slicer

A simple Python script that extracts the username and domain from an email address. This project includes two versions:
1. **Basic Email Slicer**: Extracts the username and domain directly.
2. **Enhanced Email Slicer**: Additionally checks if the username contains a dot (.) separator and removes any numbers. If a dot is present, it splits the username into first name and last name.

## Version 1: Basic Email Slicer
This version performs the following steps:
- Takes an email address as input from the user.
- Splits the email address into `username` and `domain` based on the "@" symbol.
- Displays the extracted username and domain.
- Includes basic error handling to ensure the input is in the correct email format.

### Example Output
email address: johndoe@gmail.com Username: johndoe Domain: gmail.com


## Version 2: Enhanced Email Slicer
This version adds the following functionality:
- Removes any numbers from the username before processing.
- Checks if the username contains a dot (.) separator:
  - If a dot is present, the part before the dot is considered the first name and the part after the dot is considered the last name.
  - The first name and last name are displayed in the format: "First Name, Last Name".
  - If no dot is present, the entire username is treated as a single name.
- The program capitalizes the first letter of each name for better readability.

### Example Output
1. **Input**: `john.doe123@gmail.com`
Username: John, Doe Domain: gmail.com
2. **Input**: `alice123@gmail.com`
Username: Alice Domain: gmail.com

## Running the Program
- Download the Jupyter Notebook containing the code.
- Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
- Run the cells and follow the prompts to input an email address.

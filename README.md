# Password Strength Assessment Tool

## Description
This Python script assesses the strength of a given password based on several criteria, providing feedback and a strength rating. The criteria include password length, presence of uppercase and lowercase letters, numbers, and special characters. This tool helps users create stronger passwords by highlighting areas for improvement.

## Features
- Strength Assessment: Evaluates the strength of a password based on length, and inclusion of uppercase letters, lowercase letters, numbers, and special characters.
- Feedback: Provides detailed feedback on how to improve the password strength if it doesn't meet all criteria.
- Interactive Interface: Allows users to input a password and receive an immediate assessment and feedback.

## How It Works
- Criteria: The script checks if the password meets the following criteria:
  - At least 8 characters long
  - Contains at least one uppercase letter
  - Contains at least one lowercase letter
  - Contains at least one number
  - Contains at least one special character (e.g., @$!%*?&)
- Strength Rating: Based on the number of criteria met, the password is rated as Very Weak, Weak, Moderate, Strong, or Very Strong.
- Feedback: Specific feedback is provided to help improve password strength if any criteria are not met.

## Code Explanation
1. assess_password_strength(password):
   - Criteria Definition: Defines the criteria for password strength.
   - Criteria Evaluation: Evaluates the password against each criterion.
   - Strength Determination: Determines the strength of the password based on the number of criteria met.
   - Feedback Generation: Generates feedback on how to improve the password.

2. Example Usage:
   - Prompts the user to enter a password.
   - Calls the assess_password_strength function to evaluate the password.
   - Displays the password strength and feedback.

## Usage
1. Clone the Repository:
   ```bash
   git clone https://github.com/Mohansaikrishna1601/PRODIGY_CS_01.git
   cd PRODIGY_CS_01

2. Run the Script:

       python password_strength_assessment_tool.py
3. Follow the Prompts:

    -Enter a password when prompted.
    -View the strength assessment and feedback.

# Example:

Enter a password to assess its strength: MyPassword123!

Password Strength: Strong

Feedback:

- Password should contain at least one special character (e.g., @$!%*?&)

# Requirements
    Python 3.x

# Author

Mohan Sai Krishna G M


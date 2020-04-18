# homework3 > 03 JavaScript: Password Generator

Create an application that generates a random password based on user-selected criteria.

Random password generator will be based on our 3rd week of the BootCamp learning Java

# Requiremets:

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```

# Acceptance Criteria

```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```

# Pseudocode

1. Add function to "Generate Password" button to generate a prompt
2. Prompt user to enter how many characters he needs for his password
    
    * If user imput doesn't match 8 to 128 characters criteria
    > First alert: You must choose between 8 and 128
    > Second alert: You must choose a criteria
    
    * If user imput doesn't match number criteria for 8 and 128 and writes an alpha imput
    > Alert: Enter a value

3. After typing the imput it will start the questions about the criteria
4. Validate user imput
5. Statements that uses user input prompts to determine choices
6. Variable to fill uppercase conversion > In case the user choose uppercase
7. Random selection for all variables
8. Show password on Secure Password Box




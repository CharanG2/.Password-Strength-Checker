# Password Strength Checker

## Objective
This Python script evaluates the strength of a given password based on predefined security criteria. It helps users create stronger passwords by providing suggestions for improvement.

## Features
- Checks if the password meets a minimum length requirement.
- Ensures the presence of a mix of character types (uppercase, lowercase, digits, and special characters).
- Prevents the use of common weak passwords.
- Classifies passwords as **Weak**, **Moderate**, or **Strong**.
- Provides actionable suggestions for strengthening weak passwords.

## Requirements
- Python 3.x installed on your system.

## Installation and Setup
1. Clone or download the script to your local system.
2. Ensure you have Python installed.
3. Run the script using:
```sh
python password_strength_checker.py
```

## How It Works
Upon execution, the script prompts the user to enter a password and evaluates it based on:
1. **Minimum Length (8 characters)**
2. **Character Variety (Must include at least one lowercase, one uppercase, one digit, and one special character)**
3. **Common Passwords List (Prevents the use of commonly used weak passwords)**

### Classification
- **Strong**: Meets all criteria.
- **Moderate**: Meets two out of three criteria.
- **Weak**: Meets one or no criteria.

If the password is not strong, the script provides suggestions to improve it.

## Code Explanation
- `check_password_strength(password)`: Evaluates the password based on the three criteria and returns a strength rating.
- `suggest_improvements(password)`: Provides recommendations to enhance the password’s security.
- `main()`: Takes user input, checks password strength, and displays suggestions if necessary.

## Example Usage
```sh
Enter your password: Password123
Password strength: Moderate
Suggestions to improve your password:
- Include a mix of uppercase, lowercase, numbers, and special characters.
```

```sh
Enter your password: P@ssw0rd123
Password strength: Strong
```

## Best Practices for Strong Passwords
- Use at least **12 characters** instead of the minimum 8.
- Mix **uppercase, lowercase, numbers, and special characters**.
- Avoid using **common words** or predictable sequences.
- Consider using **password managers** to generate and store strong passwords.

## License
This project is open-source and can be used for educational and security awareness purposes.


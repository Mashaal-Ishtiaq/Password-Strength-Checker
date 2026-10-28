
# Password Strength Checker

A lightweight Python command-line application that evaluates password strength using a set of basic validation rules.

## Overview

The Password Strength Checker helps users identify whether a password meets a defined set of strength requirements. It checks the password and reports the first requirement that is not satisfied.

## Features

- Minimum password length of 8 characters
- At least one uppercase letter (`A–Z`)
- At least one lowercase letter (`a–z`)
- At least one digit (`0–9`)
- At least one supported special character
- Clear feedback when a requirement is not met
- Simple command-line interface

## Technology Stack

- **Language:** Python
- **Module:** `re` (regular expressions)

## Prerequisites

- Python 3.8 or later

No external dependencies are required.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Mashaal-Ishtiaq/Password-Strength-Checker.git
```

### 2. Navigate to the project directory

```bash
cd Password-Strength-Checker
```

### 3. Run the application

```bash
python password_strength_checker.py
```

If your system uses `python3`, run:

```bash
python3 password_strength_checker.py
```

## Usage

Run the program and enter a password when prompted.

Example:

```text
----------Password Strength Checker----------

Enter your password: Example@123
Password is strong!
```

The application checks the password against its configured rules and displays the first unmet requirement or a success message.

**Note:** The example password is for demonstration only. Do not reuse example credentials for real accounts.

## Validation Rules

| Requirement | Description |
|---|---|
| Length | At least 8 characters |
| Uppercase | At least one uppercase letter |
| Lowercase | At least one lowercase letter |
| Number | At least one digit |
| Special character | At least one character from the supported set |

## Limitations

- This is a basic rule-based checker, not a complete password security assessment.
- It does not measure password entropy or check against known compromised passwords.
- It does not determine whether a password is unique or safe to reuse.
- The result should not be treated as a guarantee of password security.

## Future Improvements

- Add automated unit tests.
- Provide an overall strength score.
- Support additional password policies.
- Improve input handling and validation feedback.

## License

No license is currently documented. Check the repository's licensing before redistributing or reusing this project.

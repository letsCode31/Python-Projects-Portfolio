# Password Authentication Tool

This Python project is a Password Authentication Tool that validates passwords based on several security requirements. It provides feedback to help users create stronger, more secure passwords, and optionally hashes valid passwords for secure storage.

## Features

- **Password Requirements**:
  - Minimum length of 8 characters
  - At least one uppercase letter
  - At least one lowercase letter
  - At least one digit
  - At least one special character (!@#$%^&*()-_+=<>?/)
  - Password must **not** contain the username

- **Feedback and Validation**: 
  - Provides detailed feedback if the password doesn’t meet security requirements.
  - Informs users of missing criteria to help them create stronger passwords.

- **Optional Hashing**: 
  - Uses SHA-256 hashing to securely store valid passwords.

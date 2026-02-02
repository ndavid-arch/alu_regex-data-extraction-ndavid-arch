Overview

This project is a JavaScript-based data extraction and validation tool that uses regular expressions (regex) to safely process user input. It simulates a realistic frontend scenario where untrusted data must be validated, extracted, and handled securely.

What the Program Does

Extracts name, country, and payment amount from a user introduction paragraph

Validates email, password strength, and credit card number using regex

Hashes passwords using the browser Web Crypto API

Masks sensitive data (email and credit card)

Rejects invalid or unsafe input

Displays a structured preview and allows saving the data as JSON

Security Awareness

User input is treated as untrusted

Passwords are never stored or displayed in plain text

Sensitive data is masked in output

Malformed or malicious input is safely rejected

Project Structure
alu_regex-data-extraction-ndavid-arch
│
├── README.md
├── sample_user_inputs.txt
├── extracted_output.json
└── srccode.html

How to Run

Open srccode.html in a web browser

Fill in the form

Click Extract Data

Optionally save the output as JSON

Implementation Note

All regex extraction, validation, and security logic is implemented in JavaScript. HTML and CSS are used only for frontend input simulation and styling.

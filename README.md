Overview

DigiShield is a secure and user-friendly digital identity management system designed to protect individuals and organizations from identity theft, unauthorized access, and data breaches. It incorporates advanced features like multi-factor authentication, encrypted file uploads, and activity monitoring to ensure the highest level of security and privacy.
Features

    Secure Authentication:
        Multi-factor authentication (2FA) via OTP (SMS/email).
        Biometric authentication (planned future feature).

    Identity Protection Tools:
        Security level indicators with actionable recommendations.
        Last login details to monitor suspicious activity.

    Encrypted File Storage:
        Supports encrypted uploads for sensitive files.

    User-Friendly Design:
        Intuitive, responsive interface compatible with all devices.

Technologies Used

    Frontend:
        HTML, CSS, JavaScript (or frameworks like React/Angular if applicable).

    Backend:
        Node.js, Python (Flask/Django), or any backend language/framework you used.

    Database:
        MySQL, PostgreSQL, or MongoDB for secure data storage.

    Security:
        AES-256 for encryption.
        Hashing algorithms like SHA-256 for password storage.

Setup Instructions
Prerequisites:

    Node.js and npm installed (if applicable).
    Python environment set up (if using Python-based backend).
    Database service (MySQL/PostgreSQL/MongoDB) running locally or on a server.

Installation:

    Clone the repository:

git clone https://github.com/your-username/digishield.git  
cd digishield  

Install dependencies:
For Node.js:

npm install  

For Python:

pip install -r requirements.txt  

Configure the .env file:

    Add your database credentials.
    Specify API keys for any external services (e.g., SMS/email).

Initialize the database:
Run the migration scripts:

python manage.py migrate  

Start the server:
For Node.js:

npm start  

For Python:

python manage.py runserver  

Open your browser and navigate to:

    http://localhost:8000  

Usage

    Sign-Up:
    Users can register using their email and mobile number.
    Login:
    Login using 2FA (OTP will be sent to registered email/SMS).
    Upload Files:
    Upload and manage encrypted files securely.
    Monitor Account Security:
    View account security levels and take recommended actions.


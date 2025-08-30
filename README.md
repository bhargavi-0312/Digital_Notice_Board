[DIGITAL NOTOCE BOARD.txt](https://github.com/user-attachments/files/22057536/DIGITAL.NOTOCE.BOARD.txt)
DIGITAL NOTOCE BOARD

(FLASK BASED WEB APPLICATION)

The Digital Notice Board is a modern, Flask-powered web application designed to streamline the way institutions manage and display public announcements. Unlike traditional Google Sheets or Forms-based systems, this platform offers full backend control, secure data handling, and scalable deployment options.

KEY FEATURES

->Secure Admin Portal

->Role-based login and authentication system for admins to manage notices.

->Notice Submission & Management

->Real-time notice creation.

->Support for image or PDF uploads.

->Category-based filtering and keyword search.

->Interactive poster view for previewing notices.

->Responsive & Accessible Design

->Works seamlessly across devices (desktop, tablet, mobile) and supports offline access via service workers.


API ACCESS

Lightweight REST API to fetch notice data as JSON, enabling integration with mobile apps or third-party platforms.


TECH STACK

->Backend: Python, Flask

->Database: SQLite / PostgreSQL

->Frontend: HTML, CSS, Bootstrap, JavaScript


Installation & Setup

1. Create and activate a virtual environment

python -m venv venv

source venv/bin/activate  # Linux/macOS

venv\Scripts\activate     # Windows


2. Install dependencies

pip install -r requirements.txt


3. Configure environment variables

4. Create a .env file with necessary variables:

FLASK_APP=app.py

FLASK_ENV=development

SECRET_KEY=your_secret_key

DATABASE_URL=sqlite:///db.sqlite3  # or PostgreSQL URI


5. Initialize the database
6. 
flask db init

flask db migrate -m "Initial migration"

flask db upgrade


6. Run the application

flask run

Access the app at http://localhost:5000


Usage

Admin Login:

Access the admin portal to manage notices securely.

Submit Notices:

Create notices with images, PDFs, categories, and keywords.

Search & Filter:

Users can search notices by keyword or category.

Preview Notices:

Interactive poster view to visualize announcements before publishing.


Deployment

Local Deployment: Use flask run 




# Automated Placement Portal

A web-based application built using Flask and SQLite3 to automate and streamline the college placement process. This portal provides role-based access for administrators, students, and recruiters, simplifying job postings, student applications, and interview management.

## Features

### Admin Module

* Approve or reject company registration requests
* Manage student records and verify registrations
* Create and manage job postings and mock interview schedules
* View analytics and placement statistics

### Company Module

* Register and request portal access
* Post job opportunities for students
* View applicant lists and schedule interviews
* Update results and track recruitment status

### Student Module

* Register and log in to view eligible job openings
* Apply for jobs and upload resumes
* View mock interview schedules and final results
* Receive notifications on application status

## Tech Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Database:** SQLite3
* **Authentication:** Flask-Login
* **Templating Engine:** Jinja2

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rahul-1809/College-Placement-Portal.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python main.py
   ```

4. Open your browser and navigate to:

   ```
   http://127.0.0.1:5000/
   ```

## Folder Structure

* `main.py`: Main Flask application
* `templates/`: HTML templates
* `static/`: CSS, JavaScript, images
* `database/`: SQLite database file and models
* `.py`: Python applications

## Contributing

Feel free to fork the project and submit pull requests for new features or bug fixes. For major changes, open an issue first to discuss what you would like to change.


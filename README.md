# ApptiMock Quiz Application

ApptiMock is a comprehensive quiz application built using HTML, CSS, JavaScript, and Django. This application features multiple pages including a home page, leadership page, quiz page, about page, registration and login pages, a dashboard for superusers, and a blogs page.

## Features

- **Home Page:** Introduction and navigation to other sections of the app.
- **Leadership Page:** Information about the leadership team.
- **Quiz Page:** Interactive quiz section.
- **About Page:** Details about the application and its purpose.
- **Register Page:** User registration functionality.
- **Login Page:** User authentication.
- **Dashboard Page (Superuser Only):** Administrative panel for superusers to manage content.
- **Blogs Page:** A section for blog posts.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.x
- pip (Python package installer)

## Setup

Follow these steps to set up the project on your local machine:

### Clone the Repository

```bash
git clone https://github.com/Baig-fatema/ApptiMock-Quiz-Application.git
```
### Navigate to the Project Directory
```bash
cd ApptiMocl-Quiz-Application
```
### Create a Virtual Environment
```bash
python -m venv env
```
### Activate the Virtual Environment
Windows:

```bash
env\Scripts\activate
```
macOS/Linux:

```bash
source env/bin/activate
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
### Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### Create a Superuser
```bash
python manage.py createsuperuser
```
### Run the Development Server
```bash
python manage.py runserver
```
### Usage
Open a web browser and go to http://127.0.0.1:8000 to access the application.
Use the registration and login pages to manage user accounts.
Access the superuser dashboard at http://127.0.0.1:8000/admin to manage the application content.
Contributing
Contributions are welcome! Please open issues or submit pull requests to enhance the project.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Contact
For questions or feedback, reach out to mirzafatmabaig1012@gmail.com.

### Author
[Baig-Fatem](https://github.com/Baig-fatema)











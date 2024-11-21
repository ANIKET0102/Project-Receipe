Project Recipe 🍴

Project Recipe is a web application designed for culinary enthusiasts to share, manage, and organize their recipes. Built using Django and Bootstrap, it offers a user-friendly platform to store and manage recipe data with ease.

🌟 Features
Add Recipes: Users can submit recipes along with an image of the dish.
Manage Recipes: Options to update or delete existing recipe entries.
Backend Storage: All recipe data and images are securely stored in the backend for efficient management and retrieval.
Responsive Design: Styled with Bootstrap for a clean and user-friendly interface across devices.

💻 Technologies Used
Django: For building the backend and managing data storage.
Bootstrap: For responsive and modern UI design.
SQLite: (Default) Backend database for storing recipe data.

📂 Project Structure
php
Copy code
Project-Receipe/  
├── manage.py                # Django management script  
├── app/                     # Main application folder  
│   ├── templates/           # HTML templates for the UI  
│   ├── static/              # Static files (CSS, JS, images)  
│   ├── models.py            # Django models for data management  
│   ├── views.py             # Logic to handle user requests  
│   └── urls.py              # URL routing  
├── db.sqlite3               # Database file  
└── README.md                # Project documentation  


🚀 Getting Started
Follow these steps to set up and run the project on your local machine:

Prerequisites
Ensure you have Python and Django installed.

Clone the repository:
git clone https://github.com/ANIKET0102/Project-Receipe.git  

Navigate to the project directory:
cd Project-Receipe  

Install required dependencies:
pip install -r requirements.txt  

Run database migrations:
python manage.py migrate  

Start the development server:
python manage.py runserver

Open the application in your browser:
Visit http://127.0.0.1:8000/ to access the app.

🛠️ How It Works
Add Recipes: Fill out the form with recipe details and upload an image.
View Recipes: View all stored recipes in an organized manner.
Edit or Delete: Modify or remove entries as needed using intuitive controls.




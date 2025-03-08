1. Clone the Repository
git clone https://github.com/KhaldZ1/TaskManager.git
cd task_manager
2. Create a Virtual Environment
python -m venv venv
Activate it:
venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Apply Migrations
python manage.py makemigrations
python manage.py migrate
5. Run the Server
python manage.py runserver
Now open http://127.0.0.1:8000/ in your browser.
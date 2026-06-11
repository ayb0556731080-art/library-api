# תיאור המערכת 
שרת API באמצעות FastAPI שמתחבר למסד נתונים MySQL ומנהל מערכת של ספרים וחברי ספרייה.

# הקוד ליצירת docker עם MySql
docker run --name mysql-library -e MYSQL_ROOT_PASSWORD=1234 -e MYSQL_DATABASE=library_db -p 3306:3306 -v library_data:/var/lib/mysql -d mysql:latest

# מבנה התיקיות
library-api/
│
│
├── main.py
├── database/
│ ├── db_connection.py
│ ├── book_db.py
│ └── member_db.py
├── routes/
│ ├── book_routes.py
│ ├── member_routes.py
│ └── report_routes.py
├── logs/
│ └── app.log
│
├── README.md
├── requirements.txt
└── .gitignore
# מבנה הטבלאות

# חוקי המערכת

# רשימת Endpoints

# זרימת המערכת

# הוראות הרצה

# 📝 Flask To-Do List App

A **feature-rich** To-Do List application built using Flask, with user authentication, task sorting, priority levels, analytics, and more.

## 🚀 Features
- ✅ **User Authentication** (Register, Login, Logout)
- 📌 **Task Management** (Add, Edit, Delete, Complete)
- 🎯 **Priority-Based Sorting** (High, Medium, Low)
- 📅 **Due Date Assignment**
- 📊 **Task Analytics & Reports**
- 🔄 **Drag & Drop Reordering** (Planned)
- 🎨 **Minimal UI** with Jinja Templates

## 🛠️ Tech Stack
- **Backend:** Flask, Flask-Login, Flask-WTF, Flask-SQLAlchemy, Flask-Migrate
- **Database:** SQLite (Can be switched to PostgreSQL/MySQL)
- **Frontend:** HTML, CSS, Jinja2
- **Authentication:** Password Hashing (Werkzeug)

## 🔧 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate  # Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize Database**
   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

5. **Run the App**
   ```bash
   flask run
   ```

6. Open `http://127.0.0.1:5000/` in your browser.

## 📸 Screenshots
![Screenshot 2025-03-22 101928](https://github.com/user-attachments/assets/656745f6-04e2-49a4-87bc-a9702ce0b7a1)


## 📌 API Routes
| Route           | Method | Description              |
|----------------|--------|--------------------------|
| `/`            | GET    | Dashboard (Requires login) |
| `/register`    | GET/POST | User Registration |
| `/login`       | GET/POST | User Login |
| `/logout`      | GET    | Logout User |
| `/add`         | POST   | Add a New Task |
| `/delete/<id>` | POST   | Delete a Task |
| `/complete/<id>` | GET  | Mark Task as Complete |
| `/analytics`   | GET    | Get Task Statistics |

## 🛠️ Future Enhancements
- 🔄 **Drag & Drop Task Ordering**
- 🔔 **Reminders & Notifications**
- 📱 **Mobile-Friendly UI**

## 📜 License
This project is open-source under the MIT License.

---

💡 **Contributions are welcome!** Feel free to fork this repo and submit a PR.

```

Would you like me to add anything else? 🚀

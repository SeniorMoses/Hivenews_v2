# Hivenews_v2 📰

Hivenews_v2 is a FastAPI-based news web service where users can read news articles, search for news, and interact through comments.

The API implements several security features and follows modern REST API development practices.

## 🚀 Features

### Authentication & Security
- User signup
- User login
- OAuth2 authentication
- JWT-based authentication
- Authorization
- Role-Based Access Control (RBAC)
- Password hashing with bcrypt
- Dependency injection

### News Management
- Post news (admin access)
- Read news
- Search news by title
- Pagination support

### User Interaction
- Add comments to news articles
- Read comments

---

## 🛠️ Technologies Used

- **FastAPI** — Web framework for building REST APIs
- **SQLAlchemy** — ORM for database management
- **OAuth2 + JWT** — Authentication and authorization
- **bcrypt** — Secure password hashing
- **Pydantic** — Data validation
- **Dependency Injection** — Managing application dependencies
- **PostgreSQL** — Database support

---

## 🔮 Future Improvements

Planned features:

- Like news articles
- user connection 
- Rate limiting
- Alembic database migrations
- Docker containerization
- Logging system
- Automated testing
- CI/CD pipeline

---

## 🌍 Live Demo

The service is deployed on Render:

url:https://hivenews-v2.onrender.com
interactive documentation:
https://hivenews-v2.onrender.com/docs

---


---

## ⚙️ Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/SeniorMoses/Hivenews_v2.git

cd Hivenews_v2
```
### 2. install depency

pip install -r requirements.txt

### 3. create .env file
SECRET = your_secret_key
DBURL = your_db_url

### 4. start the server
uvicorn main:app 

or if using gunicorn
gunicorn main:app -k uvicorn.workers.UvicornWorker

AUTHOR
SENIOR MOSES
GHANA 




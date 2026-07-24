# 📰 Hivenews_v2

Hivenews_v2 is a **FastAPI-powered news REST API** that allows users to read news articles, search news by title, and interact through comments.

The project focuses on building a secure backend system using modern API development practices, including authentication, authorization, and role-based access control.

---

# 🚀 Features

## 🔐 Authentication & Security

- User registration (Signup)
- User login
- OAuth2 authentication flow
- JWT access token authentication
- Authorization system
- Role-Based Access Control (RBAC)
- Secure password hashing using bcrypt
- Dependency injection with FastAPI

---

## 📰 News Management

- Create news articles (Admin only)
- Read news articles
- Search news by title
- Pagination support

---

## 💬 User Interaction

- Add comments to news articles
- View comments on articles

---

# 🛠️ Technologies Used

| Technology | Purpose |

| FastAPI | High-performance REST API framework 


| SQLAlchemy | Database ORM 


| PostgreSQL | Production database 


| OAuth2 | Authentication protocol 


| JWT | Secure token-based authentication 


| bcrypt | Password hashing 


| Pydantic | Data validation and serialization 


| Dependency Injection | Managing application dependencies 

---

# 🏗️ API Security Implementation

Hivenews_v2 includes:

- Protected API routes using JWT tokens
- Admin-only endpoints using RBAC
- Secure password storage
- Token-based user authentication
- Validation using Pydantic schemas

---

# 🔮 Future Improvements

Planned features:

- ❤️ Like news articles
- 👥 User connections/follow system
- 🚦 Rate limiting
- 🗄️ Alembic database migrations
- 🐳 Docker containerization
- 📝 Logging system
- 🧪 Automated testing
- ⚙️ CI/CD pipeline

---

# 🌍 Live Demo

The API is deployed on Render:

**API Base URL**
```
https://hivenews-v2.onrender.com
```

**Interactive Swagger Documentation**
```
https://hivenews-v2.onrender.com/docs
```

---

# ⚙️ Running Locally

## 1. Clone the repository

```bash
git clone https://github.com/SeniorMoses/Hivenews_v2.git

cd Hivenews_v2
```

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

## 3. Create environment variables

Create a `.env` file:

```env
SECRET=your_secret_key
DBURL=your_database_url
```

## 4. Start the development server

Using Uvicorn:

```bash
uvicorn main:app --reload
```

Using Gunicorn:

```bash
gunicorn main:app -k uvicorn.workers.UvicornWorker
```

---

# 📌 Author

**Senior Moses**

Backend Developer  
Ghana 🇬🇭

GitHub:
https://github.com/SeniorMoses

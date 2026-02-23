## Installation & Setup Guide

Follow the steps below to run the application successfully.

---

### 1. Clone the Repository

```bash
git clone https://github.com/7Vijval/library-management-system.git
cd library-management-system
```

---

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

---

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Set Environment Variables

**Windows (PowerShell)**

```bash
$env:FLASK_APP="app.py"
$env:FLASK_ENV="development"
```

**Mac/Linux**

```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

---

### 5. Run the Application

Start the Flask development server:

```bash
flask run
```

OR

```bash
python -m flask run
```

---

### Application Running

Open browser and visit:

```
http://127.0.0.1:5000
```

The application should now run successfully.

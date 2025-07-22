# 🔥 Flask Mock API + Frontend Template

A simple **Flask web app** that renders an HTML page and serves mock JSON data via an API endpoint.

---

## 🚀 Features

- ✅ Serves an HTML page at `/`
- ✅ Exposes a mock API endpoint at `/api/data`
- ✅ Reads data from a local `mock_data.json` file
- ✅ Easily extendable for frontend/backend projects
- ✅ Lightweight and beginner-friendly Flask setup

---

## ⚙️ Setup Instructions

### 1. Clone or Download

```
git clone https://github.com/Nomahk25/flask-mock-api.git
cd flask-mock-api
```

### 2. Create a Virtual Environment (optional but recommended)

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Flask

```
pip install flask
```

### 4. Run the App

```
python app.py
```

Then open your browser and navigate to:
👉 http://localhost:5000

---

## 📡 API Endpoint
GET /api/data
Returns data from mock_data.json.

Example Response:
```
[
  {
    "id": 1,
    "name": "Sample Item",
    "value": 42
  },
  {
    "id": 2,
    "name": "Another Item",
    "value": 17
  }
]
```

## 🧪 Example Use Case
You can fetch the mock data from the frontend using JavaScript:

```
fetch('/api/data')
  .then(response => response.json())
  .then(data => console.log(data));
```

## 📄 License

This project is licensed under the MIT License.

## ✍️ Author

Built with Flask ❤️ by Nomanguni Khumalo

# Flask DevOps Lab - (Version A)

Flask app for practicing Git, GitHub, and Docker

## Usage

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

The app runs on port 8080. Available endpoints:

- /api/health – returns a status check confirming the app is running
- /api/config – returns the contents of config.json
- /api/report – returns hostname, Python version, and uptime

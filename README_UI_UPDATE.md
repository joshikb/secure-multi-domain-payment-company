# Secure Multi-Domain Payment Company — UI update

This replaces the original basic `render_template_string` UI while preserving the
existing Flask routes and security/demo logic.

Files:
- `app.py` — updated application with responsive SecurePay UI
- `requirements.txt` — Flask + Gunicorn

Render:
- Build: `pip install -r requirements.txt`
- Start: `gunicorn --bind 0.0.0.0:$PORT app:app`

Demo accounts:
- customer1 / Cust#1234
- admin1 / Adm!n#987

This remains a prototype. Do not use real card credentials or production secrets.
Set `SECRET_KEY` and `ADMIN_API_KEY` as environment variables in production.

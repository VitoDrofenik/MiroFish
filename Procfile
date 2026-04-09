# Force FLASK_DEBUG off so the dev reloader never runs (saves ~1x RAM on small dynos).
web: bash -c 'export FLASK_DEBUG=false; cd backend && export FLASK_PORT=$PORT && python run.py'

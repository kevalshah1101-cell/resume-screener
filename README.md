powershelldir
cd resume-screener
dir
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

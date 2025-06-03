- created branch origin/cleanupopenwebuilinks
- created environment
conda activate openwebui

- HOW TO START THIS THING?



ACTIVATE ENVIRONMENT & BACKEND START
cd backend
conda activate openwebui
python -m uvicorn open_webui.main:app --port 8080 --host 0.0.0.0 --reload

FRONTEND
npm run dev

http://localhost:5173/

ADMIN ACCOUNT
Login email: george@discoverlatitude.com
password: L*****27
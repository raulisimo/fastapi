# START LOCAL SERVER
uvicorn app.main:app

# START LOCAL SERVER USING WATCHGOD
uvicorn app.main:app --reload
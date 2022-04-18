# Movies Website for COSc 381
## Steps or starting the website (development mode)

Steps and commands to follow:
1. creating virtual environment in the root directory : 'python3 -m venv venv'
2. Activate the virtual environment: 'source venv/bin/activate'
3. Install dependencies: 'python3 -m pip install -r requirements.txt'
4. Set up environment variables for the flask app: 'source env-var.sh'
5. Initalize the database : 'flask init-db' After the database is initialize, the database files at : 'instance/flasker.sqlite'
6. Start the website: 'flask run'
7. The webpage can be checked at :`http://127.0.0.1:5000/movies/`

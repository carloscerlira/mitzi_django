# Run Locally
git clone https://github.com/carloscerlira/mitzi_django.git  
cd mitzi_django  
python3 -m venv --upgrade-deps .venv  
.\.venv\Scripts\activate (windows)  
source .venv/bin/activate (linux)  
pip install -r requirements.txt  
heroku local --port 5001 -f Procfile.windows (windows)  
heroku local --port 5001 (linux)  


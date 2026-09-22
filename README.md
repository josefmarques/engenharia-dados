pip3 install virtualenv

mkdir fast_master 
cd fast_master/ 
poetry new --flat eletrosil_api 
cd eletrosil_api/ 
poetry python install 3.14 poetry 
python list poetry env use 3.14 
poetry env info poetry install (cria o poetry.lock e dependências) poetry add 'fastapi[standard]' poetry run fastapi dev car_api/app.py

python3 -m venv venv 
source venv/bin/activate ou . venv/bin/activate 
pip install pylint pylint --generate-rcfile > .pylintrc (para formatação de código)
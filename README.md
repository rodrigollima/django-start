# django-start

APP_NAME='eventex'

PROJECT_SOURCE='wttd'

mkdir $PROJECT_SOURCE

cd $PROJECT_SOURCE

pip3 install virtualenv

python3 -m venv ".$PROJECT_SOURCE"

source ".$PROJECT_SOURCE/bin/activate"

pip install django

django-admin startproject $APP_NAME .

cd $APP_NAME

alias manage='python $VIRTUAL_ENV/../../$PROJECT_SOURCE/manage.py'

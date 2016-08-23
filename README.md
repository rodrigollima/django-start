# django-start

APP_NAME='eventex'
PROJECT_SOURCE='wttd'

mkdir $PROJECT_SOURCE

pip3 install virtualenv

python3 -m venv ".$PROJECT_SOURCE"

source ".$PROJECT_SOURCE/bin/activate"

cd $PROJECT_SOURCE

pip install django

django-admin startproject $APP_NAME .

cd $APP_NAME


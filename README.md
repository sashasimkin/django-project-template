Template, that makes easier to start django projects.

Usage
---
First install django to your system python installation(by root), and simply do following:
```bash
django-admin.py startproject \
--template=https://github.com/sashasimkin/django-project-template/archive/master.zip \
%project_name%
```
Optionally if you preffer to use virtualenv
```bash
virtualenv .env
. .env/bin/activate
pip install -r requirements/pip.txt
```
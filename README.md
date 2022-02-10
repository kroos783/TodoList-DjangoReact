# BLD Devs 2.0

---

## How to prepare

_requirement : python installed_
<br><br>
for Windows : 

```
pip install virtualenv
virtualenv venv
venv\Scripts\activate.ps1
pip install -r packages.txt
npm install *in folder frontend*
npm run build *in folder frontend*
```

for Linux & Mac :

```
sudo pip install virtualenv
virtualenv venv
venv\Scripts\activate
pip install -r packages.txt
sudo npm install *in folder frontend*
npm run build *in folder frontend*
```

---

## How to run

_requirement : npm & node.js installed_
<br><br>
in shell (venv) /backend :

```
python manage.py runserver
```

in shell (venv) /frontend :

```
npm start
```

---

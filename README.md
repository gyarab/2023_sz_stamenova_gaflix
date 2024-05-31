# 2023_wa_sz_stamenova_gaflix
## Spuštění projektu:
./manage.py makemigrations
./manage.py migrate
## Kdyby nefungovalo:
rm db.sqlite3 
./manage.py migrate
./manage.py makemigrations
./manage.py migrate
./manage.py loaddata fixtures/*.json

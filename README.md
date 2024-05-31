# 2023_wa_sz_stamenova_gaflix
## Spuštění projektu:
./manage.py makemigrations <br />
./manage.py migrate<br />
## Kdyby nefungovalo:
rm db.sqlite3 
./manage.py migrate
./manage.py makemigrations
./manage.py migrate
./manage.py loaddata fixtures/*.json

# 2023_wa_sz_stamenova_gaflix
## Spuštění projektu:
./manage.py makemigrations <br />
./manage.py migrate <br />
## Kdyby nefungovalo:
rm db.sqlite3 <br />
./manage.py migrate <br />
./manage.py makemigrations <br />
./manage.py migrate <br />
./manage.py loaddata fixtures/*.json <br />

# TestWork_ApiBest

git clone https://github.com/laravel/quickstart-basic quickstart
cd quickstart
docker-project update # клонирует указанные репозитории в структуру apps/vendor/web-ui
docker-project build # собирает имиджи тем где указана команда build, вполне возможно вам это не нужно
docker-compose up # далее обычная работа обычная работа.
...

docker-project update # повторный вызов делает git pull

#Коммит кода в конкретном репозитории сервиса происходит обычным образом.
cd apps/vendor/web-ui
git add .
git commit -m "...."
git push


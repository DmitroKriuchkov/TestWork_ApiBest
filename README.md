# TestWork_ApiBest

``` bash
git clone https://github.com/laravel/quickstart-basic quickstart
```
``` bash
cd quickstart
```
``` bash
docker-project update # клонирует указанные репозитории в структуру apps/vendor/web-ui
```
``` bash
docker-project build # собирает имиджи тем где указана команда build, вполне возможно вам это не нужно
```
``` bash
docker-compose up # далее обычная работа обычная работа.
...

docker-project update # повторный вызов делает git pull
```
# Коммит кода в конкретном репозитории сервиса происходит обычным образом.

``` bash
cd apps/vendor/web-ui
```
``` bash
git add .
```
``` bash
git commit -m "...."
```
``` bash
git push
```

Превращаем папку в локальный репозиторий git init
прежде чем сделать первый commit git попросит нас представиться через команды git config --global user.email "Почта", git config --global user.name "Имя пользывателя"
Даём команду git отслеживать файл git add название папки
Делаем наш первый commit git commit -m "Комментарий"
git branch -M main
git remote add origin https://github.com/Saidbegov21/DZ.git
git push -u origin main
------------------
git clone
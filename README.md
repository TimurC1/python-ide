# python-ide
⚡ Простая и функциональная веб-IDE для разработки на Python. Перевод и адаптация репозитория vimior

## Особенности
- Для проекта использовался Python, Tornado, VueJS и WebSocket.
- Проект состоит из бэкенда на Python, Tornado и фронтенда на VueJS и WebSocket.
## Функционал
- Создание проектов, файлов, папок, дополнений и изменений
- Поддержка Python без фреймворков.
## Скриншоты
![image](doc/img/ide/code.png)
![image](doc/img/ide/complete.png)
![image](doc/img/ide/run.png)

## Установка на сервер фронтенда
``` bash
# Клонирование репозитория
git clone https://github.com/TimurC1/python-ide

# Зайдите в данный репозиторий
cd python-ide

# Воспользуйтесь npm, если у вас его нет, установите его вместе с Node.js: https://nodejs.org/en/download/
npm install

# Запуск веб-сервера разработки на порту 8080
npm run dev

# Компиляция
npm run build 
```
### Установка на сервер бэкенда
```
# Зайдите в папку backend
cd backend

# Установите необходимые дополнения для Python
pip install -r requirements.txt

# Запустите сервер разработки
python server.py --port=$ПОРТ, КОТОРЫЙ ВЫ ЖЕЛАЕТЕ ИСПОЛЬЗОВАТЬ$
```
Убедитесь, что у вас открыт порт, который вы указали в последней команде.

© https://github.com/vimior

© Перевод и улучшение README.md https://github.com/timurc1

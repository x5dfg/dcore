# [D-Core](https://x5dfg.github.io/bio/#dcore)
![](https://avatars.githubusercontent.com/u/142392565?v=4)
## Notes:
> [!NOTE]
> Проект лишь объединяет функционал Discord, Telegram и некоторых внешних API. 
> 
> Не подавайте на нас в суд пожалуйста!



## Скачивание и установка:
**( Будет доступно здесь в Июне )**

> [!IMPORTANT]
> Для корректного запуска клиента вам нужно установить следующие пакеты:
> - Node.js
> - Electron.js
> - Axios
> - WS


> [!WARNING]
> Помните, что этот список не постоянен, и будет изменяться во время разработки. 
> 
> Для установки зависимостей в виртуальное окружение используйте команду:
>
> `npm install ...`
>
> Для запуска клиента используйте команду `npm start`, если ваш `package.json` выглядит следующим образом:


```json 
{
  "name": "d-core",
  "version": "0.1.8",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "electron ."
  },
  "author": "DSC",
  "license": "ISC",
  "dependencies": {
    "axios": "^1.6.8",
    "electron": "^30.0.1",
    "ws": "^8.16.0"
  }
}
```

## Info:
### About:
Проект является **соц.сетью**, по задумке, объединяющую как Api [Discord](https://discord.com/invite/8fVBVpeast), [Telegram](https://t.me/x5dfg_dcore) и [Youtube](https://www.youtube.com/@x5dfg-dcore?sub_confirmation=1), так и их пользовательские возможности. 

Например: вы сможете создавать свои чаты/каналы/сервера, сообщества, публиковать свой медиа контент, делиться своими идеями и многое другое.

>Разработчики не забыты! Вскоре после завершения разработки клиента, будет начата разработка открытого **API** *на основе ядра клиента* с соответствующими возможностями.
 
### Tech:

Языки: **Python**, **JS**, **HTML5**, **CSS**
Применение: 
- **Python** - серверная часть. *(FastAPI, Uvicorn, aiohttp и др.)*
- **JS**, **HTML5**, **CSS** -Клиентская часть. *(Electron.js, Node.js, Axios, WS и др.)*

Сервера: 
1. **D-Core main** - Служит для обработки сообщений, каналов, профилей пользователей и хранения статичных или полустатичных данных. Локация: **Германия**.
2. **OAuth2** - Будет обрабатывать вход и авторизацию пользователя, взаимодействие с бд, сессии и куки, а также другие всевозможные данные связанные с процессом OAuth2.
3. **Voice server** - Данные отсутсвуют.
4. 
В планах:
- Установка прокси.
- Балонсировщик нагрузки.
- **Api Gateway**.
- Видео и Аудио сервера.
- Доставка обновлений.
- Настройка **HTTPS**.
- Домен для работы апи и системы.
- Подключение к мощной бд.
- Локализация на: 
- [ **Русский, Белорусский, Украинский, Польский, Немецкий и Английский** *(США)* ] 
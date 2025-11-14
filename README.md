# Общая информация о решении кейса "Генерация сценариев и раскадровок для коротких видеороликов"
### Команда input math
### Деплой
[Решение доступно по ссылке](http://87.228.89.123:3000/register)
### Репозитории
Репозиторий [Frontend](https://github.com/realSlimPudge/madrigal-front)  
Репозиторий [Api Gateway](https://github.com/immxrtalbeast/madrigal_api-gateway)  
Репозиторий [Auth Service](https://github.com/immxrtalbeast/madrigal_auth)  
Репозиторий [Video Service](https://github.com/immxrtalbeast/madrigal_video-service)
### Инструкция по запуску
1. Скопируйте docker-compose.yml
2. Скопируйте .env в папку с docker-compose.yml
3. Замените следущие поля своими значениями
```
VIDEO_SERVICE_ELEVENLABS_API_KEY=
VIDEO_SERVICE_MISTRAL_API_KEY=
VIDEO_SERVICE_S3_ACCESS_KEY=
VIDEO_SERVICE_S3_SECRET_KEY=
VIDEO_SERVICE_S3_PUBLIC_URL=
VIDEO_SERVICE_GEMINI_API_KEY=
```
4. Выполните ```docker-compose up```

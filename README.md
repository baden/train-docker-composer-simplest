### Простейший пример кластера.

Запуск кластера:

```
docker-compose up -d
```

Масштабирование кластера:

```
docker-compose scale web=5
docker-compose up --force-recreate -d
```

Открыть в браузере http://0.0.0.0:8080/

Просмотреть логи:

```
docker-compose logs
```

Остановить кластер:

```
docker-compose stop
```

### Запуск с ручным указанием нод:

```
docker-compose --file docker-compose-manual-scale.yml up -d
```

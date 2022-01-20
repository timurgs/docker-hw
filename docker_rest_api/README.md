Для запуска контейнера требуется:
1. Создать образ: docker build --tag new_python ./
2. Создать контейнер: docker run -d -p 8000:8000 --name=rest_api new_python
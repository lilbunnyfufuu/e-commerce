# Django e-commerce
## Cài đặt
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

```shell
git clone https://github.com/lilbunnyfufuu/e-commerce.git
```

- Tải docker, cài đặt và chạy docker

- Tải PostgreSQL và tạo schema shopping

- Tạo file .env và điền các biến cần thiết
```shell
docker build .
docker-compose build
docker-compose up
```
- Tạo một cửa sổ CMD khác và chạy tiếp:

```shell
docker-compose exec web pip install -r requirements.txt
docker-compose exec web python manage.py makemigrations
docker-compose exec web python manage.py migrate
```

**Ứng dụng chạy tại ```127.0.0.1:8000```**

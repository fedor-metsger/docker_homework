
## Ответы по домашнему заданию к лекции «Docker»

### Задание 1

Файл [Dockerfile](ex1/Dockerfile)

Файл [index.html](ex1/index.html)


### Задание 2

Файл [Dockerfile](ex2/Dockerfile)


Команда создания образа:

`docker build -t ex2 .`

Команда запуска:

`docker run -it --rm -p 80:80 ex2`

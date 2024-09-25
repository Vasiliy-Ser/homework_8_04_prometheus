# Домашнее задание к занятию "`Система мониторинга Prometheus`" - `Падеев Василий`


---

### Задание 1

Установите Prometheus.

Процесс выполнения
1. Выполняя задание, сверяйтесь с процессом, отражённым в записи лекции
2. Создайте пользователя prometheus
3. Скачайте prometheus и в соответствии с лекцией разместите файлы в целевые директории
4. Создайте сервис как показано на уроке
5. Проверьте что prometheus запускается, останавливается, перезапускается и отображает статус с помощью systemctl

Требования к результату

 Прикрепите к файлу README.md скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО]


`При необходимости прикрепитe сюда скриншоты
![1](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/1.png)


---

### Задание 2

Установите Node Exporter.

Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Скачайте node exporter приведённый в презентации и в соответствии с лекцией разместите файлы в целевые директории
3. Создайте сервис для как показано на уроке
4. Проверьте что node exporter запускается, останавливается, перезапускается и отображает статус с помощью systemctl

Требования к результату

 Прикрепите к файлу README.md скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО]


```
Поле для вставки кода...
....
```

`При необходимости прикрепитe сюда скриншоты
![2](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/2.png)



---

### Задание 3

Подключите Node Exporter к серверу Prometheus.

Процесс выполнения
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Отредактируйте prometheus.yaml, добавив в массив таргетов установленный в задании 2 node exporter
3. Перезапустите prometheus
4. Проверьте что он запустился

Требования к результату

1.  Прикрепите к файлу README.md скриншот конфигурации из интерфейса Prometheus вкладки Status > Configuration
2.  Прикрепите к файлу README.md скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта


```
Поле для вставки кода...
....
```

`При необходимости прикрепитe сюда скриншоты
![3](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/3.1.png)
![4](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/3.2.png)



Дополнительные задания со звёздочкой*
Эти задания дополнительные. Их можно не выполнять. Это не повлияет на зачёт. Вы можете их выполнить, если хотите глубже разобраться в материале.

### Задание 4*

Установите Grafana.

Требования к результату
 Прикрепите к файлу README.md скриншот левого нижнего угла интерфейса, чтобы при наведении на иконку пользователя были видны ваши ФИО


```
Поле для вставки кода...
....
```

`При необходимости прикрепитe сюда скриншоты
![5](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/4.1.png)



### Задание 5*

Интегрируйте Grafana и Prometheus.


```
Поле для вставки кода...
....
```

`При необходимости прикрепитe сюда скриншоты
![6](https://github.com/Vasiliy-Ser/homework_8_04_prometheus/blob/main/img/5.1.png)



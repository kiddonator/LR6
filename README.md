# LR6 #
Лабораторная работа №6

# Шаги выполнения #
1. **Настройка клиент git**

Вводим имя пользователя - "Ткачев М.А. 4918" и email - tkachovmax@yandex.ru

2. **Клонирование удалённого репозитория на компьютер**

Клонируем рупазиторий на рабочий стол компьютера.


3. **Добавление файла через интерфейс GitHub**

Добавляем файл monke.txt через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.

![Шаг с 1 по 3](https://github.com/kiddonator/LR6/blob/report/1.jpg)

4. **Получение всей истории операций**

Получаем историю всех операций для каждой из веток.


5. **Получение последних изменениий**

Получаем историю последних двух операций для каждой из веток.

![Шаг с 4 по 5](https://github.com/kiddonator/LR6/blob/report/3.jpg)

6. **Слияние в ветку master**

Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.


![Шаг 6 Разрешение конфликта (1)](https://github.com/kiddonator/LR6/blob/report/4.jpg)


7. **Удаление побочной ветки**

Удаляем побочную ветку после успешного слияния.

![Шаг 7](https://github.com/Lceva/LR6/blob/report/Скриншоты/sc..)

8. **Фиксирование изменений**

Делаем изменения в файле monke.txt и зафиксируем их, оставляя комментарии.


9. **Откат коммита**

Делаем «хард» откат коммита.

![Шаг с 8 по 9](https://github.com/kiddonator/LR6/blob/report/6.jpg)

10. **Создание ветки**

Создаем ветку report для отчёта.

![Шаг 10](https://github.com/kiddonator/LR6/blob/report/Screenshot_1.png)


# Лог команд #
```sh
> cd C:\Users\danch\Desktop\yolo
> git config —global user.name "Ткачев М А 4918"
> git config —global usre.email tkachovmax@yandex.ru
> git clone https://github.com/kiddonator/LR6
> cd LR6

/*Добавление файла monke.txt через интерфейс GitHub*/

> git pull //подтягивание изменений
> git log //Получить историю операций для каждой из веток.
> git log -2 //Просмотреть последние изменения
> git checkout master
> git merge branch1 //Слияние с веткой мастер

/*Устранение конфликта в git GUI*/

> git branch -d branch1 //удаление ветки

/*Изменение файла №1 monke*/

> git add monke.txt //индексация файла
> git commit -m "monke" //коммит (фиксация изменений)

> git checkout -b report //создание и переход на ветку репорта

```

![log_list](https://github.com/kiddonator/LR6/blob/report/logs.png)




  

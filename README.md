# LR6
Лабораторная работа №6
Выполнил Ткачев М.А. 4918

использованные команды:

  1.> cd C:\Users\tkach\Desktop\github 
  2.> git config --global user.name "Ткачев М.А. 4918"
  3.>  git config --global usre.email tkachovmax@yandex.ru
  4.> git clone https://github.com/kiddonator/LR6
  5.>  cd LR6;

/*Добавление файла monke.txt через интерфейс GitHub*/

> git pull      				//подтягивание изменений
> git log    					//Получить историю операций для каждой из веток. 
> git log -2 					//Просмотреть последние изменения
> git checkout master
> git merge branch1				//Слияние с веткой мастер

/*Устранение конфликта в git GUI*/

> git branch -d branch1 		       //удаление ветки

/*Изменение файла №1 monke*/

> git add monke.txt   	                       //индексация файла
> git commit -m "report"   //коммит (фиксация изменений)

/*Изменение файла №2 monke.txt*/

> git add monke.txt                           //индексация файла
> git commit -m "report"   //коммит (фиксация изменений)
> git reset --hard @~2			       //откат на 2 комит назад
> git checkout -b report 			       //создание ветки report
> git push —set-upstream origin report            //создание ветки репорт на гихаб


![создание и переход на ветку репорт](https://github.com/kiddonator/LR6/blob/report/Screenshot_1.png)

![сохранение скриншотов на ветку репорта](https://github.com/kiddonator/LR6/blob/report/2.png)

  

# LR6 #
Лабораторная работа №6

# Шаги выполнения #
1.	**Настройка клиент git**
	Вводим имя пользователя - "4918 Евдокимова Д.А." и email - dasha.eudokimova@yandex.ru
    ![Шаг 1](screenshots/screenshot1.png)

2.	**Клонирование удалённого репозитория на компьютер**
	Клонируем рупазиторий на рабочий стол компьютера.
    ![Шаг 2](screenshots/screenshot2.png)
    
3.	**Добавление файла через интерфейс GitHub**
	Добавляем файл myFile.txt через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.
    ![Шаг 3](screenshots/screenshot3.png)

4.	**Получение всей истории операций**
	 Получаем историю всех операций для каждой из веток.
    ![Шаг 4](screenshots/screenshot4.png)

5.	**Получение последних изменениий**
	Получаем историю последних двух операций для каждой из веток.
    ![Шаг 5](screenshots/screenshot5.png)

6.	**Слияние в ветку master**
	Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.
    ![Шаг 6(1)](screenshots/screenshot6.png)  
    ![Шаг 6(2)](screenshots/screenshot7.png) 
    ![Шаг 6()3](screenshots/screenshot8.png)  

7.	**Удаление побочной ветки**
	Удаляем побочную ветку после успешного слияния.
    ![Шаг 7](screenshots/screenshot9.png)  

8.	**Фиксирование изменений**
	Делаем изменения в файле myFile= и зафиксируем их, оставляя комментарии два раза.
    ![Шаг 8(1)](screenshots/screenshot10.png)
    ![Шаг 8(2)](screenshots/screenshot11.png)
    
9.	**Откат коммита**
	Делаем «хард» откат коммита. 
    ![Шаг 9](screenshots/screenshot12.png) 

10.	**Создание ветки**
    Создаем ветку report для отчёта.
    ![Шаг 10](screenshots/screenshot13.png) 

# Лог команд  #
```sh

> git config --global user.name "4918 Евдокимова Д.А."
> git config --global user.email dasha.eudokimova@yandex.ru
> git clone https://github.com/Lamontin/LR6
> git pull      				
> git log    					 
> git log -2 					
> git merge branch1				
> git branch -d branch1 		       
> git add myFile  	                       
> git commit -m "change№1 myFile"   
> git add myFile                        
> git commit -m "change№2 myFile"   
> git reset --hard @~2			     
> git branch report 			       
> git checkout report
  
```
    
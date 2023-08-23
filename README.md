# TXT

1. Создать внешний репозиторий c названием TXT. `Repositories --> New`
2. Клонировать репозиторий TXT на локальный компьютер. `git clone https://github.com/ElenaChadushkina/TXT.git`
3. Внутри локального TXT создать файл “new.txt”. `cd TXT && touch new.txt`
4. Добавить файл под гит. `git add new.txt`
5. Закоммитить файл. `git commit -m "new.txt"`
6. Отправить файл на внешний GitHub репозиторий. `git push`
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT. `vim new.txt` --> `i`
```
First name: Lena
Middle name: Mikhailovna
Last name: Chadushkina
Age: 32
Pet: 1
Salary:1000$
```
<pre>esc--> :wq</pre>
8. Отправить изменения на внешний репозиторий. `git add new.txt`-->`git commit -m "TXT new"`-->` git push `
9. Создать файл preferences.txt `touch preferences.txt`
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT. `vim preferences.txt` ---> `i`
 ```
Favorite movie:The Pursuit of Happyness
Favorite series: Game of Thrones
Favorite food:kebab, pizza, grilled cheese
Favorite time year: Summer
Country: Indonesia
```
<pre>esc--> :wq</pre>
12. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT `vim sklls.txt` ---> `i`
   ```
1.Basic testing theory: What is testing, Bug reports, Test documentation, SDLC, STLC, Design Test Techniques.
2.HTTP: Methods, Status code, Structure of requests and responses.
3.Data exchange formats:JSON, XML
4.API testing: Postman, JS, Autotests API
5.Traffic sniffing: Charles, Fiddler
6.Dev Tools: Google Chrome, Firefox
7.VPN: How it works, How to use it, Tool options
8.Mobile testing: iOS, Android, Guidelines, XCode, Android Studio, ADB
9.Terminal: GitBash
10.SQL: The basics, Postgres, Redis
11.Load testing: Jmeter,
12.Python: The basics, Creating a client server application
```
<pre>esc--> :wq</pre>
13. Сделать коммит в одну строку.` git add . && git commit -m "prefernces and skills"`
14. Отправить сразу 2 файла на внешний репозиторий.`git push`
15. На веб интерфейсе создать файл bug_report.txt.  `Add file`--> `Create new file`
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.`Commit changes`
18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT. `Edit this file`
   ```
     Bug-ID: 01
Title: Ошибка авторизации пользователя при вводе валидного логина и пароля
Project: Сайт Форум Хомячки
STR: 
   1. Открыть страницу авторизации https://forumhomyachki.com/authorization
   2. Ввести валидный логин и пароль (test@com.ru, 123456)
   3. Нажать кнопку 'Войти'   
Actual result: Система отображает сообщение об ошибке 'При входе произошла ошибка, попробуйте позднее' ,
Expected result: Авторизация прошла успешно, произошел переход в раздел 'Мой профиль',
Environment:OS: Windows 10 PRO 64-bit operating system, x64 processor,
Browser: Microsoft Edge Версия 115.0.1901.200 (Официальная сборка) (64-разрядная версия)
Severity: Critical
Priority: High
Status: New
Author: Чадушкина Елена
```
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.`Commit changes`
20. Синхронизировать внешний и локальный репозиторий TXT `git pull`

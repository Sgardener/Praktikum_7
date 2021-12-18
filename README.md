Посмотреть содержимое папки; Верхнее окно - клиент, нижнее - сервер.

![image](https://user-images.githubusercontent.com/72302486/146651107-a5189f77-4c82-432b-ad54-68a5cc4ed51a.png)

![image](https://user-images.githubusercontent.com/72302486/146651181-4b0ff5df-5e8d-4100-a087-a018ee04e0f4.png)

Создание папки - 

![image](https://user-images.githubusercontent.com/72302486/146651191-d90acaad-1176-47c0-af37-3d9c148dbdd7.png)

![image](https://user-images.githubusercontent.com/72302486/146651195-aca71c87-9b35-4e6e-9f84-f1af005dfc27.png)

Создание и переименование. Далее - переименовать файл

![image](https://user-images.githubusercontent.com/72302486/146652046-456fddc1-63b0-4c42-83fc-5d1f7a277c6c.png)

Удаление файла - 

![image](https://user-images.githubusercontent.com/72302486/146652057-f0bcdb29-e253-4b1b-9942-21d6808fea3b.png)

Выход (отключение клиента от сервера); командой exit закрывается клиентское приложение

Дополнительные задания: Ограничьте возможности пользователя рамками одной определенной директории. Внутри нее он может делать все, что хочет: создавать и удалять любые файлы и папки. Нужно проследить, чтобы пользователь не мог совершить никаких действий вне пределов этой директории. Пользователь, в идеале, вообще не должен догадываться, что за пределами этой директории что-то есть. Как видно было из предыдщуих скринов выйти за пределы папки - корня не может, а это рабочая папка пользователя у admin эта папка - корень сервера.

Добавьте логирование всех действий сервера в файл. Можете использовать разные файлы для разных действий, например: подключения, авторизации, операции с файлами. Логи пишутся в файл корень сервера log.txt

![image](https://user-images.githubusercontent.com/72302486/146652230-d068ce94-dfc1-4731-84dc-b68c55758b42.png)

Добавьте возможность авторизации пользователя на сервере. Добавьте возможность регистрации новых пользователей на сервере. При регистрации для пользователя создается новая рабочая папка (проще всего для ее имени использовать логин пользователя) и сфера деятельности этого пользователя ограничивается этой папкой. пользоваталь вводит логин пароль, если такой пользователь не существует - то создается, если существует, то проверяется корректность введенных данных.

Реализуйте учётную запись администратора сервера. log/pass = admin/admin, рабочая директория - рабочая директория сервера, то есть папка с папками пользователя 13. Напишите отладочный клиент. Клиент должен подключаться к серверу и в автоматическом режиме тестировать корректность его работы. Используйте подход, аналогичный написанию модульных тестов. Клиент должен вывести предупреждающее сообщение, если сервер работает некорректно. файл ftp-test-client log/pass = test/test

![image](https://user-images.githubusercontent.com/72302486/146652293-1333d48a-0f2e-4284-94eb-be5e41c3f21e.png)

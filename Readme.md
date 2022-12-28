<h2>
!!!!!!!!!!!!!!!!!!!!!!!!! <br>
!!!   Задание B9.3.4  !!! <br>
!!!!!!!!!!!!!!!!!!!!!!!!! <br>
</h2><br>
<h3>Что нужно сделать:</h3><br><br>

1. Установите composer локально к себе в проект.<br>
<b>
root@npm:/home/odmin/project9.3.4# composer --version<br>
Composer version 2.5.1 2022-12-22 15:33:54<br>
</b><br><br>
2. Установите библиотеку swiftmailer.<br>
<b>
root@npm:/home/odmin/project9.3.4# composer show<br>
swiftmailer/swiftmailer          v6.3.0  Swiftmailer, free feature-rich PHP mailer<br>
</b> <br>
3. Обновите её до самой актуальной версии.<br>
<b>
root@npm:/home/odmin/project9.3.4# composer update swiftmailer/swiftmailer <br>
Composer is operating significantly slower than normal because you do not have the PHP curl extension enabled. <br>
Loading composer repositories with package information<br>
Updating dependencies<br>
Nothing to modify in lock file<br>
Installing dependencies from lock file (including require-dev)<br>
Nothing to install, update or remove<br>
Package swiftmailer/swiftmailer is abandoned, you should avoid using it. Use symfony/mailer instead.</b><br><br>

4. Сделайте коммит с нужными файлами и папками, чтобы при «разворачивании» вашего проекта другими разработчиками не потерялась установка библиотеки swiftmailer, но и лишнего в репозиторий не добавляйте.

5. Ссылку на удаленный репозиторий опубликуйте в форме для ввода ответа в финальном юните.

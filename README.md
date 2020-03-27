# Franz 5 плагин для maxdone (https://maxdone.micromiles.co/)

Плагин позволяет добавить maxdone почту в качестве Franz 5 приложения.

## Установка

1. Установить [Franz 5](https://meetfranz.com/#download) и настроить. Если вы используете Franz 4, то при установке новой версии установщик предложит вам импортировать настройки.

2. Склонировать этот репозиторий в папку с плагинами Franz 5 (выполнить данные команды в терминале):

    Для Mac OS X:
    ```
    mkdir -p ~/Library/Application\ Support/Franz/recipes/dev
    cd ~/Library/Application\ Support/Franz/recipes/dev
    git clone git@github.com:ksidenko/maxdone-franz-plugin.git maxdone
    ```
    
    Для Linux:
    ```
    mkdir -p ~/.config/Franz/recipes/dev
    cd ~/.config/Franz/recipes/dev 
    git clone git@github.com:ksidenko/maxdone-franz-plugin.git maxdone
    ```
    
    Для Windows (не проверено):
    ```
    md %appdata%\Franz\recipes\dev
    cd %appdata%\Franz\recipes\dev
    git clone git@github.com:ksidenko/maxdone-franz-plugin.git maxdone
    ```

3. Включить или перезагрузить Franz 5

4. Зайти в Settings > Available services > Development и добавить сервис maxdone.

5. Зайти в появившийся сервис и залогиниться.


Больше информации по плагинам [здесь](https://github.com/meetfranz/plugins/tree/master/docs).

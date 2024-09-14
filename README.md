# Инструкция по развёртке и запуску теста.

1. Установить Python версии 3.12.6;
2. Установить Git в директорию, предлагаемую при установке;
3. Установить Pycharm версии 2024.2.1 или выше;
4. Создать окружение для клонирования проекта. В корне диска C создать папку **E2E_test** в папке **projects**;
5. Клонировать проект с помощью Pycharm в папку **C:\projects\E2E_test**, используя HTTPS: `https://github.com/SuplexXx-blip/Effective_Mobile_QA_challenge.git` , либо SSH: `git@github.com:SuplexXx-blip/Effective_Mobile_QA_challenge.git`
6. После клонирования, Pycharm предложит создать виртуальное окружение. Необходимо убедиться, что в пункте Base Interpretator, выбран Python версии 3.12;
7. В Pycharm открываем файл **E2E_test.py**, ждём, когда Pycharm проиндексирует файлы проекта;
8. Запускаем наш тест;

В случае, если Pycharm выбрал Interpretator до установки, то его необходимо удалить, после чего Pycharm предложит установить зависимости с помошью файла requirements.txt - устанавливаем. Далее перезапускаем Pycharm, при запуске подтянется Interpretator из виртуального окружения, после чего можно будет запустить отладку E2Etest.py и убедится, что тест проходит успешно.

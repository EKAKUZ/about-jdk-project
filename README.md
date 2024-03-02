# Windows
---
1. Установить **JDK**
2. Добавить переменные окружения

| Переменная | Описание |
|---|---|
|**JAVA_HOME**|C:\Program Files (x86)\Amazon Corretto\jdk21.0.10_9|
|**Path**|C:\Program Files (x86)\Amazon Corretto\jdk21.0.10_9\bin|
3. Проверка установленного JDK

| Команда | 
|---|
|**echo $JAVA_HOME**|
|**where java**|
4. Проверка версии JAVA

| Команда | 
|---|
|**$ java -version**|
5. Запуск Java-файлов на компьютере

| Команда | Описание |
|---|---|
|**javac -encoding UTF-8 HelloJdk.java**|Скомпилировать исходный код в байт-код (проверить, что имя класса совпадает с именем файла)|
|**java -Dfile.encoding=UTF-8 HelloJdk**|Запустить файл с байт-кодом|
6. 

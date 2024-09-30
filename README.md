# О приложении
Автором данного приложения является студентка Московского политехнического университета - Неустроева Ольга Геннадьевна (группа 211-322)

## Запуск приложения на Windows
Работа над приложением велась на операционной системе Windows, поэтому инструкции будут для этой операционной системы.
Следуйте последующим шагам для настройки и запуска приложения

### 1 - Установка NodeJS
[Официальный сайт](https://nodejs.org/en/download/package-manager)

### 2 - Установка React Native CLI
CLI инструмент для React Native.\
```npm install -g react-native-cli```

### 3 - Установка Android Studio
[Официальный сайт](https://developer.android.com/studio)
После скачивания через настройки догружаем Android SDK Tools.\
Добавляем в PATH: ```ANDROID_PATH = C:\Users\Olga\AppData\Local\Android\Sdk```

### 4 - Установка Java
[Java](https://www.java.com/ru/download/ie_manual.jsp?locale=ru)
И проверить версию Java\
```java -version```\
Добавляем в PATH: ```JAVA_HOME = D:\downloads\jdk-21.0.4```

### 5 - Установка JDK
Не следует устанавливать JDK, который не поддерживает Gradle. Для Java версии 21.0.4 скачивается JDK 11. Устанавливается по умолчанию в папку Java.\
[Gradle](https://docs.gradle.org/current/userguide/compatibility.html)
[Скачать JDK](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)

### 6 - Запуск проекта
Далее запустите эмулятор Android в Android Studio и выполните следующие команды из директории с проектом\

```bash
npm start
```
Далее выбираем опцию "a - run on Android"
